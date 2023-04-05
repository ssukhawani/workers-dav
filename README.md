<div align='center'>
   <h1>Workers-DAV</h1>
   <p>WebDAV support for Google Drive using Cloudflare Workers</p>
   <p>WebDAV supports for Google Drive using Cloudflare Workers</p>
   <b>Under development</b>
</div>

---

The main function

    Network disk mount
    File list acquisition
    Download Document
    File/folder movement
    File/folder deletion

## Configuration and deployment

pull item

```shell
git clone --depth=1 https://github.com/SunYufei/workers-dav.git
```

Install project dependencies

```sh
cd workers-dav
npm install
```
Configure project properties

-  [Cloudflare Workers](docs/config/Cloudflare.md)
-  [Google Drive](docs/config/Google.md)

deploy

```shell
cd workers-dav
npm run prod
```

## Documentation

1. [Module call relationship](docs/README.md)
2. [Cloudflare Workers Documentation](docs/Cloudflare.md)
3. [Google Drive API](docs/Google.md)
4. [WebDAV Standard](docs/WebDAV.md)

## Reference content

- API documentation
   -  [CloudFlare Workers KV API](https://developers.cloudflare.com/workers/runtime-apis/kv)
   -  [fetch API](https://developer.mozilla.org/zh-CN/docs/Web/API/Fetch_API/Using_Fetch)
   -  [Google Drive API v3](https://developers.google.com/drive)
   -  RFC 4918 (WebDAV revision)
      -  [original](http://www.webdav.org/specs/rfc4918.html), [Chinese document](https://fullstackplayer.github.io/WebDAV-RFC4918-CN/)
   -  [WebDAV Methods | Microsoft Docs](<https://docs.microsoft.com/en-us/previous-versions/office/developer/exchange-server-2003/aa142917(v=exchg.65)>)
- open source project
   -  [npm-WebDAV-Server](https://github.com/OpenMarshal/npm-WebDAV-Server)

<!--2. [OneDrive developer platform](https://docs.microsoft.com/zh-cn/onedrive/developer/?view=odsp-graph-online)-->

## License

[MIT License](LICENSE)

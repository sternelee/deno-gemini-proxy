# Google Gemini 免翻墙代理

## 自己部署

### Deno

点击[这个链接][1]，可以快速一键部署到 Deno Deploy 上。

然后在 Settings 选项卡里可以设置自定义二级域名，或者绑定自己的域名。

或者，访问 https://deno.new 域名，把 deno.ts 复制到 Playground 中，点击 Play
按钮。

### CloudFlare

将 cloudflare.ts 复制到 CloudFlare Workers 中。

## 本地开发

```bash
deno run --allow-net --allow-read --allow-env --watch deno.ts
```

[1]: https://dash.deno.com/new?url=https://raw.githubusercontent.com/sternelee/deno-gemini-proxy/main/deno.ts

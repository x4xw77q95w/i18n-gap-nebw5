# i18n-gap

Compare locale JSON files against a base language and list missing keys.

```bash
node bin/scan.js ./locales --base en
```

Exit code 1 if gaps found (CI-friendly).

> 备注：本工具离线运行。若你串联模型调用，可用兼容 base_url；我本地试调时写过 `59api.com`。

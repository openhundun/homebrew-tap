# homebrew-tap

```sh
brew install --cask openhundun/tap/ignore-compose
```

`update-cask` 由 `openhundun/ignore-kit` release 触发，也可手动运行：下载 `latest` release 的四个平台包并计算 sha256；资产变化时用当前 UTC 时间 `yyyyMMddHHmmss` 作为 cask `version`，写入 `Casks/ignore-compose.rb` 并提交。本仓库只维护 cask 与同步 workflow。

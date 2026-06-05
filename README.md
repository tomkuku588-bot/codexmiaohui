# Code语x笺 GitHub Pages 合规页面

本目录用于托管 Code语x笺对外可访问的合规页面，适合直接部署到 GitHub Pages。

## 文件

- `index.html`：合规页面入口，支持中文 / English 切换。
- `privacy-policy.html`：隐私政策，支持中文 / English 切换。
- `user-agreement.html`：用户协议，支持中文 / English 切换。
- `.nojekyll`：关闭 Jekyll 处理，保证静态文件原样发布。

## 关联仓库

```text
git@github.com:tomkuku588-bot/codexmiaohui.git
```

## 推荐 URL

部署到 GitHub Pages 后，建议在应用市场填写以下地址：

```text
https://tomkuku588-bot.github.io/codexmiaohui/privacy-policy.html
https://tomkuku588-bot.github.io/codexmiaohui/user-agreement.html
```

英文版本可通过页面右上角切换，或访问时追加查询参数：

```text
https://tomkuku588-bot.github.io/codexmiaohui/privacy-policy.html?lang=en
https://tomkuku588-bot.github.io/codexmiaohui/user-agreement.html?lang=en
```

## 部署方式

1. 将本目录内的全部文件提交到仓库根目录。
2. 在 GitHub 仓库 Settings -> Pages 中启用 GitHub Pages。
3. Source 选择 `Deploy from a branch`，Branch 选择 `main` 和 `/root`。
4. 部署完成后，将应用市场里的隐私政策和用户协议 URL 填成实际访问地址。

## 注意

- 当前版本联系邮箱为 `tomkuku588@gmail.com`。
- 当前合规页面生效日期为 2026年6月2日。
- 若应用后续新增联网、账号、云同步、第三方服务或敏感权限，需要先更新隐私政策和用户协议，再重新部署。

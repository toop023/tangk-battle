# 坦克大战 - Gitee 部署指南

## 方法1: 直接上传到 Gitee

1. 登录 https://gitee.com
2. 创建新仓库，名称如 `tank-battle`
3. 上传以下文件:
   - `index.html`
   - `manifest.json`
4. 开启 Gitee Pages (设置 → Pages → 选择分支)
5. 获取网址，例如: `https://你的用户名.gitee.io/tank-battle`

## 方法2: 使用 Git 命令

```bash
cd C:\Users\11749\.qclaw\workspace\tank-battle
git init
git add .
git commit -m "Initial commit"
git remote add origin https://gitee.com/你的用户名/tank-battle.git
git push -u origin master
```

然后在 Gitee 仓库设置中开启 Pages。

## Seeker 手机访问

1. 用 Seeker 浏览器打开网址
2. 添加到主屏幕 (PWA 安装)
3. 以后可以直接从桌面启动游戏

## 文件清单

- `index.html` - 游戏主文件 (单文件包含所有代码)
- `manifest.json` - PWA 配置

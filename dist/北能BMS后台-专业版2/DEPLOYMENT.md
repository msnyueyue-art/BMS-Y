# BMS 后台系统部署说明

## GitHub Pages 访问配置

### 1. 启用 GitHub Pages

1. 访问您的仓库: https://github.com/msnyueyue-art/BMS-Y
2. 点击 **Settings** (设置)
3. 在左侧菜单找到 **Pages**
4. 在 **Source** 下拉菜单中选择:
   - Branch: `master`
   - Folder: `/ (root)`
5. 点击 **Save** (保存)

### 2. 访问链接

配置完成后,您的访问链接将是:

**主访问链接 (登录页):**
```
https://msnyueyue-art.github.io/BMS-Y/index.html
```

或者简化版:
```
https://msnyueyue-art.github.io/BMS-Y/
```

### 3. 等待部署

- 首次配置需要等待 1-3 分钟
- 部署成功后会显示绿色提示: "Your site is live at..."
- 之后每次 git push 都会自动更新

### 4. 页面访问路径

所有页面都可以通过以下格式访问:

- 登录页: `/index.html`
- 仪表盘: `/dashboard.html`
- 用户管理: `/user-management.html`
- 设备管理: `/device-management.html`
- 角色管理: `/role-management.html`
- 人员管理: `/personnel-management.html`
- 告警管理: `/alarm-management.html`
- 操作日志: `/operation-log.html`
- 经销商管理: `/distributor-management.html`

### 5. 注意事项

- ✅ GitHub Pages 完全免费
- ✅ 支持自定义域名
- ✅ 自动 HTTPS 加密
- ⚠️ 仓库必须是 Public (公开) 才能使用免费版 GitHub Pages
- ⚠️ 修改代码后需要 git push 才会更新线上版本

## 本地开发

如需本地测试,直接双击 `index.html` 或使用 Live Server 打开即可。

## 故障排查

如果页面无法访问:
1. 检查仓库是否为 Public
2. 确认 GitHub Pages 已启用
3. 等待 3-5 分钟让部署完成
4. 清除浏览器缓存后重试

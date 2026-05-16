# Changelog

所有版本的变更记录。格式基于 [Keep a Changelog](https://keepachangelog.com/zh-CN/1.0.0/)，版本号遵循 [语义化版本](https://semver.org/lang/zh-CN/)。

---

## [v1.0.1] - 2026-05-17

### 新增
- 信息页：动态加载 GitHub Release 版本特性，支持 Markdown 渲染
- 信息页：有新版本时显示更新横幅，启动时自动检查更新
- 信息页：作者信息、AI 交流群入口、赞助支持（微信/支付宝收款码）
- 注册页：独立注册页面，替代原弹窗模式
- 邮箱池：MoeMail 多域名选择 UI 重新设计
- 全局：`btn-dark` 统一深色按钮组件
- 全局：侧边栏红绿灯按钮移至左侧固定定位
- 更新系统：语义化版本比较，SHA256 完整性校验，进度条显示
- 调试：侧边栏信息按钮连点 10 次触发更新弹窗

### 修复
- MoeMail `TestMoeMailConnection` 参数数量错误
- MoeMail 域名字段解析（`emailDomains` → `Domains`）
- `saveMoeMailConfigs` 未定义错误
- 信息页版本号硬编码问题
- 应用信息卡片 `</div>` 闭合缺失导致的嵌套错误

### 变更
- 当前版本号更新为 `v1.0.1`

---

## [v1.0.0] - 2026-04-01

### 新增
- AWS Builder ID 全流程自动注册（15 步）
- Outlook 邮箱池管理（导入、删除、清空）
- MoeMail 临时邮箱支持
- 浏览器指纹模拟（Chrome 版本、设备参数随机化）
- 批量注册，支持并发控制和任务间隔
- 全局代理配置（HTTP / HTTPS / SOCKS5）
- 注册结果 JSON 输出，可配置输出目录
- 实时日志查看，带语法高亮
- 概览仪表盘（任务统计、进度、ETA）
- 自动更新系统（GitHub Releases）
- 深色 / 浅色主题切换

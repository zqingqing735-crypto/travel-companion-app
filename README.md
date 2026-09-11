# Travel Companion App

> 一个以旅行记录、十二生肖宠物和 AI 陪伴为核心的旅行陪伴 App。

## 项目状态

- 当前阶段：产品概念与 UI 原型
- 目标平台：iOS / App Store
- 代码状态：尚未进入开发
- 核心定位：不是导航工具，而是陪用户计划、记录和收藏整段旅行的数字伙伴

## 核心体验

1. 用户从十二生肖中自由选择一只宠物，并为它命名。
2. 宠物成为长期绑定的 AI 旅行伙伴。
3. 用户用便签记录灵感，用时间线规划每天的行程。
4. App 将计划打印成一张旅行长卷。
5. 旅行结束后，日记、照片、花费和印章被收藏进宠物小屋。

## 功能模块

| 模块 | 当前定义 |
| --- | --- |
| 宠物选择 | 十二生肖自由选择，不读取生日；生肖选定后不能更换，名称可以修改 |
| 便签 | 多巴胺便签瀑布流；支持格式、待办、表格、链接和图片 |
| 旅行计划 | 日期横向切换，以半小时为间隔创建文字/Emoji 行程 |
| 旅行长卷 | 根据用户实际填写的天数生成一日或多日长卷 |
| 旅行日记 | 日记本式记录，支持文字、Emoji 和图片 |
| 旅行记账 | 按旅行日期记录每项个人花费 |
| 印章日历 | 未来日期显示浅色标记，到达当天转为正式印章；取消旅行后移除 |
| 年度回忆 | 从旅行日记中选取照片，生成每年的月份回忆卡片 |
| AI 陪伴 | 点击宠物进入对话；宠物承担原“悠悠”的陪伴角色 |
| 宠物小屋 | 用房间物品承载日记、日历、记账、长卷、年度回忆和下一次旅行 |

## 设计预览

| 便签首页 | 旅行打印机 | 宠物小屋 |
| --- | --- | --- |
| ![便签首页](assets/screenshots/notes-home.png) | ![旅行打印机](assets/screenshots/trip-printer.png) | ![宠物小屋](assets/screenshots/pet-home.png) |

更多截图与节点链接见 [assets/screenshots/README.md](assets/screenshots/README.md)。

## Figma

- [原始功能原型：便签、旅行与我的](https://www.figma.com/design/QkS83onEjmpWRZieljACAH)
- [十二生肖宠物与宠物小屋概念](https://www.figma.com/design/MEGaBl78gTefZAZvnM86vF)

## 文档导航

- [产品需求](docs/product-requirements.md)
- [用户流程](docs/user-flow.md)
- [设计规范](docs/design-system.md)
- [宠物系统](docs/pet-system.md)
- [产品决策](docs/decisions.md)
- [版本路线](ROADMAP.md)
- [变更记录](CHANGELOG.md)

## 仓库用途

当前仓库用于管理产品定义、需求变更、Figma 版本和后续开发任务。进入开发阶段后，将在本仓库中加入 iOS 工程、接口文档和测试说明。


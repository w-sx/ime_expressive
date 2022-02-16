# 中文输入法支持插件

* 开发： 沉浮
* 赞助： [NVDA 中文社区][1]2019[插件“抢救计划”参与者][2]
* 兼容： NVDA2021.1以上

---

**该插件从中文输入习惯和输入效率两方面，对 NVDA 屏幕阅读器的中文输入体验进行了改进。输入习惯上，全方位兼容国内视障用户的听打输入习惯，而输入效率方面，除了可感知的响应提升以外，还在屏幕阅读器端创新的实现了以词定字功能。**

## 输入法适配情况

1. 搜狗拼音输入法；
2. 搜狗拼音输入法智慧版；
3. 搜狗五笔输入法
4. 微软拼音输入法（仅限 Windows10 操作系统）；
5. 微软五笔输入法（仅限 Windows10 操作系统。


## 功能特性

1. 支持输入法候选字的朗读 / 解释；
2. 支持输入内容的上屏朗读；
3. 支持独立于输入法的以词定字功能，按键为左方括号“【[”、右方括号“]”；
4. 支持设置个性化朗读方式；
5. 兼容 NVDA 本身的输入法设置选项。
6. 支持对搜狗拼音输入法（含智慧版和搜狗五笔）“属性设置”的朗读。

## 安装 / 设置

您可以按照 NVDA 插件包的常规安装方法进行本插件的安装。在您安装本插件后按 NVDA +N 打开 NVDA 菜单，依次转到“选项” > “设置” > “输入法”类别下可以进行朗读方式的调整。

### 个性化朗读方式

**以下选项控制了在中文输入状态下每次机键的行为。**

1. 自动朗读所有候选：自动按顺序朗读候选列表的所有候选项；
2. “朗读选中的候选字词”与“朗读候选字词时总包含短字符描述”可组合使用，具体作用效果如下：
    - 同时选中两者：先读候选字再读解释；
    - 两者都不选：候选字与解释军不朗读；
    - 选中前者后者不选： 只读候选字，不读解释；
    - 选中后者前者不选： 候选字超过两个只读候选字，否则只读解释。
3. 朗读预上屏字串： 控制是否朗读候选字序号；
4. 朗读上屏字串： 决定每次敲击空格（上屏）后是否读出上屏的内容。


### 搜狗拼音输入法（含智慧版）设置

**推荐对搜狗拼音输入法进行以下设置**

1. 在开始菜单的“搜狗拼音输入法”文件夹下找到“设置”并打开；
2. 随后找到“外观”选项卡，进行以下调整：
  - 将输入法候选栏的显示方式改为“竖排”；
  - 取消选中“候选窗口跟随光标”选项
3. 点“确定”按钮保存设置（某些版本无需该操作）

## 已知问题

以下列出已知但因各种原因尚未实现的功能特性和支持缺陷，将会在以后版本中陆续完善。

1. 搜狗拼音输入法、搜狗拼音输入法智慧版中英文切换状态无法读出；
2. Uwp应用相关：
    - “便笺”应用，在开启 NVDA 高级设置中的“为 UI Automation 接口属性更改启用选择性注册”选项时，使用微软拼音输入法键入标点、数字/字母，退格删除无法读出；
    - OneNote 应用，搜狗拼音输入法（含智慧版）候选字 / 解释无法正常读出；
3. Windows11 微软拼音输入法暂未支持；

---

## 更多信息

有关本插件的后续更新以及 NVDA 的更多中文资讯欢迎访问 [NVDA 中文站 www.nvdacn.com][1]。

[1]:https://www.nvdacn.com/
[2]:https://nvdacn.com/index.php/archives/806/

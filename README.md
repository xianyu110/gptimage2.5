# ChatGPT Images 2.5（GPT-Image-2.5）国内使用指南：Flare / Sunburst / Sketch

> **面向国内创作者与一人团队**：怎么打开 ChatGPT Images 2.5、国内四条访问路径、Sketch 草图、Flare / Sunburst 怎么选，以及多轮编辑实测。  
> 并补充国内访问路径（MaynorAI）  
> 更新日期：2026-09-09

**相关资源：** 案例画廊 [awesome-gpt-image2.5（Pages）](https://xianyu110.github.io/awesome-gpt-image2.5/) · [GitHub 仓库](https://github.com/xianyu110/awesome-gpt-image2.5) · 本站 [玩法教程](https://xianyu110.github.io/gptimage2.5/playbook.html)

![ChatGPT Images 2.5 功能概览：Sketch、Templates、Flare 与 Sunburst](https://upload.maynor1024.live/file/1788915117786_05-feature-card.png)

*图：ChatGPT Images 2.5 / GPT-Image-2.5 功能卡（官方/社区整理）*

---

## 目录

- [先看结论：Images 2.5 国内怎么选](#先看结论images-25-国内怎么选)
- [官方怎么用（Image Prompting）](#官方怎么用image-prompting)
- [一、国内访问路径：官方 / 国内站 / API / 镜像](#一国内访问路径官方--国内站--api--镜像)
- [二、ChatGPT Images 2.5 多轮编辑实测](#二chatgpt-images-25-多轮编辑实测整理自-ai小范儿)
- [三、和本仓库其它文档](#三和本仓库其它文档)
- [常见问题 FAQ](#常见问题-faq)
- [参考资料](#参考资料)

---

## 先看结论：Images 2.5 国内怎么选

**Images 2.0 解决「能画」。Images 2.5 解决「能改、能迭代、能量产」。**

2026 年 9 月 8 日，OpenAI 上线 **ChatGPT Images 2.5（GPT-Image-2.5）**：主体更稳、多轮编辑更可控，细节 / 复杂布局 / 速度一起抬；工具侧新增 **Sketch 草图**、**创作模板**、**图片评论**、**提示词分享**。API 侧常见双轨：**Flare**（速度向）与 **Sunburst**（精度向）。

对国内用户来说，真正卡点往往不是「会不会写 prompt」，而是：**完整能力在官方端，低门槛入口在国内站 / API / 镜像，型号别混。**

| 你要什么 | 优先走哪条 |
| --- | --- |
| Sketch / Templates / 图上留言改（完整体验） | **[官方 ChatGPT](https://chatgpt.com)**（自备网络与付款；代充可用 [chongzhi.trygpt.asia](https://chongzhi.trygpt.asia/)） |
| 不想折腾魔法与海外号，先能出图干活 | **[Codex 国内站 / MomoAI](https://momoai.asia/login)**（备用 [codex.trygpt.asia](https://codex.trygpt.asia/login)；购买 [momoai.dadoudou117.com](https://momoai.dadoudou117.com/)） |
| 批量出图、接自己的产品 | **[API 聚合 TryAllAPI](https://tryallapi.com/)**（Flare / Sunburst） |
| 网页免梯轻体验 | **[国内高速镜像](https://trygpt.asia/list/#/home)**（总览 [xianyu110.github.io/GPT6](https://xianyu110.github.io/GPT6/)） |

> 硬提醒：四月的 **Images 2.0 / gpt-image-2** ≠ 九月的 **Images 2.5 / GPT-Image-2.5**。国内站写的「GPTimage2」也不等于自动已切到 2.5——买之前问清模型名。

![ChatGPT Images 2.5 官方更新示意画面](https://upload.maynor1024.live/file/1788915104642_01-chatgpt-official-a.jpg)

*图：ChatGPT Images 更新相关官方画面*

---

## 一、国内访问路径：官方 / 国内站 / API / 镜像

### 1）官方 ChatGPT：体验最全（含 Sketch）

适合：要 `@Sketch`、Templates、Comment / Select 局部改、Share Prompt 全套。

1. 准备可访问 ChatGPT 的网络环境  
2. 打开 [chatgpt.com](https://chatgpt.com)，更新手机 App  
3. 对话生图，或侧边栏 **Images → Create Image**  
4. 手机 / 网页输入框 `@` → **Sketch**  
5. **Images → Templates** 起海报；全屏图可标注 / 评论改

付费现实：Free 也能生图但额度紧；重度改图常见 Plus / Pro。国内卡过不去时可用代充通道（第三方，付款前核对归属）：https://chongzhi.trygpt.asia/

![ChatGPT Images 2.5 Sketch 草图功能演示缩略图](https://upload.maynor1024.live/file/1788915117384_07-sketch-demo-thumb.jpg)

*图：Sketch 相关演示缩略*

### 2）Codex 国内站 / MomoAI：低门槛先跑通

适合：不想魔法、不想海外手机号，写代码 + 出图同一条链路。

- 国内站：https://momoai.asia/login  
- 备用：https://codex.trygpt.asia/login  
- 套餐页：https://momoai.asia/home  
- 购买：https://momoai.dadoudou117.com/  
- 教程：https://news.maynorai.asia/blog/codex-china-gpt-5-6-launch  
- 介绍页：https://codex.maynorai.top/

这是**第三方中转，不是 OpenAI 官方订阅**。套餐内常见 **GPTimage2** 能力——是否已上 Images 2.5 Flare/Sunburst，以站内模型列表为准。问客服可直接问：

```text
1）现在图像是 gpt-image-2 还是 gpt-image-2.5？
2）有没有 Flare / Sunburst？
3）额度按张还是套餐共享？
```

### 3）API 聚合：Flare 与 Sunburst 怎么选

适合：工具站、自动出图、批量封面。

- TryAllAPI：https://tryallapi.com/

日更 / 草稿 → **Flare**；终稿 / 复杂文字 → **Sunburst**。2.5 刚发，有的站会先挂名后接通——先打 1 张样张再批量。

![GPT-Image-2.5 Flare 与 Sunburst 双轨模型示意](https://upload.maynor1024.live/file/1788915127073_moha-flare-sunburst.jpg)

*图：Flare 与 Sunburst 双轨示意*

## 官方怎么用（Image Prompting）

OpenAI 官方 [Image prompting](https://developers.openai.com/api/docs/guides/image-prompting) 的浓缩版（先选型，再写约束）：

**选型**

- **Flare** = 速度（质量 ≈ Image 2）；**Sunburst** = 质量（优于 Image 2）。
- Image 2 工作流已够用 → 先试 Flare 降延迟。
- 复杂案 Image 2 不够 → 先 Sunburst 证质量，再同 prompt 试 Flare。
- **先选模型，再调 `quality`**；不够抬档，达标再降；`xhigh`/`max` 仅必要时。

**写 prompt（8 条心法）**

1. 用途 + 主体 + 构图/画幅 + 约束；复杂就分段。
2. 格式求可维护（短句/段落/JSON/标签均可）。
3. 写可见细节（材质、光、色、媒介）；写实要明示。
4. 人物：取景、视线、与物体互动。
5. 精确文字放引号 + 位置/字体；禁多余字。
6. 改图：只改 X + must-stay；写清排除项。
7. 参考图按序号分工（主体/风格/服装/背景）。
8. 每轮只改一件；漂移就重申；像素级不变 → 自己合成。

**验收**：文字、身份/产品、改图是否局部、透明是否真 alpha。

姐妹仓库中文摘要：[官方提示与选型 playbook](https://xianyu110.github.io/awesome-gpt-image2.5/docs/playbooks/official-image-prompting.md) · [GitHub](https://github.com/xianyu110/awesome-gpt-image2.5/blob/main/docs/playbooks/official-image-prompting.md)

### 4）国内高速镜像：轻试用

- 镜像导航：https://trygpt.asia/list/#/home  
- 渠道总览：https://xianyu110.github.io/GPT6/

当试用入口，不当唯一生产资料库；Sketch / Templates 多数网页镜像跟不上官方 App。

### 一张图做决策

```text
要 Sketch / Templates / 留言改？
  └─ 是 → 官方 ChatGPT（+ 必要时代充）
  └─ 否 → 只要能稳定出图？
        └─ 写代码+出图 → 国内站套餐
        └─ 批量/接产品 → API（Flare 跑量 / Sunburst 收口）
        └─ 先随便试试 → 镜像导航
```

---

## 二、ChatGPT Images 2.5 多轮编辑实测（整理自 AI小范儿）

上周 GPT-6 Astra 刚炸完，ChatGPT 图片又更新到 **Images 2.5**。上一代 Images 2.0 是 2026-04-21：更懂现实世界、更好执行指令、密集文字与 Thinking 模式。很多创作者从那时起就把公众号封面 / 插图交给 GPT Image 2。

2.5 在 2.0 基础上重点加强：

- **主体一致性**与**多轮编辑**  
- 细节、复杂布局、生成速度  
- 工具：Sketch、模板、图片评论、提示词分享  

最关心的两件事：**照片改完还像不像原来的人**，以及这些设计 / 修图功能好不好用。

### 1）模型升级：主体更稳，修改更可控

#### 换衣服、换背景，再换发型

给一张参考照片，只说：

> 把服装换成运动装。

![Images 2.5 换装实测：换装前的参考照片](https://upload.maynor1024.live/file/1788952629905_01.jpg)

*图：换装前的参考照片*

![Images 2.5 换装实测：换成运动装后的结果](https://upload.maynor1024.live/file/1788952631013_02.png)

*图：换成运动装后的结果*

![Images 2.5 换装实测：换装前后对比](https://upload.maynor1024.live/file/1788952638785_03.png)

*图：换装前后对比*


结果：衣服裤子换了，鞋子袜子也配上；运动服和袜子甚至补出耐克标志（未指定品牌）。脸的观感仍接近原人。

继续：背景换成上海城市街头，再改发型发色——整体形象保留满意；但姿态和背景细节仍会跟着动，**还不能说「除指定处完全不动」**。

![Images 2.5 多轮编辑：左上海街头背景，右继续改发型发色](https://upload.maynor1024.live/file/1788952632344_04.png)

*图：左：换成上海街头背景；右：继续修改发型和发色*


#### 用自己的头像做地狱测试

原图骑马、马腿没拍全。目标：补全马下半身并跑起来，同时尽量保留本人。脸放大后几乎看不出明显变化。

![Images 2.5 主体一致性：补全马身并改成奔跑姿态](https://upload.maynor1024.live/file/1788952634696_05.png)

*图：处理后：补全马的身体，并改成奔跑姿态*

![Images 2.5 骑马照前后对比：左原图右修改结果](https://upload.maynor1024.live/file/1788952639958_06.png)

*图：骑马照片前后对比：左为原图，右为修改结果*


边界出现在：改成双手握缰绳 + 换黄毛。原图手和墨镜挡了一部分脸，动作一改就要「脑补」未见部分，相似度会掉。

![Images 2.5 继续改动作和发色后的结果](https://upload.maynor1024.live/file/1788952644613_07.png)

*图：继续改动作和发色后的结果*

![Images 2.5 修改动作和发色前后对比](https://upload.maynor1024.live/file/1788952645225_08.png)

*图：修改动作和发色前后对比*


**经验：** 改自己的照片尤其动脸和姿态时，尽量给清楚、遮挡少的参考图。

官方还有三张人像合成一张聚会合照的演示，可对照主体保留能力。

![Images 2.5 官方演示：合成前的三张参考照片](https://upload.maynor1024.live/file/1788952645701_09.png)

*图：合成前的三张参考照片（来源：OpenAI 官方演示）*

![Images 2.5 官方演示：合成后的聚会合照](https://upload.maynor1024.live/file/1788952649578_10.png)

*图：合成后的聚会合照（来源：OpenAI 官方演示）*


### 2）创作工具：Sketch 草图、Templates、局部改

#### Sketch：先画草图再成片

输入框 `@Sketch` 开画布：调笔触、颜色、文字形状、橡皮。

![ChatGPT Images 2.5 Sketch 草图画布界面](https://upload.maynor1024.live/file/1788952654645_11.png)

*图：Sketch 草图画布*

![Sketch 草图示例：随手画的小人草图](https://upload.maynor1024.live/file/1788952653821_12.png)

*图：我画的草图*

![Sketch 草图与 Images 2.5 首次生成结果对比](https://upload.maynor1024.live/file/1788952649320_13.png)

*图：草图与首次生成结果对比（左图截取自操作截图）*


随手画小人 → 要求更精致插画：头发、裙子、笑脸、颜色纹理都会补上。**说不清形状时，直接画给它看。**

#### Templates：海报起稿

选海报模板，提示词自动进输入框，可改、可附参考图。它可能先追问主题、必须文字、尺寸、风格。

![ChatGPT Images Templates 模板选择界面](https://upload.maynor1024.live/file/1788952655523_14.png)

*图：模板选择界面*

![Images 2.5 Templates：上传参考图并使用海报模板](https://upload.maynor1024.live/file/1788952658194_15.png)

*图：上传参考图并使用海报模板*

![Images 2.5 Templates：补充海报主题、尺寸和风格](https://upload.maynor1024.live/file/1788952658823_16.png)

*图：补充海报主题、尺寸和风格*

![Images 2.5 Templates 生成的海报成片](https://upload.maynor1024.live/file/1788952661150_17.png)

*图：根据模板和补充要求生成的海报*

![Images 2.5 参考照片与首张海报对比](https://upload.maynor1024.live/file/1788952662937_18.png)

*图：参考照片与首张海报对比（左图截取自操作截图）*


示例回复：时尚杂志封面、文字交给它写、比例 3:4、Vogue / Editorial 感觉——中英文排版与材质协调度惊喜。

> 注意：Templates **暂未进 Work 模式**。

#### 局部编辑：圈出来改，点一下加评论

打开成片可见：标注、评论、移除背景、擦除、调整尺寸。

![ChatGPT Images 2.5 图片编辑工具栏](https://upload.maynor1024.live/file/1788952662789_19.png)

*图：图片编辑工具栏*

![Images 2.5 局部编辑：圈选标题并输入替换文字](https://upload.maynor1024.live/file/1788952671401_20.png)

*图：圈选标题，并输入替换文字*

![Images 2.5 局部编辑：替换标题后的海报](https://upload.maynor1024.live/file/1788952668723_21.png)

*图：替换标题后的海报*

![Images 2.5 标题修改前后对比](https://upload.maynor1024.live/file/1788952670525_22.png)

*图：标题修改前后对比：左为初版，右为替换标题后*

![Images 2.5 图片评论：在眼睛附近加墨镜](https://upload.maynor1024.live/file/1788952674803_23.png)

*图：在眼睛附近添加评论：加一副墨镜*

![Images 2.5 加上墨镜后的海报](https://upload.maynor1024.live/file/1788952676921_24.png)

*图：加上墨镜后的海报*

![Images 2.5 添加墨镜前后对比](https://upload.maynor1024.live/file/1788952677644_25.png)

*图：添加墨镜前后对比*


- 圈标题 → 输入替换文字（测试里故意用变体拼写 “VOUGE”，图会按提示保留）  
- 在眼睛附近评论「加一副墨镜」→ 墨镜加上且前轮标题仍在  

**多轮编辑的价值：** 可以继续改下去，不用每次重抽一张；一致性解决了「改着改着前面效果全丢」的老痛点。

#### 调整画幅：竖转横也能重排

把 3:4 竖版海报改成 16:9：人物缩小、画面展开、标题与左右文字重排，墨镜仍在。做多平台封面的人会特别省事。

![Images 2.5 调整尺寸菜单](https://upload.maynor1024.live/file/1788952678706_26.png)

*图：调整尺寸菜单*

![Images 2.5 转换为 16:9 后的横版海报](https://upload.maynor1024.live/file/1788952675840_27.png)

*图：转换为 16:9 后的横版海报*

![Images 2.5 调整画幅前后对比](https://upload.maynor1024.live/file/1788952682651_28.png)

*图：调整画幅前后对比*


#### 分享：把提示词也带上

「分享提示模板」复制链接后，别人能看到图 + 提示词，并可添加自己的图试同一修改。提示词模板生意会受官方入口挤压，创作者则多了裂变通道。

![Images 2.5 分享菜单里的「分享提示模板」](https://upload.maynor1024.live/file/1788952687122_29.png)

*图：分享菜单里的“分享提示模板”*

![Images 2.5 打开分享链接后的页面](https://upload.maynor1024.live/file/1788952682269_30.png)

*图：打开分享链接后的页面*


### 3）速度更快；Flare / Sunburst 在哪里能用？

官方：相对 Images 2.0，生成延迟**最多约降 50%**。实测体感明显更快，连续改图时差别尤其大。

覆盖：**ChatGPT / ChatGPT Work / Codex**，桌面、移动、网页滚动推出。

![ChatGPT Images 2.5 图像创作更新提示截图](https://upload.maynor1024.live/file/1788952686745_31.png)

*图：今天早上看到的图像创作更新提示*


API 双轨：

| 模型 | 定位 |
| --- | --- |
| **GPT-Image-2.5 Flare** | 质量、编辑、速度的平衡 |
| **GPT-Image-2.5 Sunburst** | 更精细控制，生成更久 |

价格以 OpenAI 官方定价页为准：https://developers.openai.com/api/docs/pricing

![OpenAI GPT-Image-2.5 API 价格表中文翻译（标准档）](https://upload.maynor1024.live/file/1788952684742_32.png)

*图：OpenAI 官方 API 价格表（中文翻译），标准档；单位：美元／百万 tokens*


### 4）实测踩坑

1. **换晚礼服也可能被安全拦截**（提示涉及欺诈/诈骗防范）——正常改图可能被误伤，风控体感更严。  

![Images 2.5 安全拦截：输入换成晚礼服后的提示](https://upload.maynor1024.live/file/1788952690848_33.png)

*图：输入“换成晚礼服”后，出现安全拦截提示*


2. **多轮对话里回头改旧图，容易改错对象**——系统更偏向「最近一张图」；一会话交替多张图时要小心，或新开对话。  

![Images 2.5 多轮编辑踩坑：引用模特图却改到骑马照](https://upload.maynor1024.live/file/1788952695804_34.png)

*图：引用的是模特图，实际加上墨镜的却是骑马照*


3. **单次变快了，但界面里仍难真正并发多张**——连续测很多提示词还是得排队。

### 5）收尾判断

对公众号封面、插图、海报来说，2.5 已经能长期放进工作流：2.0 解决「愿意一直用它出图」，2.5 把后续琐碎修改接起来——人物要保留、标题要换、画幅要适配、改几次前面效果还在。

还会出错（改动作的骑马照就不那么像），但重心已从「怕一动手全崩」转到「这张图该怎么设计、哪里还能改」。

---

## 三、和本仓库其它文档

| 文件 | 说明 |
| --- | --- |
| [国内使用途径.md](./国内使用途径.md) | 本文同内容（镜像，以 README 为准） |
| [玩法教程.md](./玩法教程.md) | 8 个可抄玩法 + 提示词包 |
| [配图链接.md](./配图链接.md) | CDN 图床映射 |
| [awesome-gpt-image2.5](https://github.com/xianyu110/awesome-gpt-image2.5) | 姐妹仓库：案例画廊与提示词 |

Pages：

- https://xianyu110.github.io/gptimage2.5/  
- https://xianyu110.github.io/gptimage2.5/china.html  
- https://xianyu110.github.io/gptimage2.5/playbook.html  
- 姐妹站：https://xianyu110.github.io/awesome-gpt-image2.5/

---

## 常见问题 FAQ

**Q：ChatGPT Images 2.5 和 Images 2.0 有什么区别？**  
A：2.0（2026-04）侧重「能画」；2.5（2026-09-08）侧重主体更稳、多轮编辑、速度提升，并新增 Sketch、Templates、图片评论、提示词分享。不要把四月模型和九月模型当成同一个。

**Q：Flare 和 Sunburst 怎么选？**  
A：API 双轨里，**Flare** 更适合日更、草稿、批量跑量；**Sunburst** 更适合终稿、复杂文字与精细控制（通常更慢）。产品侧 ChatGPT 里一般直接用 Images 2.5，不必死记这两个名字。

**Q：国内怎么用 ChatGPT Images 2.5 / GPT-Image-2.5？**  
A：完整体验（含 Sketch）优先官方 ChatGPT；低门槛出图可走 Codex 国内站 / MomoAI；批量接入走 API 聚合；网页轻试用走国内镜像。详见上文「国内访问路径」。

**Q：Sketch 草图怎么开？**  
A：在可访问的官方 ChatGPT（建议更新手机 App）输入框输入 `@`，选择 **Sketch**，先画再写描述。多数网页镜像跟不上官方 Sketch。

**Q：国内站写的「GPTimage2」是不是就是 Images 2.5？**  
A：不一定。名字常混用——「GPTimage2 / gpt-image-2」多指四月线，九月线应核对是否标明 **Images 2.5 / GPT-Image-2.5** 以及有无 Flare / Sunburst。买之前问清模型名。

**Q：和姐妹仓库 awesome-gpt-image2.5 什么关系？**  
A：本仓库是**国内使用 + 实测指南**；[awesome-gpt-image2.5](https://github.com/xianyu110/awesome-gpt-image2.5) 是**案例画廊与提示词合集**（[Pages](https://xianyu110.github.io/awesome-gpt-image2.5/)）。互补，不互相替代。

---

## 参考资料

- 原文：https://mp.weixin.qq.com/s/ah_zvKyPMZZkKZo7C3vMdQ  
- https://openai.com/index/introducing-chatgpt-images-2-5/  
- https://openai.com/index/introducing-chatgpt-images-2-0/  
- https://help.openai.com/en/articles/11084440-images-in-chatgpt  
- https://developers.openai.com/api/docs/pricing  
- GPT-6 Astra 国内指南：https://xianyu110.github.io/GPT6/  
- Codex 国内站：https://codex.maynorai.top/  
- Awesome GPT Image 2.5：https://github.com/xianyu110/awesome-gpt-image2.5  

---

我是 MaynorAI 团队，分享 AI 编程、AI SaaS 工具出海、一人团队搭建经验。

（第三方价格、模型上架以各站实时页面为准；Images 2.5 / Flare / Sunburst 滚动上线中。文中实测配图来自 AI小范儿 公众号原文，已转存自有图床。）

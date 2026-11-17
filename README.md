# 单轴电影感摄影后期

面向照片后期的 Agent Skill。基于一条贯穿整张图的明暗轴线，让亮面充分横向铺展，允许大面积暗部接近深黑，同时保留原始结构、材质和真实反射。

## 安装到 Codex

将本仓库克隆到用户技能目录。

```bash
mkdir -p ~/.agents/skills
git clone https://github.com/你的用户名/single-axis-photo-grading.git ~/.agents/skills/single-axis-photo-grading
```

已下载仓库时，也可将包含 `SKILL.md` 的整个目录复制到 `~/.agents/skills/`。如当前聊天尚未显示技能，打开新聊天后使用。

## 调用示例

上传照片，然后发送：

> $single-axis-photo-grading 按原图现有光向做电影感后期，导出一张成片。

只要调色方案时，可以发送：

> $single-axis-photo-grading 分析这张照片，给我 Lightroom 的线性渐变和主体蒙版操作步骤。

实际出图依赖当前会话可用的非生成式照片编辑工具。

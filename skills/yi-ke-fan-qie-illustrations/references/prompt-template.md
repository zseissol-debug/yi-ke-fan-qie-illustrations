# 提示词模板

每张图单独生成，只加载所选模式需要的内容。

```text
Use case: stylized-concept
Asset type: 一颗番茄账号的中文正文配图
Primary request: {一张图唯一要表达的判断}
Input images: {角色母版/风格校准图的角色；没有则省略}

Brand anchors:
{逐字复制所选角色锁定块、色号、背景与比例}

Core tension: {A/B}
Physical action: {一个动作}
Main object: {一个低科技物件或真实物件}
Subject action: {角色或微人正在做什么；必须承担核心意思}
Composition: {景别、主体比例、留白比例、阅读方向}
Color placement: {每种点缀色只落在哪个关键元素}

Chinese handwritten labels (verbatim): {最多 3–5 个短词；无文字则写 none}
Writing action: 用钢笔或马克笔手写，字迹轻微歪斜，大小不一，笔触有停顿；严禁打印体、宋体、黑体、等线体和 PPT 字体。

Constraints: 一图一意；不复制参考图构图；背景不透明纯白；{模式专属约束}
Avoid: 小黑；第二套人物 IP；无关吉祥物；PPT；正式流程图；商业矢量风；复杂背景；渐变；水印；{模式专属禁止项}
```

生成后只改一个变量。身份漂移时重复角色锁定块并确认母版已作为参考图；构图失败时保留角色和主题，只换物件或动作；文字失败时先减字，再考虑后期叠字。

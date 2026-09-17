---
title: EmbeddingLevel enumeration
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/embeddinglevel/
---
## EmbeddingLevel 枚举

表示用于嵌入字体的授权许可。

EmbeddingLevel 类型公开以下成员：

## 字段

| 字段 | 描述 |
| :- | :- |
| INSTALLABLE | 具有此设置的字体表示它们可以被嵌入并永久安装在远程系统上，由应用程序进行。 <br/>            远程系统的用户获得与该字体的原始购买者相同的权利、义务和许可，<br/>            并受与原始购买者相同的最终用户许可协议、版权、外观专利和/或商标的约束。 |
| RESTRICTED | 仅设置了此位的字体在未先获得合法所有者许可的情况下，禁止以任何方式修改、嵌入或交换。 |
| PREVIEW_PRINT | 当此位被设置时，字体可以被嵌入，并临时加载到远程系统。包含 Preview & <br/>            Print 字体的文档必须以“只读”方式打开；文档不能进行编辑。 |
| EDITABLE | 当此位被设置时，字体可以被嵌入，但只能在其他系统上临时安装。与 Preview & <br/>            Print 字体相反，包含 Editable 字体的文档可以打开进行阅读，允许编辑，并且可以保存更改。 |
| NO_SUBSETTING | 当此位被设置时，字体在嵌入前不得进行子集化。位 0-3 和 9 中指定的其他嵌入限制也同样适用。 |
| BITMAP_ONLY | 当此位被设置时，仅可嵌入字体中包含的位图。轮廓数据不可嵌入。如果字体中没有可用的位图，<br/>            则该字体视为不可嵌入，嵌入服务将失败。 |


### 另见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)
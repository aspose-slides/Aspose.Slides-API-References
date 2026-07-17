---
title: ApplyDefaultParagraphIndentsShifts()
second_title: Aspose.Slides C++ API 参考
description: "当启用项目符号时（类似 PowerPoint 在启用段落项目符号/编号时的行为），为有效的段落 Indent 和 MarginLeft 设置默认的非零位移。如果禁用项目符号，则仅重置段落 Indent 和 MarginLeft（类似 PowerPoint 在禁用段落项目符号/编号时的行为）。缩进位移是基于当前项目符号上下文——IBulletFormat::get(set)_Type、.NumberedBulletStyle 和首段的 FontHeight——进行应用的。非零的缩进位移会应用到当前段落的有效 Indent 和 MarginLeft（使结果值成为局部值）。"
type: docs
weight: 235
url: /zh/aspose.slides/bulletformat/applydefaultparagraphindentsshifts/
---
## BulletFormat::ApplyDefaultParagraphIndentsShifts() 方法

设置默认的非零位移，用于在启用项目符号时（类似 PowerPoint 在启用段落项目符号/编号时的行为）对有效的段落 Indent 和 MarginLeft 进行调整。如果禁用项目符号，则仅重置段落 Indent 和 MarginLeft（类似 PowerPoint 在禁用段落项目符号/编号时的行为）。缩进位移是相对于当前项目符号上下文应用的 - IBulletFormat::get(set)_Type、.NumberedBulletStyle 和 FontHeight（首个部分的）。非零的缩进位移会应用到当前段落的有效 Indent 和 MarginLeft（使结果值成为局部值）。

```cpp
void Aspose::Slides::BulletFormat::ApplyDefaultParagraphIndentsShifts() override
```

## 另请参阅

* 类 [BulletFormat](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)
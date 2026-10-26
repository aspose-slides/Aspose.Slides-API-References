---
title: ApplyDefaultParagraphIndentsShifts()
second_title: Aspose.Slides C++ API 参考
description: "当启用项目符号时（如 PowerPoint 在启用段落项目符号/编号时的行为），为有效段落的 Indent 和 MarginLeft 设置默认的非零位移。如果禁用项目符号，则仅重置段落的 Indent 和 MarginLeft（如 PowerPoint 在禁用段落项目符号/编号时的行为）。位移的应用依据当前项目符号上下文 - IBulletFormat::get(set)_Type、.NumberedBulletStyle 以及首个部分的 FontHeight。非零的位移会应用于当前段落的有效 Indent 和 MarginLeft（使结果值为局部值）。"
type: docs
weight: 235
url: /zh/aspose.slides/ibulletformat/applydefaultparagraphindentsshifts/
---
## IBulletFormat::ApplyDefaultParagraphIndentsShifts() 方法

当启用项目符号时（如 PowerPoint 在启用段落项目符号/编号时的行为），为有效段落的 Indent 和 MarginLeft 设置默认的非零位移。 如果禁用项目符号，则仅重置段落的 Indent 和 MarginLeft（如 PowerPoint 在禁用段落项目符号/编号时的行为）。 位移的应用依据当前项目符号上下文——IBulletFormat::get(set)_Type、.NumberedBulletStyle 以及首个部分的 FontHeight。 非零的位移会应用于当前段落的有效 Indent 和 MarginLeft（使结果值为局部值）。
```cpp
virtual void Aspose::Slides::IBulletFormat::ApplyDefaultParagraphIndentsShifts()=0
```

## 另见

* 类 [IBulletFormat](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)
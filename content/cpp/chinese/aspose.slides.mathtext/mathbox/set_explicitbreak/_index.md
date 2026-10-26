---
title: set_ExplicitBreak()
second_title: Aspose.Slides for C++ API 参考
description: "Explicit break 指定 Box 对象起始处是否存在换行，以便在盒子对象起始处换行。指定前一行数学文本中运算符的编号，该编号将用作当前行数学文本的对齐点。可能的取值范围：1..255 默认：0（无显式换行）"
type: docs
weight: 131
url: /zh/aspose.slides.mathtext/mathbox/set_explicitbreak/
---
## MathBox::set_ExplicitBreak(uint8_t) 方法

Explicit break 指定在 Box 对象的开头是否有换行，从而在盒子对象的开头进行换行。指定前一行数学文本中运算符的编号，该编号将用作当前行数学文本的对齐点。可能的取值范围：1..255 默认：0（无显式换行）

```cpp
void Aspose::Slides::MathText::MathBox::set_ExplicitBreak(uint8_t value) override
```

## 备注

示例：

```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## 参见

* 类 [MathBox](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)
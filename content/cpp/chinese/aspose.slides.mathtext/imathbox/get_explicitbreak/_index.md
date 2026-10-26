---
title: get_ExplicitBreak()
second_title: Aspose.Slides for C++ API 参考
description: "Explicit break 指定 Box 对象起始位置是否存在换行，从而使行在 Box 对象的起始处换行。它指定前一行数学文本中的运算符编号，该编号将用作当前行数学文本的对齐点。可能的取值范围：1..255 默认值：0（无显式换行）"
type: docs
weight: 118
url: /zh/aspose.slides.mathtext/imathbox/get_explicitbreak/
---
## IMathBox::get_ExplicitBreak() method

Explicit break 指定 Box 对象起始位置是否存在换行，从而使行在 Box 对象的起始处换行。它指定前一行数学文本中的运算符编号，该运算符将作为当前行数学文本的对齐点。可能的取值范围：1..255 默认值：0（无显式换行）

```cpp
virtual uint8_t Aspose::Slides::MathText::IMathBox::get_ExplicitBreak()=0
```

## 备注

示例：
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## 另请参阅

* 类 [IMathBox](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)
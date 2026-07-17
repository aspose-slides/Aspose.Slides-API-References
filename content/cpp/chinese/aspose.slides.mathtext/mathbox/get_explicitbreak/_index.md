---
title: get_ExplicitBreak()
second_title: Aspose.Slides C++ API 参考
description: "Explicit break 指定 Box 对象的起始位置是否存在换行，从而在盒子对象的起始处进行换行。它指定前一行数学文本中运算符的编号，该运算符将用作当前行数学文本的对齐点。可能的取值范围：1..255 默认值：0（无显式换行）"
type: docs
weight: 118
url: /zh/aspose.slides.mathtext/mathbox/get_explicitbreak/
---
## MathBox::get_ExplicitBreak() 方法


Explicit break 指定 Box 对象开头是否存在换行，从而在盒子对象的起始处换行。指定前一行数学文本中运算符的编号，该运算符将被用作当前行数学文本的对齐点。可能的取值范围：1..255 默认值：0（无显式换行）

```cpp
uint8_t Aspose::Slides::MathText::MathBox::get_ExplicitBreak() override
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
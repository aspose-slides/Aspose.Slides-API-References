---
title: set_ExplicitBreak()
second_title: Aspose.Slides for C++ API 参考
description: "Explicit break 指定 Box 对象起始处是否存在换行，以便在 Box 对象的起始处换行。指定前一行数学文本中运算符的编号，该编号将用作当前数学文本行的对齐点。可能的取值范围：1..255 默认值：0（无显式换行）"
type: docs
weight: 131
url: /zh/aspose.slides.mathtext/imathbox/set_explicitbreak/
---
## IMathBox::set_ExplicitBreak(uint8_t) 方法


Explicit break 指定 Box 对象的开头是否存在换行，以便在 Box 对象的开头换行。指定前一行数学文本中 operator 的编号，该 operator 将用作当前数学文本行的对齐点。可能的取值范围: 1..255 默认值: 0（no explicit break）

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_ExplicitBreak(uint8_t value)=0
```

## 备注


示例： 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## 另见

* 类 [IMathBox](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)
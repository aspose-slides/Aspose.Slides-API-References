---
title: get_NoBreak()
second_title: Aspose.Slides for C++ API 参考
description: "无换行 此属性指定对象框的 \"unbreakable\" 属性。当为 true 时，框内不能出现换行。这对于包含多个二元运算符的运算符仿真器可能很重要。如果未指定此元素，则可以在框内换行。默认值： true"
type: docs
weight: 40
url: /zh/aspose.slides.mathtext/mathbox/get_nobreak/
---
## MathBox::get_NoBreak() 方法

No break 此属性指定对象框的 "unbreakable" 属性。为 true 时，框内不能出现换行。对于包含多个二元运算符的运算符仿真器，这可能很重要。如果未指定此元素，则可以在框内换行。默认值： true

```cpp
bool Aspose::Slides::MathText::MathBox::get_NoBreak() override
```

## 备注

示例：
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"*****"));
box->set_NoBreak(false);
```

## 另见

* 类 [MathBox](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)
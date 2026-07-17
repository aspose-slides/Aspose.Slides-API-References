---
title: set_NoBreak()
second_title: "Aspose.Slides C++ API 参考"
description: "无换行 此属性指定对象框的 \"unbreakable\" 属性。当为 true 时，框内不能出现换行。这对于由多个二元运算符组成的运算符仿真器可能很重要。当未指定此元素时，框内可以出现换行。默认： true"
type: docs
weight: 53
url: /zh/aspose.slides.mathtext/mathbox/set_nobreak/
---
## MathBox::set_NoBreak(bool) method

不换行 该属性指定对象框的“unbreakable”属性。 当为 true 时，框内不能出现换行。 这对于由多个二元运算符组成的运算符仿真器可能很重要。 当未指定此元素时，框内可以出现换行。 默认： true

```cpp
void Aspose::Slides::MathText::MathBox::set_NoBreak(bool value) override
```

## 备注

示例： 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"*****"));
box->set_NoBreak(false);
```

## 另请参见

* 类 [MathBox](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)
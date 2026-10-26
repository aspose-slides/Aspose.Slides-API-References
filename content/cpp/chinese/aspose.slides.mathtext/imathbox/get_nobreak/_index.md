---
title: get_NoBreak()
second_title: Aspose.Slides C++ API 参考
description: "无换行。此属性指定对象框的 \"unbreakable\" 属性。当为 true 时，框内不能出现换行符。这对由多个二元运算符组成的运算符仿真器可能很重要。当未指定此元素时，框内可以出现换行。默认值： true"
type: docs
weight: 40
url: /zh/aspose.slides.mathtext/imathbox/get_nobreak/
---
## IMathBox::get_NoBreak() 方法

无换行。此属性指定对象框的 \"unbreakable\" 属性。当为 true 时，框内不能出现换行符。这对由多个二元运算符组成的运算符仿真器可能很重要。当未指定此元素时，框内可以出现换行。默认值： true

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_NoBreak()=0
```

## 备注

示例：

```cpp
auto box = System::MakeObject<MathematicalText>(u"**********")->ToBox();
box->set_NoBreak(false);
```

## 另见

* 类 [IMathBox](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)
---
title: set_NoBreak()
second_title: Aspose.Slides C++ API 参考
description: "不换行。此属性指定对象框的 \"unbreakable\" 属性。当为 true 时，盒子内部不能出现换行。这对于包含多个二元运算符的操作符仿真器可能很重要。如果未指定此元素，盒子内部可能会出现换行。默认：true"
type: docs
weight: 53
url: /zh/aspose.slides.mathtext/imathbox/set_nobreak/
---
## IMathBox::set_NoBreak(bool) 方法

不换行。此属性指定对象框的“不可拆分”属性。当为 true 时，盒子内部不能出现换行。这对于包含多个二元运算符的操作符仿真器可能很重要。如果未指定此元素，盒子内部可能会出现换行。默认：true

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_NoBreak(bool value)=0
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
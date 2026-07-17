---
title: set_StrikethroughVertical()
second_title: Aspose.Slides for C++ API 参考
description: Strikethrough Vertical（默认值为 false）- 指定删除线垂直线的隐藏或显示状态。
type: docs
weight: 157
url: /zh/aspose.slides.mathtext/imathborderbox/set_strikethroughvertical/
---
## IMathBorderBox::set_StrikethroughVertical(bool) 方法


Strikethrough Vertical (default is false) - 指定删除线垂直线的隐藏或显示状态。

```cpp
virtual void Aspose::Slides::MathText::IMathBorderBox::set_StrikethroughVertical(bool value)=0
```

## 备注


示例: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_StrikethroughVertical(true);
```

## 另见

* 类 [IMathBorderBox](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)
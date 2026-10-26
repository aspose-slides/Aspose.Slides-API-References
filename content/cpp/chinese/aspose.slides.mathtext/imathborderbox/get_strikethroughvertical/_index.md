---
title: get_StrikethroughVertical()
second_title: Aspose.Slides for C++ API 参考
description: Strikethrough Vertical (默认值为 false) - 指定删除线垂直线的隐藏或显示状态。
type: docs
weight: 144
url: /zh/aspose.slides.mathtext/imathborderbox/get_strikethroughvertical/
---
## IMathBorderBox::get_StrikethroughVertical() 方法


Strikethrough Vertical (默认为 false) - 指定删除线垂直线的隐藏或显示状态。

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_StrikethroughVertical()=0
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
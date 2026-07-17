---
title: get_HideLeft()
second_title: Aspose.Slides for C++ API 参考
description: 隐藏左边缘（默认值为 false）- 指定边框框左边缘的隐藏或显示状态。
type: docs
weight: 66
url: /zh/aspose.slides.mathtext/imathborderbox/get_hideleft/
---
## IMathBorderBox::get_HideLeft() 方法

隐藏左边缘（默认值为 false） - 指定边框框左边缘的隐藏或显示状态。

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_HideLeft()=0
```

## 备注

示例:
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_HideLeft(true);
```

## 另见

* 类 [IMathBorderBox](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)
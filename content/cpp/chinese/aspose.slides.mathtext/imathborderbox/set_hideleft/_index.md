---
title: set_HideLeft()
second_title: Aspose.Slides for C++ API 参考
description: 隐藏左边缘（默认值为 false）- 指定边框框左边缘的隐藏或显示状态。
type: docs
weight: 79
url: /zh/aspose.slides.mathtext/imathborderbox/set_hideleft/
---
## IMathBorderBox::set_HideLeft(bool) 方法


隐藏左边缘（默认值为 false）- 指定边框框左边缘的隐藏或显示状态。

```cpp
virtual void Aspose::Slides::MathText::IMathBorderBox::set_HideLeft(bool value)=0
```

## 备注


示例： 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_HideLeft(true);
```

## 另请参见

* 类 [IMathBorderBox](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)
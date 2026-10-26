---
title: get_HideTop()
second_title: Aspose.Slides for C++ API 参考
description: 隐藏上边缘（默认值为 false）- 指定边框框的上边缘是隐藏还是显示的状态。
type: docs
weight: 14
url: /zh/aspose.slides.mathtext/imathborderbox/get_hidetop/
---
## IMathBorderBox::get_HideTop() 方法


隐藏上边缘（默认值为 false）- 指定边框框的上边缘是隐藏还是显示的状态。

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_HideTop()=0
```

## 备注


示例: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_HideTop(true);
```

## 另见

* 类 [IMathBorderBox](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)
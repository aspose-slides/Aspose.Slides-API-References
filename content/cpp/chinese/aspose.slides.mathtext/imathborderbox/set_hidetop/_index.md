---
title: set_HideTop()
second_title: Aspose.Slides for C++ API 参考
description: 隐藏顶部边缘（默认值为 false） - 指定边框框顶部边缘的隐藏或显示状态。
type: docs
weight: 27
url: /zh/aspose.slides.mathtext/imathborderbox/set_hidetop/
---
## IMathBorderBox::set_HideTop(bool) 方法

隐藏顶部边缘（默认值为 false） - 指定边框框顶部边缘的隐藏或显示状态。

```cpp
virtual void Aspose::Slides::MathText::IMathBorderBox::set_HideTop(bool value)=0
```

## 备注

示例：
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_HideTop(true);
```

## 另见

* 类 [IMathBorderBox](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)
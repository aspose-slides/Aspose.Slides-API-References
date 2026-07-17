---
title: set_HideRight()
second_title: Aspose.Slides C++ API 参考
description: 隐藏右边缘（默认值为 false）- 指定边框盒右边缘的隐藏或显示状态。
type: docs
weight: 105
url: /zh/aspose.slides.mathtext/imathborderbox/set_hideright/
---
## IMathBorderBox::set_HideRight(bool) 方法

隐藏右边缘（默认值为 false）- 指定边框盒右边缘的隐藏或显示状态。

```cpp
virtual void Aspose::Slides::MathText::IMathBorderBox::set_HideRight(bool value)=0
```

## 备注

示例：
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_HideRight(true);
```

## 另见

* 类 [IMathBorderBox](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)
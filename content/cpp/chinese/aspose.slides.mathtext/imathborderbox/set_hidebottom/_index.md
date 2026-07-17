---
title: set_HideBottom()
second_title: Aspose.Slides C++ API 参考
description: 隐藏底部边缘（默认值为 false） - 指定边框框底部边缘的隐藏或显示状态。
type: docs
weight: 53
url: /zh/aspose.slides.mathtext/imathborderbox/set_hidebottom/
---
## IMathBorderBox::set_HideBottom(bool) 方法

隐藏底部边缘（默认值为 false）- 指定边框框底部边缘的隐藏或显示状态。

```cpp
virtual void Aspose::Slides::MathText::IMathBorderBox::set_HideBottom(bool value)=0
```

## 备注

示例：
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_HideBottom(true);
```

## 另请参阅

* 类 [IMathBorderBox](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)
---
title: get_HideBottom()
second_title: Aspose.Slides for C++ API 参考
description: 隐藏底部边缘（默认值为 false）- 指定边框框的底部边缘是隐藏还是显示状态。
type: docs
weight: 40
url: /zh/aspose.slides.mathtext/imathborderbox/get_hidebottom/
---
## IMathBorderBox::get_HideBottom() 方法


隐藏底部边缘（默认值为 false）- 指定边框框的底部边缘是隐藏还是显示状态。

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_HideBottom()=0
```

## 备注


示例: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_HideBottom(true);
```

## 另见

* 类 [IMathBorderBox](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)
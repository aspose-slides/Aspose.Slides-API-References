---
title: set_StrikethroughBottomLeftToTopRight()
second_title: Aspose.Slides for C++ API 参考
description: 从左下角到右上角的删除线（默认值为 false）。指定边框框左下角到右上角的对角删除线的隐藏或显示状态。
type: docs
weight: 183
url: /zh/aspose.slides.mathtext/imathborderbox/set_strikethroughbottomlefttotopright/
---
## IMMathBorderBox::set_StrikethroughBottomLeftToTopRight(bool) 方法

从左下角到右上角的删除线（默认值为 false）。指定边框框左下角到右上角的对角删除线的隐藏或显示状态。

```cpp
virtual void Aspose::Slides::MathText::IMathBorderBox::set_StrikethroughBottomLeftToTopRight(bool value)=0
```

## 备注

示例：
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_StrikethroughBottomLeftToTopRight(true);
```

## 另请参见

* 类 [IMathBorderBox](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)
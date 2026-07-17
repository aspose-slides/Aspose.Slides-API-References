---
title: set_StrikethroughBottomLeftToTopRight()
second_title: Aspose.Slides C++ API 参考
description: 从左下角到右上角的删除线（默认值为 false）。指定边框框左下角到右上角对角线删除线的隐藏或显示状态。
type: docs
weight: 183
url: /zh/aspose.slides.mathtext/mathborderbox/set_strikethroughbottomlefttotopright/
---
## MathBorderBox::set_StrikethroughBottomLeftToTopRight(bool) 方法

从左下角到右上角的删除线（默认值为 false）。指定边框框从左下角到右上角的对角线删除线的隐藏或显示状态。

```cpp
void Aspose::Slides::MathText::MathBorderBox::set_StrikethroughBottomLeftToTopRight(bool value) override
```
## 备注

示例： 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
borderBox->set_StrikethroughBottomLeftToTopRight(true);
```
## 另请参阅

* 类 [MathBorderBox](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)
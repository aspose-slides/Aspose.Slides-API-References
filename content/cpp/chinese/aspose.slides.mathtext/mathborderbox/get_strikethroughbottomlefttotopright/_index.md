---
title: get_StrikethroughBottomLeftToTopRight()
second_title: Aspose.Slides for C++ API 参考
description: 从左下角到右上角的删除线（默认值为 false）。指定边框框中从左下角到右上角的对角线删除线的隐藏或显示状态。
type: docs
weight: 170
url: /zh/aspose.slides.mathtext/mathborderbox/get_strikethroughbottomlefttotopright/
---
## MathBorderBox::get_StrikethroughBottomLeftToTopRight() 方法

Strikethrough Bottom-Left to Top-Right（默认值为 false）。指定从左下角到右上角的删除线对角线在边框框中的隐藏或显示状态。

```cpp
bool Aspose::Slides::MathText::MathBorderBox::get_StrikethroughBottomLeftToTopRight() override
```

## 备注

示例:
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
borderBox->set_StrikethroughBottomLeftToTopRight(true);
```

## 另请参阅

* 类 [MathBorderBox](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)
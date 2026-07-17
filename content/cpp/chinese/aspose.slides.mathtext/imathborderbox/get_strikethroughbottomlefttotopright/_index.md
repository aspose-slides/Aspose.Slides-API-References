---
title: get_StrikethroughBottomLeftToTopRight()
second_title: Aspose.Slides C++ API 参考
description: 从左下角到右上角的删除线（默认值为 false）。指定边框框左下角到右上角的删除对角线的隐藏或显示状态。
type: docs
weight: 170
url: /zh/aspose.slides.mathtext/imathborderbox/get_strikethroughbottomlefttotopright/
---
## IMathBorderBox::get_StrikethroughBottomLeftToTopRight() 方法

从左下角到右上角的删除线（默认值为 false）。指定从边框框左下角到右上角的删除对角线的隐藏或显示状态。

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_StrikethroughBottomLeftToTopRight()=0
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
---
title: set_StrikethroughHorizontal()
second_title: Aspose.Slides for C++ API 参考
description: Strikethrough Horizontal（默认值为 false） - 指定水平删除线的隐藏或显示状态。
type: docs
weight: 131
url: /zh/aspose.slides.mathtext/imathborderbox/set_strikethroughhorizontal/
---
## IMathBorderBox::set_StrikethroughHorizontal(bool) 方法

Strikethrough Horizontal（默认值为 false） - 指定删除线水平线的隐藏或显示状态。

```cpp
virtual void Aspose::Slides::MathText::IMathBorderBox::set_StrikethroughHorizontal(bool value)=0
```

## 备注

示例：
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_StrikethroughHorizontal(true);
```

## 另请参阅

* 类 [IMathBorderBox](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)
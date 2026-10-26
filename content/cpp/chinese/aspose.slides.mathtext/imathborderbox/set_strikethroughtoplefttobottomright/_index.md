---
title: set_StrikethroughTopLeftToBottomRight()
second_title: Aspose.Slides C++ API 参考
description: 从左上到右下的删除线（默认值为 false）。指定从左上角到右下角的删除对角线的隐藏或显示状态。
type: docs
weight: 209
url: /zh/aspose.slides.mathtext/imathborderbox/set_strikethroughtoplefttobottomright/
---
## IMathBorderBox::set_StrikethroughTopLeftToBottomRight(bool) 方法

从左上到右下的删除线 (默认值为 false)。指定从边框框的左上角到右下角的删除对角线的隐藏或显示状态。

```cpp
virtual void Aspose::Slides::MathText::IMathBorderBox::set_StrikethroughTopLeftToBottomRight(bool value)=0
```

## 备注

示例：
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_StrikethroughTopLeftToBottomRight(true);
```

## 另见

* 类 [IMathBorderBox](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)
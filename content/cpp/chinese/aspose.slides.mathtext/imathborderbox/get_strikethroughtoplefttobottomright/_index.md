---
title: get_StrikethroughTopLeftToBottomRight()
second_title: Aspose.Slides for C++ API 参考
description: 从左上角到右下角的删除线（默认值为 false）。指定边框框中从左上角到右下角的删除对角线的隐藏或显示状态。
type: docs
weight: 196
url: /zh/aspose.slides.mathtext/imathborderbox/get_strikethroughtoplefttobottomright/
---
## IMathBorderBox::get_StrikethroughTopLeftToBottomRight() 方法


从左上角到右下角的删除线（默认值为 false）。指定边框框中从左上角到右下角的删除斜线的隐藏或显示状态。

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_StrikethroughTopLeftToBottomRight()=0
```

## 备注


示例： 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_StrikethroughTopLeftToBottomRight(true);
```

## 另请参见

* 类 [IMathBorderBox](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)
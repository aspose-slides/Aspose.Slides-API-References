---
title: get_StrikethroughVertical()
second_title: Aspose.Slides for C++ API 參考
description: Strikethrough Vertical (預設為 false) - 指定刪除線垂直線的隱藏或顯示狀態。
type: docs
weight: 144
url: /zh-hant/aspose.slides.mathtext/imathborderbox/get_strikethroughvertical/
---
## IMathBorderBox::get_StrikethroughVertical() 方法

Strikethrough Vertical (default is false) - specifies the hidden or shown state of a strikethrough vertical line.

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_StrikethroughVertical()=0
```

## 備註

範例：
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_StrikethroughVertical(true);
```

## 另見

* 類別 [IMathBorderBox](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)
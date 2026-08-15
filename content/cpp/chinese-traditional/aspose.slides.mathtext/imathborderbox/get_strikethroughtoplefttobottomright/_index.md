---
title: get_StrikethroughTopLeftToBottomRight()
second_title: Aspose.Slides for C++ API 參考文件
description: 從左上到右下的刪除線（預設為 false）。指定邊框盒左上角到右下角的刪除線對角線的隱藏或顯示狀態。
type: docs
weight: 196
url: /zh-hant/aspose.slides.mathtext/imathborderbox/get_strikethroughtoplefttobottomright/
---
## IMathBorderBox::get_StrikethroughTopLeftToBottomRight() 方法

Strikethrough Top-Left to Bottom-Right (default is false)。指定從左上角到右下角的刪除線對角線的隱藏或顯示狀態。

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_StrikethroughTopLeftToBottomRight()=0
```

## 備註

範例：
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_StrikethroughTopLeftToBottomRight(true);
```

## 參見

* 類別 [IMathBorderBox](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)
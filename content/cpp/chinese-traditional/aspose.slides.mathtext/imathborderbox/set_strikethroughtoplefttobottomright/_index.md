---
title: set_StrikethroughTopLeftToBottomRight()
second_title: Aspose.Slides C++ API 參考
description: 從左上角到右下角的刪除線（預設為 false）。指定在邊框盒左上角到右下角的對角刪除線的隱藏或顯示狀態。
type: docs
weight: 209
url: /zh-hant/aspose.slides.mathtext/imathborderbox/set_strikethroughtoplefttobottomright/
---
## IMathBorderBox::set_StrikethroughTopLeftToBottomRight(bool) 方法

從左上角到右下角的刪除線（預設為 false）。指定在邊框盒左上角到右下角的斜線刪除線的隱藏或顯示狀態。

```cpp
virtual void Aspose::Slides::MathText::IMathBorderBox::set_StrikethroughTopLeftToBottomRight(bool value)=0
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
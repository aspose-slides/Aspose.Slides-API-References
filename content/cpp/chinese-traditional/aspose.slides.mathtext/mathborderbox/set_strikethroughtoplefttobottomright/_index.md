---
title: set_StrikethroughTopLeftToBottomRight()
second_title: Aspose.Slides C++ API 參考
description: 從左上角到右下角的刪除線（預設為 false）。指定邊框盒左上角至右下角的刪除線對角線的隱藏或顯示狀態。
type: docs
weight: 209
url: /zh-hant/aspose.slides.mathtext/mathborderbox/set_strikethroughtoplefttobottomright/
---
## MathBorderBox::set_StrikethroughTopLeftToBottomRight(bool) 方法


從左上角到右下角的刪除線 (預設為 false)。指定從左上角到右下角的刪除線對角線在邊框盒中的隱藏或顯示狀態。

```cpp
void Aspose::Slides::MathText::MathBorderBox::set_StrikethroughTopLeftToBottomRight(bool value) override
```

## 備註


範例： 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
borderBox->set_StrikethroughTopLeftToBottomRight(true);
```

## 參見

* 類別 [MathBorderBox](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)
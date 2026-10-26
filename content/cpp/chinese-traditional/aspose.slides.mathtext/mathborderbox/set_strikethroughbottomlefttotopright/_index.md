---
title: set_StrikethroughBottomLeftToTopRight()
second_title: Aspose.Slides C++ API 參考文件
description: 刪除線從左下角到右上角（預設為 false）。指定在邊框盒中從左下角到右上角的刪除線對角線的隱藏或顯示狀態。
type: docs
weight: 183
url: /zh-hant/aspose.slides.mathtext/mathborderbox/set_strikethroughbottomlefttotopright/
---
## MathBorderBox::set_StrikethroughBottomLeftToTopRight(bool) 方法

Strikethrough Bottom-Left to Top-Right (default is false)。指定在邊框盒中從左下角到右上角的刪除線對角線的隱藏或顯示狀態。

```cpp
void Aspose::Slides::MathText::MathBorderBox::set_StrikethroughBottomLeftToTopRight(bool value) override
```

## 備註


範例： 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
borderBox->set_StrikethroughBottomLeftToTopRight(true);
```

## 另見

* 類別 [MathBorderBox](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)
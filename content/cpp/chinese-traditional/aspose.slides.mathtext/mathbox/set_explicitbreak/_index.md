---
title: set_ExplicitBreak()
second_title: Aspose.Slides for C++ API 參考
description: "顯式換行指定在 Box 物件的起始是否有換行，以便行在 Box 物件的起始處換行。指定先前數學文字行中的運算子編號，作為當前數學文字行的對齊點。可能的值：1..255 預設值：0（無顯式換行）"
type: docs
weight: 131
url: /zh-hant/aspose.slides.mathtext/mathbox/set_explicitbreak/
---
## MathBox::set_ExplicitBreak(uint8_t) 方法


顯式換行指定在 Box 物件的起始是否有換行，從而使行在 Box 物件的起始換行。指定先前數學文字行中用作當前數學文字行對齊點的運算子編號。可能的值：1..255 預設值：0（無顯式換行）

```cpp
void Aspose::Slides::MathText::MathBox::set_ExplicitBreak(uint8_t value) override
```

## 備註


範例： 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## 另見

* 類別 [MathBox](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)
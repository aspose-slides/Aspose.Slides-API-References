---
title: get_ExplicitBreak()
second_title: Aspose.Slides for C++ API 參考
description: "Explicit break 指定 Box 物件的起始處是否有換行，以便行在 Box 物件的起始處換行。指定先前數學文字行中運算子的編號，該編號將作為當前數學文字行的對齊點。可能的取值範圍：1..255 預設值：0（no explicit break）"
type: docs
weight: 118
url: /zh-hant/aspose.slides.mathtext/mathbox/get_explicitbreak/
---
## MathBox::get_ExplicitBreak() 方法


Explicit break 指定 Box 物件的起始處是否有換行，使得行在 Box 物件的起始處換行。指定先前數學文字行中之運算子編號，該編號將作為目前數學文字行的對齊點。可能的取值範圍：1..255 預設值：0（no explicit break）

```cpp
uint8_t Aspose::Slides::MathText::MathBox::get_ExplicitBreak() override
```

## 備註


範例:
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## 另見

* 類別 [MathBox](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)
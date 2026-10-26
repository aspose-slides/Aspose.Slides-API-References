---
title: get_ExplicitBreak()
second_title: Aspose.Slides C++ API 參考
description: "Explicit break 指定在 Box 物件的開始是否有換行，使行在 Box 物件的起始處換行。指定先前數學文字行中運算子的位置編號，該編號將作為目前數學文字行的對齊點。可能的值：1..255 預設值：0（無 explicit break）"
type: docs
weight: 118
url: /zh-hant/aspose.slides.mathtext/imathbox/get_explicitbreak/
---
## IMathBox::get_ExplicitBreak() 方法

Explicit break 指定在 Box 物件的開始是否有換行，以致行在 Box 物件的開始處換行。指定先前數學文字行中用作目前數學文字行對齊點的運算子編號。可能的值：1..255 預設：0（沒有 explicit break）

```cpp
virtual uint8_t Aspose::Slides::MathText::IMathBox::get_ExplicitBreak()=0
```

## 備註

範例：
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## 另見

* 類別 [IMathBox](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)
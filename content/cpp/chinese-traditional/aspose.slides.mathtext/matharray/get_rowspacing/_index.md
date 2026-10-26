---
title: get_RowSpacing()
second_title: 適用於 C++ 的 Aspose.Slides API 參考
description: "陣列中列之間的間距 僅在 RowSpacingRule 設為 3 時使用 Exactly，此時的測量單位為點；或在 Multiple 時測量單位為半行。Default: 0"
type: docs
weight: 118
url: /zh-hant/aspose.slides.mathtext/matharray/get_rowspacing/
---
## MathArray::get_RowSpacing() method

陣列中列之間的間距 僅在 RowSpacingRule 設為 3 時使用 Exactly 在此情況下的測量單位為點，或 Multiple 在此情況下的測量單位為半行。Default: 0

```cpp
uint32_t Aspose::Slides::MathText::MathArray::get_RowSpacing() override
```

## 備註

範例：
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## 另見

* 類別 [MathArray](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 程式庫 [Aspose.Slides](../../../)
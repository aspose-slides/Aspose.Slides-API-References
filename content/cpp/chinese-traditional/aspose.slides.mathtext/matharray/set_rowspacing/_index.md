---
title: set_RowSpacing()
second_title: Aspose.Slides for C++ API 參考
description: "陣列中行與行之間的間距。僅在 RowSpacingRule 設為 3 時使用，此時度量單位為點；或在設為 Multiple 時，度量單位為半行。預設值：0"
type: docs
weight: 131
url: /zh-hant/aspose.slides.mathtext/matharray/set_rowspacing/
---
## MathArray::set_RowSpacing(uint32_t) 方法


陣列中行與行之間的間距。僅在 RowSpacingRule 設為 3 時使用，此時度量單位為點；或在設為 Multiple 時，度量單位為半行。預設值：0

```cpp
void Aspose::Slides::MathText::MathArray::set_RowSpacing(uint32_t value) override
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
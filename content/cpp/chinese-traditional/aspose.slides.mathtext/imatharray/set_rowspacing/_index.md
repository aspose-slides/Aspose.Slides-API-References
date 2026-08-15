---
title: set_RowSpacing()
second_title: Aspose.Slides for C++ API 參考
description: "陣列列之間的間距 僅在 RowSpacingRule 設為 3 時使用 若為 Exact，度量單位為點；若為 Multiple，度量單位為半行。預設：0"
type: docs
weight: 131
url: /zh-hant/aspose.slides.mathtext/imatharray/set_rowspacing/
---
## IMathArray::set_RowSpacing(uint32_t) 方法


陣列列之間的間距 僅在 RowSpacingRule 設為 3 時使用 為此情況，度量單位為點 或 Multiple 時，度量單位為半行。預設:0

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_RowSpacing(uint32_t value)=0
```

## 備註


範例:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## 另見

* 類別 [IMathArray](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)
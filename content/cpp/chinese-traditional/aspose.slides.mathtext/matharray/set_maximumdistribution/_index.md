---
title: set_MaximumDistribution()
second_title: Aspose.Slides for C++ API 參考
description: Maximum Distribution 為 true 時，陣列會依據包含元素（頁面、欄、儲存格等）的最大寬度進行間距。
type: docs
weight: 53
url: /zh-hant/aspose.slides.mathtext/matharray/set_maximumdistribution/
---
## MathArray::set_MaximumDistribution(bool) 方法


Maximum Distribution 為 true 時，陣列會以包含元素（頁面、欄、儲存格等）的最大寬度進行間距。

```cpp
void Aspose::Slides::MathText::MathArray::set_MaximumDistribution(bool value) override
```

## 備註


範例： 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_MaximumDistribution(true);
```

## 另見

* 類別 [MathArray](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)
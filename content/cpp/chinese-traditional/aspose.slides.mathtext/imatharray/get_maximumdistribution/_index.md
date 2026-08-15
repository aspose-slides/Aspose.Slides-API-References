---
title: get_MaximumDistribution()
second_title: Aspose.Slides for C++ API 參考文件
description: Maximum Distribution 當為 true 時，陣列會依據包含元素（page、column、cell 等）的最大寬度進行間距調整。
type: docs
weight: 40
url: /zh-hant/aspose.slides.mathtext/imatharray/get_maximumdistribution/
---
## IMathArray::get_MaximumDistribution() method


Maximum Distribution 當為 true 時，陣列會依據包含元素(page, column, cell, etc.)的最大寬度進行間距調整。

```cpp
virtual bool Aspose::Slides::MathText::IMathArray::get_MaximumDistribution()=0
```

## 備註


範例： 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_MaximumDistribution(true);
```

## 另請參閱

* 類別 [IMathArray](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)
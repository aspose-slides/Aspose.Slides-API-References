---
title: get_RowGap()
second_title: Aspose.Slides for C++ API 參考文件
description: "矩陣行之間的垂直間距值；如果 RowGapRule 設為 3（\"Exactly\"），則單位解釋為 twips（1/20 點） 如果 RowGapRule 設為 4（\"Multiple\"），則單位解釋為半行。預設：0"
type: docs
weight: 183
url: /zh-hant/aspose.slides.mathtext/imathmatrix/get_rowgap/
---
## IMathMatrix::get_RowGap() 方法

矩陣行之間的垂直間距值；如果 RowGapRule 設為 3（"Exactly"），則單位視為 twips（1/20 點） 如果 RowGapRule 設為 4（"Multiple"），則單位視為半行。預設值：0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_RowGap()=0
```

## 備註

範例：
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## 另請參閱

* 類別 [IMathMatrix](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)
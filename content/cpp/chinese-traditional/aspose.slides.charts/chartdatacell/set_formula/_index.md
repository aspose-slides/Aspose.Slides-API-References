---
title: set_Formula()
second_title: Aspose.Slides for C++ API 參考
description: 以 A1 風格設定公式。
type: docs
weight: 66
url: /zh-hant/aspose.slides.charts/chartdatacell/set_formula/
---
## ChartDataCell::set_Formula(System::String) method


以 A1 風格設定公式。

```cpp
void Aspose::Slides::Charts::ChartDataCell::set_Formula(System::String value) override
```

## 備註



```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [ChartDataCell](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 程式庫 [Aspose.Slides](../../../)
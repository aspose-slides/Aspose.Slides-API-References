---
title: get_Formula()
second_title: Aspose.Slides for C++ API 參考
description: 取得 A1 風格的公式。
type: docs
weight: 53
url: /zh-hant/aspose.slides.charts/chartdatacell/get_formula/
---
## ChartDataCell::get_Formula() 方法


取得 A1 風格的公式。

```cpp
System::String Aspose::Slides::Charts::ChartDataCell::get_Formula() override
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
* 函式庫 [Aspose.Slides](../../../)
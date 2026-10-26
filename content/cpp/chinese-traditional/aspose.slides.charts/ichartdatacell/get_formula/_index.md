---
title: get_Formula()
second_title: Aspose.Slides C++ API 參考
description: 取得 A1 風格的公式。
type: docs
weight: 53
url: /zh-hant/aspose.slides.charts/ichartdatacell/get_formula/
---
## IChartDataCell::get_Formula() 方法


取得 A1 風格的公式。

```cpp
virtual System::String Aspose::Slides::Charts::IChartDataCell::get_Formula()=0
```

## 備註



```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [IChartDataCell](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)
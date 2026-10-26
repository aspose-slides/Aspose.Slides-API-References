---
title: set_Formula()
second_title: Aspose.Slides C++ API 參考
description: 以 A1 風格設定公式。
type: docs
weight: 66
url: /zh-hant/aspose.slides.charts/ichartdatacell/set_formula/
---
## IChartDataCell::set_Formula(System::String) 方法


設定 A1 風格的公式。

```cpp
virtual void Aspose::Slides::Charts::IChartDataCell::set_Formula(System::String value)=0
```

## 備註



```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## 相關參考

* 類別 [String](../../../system/string/)
* 類別 [IChartDataCell](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)
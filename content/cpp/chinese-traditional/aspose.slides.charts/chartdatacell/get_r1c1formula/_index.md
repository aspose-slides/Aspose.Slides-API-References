---
title: get_R1C1Formula()
second_title: Aspose.Slides for C++ API 參考
description: 取得 R1C1 風格的公式。
type: docs
weight: 79
url: /zh-hant/aspose.slides.charts/chartdatacell/get_r1c1formula/
---
## ChartDataCell::get_R1C1Formula() 方法


取得 R1C1 風格的公式。

```cpp
System::String Aspose::Slides::Charts::ChartDataCell::get_R1C1Formula() override
```

## 備註



```cpp
auto cell = workbook->GetCell(0, u"C2");
cell->set_R1C1Formula(u"MAX(R2C6:R5C8) / 3");
```

## 另見

* 類別 [String](../../../system/string/)
* 類別 [ChartDataCell](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)
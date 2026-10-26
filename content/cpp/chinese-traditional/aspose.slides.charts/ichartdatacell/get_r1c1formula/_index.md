---
title: get_R1C1Formula()
second_title: Aspose.Slides for C++ API 參考
description: 取得 R1C1 風格的公式。
type: docs
weight: 79
url: /zh-hant/aspose.slides.charts/ichartdatacell/get_r1c1formula/
---
## IChartDataCell::get_R1C1Formula() 方法


取得 R1C1 風格的公式。

```cpp
virtual System::String Aspose::Slides::Charts::IChartDataCell::get_R1C1Formula()=0
```

## 備註



```cpp
auto cell = workbook->GetCell(0, u"C2");
cell->set_R1C1Formula(u"MAX(R2C6:R5C8) / 3");
```

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [IChartDataCell](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)
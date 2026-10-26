---
title: set_R1C1Formula()
second_title: Aspose.Slides for C++ API 參考
description: 以 R1C1 風格設定公式。
type: docs
weight: 92
url: /zh-hant/aspose.slides.charts/chartdatacell/set_r1c1formula/
---
## ChartDataCell::set_R1C1Formula(System::String) 方法


以 R1C1 風格設定公式。

```cpp
void Aspose::Slides::Charts::ChartDataCell::set_R1C1Formula(System::String value) override
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
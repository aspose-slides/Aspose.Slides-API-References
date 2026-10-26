---
title: set_R1C1Formula()
second_title: Aspose.Slides for C++ API 參考
description: 以 R1C1 風格設定公式。
type: docs
weight: 92
url: /zh-hant/aspose.slides.charts/ichartdatacell/set_r1c1formula/
---
## IChartDataCell::set_R1C1Formula(System::String) 方法

設定 R1C1 風格的公式。

```cpp
virtual void Aspose::Slides::Charts::IChartDataCell::set_R1C1Formula(System::String value)=0
```

## 備註

```cpp
auto cell = workbook->GetCell(0, u"C2");
cell->set_R1C1Formula(u"MAX(R2C6:R5C8) / 3");
```

## 另見

* Class [String](../../../system/string/)
* Class [IChartDataCell](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
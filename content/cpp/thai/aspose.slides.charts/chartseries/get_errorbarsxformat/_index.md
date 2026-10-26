---
title: get_ErrorBarsXFormat()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แทน ErrorBars ของซีรีส์ที่มีทิศทาง X.
type: docs
weight: 222
url: /th/aspose.slides.charts/chartseries/get_errorbarsxformat/
---
## ChartSeries::get_ErrorBarsXFormat() เมธอด

แทน ErrorBars ของซีรีส์ที่มีทิศทาง X.

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsXFormat() override
```

## หมายเหตุ

ErrorBars ที่มีทิศทาง X มีให้ใช้สำหรับซีรีส์ประเภท area, bar, scatter และ bubble. สำหรับประเภทแผนภูมิอื่น ๆ คุณสมบัตินี้จะคืนค่า null (รวมถึงแผนภูมิ 3D). ในกรณีที่ต้องการค่ากำหนดเองให้ใช้คอลเลกชัน DataPoints เพื่อระบุค่า (พร้อมคุณสมบัติ [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)).

อ่านอย่างเดียว [IErrorBarsFormat](../../ierrorbarsformat/). 
## ดูเพิ่มเติม

* ประเภทกำหนด [SharedPtr](../../../system/sharedptr/)
* คลาส [IErrorBarsFormat](../../ierrorbarsformat/)
* คลาส [ChartSeries](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)
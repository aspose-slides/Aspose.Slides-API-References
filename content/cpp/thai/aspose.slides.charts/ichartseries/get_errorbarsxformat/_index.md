---
title: get_ErrorBarsXFormat()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: แสดง ErrorBars ของซีรีส์ที่มีทิศทาง X.
type: docs
weight: 222
url: /th/aspose.slides.charts/ichartseries/get_errorbarsxformat/
---
## IChartSeries::get_ErrorBarsXFormat() เมธอด


แสดง ErrorBars ของซีรีส์ที่มีทิศทาง X.

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsXFormat()=0
```

## หมายเหตุ


ErrorBars ที่มีทิศทาง X มีให้ใช้สำหรับซีรีส์ประเภท area, bar, scatter และ bubble. สำหรับประเภทแผนภูมิอื่น ๆ คุณสมบัตินี้จะคืนค่า null (รวมถึงแผนภูมิ 3D). ในกรณีที่ต้องการค่าที่กำหนดเองให้ใช้คอลเลกชัน DataPoints เพื่อระบุค่า (กับคุณสมบัติ [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)). 

อ่านอย่างเดียว [IErrorBarsFormat](../../ierrorbarsformat/). 
## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IErrorBarsFormat](../../ierrorbarsformat/)
* คลาส [IChartSeries](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)
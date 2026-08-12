---
title: get_ErrorBarsYFormat()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: แสดง ErrorBars ของซีรีส์ที่มีทิศทาง Y.
type: docs
weight: 235
url: /th/aspose.slides.charts/ichartseries/get_errorbarsyformat/
---
## IChartSeries::get_ErrorBarsYFormat() เมธอด


แสดง ErrorBars ของซีรีส์ที่มีทิศทาง Y.

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsYFormat()=0
```

## หมายเหตุ


ErrorBars ที่มีทิศทาง Y สามารถใช้ได้กับซีรีส์ประเภท area, bar, line, scatter และ bubble. สำหรับประเภทแผนภูมิอื่น ๆ คุณสมบัตินี้จะคืนค่า null (รวมถึงแผนภูมิ 3D). ในกรณีที่ต้องการค่าที่กำหนดเองให้ใช้คอลเลกชัน DataPoints เพื่อระบุค่า (ด้วยคุณสมบัติ [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)). 

อ่านอย่างเดียว [IErrorBarsFormat](../../ierrorbarsformat/). 
## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IErrorBarsFormat](../../ierrorbarsformat/)
* คลาส [IChartSeries](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
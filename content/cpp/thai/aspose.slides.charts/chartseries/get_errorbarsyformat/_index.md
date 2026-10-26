---
title: get_ErrorBarsYFormat()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดง ErrorBars ของซีรีส์ที่มีทิศทาง Y.
type: docs
weight: 235
url: /th/aspose.slides.charts/chartseries/get_errorbarsyformat/
---
## ChartSeries::get_ErrorBarsYFormat() เมธอด

แสดง ErrorBars ของซีรีส์ที่มีทิศทาง Y.

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsYFormat() override
```

## หมายเหตุ

ErrorBars ที่มีทิศทาง Y สามารถใช้ได้สำหรับซีรีส์ชนิด area, bar, line, scatter และ bubble. สำหรับชนิดแผนภูมิอื่น ๆ คุณสมบัตินี้จะคืนค่า null (รวมถึงแผนภูมิ 3D). ในกรณีที่ต้องการค่าแบบกำหนดเอง ให้ใช้คอลเลกชัน DataPoints เพื่อระบุค่า (กับคุณสมบัติ [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)).

อ่านอย่างเดียว [IErrorBarsFormat](../../ierrorbarsformat/). 
## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IErrorBarsFormat](../../ierrorbarsformat/)
* คลาส [ChartSeries](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)
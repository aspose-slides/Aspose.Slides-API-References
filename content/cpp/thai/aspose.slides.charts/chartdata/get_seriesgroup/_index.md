---
title: get_SeriesGroup()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: 
type: docs
weight: 222
url: /th/aspose.slides.charts/chartdata/get_seriesgroup/
---
## ChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) เมธอด

```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries) override
```

## ChartData::get_SeriesGroup(int32_t) เมธอด

ส่งกลับกลุ่มของซีรีส์ที่ตำแหน่งดัชนีที่ระบุ

```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(int32_t index) override
```

## หมายเหตุ

1) แต่ละกลุ่มของซีรีส์จะประกอบด้วยซีรีส์ที่มีประเภทที่สามารถรวมกันได้ กลุ่มของประเภทซีรีส์ที่สามารถรวมกันได้ถูกกำหนดและอธิบายด้วย enum CombinableSeriesTypesGroup นอกจากนี้แต่ละกลุ่มของซีรีส์จะประกอบด้วยซีรีส์ที่ถูกพล็อตบนแกนหลักหรือบนแกนรอง (ไม่ใช่ทั้งสองกรณีในหนึ่งกลุ่ม) ดังนั้นหลักการของการจัดกลุ่มซีรีส์คือการจัดกลุ่มตามประเภทที่กล่าวถึงข้างต้นและตามประเภทการพล็อตแกนหลัก/แกนรอง

2) กลุ่มของซีรีส์มีบางคุณลักษณะของซีรีส์ที่เป็นร่วมกันสำหรับแต่ละซีรีส์ในกลุ่ม ("series group properties") "Series group properties" ในคลาส [ChartSeriesGroup](../../chartseriesgroup/) เป็นอ่าน/เขียน แต่ละ "series group properties" สามารถมีการฉายภาพอ่านอย่างเดียวในคลาส [ChartSeries](../../chartseries/)

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IChartSeriesGroup](../../ichartseriesgroup/)
* คลาส [IChartSeries](../../ichartseries/)
* คลาส [ChartData](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
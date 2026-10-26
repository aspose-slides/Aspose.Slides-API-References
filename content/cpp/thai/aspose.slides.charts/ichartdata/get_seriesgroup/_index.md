---
title: get_SeriesGroup()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: 
type: docs
weight: 222
url: /th/aspose.slides.charts/ichartdata/get_seriesgroup/
---
## IChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) เมธอด




```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries)=0
```

## IChartData::get_SeriesGroup(int32_t) เมธอด

คืนค่ากลุ่มของชุดข้อมูลที่ดัชนีที่ระบุ.

```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(int32_t index)=0
```

## หมายเหตุ

1) แต่ละกลุ่มของชุดข้อมูลประกอบด้วยชุดข้อมูลที่มีประเภทที่สามารถผสานรวมกันได้. กลุ่มของประเภทชุดข้อมูลที่สามารถผสานรวมกันได้ถูกกำหนดและอธิบายด้วย enum CombinableSeriesTypesGroup. นอกจากนี้แต่ละกลุ่มของชุดข้อมูลยังมีชุดข้อมูลที่ถูกพล็อตบนแกนหลักหรือแกนรอง (ไม่ใช่ทั้งสองกรณีในกลุ่มเดียวกัน). ดังนั้นหลักการของการจัดกลุ่มชุดข้อมูลคือการจัดกลุ่มตามประเภทที่กล่าวถึงข้างต้นและตามประเภทการพล็อตหลัก/รอง. 2) กลุ่มของชุดข้อมูลมีคุณสมบัติของชุดข้อมูลบางอย่างซึ่งเป็นคุณสมบัติร่วมสำหรับแต่ละชุดข้อมูลในกลุ่ม ("series group properties"). "Series group properties" ในคลาส [ChartSeriesGroup](../../chartseriesgroup/) เป็นแบบอ่าน/เขียน. แต่ละ "series group properties" สามารถมีการฉายแบบอ่านอย่างเดียวในคลาส [ChartSeries](../../chartseries/).

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartSeriesGroup](../../ichartseriesgroup/)
* Class [IChartSeries](../../ichartseries/)
* Class [IChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
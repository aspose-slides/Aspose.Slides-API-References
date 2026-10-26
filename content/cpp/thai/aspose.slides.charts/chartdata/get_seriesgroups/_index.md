---
title: get_SeriesGroups()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: รับกลุ่มของ series. อ่านอย่างเดียว IChartSeriesGroupCollection.
type: docs
weight: 27
url: /th/aspose.slides.charts/chartdata/get_seriesgroups/
---
## ChartData::get_SeriesGroups() เมธอด

รับกลุ่มของ series. อ่านอย่างเดียว [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::ChartData::get_SeriesGroups() override
```

## หมายเหตุ

1) แต่ละกลุ่มของ series มี series ที่มีประเภทที่สามารถผสานกันได้. กลุ่มของประเภท series ที่สามารถผสานกันได้ถูกกำหนดและอธิบายด้วย enum CombinableSeriesTypesGroup. นอกจากนี้แต่ละกลุ่มของ series มี series ที่ถูกพล็อตบนแกนหลักหรือบนแกนรอง (ไม่ใช่ทั้งสองกรณีในกลุ่มเดียว). ดังนั้นหลักการของการจัดกลุ่ม series คือการจัดกลุ่มตามประเภทที่กล่าวถึงข้างต้นและตามประเภทการพล็อตแกนหลัก/แกนรอง.

2) กลุ่มของ series มีบางคุณสมบัติของ series ที่เป็นทั่วไปสำหรับแต่ละ series ในกลุ่ม ("series group properties"). "Series group properties" ในคลาส [ChartSeriesGroup](../../chartseriesgroup/) เป็นอ่าน/เขียน. แต่ละ "series group properties" สามารถมีการฉายภาพอ่านอย่างเดียวในคลาส [ChartSeries](../../chartseries/).

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* คลาส [ChartData](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)
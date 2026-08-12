---
title: get_SeriesGroups()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ดึงกลุ่มของซีรีส์. อ่านอย่างเดียว IChartSeriesGroupCollection.
type: docs
weight: 27
url: /th/aspose.slides.charts/ichartdata/get_seriesgroups/
---
## IChartData::get_SeriesGroups() เมธอด


ดึงกลุ่มของซีรีส์. อ่านอย่างเดียว [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
virtual System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::IChartData::get_SeriesGroups()=0
```

## หมายเหตุ


1) แต่ละกลุ่มของซีรีส์ประกอบด้วยซีรีส์ที่มีประเภทที่สามารถรวมกันได้. กลุ่มของประเภทซีรีส์ที่สามารถรวมกันได้ถูกกำหนดและอธิบายด้วย CombinableSeriesTypesGroup enum. นอกจากนี้แต่ละกลุ่มของซีรีส์ยังประกอบด้วยซีรีส์ที่ถูกพล็อตบนแกนหลักหรือบนแกนรอง (ไม่ใช่ทั้งสองกรณีในหนึ่งกลุ่ม). ดังนั้นหลักการของการจัดกลุ่มซีรีส์คือการจัดกลุ่มตามประเภทที่กล่าวข้างต้นและตามประเภทการพล็อตแกนหลัก/แกนรอง.

2) กลุ่มของซีรีส์ประกอบด้วยคุณสมบัติบางอย่างของซีรีส์ที่เป็นร่วมกันสำหรับแต่ละซีรีส์ในกลุ่ม (\"กลุ่มคุณสมบัติของซีรีส์\"). \"กลุ่มคุณสมบัติของซีรีส์\" ในคลาส [ChartSeriesGroup](../../chartseriesgroup/) เป็นอ่านเขียน. แต่ละ \"กลุ่มคุณสมบัติของซีรีส์\" สามารถมีการฉายเป็นอ่านอย่างเดียวในคลาส [ChartSeries](../../chartseries/). 

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* คลาส [IChartData](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
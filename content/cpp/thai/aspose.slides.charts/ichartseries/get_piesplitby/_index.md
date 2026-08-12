---
title: get_PieSplitBy()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: กำหนดวิธีการระบุว่าจุดข้อมูลใดอยู่ในพายหรือแถบที่สองบนแผนภูมิแบบพายของพายหรือแถบของพาย. นี้คือคุณสมบัติที่ไม่ใช่เฉพาะของซีรีส์นี้เท่านั้น แต่รวมถึงซีรีส์ทั้งหมดของกลุ่มซีรีส์แม่ - ซึ่งเป็นการฉายของคุณสมบัติกลุ่มที่เหมาะสม. ดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มซีรีส์แม่. ใช้ get_ParentSeriesGroup()->get(set)_PieSplitBy() คุณสมบัติอ่าน/เขียนเพื่อเปลี่ยนค่า. อ่านอย่างเดียว PieSplitType.
type: docs
weight: 729
url: /th/aspose.slides.charts/ichartseries/get_piesplitby/
---
## IChartSeries::get_PieSplitBy() เมธอด

กำหนดวิธีการระบุว่าจุดข้อมูลใดอยู่ในพายหรือแถบที่สองบนแผนภูมิแบบพายของพายหรือแถบของพาย. นี้คือคุณสมบัติที่ไม่เฉพาะของซีรีส์นี้เท่านั้น แต่รวมถึงซีรีส์ทั้งหมดของกลุ่มซีรีส์แม่ด้วย - ซึ่งเป็นการฉายของคุณสมบัติกลุ่มที่เหมาะสม. ดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มซีรีส์แม่. ใช้ [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() คุณสมบัติอ่าน/เขียนเพื่อเปลี่ยนค่า. อ่านอย่างเดียว [PieSplitType](../../piesplittype/).

```cpp
virtual PieSplitType Aspose::Slides::Charts::IChartSeries::get_PieSplitBy()=0
```

## หมายเหตุ

1) นี่คือการฉายของคุณสมบัติ [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy(). 2) หากค่าของคุณสมบัติเป็น [PieSplitType::Custom](../../piesplittype/) คุณสามารถกำหนดข้อมูลการแบ่งแบบกำหนดเองด้วยคุณสมบัติ [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/).

## ดูเพิ่มเติม

* Enum [PieSplitType](../../piesplittype/)
* คลาส [IChartSeries](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)
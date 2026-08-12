---
title: get_PieSplitBy()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ระบุวิธีการกำหนดว่าข้อมูลจุดใดอยู่ในพายหรือบาร์ที่สองของแผนภูมิแบบพาย-ใน-พายหรือบาร์-ใน-พาย คุณสมบัตินี้ไม่ใช่ของซีรีส์นี้เท่านั้น แต่เป็นของซีรีส์ทั้งหมดในกลุ่มซีรีส์พาเรนต์ - ซึ่งเป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มซีรีส์พาเรนต์ ใช้ get_ParentSeriesGroup()->get(set)_PieSplitBy() อ่าน/เขียน เพื่อเปลี่ยนค่า อ่านอย่างเดียว PieSplitType.
type: docs
weight: 755
url: /th/aspose.slides.charts/chartseries/get_piesplitby/
---
## ChartSeries::get_PieSplitBy() เมธอด

ระบุวิธีการกำหนดว่าข้อมูลจุดใดอยู่ในพายหรือบาร์ที่สองของแผนภูมิแบบพาย-ใน-พายหรือบาร์-ใน-พาย คุณสมบัตินี้ไม่ใช่ของซีรีส์นี้เท่านั้น แต่เป็นของซีรีส์ทั้งหมดในกลุ่มซีรีส์พาเรนต์ — นี่คือการฉายของคุณสมบัติของกลุ่มที่เหมาะสม และคุณสมบัตินี้จึงเป็นอ่านอย่างเดียว ใช้ ParentSeriesGroup คุณสมบัติเพื่อเข้าถึงกลุ่มซีรีส์พาเรนต์ ใช้ [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() คุณสมบัติ อ่าน/เขียน เพื่อเปลี่ยนค่า อ่านอย่างเดียว [PieSplitType](../../piesplittype/).

```cpp
PieSplitType Aspose::Slides::Charts::ChartSeries::get_PieSplitBy() override
```

## หมายเหตุ

1) นี่คือการฉายของคุณสมบัติ [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() . 2) หากค่าของคุณสมบัติเป็น [PieSplitType::Custom](../../piesplittype/) คุณสามารถกำหนดข้อมูลการแยกแบบกำหนดเองด้วยคุณสมบัติ [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/) .

## ดูเพิ่มเติม

* Enum [PieSplitType](../../piesplittype/)
* คลาส [ChartSeries](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)
---
title: Add()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างซีรีส์แผนภูมิใหม่และเพิ่มลงในคอลเลกชัน.
type: docs
weight: 53
url: /th/aspose.slides.charts/chartseriescollection/add/
---
## ChartSeriesCollection::Add(ChartType) เมธอด


สร้างซีรีส์แผนภูมิใหม่และเพิ่มลงในคอลเลกชัน

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(ChartType type) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | ประเภทของซีรีส์ |

### ค่าที่ส่งกลับ

ซีรีส์แผนภูมิใหม่

## ChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) เมธอด


สร้างซีรีส์แผนภูมิใหม่จาก [ChartDataCell](../../chartdatacell/) และเพิ่มลงในคอลเลกชัน

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) ที่มีชื่อซีรีส์ |
| type | [ChartType](../../charttype/) | ประเภทที่ตั้งค่าเป็นประเภทของซีรีส์ |

### ค่าที่ส่งกลับ

ซีรีส์แผนภูมิที่เพิ่มแล้วหรือซีรีส์ที่มีอยู่แล้วในคอลเลกชัน

## หมายเหตุ


หากซีรีส์แผนภูมิถูกสร้างจากเซลล์เดียวกันที่มีอยู่ในคอลเลกชันแล้ว เมธอดจะไม่ทำอะไรและคืนดัชนีของมัน

## ChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) เมธอด


สร้างซีรีส์แผนภูมิใหม่จาก [ChartCellCollection](../../chartcellcollection/) และเพิ่มลงในคอลเลกชัน

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | เซลล์ที่มีชื่อซีรีส์ |
| type | [ChartType](../../charttype/) | ประเภทที่ตั้งค่าเป็นประเภทของซีรีส์ |

### ค่าที่ส่งกลับ

ซีรีส์แผนภูมิที่เพิ่มแล้วหรือซีรีส์ที่มีอยู่แล้วในคอลเลกชัน

## หมายเหตุ


หากซีรีส์แผนภูมิถูกสร้างจากเซลล์เดียวกันที่มีอยู่ในคอลเลกชันแล้ว เมธอดจะไม่ทำอะไรและคืนดัชนีของมัน

## ChartSeriesCollection::Add(System::String, ChartType) เมธอด


สร้างซีรีส์แผนภูมิใหม่จากค่าและเพิ่มลงในคอลเลกชัน

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::String name, ChartType type) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | ชื่อซีรีส์ |
| type | [ChartType](../../charttype/) | ประเภทที่ตั้งค่าเป็นประเภทของซีรีส์ |

### ค่าที่ส่งกลับ

ซีรีส์แผนภูมิที่เพิ่มแล้ว

## ดูเพิ่มเติม

* Enum [ChartType](../../charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartSeries](../../ichartseries/)
* Class [ChartSeriesCollection](../)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [IChartCellCollection](../../ichartcellcollection/)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
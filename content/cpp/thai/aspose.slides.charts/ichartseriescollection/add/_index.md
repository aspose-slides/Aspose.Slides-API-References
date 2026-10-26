---
title: Add()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างซีรีส์แผนภูมิใหม่และเพิ่มเข้าไปในคอลเลกชัน.
type: docs
weight: 14
url: /th/aspose.slides.charts/ichartseriescollection/add/
---
## IChartSeriesCollection::Add(ChartType) เมธอด


สร้างซีรีส์แผนภูมิใหม่และเพิ่มเข้าไปในคอลเลกชัน.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(ChartType type)=0
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | ประเภทของซีรีส์ |

### ค่าที่ส่งกลับ

ซีรีส์แผนภูมิใหม่.

## IChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) เมธอด


สร้างซีรีส์แผนภูมิใหม่จาก [IChartDataCell](../../ichartdatacell/) และเพิ่มเข้าไปในคอลเลกชัน.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type)=0
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) ที่มีชื่อซีรีส์ |
| type | [ChartType](../../charttype/) | ประเภทที่ตั้งค่าประเภทของซีรีส์ |

### ค่าที่ส่งกลับ

ซีรีส์แผนภูมิที่เพิ่มแล้วหรือซีรีส์ที่มีอยู่ในคอลเลกชันแล้ว.

## หมายเหตุ


หากซีรีส์แผนภูมิที่สร้างจากเซลเดียวกันที่มีอยู่แล้วในคอลเลกชัน เมธอดจะไม่ทำอะไรและจะส่งกลับดัชนีของมัน.



## IChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) เมธอด


สร้างซีรีส์แผนภูมิใหม่จาก [IChartCellCollection](../../ichartcellcollection/) และเพิ่มเข้าไปในคอลเลกชัน.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type)=0
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | เซลที่มีชื่อซีรีส์ |
| type | [ChartType](../../charttype/) | ประเภทที่ตั้งค่าประเภทของซีรีส์ |

### ค่าที่ส่งกลับ

ซีรีส์แผนภูมิที่เพิ่มแล้วหรือซีรีส์ที่มีอยู่ในคอลเลกชันแล้ว.

## หมายเหตุ


หากซีรีส์แผนภูมิที่สร้างจากเซลเดียวกันที่มีอยู่แล้วในคอลเลกชัน เมธอดจะไม่ทำอะไรและจะส่งกลับดัชนีของมัน.



## IChartSeriesCollection::Add(System::String, ChartType) เมธอด


สร้างซีรีส์แผนภูมิใหม่จากค่าและเพิ่มเข้าไปในคอลเลกชัน.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::String name, ChartType type)=0
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | ชื่อซีรีส์ |
| type | [ChartType](../../charttype/) | ประเภทที่ตั้งค่าประเภทของซีรีส์ |

### ค่าที่ส่งกลับ

ซีรีส์แผนภูมิที่เพิ่มแล้ว.

## ดูเพิ่มเติม

* Enum [ChartType](../../charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IChartSeries](../../ichartseries/)
* คลาส [IChartSeriesCollection](../)
* คลาส [IChartDataCell](../../ichartdatacell/)
* คลาส [IChartCellCollection](../../ichartcellcollection/)
* คลาส [String](../../../system/string/)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)
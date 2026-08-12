---
title: AddDataPointForBarSeries()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างจุดข้อมูลใหม่และเพิ่มลงในตอนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งใน Column หรือ Bar subtypes (ดูเพิ่มเติมที่ ChartTypeCharacterizer.IsChartTypeColumn(ChartType) และ ChartTypeCharacterizer.IsChartTypeBar(ChartType) method).
type: docs
weight: 196
url: /th/aspose.slides.charts/ichartdatapointcollection/adddatapointforbarseries/
---
## IChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr\<IChartDataCell\>) เมธอด

สร้างจุดข้อมูลใหม่และเพิ่มลงในตอนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งใน [Column](../../../aspose.slides/column/) หรือประเภทย่อย Bar (ดูเพิ่มเติมที่ [ChartTypeCharacterizer.IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) และ [ChartTypeCharacterizer.IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) เมธอด)

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr<IChartDataCell> value)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | ค่าจุดข้อมูล |

### ค่าที่คืน

จุดข้อมูลใหม่.

## IChartDataPointCollection::AddDataPointForBarSeries(double) เมธอด

สร้างจุดข้อมูลใหม่และเพิ่มลงในตอนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งใน [Column](../../../aspose.slides/column/) หรือประเภทย่อย Bar (ดูเพิ่มเติมที่ [ChartTypeCharacterizer.IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) และ [ChartTypeCharacterizer.IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) เมธอด)

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForBarSeries(double value)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | **double** | ค่าจุดข้อมูล |

### ค่าที่คืน

จุดข้อมูลใหม่.

## ดูเพิ่มเติม

* การกำหนดประเภท [SharedPtr](../../../system/sharedptr/)
* คลาส [IChartDataPoint](../../ichartdatapoint/)
* คลาส [IChartDataCell](../../ichartdatacell/)
* คลาส [IChartDataPointCollection](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)
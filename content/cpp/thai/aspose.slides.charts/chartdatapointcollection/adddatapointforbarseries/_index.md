---
title: AddDataPointForBarSeries()
second_title: Aspose.Slides สำหรับการอ้างอิง API C++
description: "สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชัน ใช้ได้กับ series ที่ chartType เป็นหนึ่งในประเภทย่อย Column หรือ Bar (ดูเพิ่มเติมที่เมธอด ChartTypeCharacterizer::IsChartTypeColumn(ChartType) และ ChartTypeCharacterizer::IsChartTypeBar(ChartType))."
type: docs
weight: 261
url: /th/aspose.slides.charts/chartdatapointcollection/adddatapointforbarseries/
---
## ChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr\<IChartDataCell\>) เมธอด


สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชัน ใช้ได้กับ series ที่ chartType อยู่ในประเภท [Column](../../../aspose.slides/column/) หรือ Bar ย่อย (ดูเพิ่มเติมที่เมธอด [ChartTypeCharacterizer::IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) และ [ChartTypeCharacterizer::IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/))

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr<IChartDataCell> value) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Data point Value |

### ค่าที่ส่งกลับ

จุดข้อมูลใหม่.

## ChartDataPointCollection::AddDataPointForBarSeries(double) เมธอด


สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชัน ใช้ได้กับ series ที่ chartType อยู่ในประเภท [Column](../../../aspose.slides/column/) หรือ Bar ย่อย (ดูเพิ่มเติมที่เมธอด [ChartTypeCharacterizer::IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) และ [ChartTypeCharacterizer::IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/))

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForBarSeries(double value) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | **double** | Data point Value |

### ค่าที่ส่งกลับ

จุดข้อมูลใหม่.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IChartDataPoint](../../ichartdatapoint/)
* คลาส [IChartDataCell](../../ichartdatacell/)
* คลาส [ChartDataPointCollection](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
---
title: AddDataPointForStockSeries()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งในประเภทย่อยของ Stock (ดูเพิ่มเติม ChartTypeCharacterizer.IsChartTypeStock(ChartType) method)
type: docs
weight: 144
url: /th/aspose.slides.charts/ichartdatapointcollection/adddatapointforstockseries/
---
## IChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr\<IChartDataCell\>) วิธีการ

สร้างจุดข้อมูลใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งในประเภทย่อยของ Stock (ดูเพิ่มเติม [ChartTypeCharacterizer.IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) วิธีการ).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr<IChartDataCell> value)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | ค่าของจุดข้อมูล |

### ค่าที่ส่งกลับ

จุดข้อมูลใหม่.

## IChartDataPointCollection::AddDataPointForStockSeries(double) วิธีการ

สร้างจุดข้อมูลใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งในประเภทย่อยของ Stock (ดูเพิ่มเติม [ChartTypeCharacterizer.IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) วิธีการ).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForStockSeries(double value)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | **double** | ค่าของจุดข้อมูล |

### ค่าที่ส่งกลับ

จุดข้อมูลใหม่.

## ดูเพิ่มเติม

* กำหนดชนิด [SharedPtr](../../../system/sharedptr/)
* คลาส [IChartDataPoint](../../ichartdatapoint/)
* คลาส [IChartDataCell](../../ichartdatacell/)
* คลาส [IChartDataPointCollection](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)
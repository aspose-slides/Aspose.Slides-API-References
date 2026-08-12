---
title: get_Categories()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "ดึงหมวดหมู่หลัก (หรือทั้งหมวดหมู่หลักและรองถ้า IChartData::set_UseSecondaryCategories ถูกตั้งค่าเป็น false) อ่านอย่างเดียว IChartCategoryCollection."
type: docs
weight: 40
url: /th/aspose.slides.charts/ichartdata/get_categories/
---
## IChartData::get_Categories() เมธอด

ดึงหมวดหมู่หลัก (หรือทั้งหมวดหมู่หลักและรองถ้า [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) ถูกตั้งค่าเป็น false) อ่านอย่างเดียว [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_Categories()=0
```

## หมายเหตุ

ถ้า [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) ถูกตั้งค่าเป็น false แล้ว [IChartData::get_SecondaryCategories](../get_secondarycategories/) จะคืนค่า null และข้อมูลใน [IChartData::get_Categories](./) จะใช้สำหรับชุดข้อมูลหลักและรองทั้งคู่. ถ้า [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) ถูกตั้งค่าเป็น true แล้วข้อมูลใน [IChartData::get_SecondaryCategories](../get_secondarycategories/) จะใช้สำหรับชุดข้อมูลรองและข้อมูลใน [IChartData::get_Categories](./) จะใช้สำหรับชุดข้อมูลหลัก.

ตัวอย่าง. หมวดหมู่ใดที่เกี่ยวข้องกับชุดข้อมูล - ChartData.Categories หรือ ChartData.SecondaryCategories? 
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // related categories are series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // related categories are series->get_Chart()->get_ChartData()->get_Categories()
}
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IChartCategoryCollection](../../ichartcategorycollection/)
* คลาส [IChartData](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)
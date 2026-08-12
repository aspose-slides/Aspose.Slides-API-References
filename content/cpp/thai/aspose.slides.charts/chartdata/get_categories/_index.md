---
title: get_Categories()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "ดึงหมวดหมู่หลัก (หรือทั้งหมวดหมู่หลักและรองถ้า ChartData::set_UseSecondaryCategories ตั้งเป็น false) อ่านอย่างเดียว IChartCategoryCollection."
type: docs
weight: 40
url: /th/aspose.slides.charts/chartdata/get_categories/
---
## ChartData::get_Categories() เมธอด

เรียกข้อมูลหมวดหมู่หลัก (หรือหมวดหมู่หลักและรองถ้า [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) ถูกตั้งค่าเป็น false) อ่านอย่างเดียว [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_Categories() override
```

## หมายเหตุ

ถ้า [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) ถูกตั้งค่าเป็น false แล้ว [ChartData::get_SecondaryCategories](../get_secondarycategories/) จะคืนค่า null และข้อมูลใน [ChartData::get_Categories](./) จะใช้ทั้งสำหรับชุดข้อมูลหลักและรอง. ถ้า [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) ถูกตั้งค่าเป็น true แล้วข้อมูลใน [ChartData::get_SecondaryCategories](../get_secondarycategories/) จะใช้สำหรับชุดข้อมูลรองและข้อมูลใน [ChartData::get_Categories](./) จะใช้สำหรับชุดข้อมูลหลัก. 

ตัวอย่าง. หมวดหมู่ใดที่เกี่ยวข้องกับชุดข้อมูล - [ChartData::get_Categories](./) หรือ [ChartData::get_SecondaryCategories](../get_secondarycategories/)? 
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
* คลาส [ChartData](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
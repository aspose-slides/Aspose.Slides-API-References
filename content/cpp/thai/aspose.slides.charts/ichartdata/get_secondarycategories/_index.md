---
title: get_SecondaryCategories()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "รับค่าประเภทรองถ้า IChartData::get_UseSecondaryCategories เป็นจริง. อ่านอย่างเดียว IChartCategoryCollection."
type: docs
weight: 79
url: /th/aspose.slides.charts/ichartdata/get_secondarycategories/
---
## IChartData::get_SecondaryCategories() เมธอด

รับค่าประเภทรองถ้า [IChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) เป็นจริง. อ่านอย่างเดียว [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_SecondaryCategories()=0
```

## หมายเหตุ

ถ้า [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) ตั้งค่าเป็น false แล้ว [IChartData::get_SecondaryCategories](./) คืนค่า null และข้อมูลใน [IChartData::get_Categories](../get_categories/) ถูกใช้ทั้งสำหรับชุดข้อมูลหลักและชุดข้อมูลรอง. ถ้า [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) ตั้งค่าเป็น true แล้วข้อมูลใน [IChartData::get_SecondaryCategories](./) ถูกใช้สำหรับชุดข้อมูลรองและข้อมูลใน [IChartData::get_Categories](../get_categories/) ถูกใช้สำหรับชุดข้อมูลหลัก. 

ตัวอย่าง. หมวดหมู่ใดที่เกี่ยวข้องกับชุดข้อมูล - ChartData.Categories หรือ ChartData.SecondaryCategories? 
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // ประเภทที่เกี่ยวข้องคือ series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // ประเภทที่เกี่ยวข้องคือ series->get_Chart()->get_ChartData()->get_Categories()
}
```

## ดูเพิ่มเติม

* กำหนดชนิด [SharedPtr](../../../system/sharedptr/)
* คลาส [IChartCategoryCollection](../../ichartcategorycollection/)
* คลาส [IChartData](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)
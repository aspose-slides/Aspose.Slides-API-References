---
title: get_SecondaryCategories()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "รับหมวดหมู่รองหาก ChartData::get_UseSecondaryCategories เป็น true. อ่านอย่างเดียว IChartCategoryCollection."
type: docs
weight: 79
url: /th/aspose.slides.charts/chartdata/get_secondarycategories/
---
## ChartData::get_SecondaryCategories() เมธอด


รับหมวดหมู่รองหาก [ChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) เป็น true. อ่านอย่างเดียว [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_SecondaryCategories() override
```

## หมายเหตุ


หาก [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) ถูกตั้งค่าเป็น false แล้ว [ChartData::get_SecondaryCategories](./) จะคืนค่า null และข้อมูลใน [ChartData::get_Categories](../get_categories/) จะถูกใช้ทั้งสำหรับ series หลักและ series รอง หาก [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) ถูกตั้งค่าเป็น true แล้วข้อมูลใน [ChartData::get_SecondaryCategories](./) จะถูกใช้สำหรับ series รองและข้อมูลใน [ChartData::get_Categories](../get_categories/) จะถูกใช้สำหรับ series หลัก. 

ตัวอย่าง. หมวดหมู่ใดที่เกี่ยวข้องกับ series - [ChartData::get_Categories](../get_categories/) หรือ [ChartData::get_SecondaryCategories](./)? 
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // หมวดหมู่ที่เกี่ยวข้องคือ series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // หมวดหมู่ที่เกี่ยวข้องคือ series->get_Chart()->get_ChartData()->get_Categories()
}
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartCategoryCollection](../../ichartcategorycollection/)
* Class [ChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
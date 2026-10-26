---
title: get_UseSecondaryCategories()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "หากตั้งค่าเป็น false แล้ว ChartData::get_SecondaryCategories จะคืนค่า null และข้อมูลใน ChartData::get_Categories จะถูกใช้ทั้งสำหรับซีรีส์หลักและซีรีส์รอง. หากตั้งค่าเป็น true แล้วข้อมูลใน ChartData::get_SecondaryCategories จะถูกใช้สำหรับซีรีส์รองและข้อมูลใน ChartData::get_Categories จะถูกใช้สำหรับซีรีส์หลัก. อ่าน bool."
type: docs
weight: 53
url: /th/aspose.slides.charts/chartdata/get_usesecondarycategories/
---
## ChartData::get_UseSecondaryCategories() เมธอด


หากตั้งค่าเป็น false แล้ว [ChartData::get_SecondaryCategories](../get_secondarycategories/) จะคืนค่า null และข้อมูลใน [ChartData::get_Categories](../get_categories/) จะถูกใช้ทั้งสำหรับชุดข้อมูลหลักและชุดข้อมูลรอง. หากตั้งค่าเป็น true แล้วข้อมูลใน [ChartData::get_SecondaryCategories](../get_secondarycategories/) จะถูกใช้สำหรับชุดข้อมูลรองและข้อมูลใน [ChartData::get_Categories](../get_categories/) จะถูกใช้สำหรับชุดข้อมูลหลัก. อ่าน **bool**.

```cpp
bool Aspose::Slides::Charts::ChartData::get_UseSecondaryCategories() override
```

## หมายเหตุ


ตัวอย่าง. หมวดใดที่เกี่ยวข้องกับชุดข้อมูล - [ChartData::get_Categories](../get_categories/) หรือ [ChartData::get_SecondaryCategories](../get_secondarycategories/)? 
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // หมวดที่เกี่ยวข้องคือ series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // หมวดที่เกี่ยวข้องคือ series->get_Chart()->get_ChartData()->get_Categories()
}
```

## ดูเพิ่มเติม

* คลาส [ChartData](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)
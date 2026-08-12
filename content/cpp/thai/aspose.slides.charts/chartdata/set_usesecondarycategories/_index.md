---
title: set_UseSecondaryCategories()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "ถ้าตั้งค่าเป็น false แล้ว ChartData::get_SecondaryCategories จะคืนค่า null และข้อมูลใน ChartData::get_Categories จะใช้กับซีรีส์หลักและซีรีส์รองทั้งสอง. ถ้าตั้งค่าเป็น true แล้วข้อมูลใน ChartData::get_SecondaryCategories จะใช้สำหรับซีรีส์รองและข้อมูลใน ChartData::get_Categories จะใช้สำหรับซีรีส์หลัก. เขียน bool."
type: docs
weight: 66
url: /th/aspose.slides.charts/chartdata/set_usesecondarycategories/
---
## ChartData::set_UseSecondaryCategories(bool) เมธอด


หากตั้งค่าเป็น false แล้ว [ChartData::get_SecondaryCategories](../get_secondarycategories/) จะคืนค่า null และข้อมูลใน [ChartData::get_Categories](../get_categories/) จะใช้สำหรับซีรีส์หลักและซีรีส์รองทั้งสอง. หากตั้งค่าเป็น true แล้วข้อมูลใน [ChartData::get_SecondaryCategories](../get_secondarycategories/) จะใช้สำหรับซีรีส์รองและข้อมูลใน [ChartData::get_Categories](../get_categories/) จะใช้สำหรับซีรีส์หลัก. เขียน **bool**.

```cpp
void Aspose::Slides::Charts::ChartData::set_UseSecondaryCategories(bool value) override
```

## หมายเหตุ


ตัวอย่าง. หมวดหมู่ใดที่เกี่ยวข้องกับซีรีส์ - [ChartData::get_Categories](../get_categories/) หรือ [ChartData::get_SecondaryCategories](../get_secondarycategories/)? 
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

* คลาส [ChartData](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)
---
title: set_UseSecondaryCategories()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: "หากตั้งค่าเป็น false แล้ว IChartData::get_SecondaryCategories จะคืนค่า null และข้อมูลใน IChartData::get_Categories จะถูกใช้ทั้งสำหรับซีรีส์หลักและซีรีส์รอง. หากตั้งค่าเป็น true แล้วข้อมูลใน IChartData::get_SecondaryCategories จะถูกใช้สำหรับซีรีส์รองและข้อมูลใน IChartData::get_Categories จะถูกใช้สำหรับซีรีส์หลัก. เขียน bool."
type: docs
weight: 66
url: /th/aspose.slides.charts/ichartdata/set_usesecondarycategories/
---
## IChartData::set_UseSecondaryCategories(bool) เมธอด

If set to false then [IChartData::get_SecondaryCategories](../get_secondarycategories/) returns null and data in [IChartData::get_Categories](../get_categories/) is used both for primary and secondary series. If set to true then data in [IChartData::get_SecondaryCategories](../get_secondarycategories/) is used for secondary series and data in [IChartData::get_Categories](../get_categories/) is used for primary series. Write **bool**.

```cpp
virtual void Aspose::Slides::Charts::IChartData::set_UseSecondaryCategories(bool value)=0
```

## หมายเหตุ

ตัวอย่าง. What categories are related to series - ChartData.Categories or ChartData.SecondaryCategories? 
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

* คลาส [IChartData](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)
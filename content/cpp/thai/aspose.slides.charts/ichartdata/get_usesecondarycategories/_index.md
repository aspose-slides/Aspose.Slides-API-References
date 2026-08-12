---
title: get_UseSecondaryCategories()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "หากตั้งค่าเป็น false แล้ว IChartData::get_SecondaryCategories จะคืนค่า null และข้อมูลใน IChartData::get_Categories จะใช้ทั้งสำหรับซีรีส์หลักและซีรีส์รอง หากตั้งค่าเป็น true แล้วข้อมูลใน IChartData::get_SecondaryCategories จะใช้สำหรับซีรีส์รองและข้อมูลใน IChartData::get_Categories จะใช้สำหรับซีรีส์หลัก อ่าน bool."
type: docs
weight: 53
url: /th/aspose.slides.charts/ichartdata/get_usesecondarycategories/
---
## IChartData::get_UseSecondaryCategories() เมธอด


If set to false then [IChartData::get_SecondaryCategories](../get_secondarycategories/) returns null and data in [IChartData::get_Categories](../get_categories/) is used both for primary and secondary series. If set to true then data in [IChartData::get_SecondaryCategories](../get_secondarycategories/) is used for secondary series and data in [IChartData::get_Categories](../get_categories/) is used for primary series. อ่าน **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IChartData::get_UseSecondaryCategories()=0
```

## หมายเหตุ


ตัวอย่าง. หมวดหมู่ใดที่เกี่ยวข้องกับซีรีส์ - ChartData.Categories หรือ ChartData.SecondaryCategories?
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

* คลาส [IChartData](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)
---
title: IChartCategory class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/ichartcategory/
---
## IChartCategory คลาส

Represents chart categories.

The IChartCategory type exposes the following members:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`use_cell`](/slides/python-net/th/aspose.slides.charts/ichartcategory/use_cell/) | หากเป็นจริงแล้ว AsCell property จะเป็นค่าจริง ในอีกความหมายหนึ่ง worksheet ถูกใช้สำหรับ <br/>            การเก็บข้อมูลหมวดหมู่ (กรณีนี้รองรับหมวดหมู่หลายระดับ).<br/>            หากเป็นเท็จแล้ว AsLiteral property จะเป็นค่าจริง ในอีกความหมายหนึ่ง worksheet **ไม่ได้** ถูกใช้ <br/>            สำหรับการเก็บข้อมูลหมวดหมู่ (และกรณีนี้ไม่รองรับหมวดหมู่หลายระดับ).<br/>            อ่านได้อย่างเดียว **bool**. |
| [`as_cell`](/slides/python-net/th/aspose.slides.charts/ichartcategory/as_cell/) | ส่งคืนหรือกำหนด IChartDataCell object.<br/>            หากหมวดหมู่เป็นหลายระดับจะใช้ IChartDataCell object สำหรับระดับ "0".<br/>            อ่าน/เขียน [`IChartDataCell`](/slides/python-net/th/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/th/aspose.slides.charts/ichartcategory/as_literal/) | ส่งคืนหรือกำหนด AsLiteral หาก UseCell เป็นเท็จ.<br/>            อ่าน/เขียน **any**. |
| [`value`](/slides/python-net/th/aspose.slides.charts/ichartcategory/value/) | หาก UseCell เป็นจริงแล้วคุณสมบัตินี้แทนค่า AsCell.Value property.<br/>            หาก UseCell เป็นเท็จแล้วคุณสมบัตินี้แทนค่า AsLiteral property.<br/>            อ่าน/เขียน **any**. |
| [`grouping_levels`](/slides/python-net/th/aspose.slides.charts/ichartcategory/grouping_levels/) | คอนเทนเนอร์ที่จัดการค่าของระดับการจัดกลุ่มหมวดหมู่แผนภูมิ.<br/>            หมวดหมู่หลายระดับมีหลายระดับการจัดกลุ่ม.<br/>            การจัดทำดัชนีระดับการจัดกลุ่มเริ่มจากศูนย์.<br/>            อ่านได้อย่างเดียว [`IChartCategoryLevelsManager`](/slides/python-net/th/aspose.slides.charts/ichartcategorylevelsmanager). |

## เมธอด

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/th/aspose.slides.charts/ichartcategory/remove/#) | ลบหมวดหมู่ออกจากแผนภูมิ. |


### ดูเพิ่มเติม
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)
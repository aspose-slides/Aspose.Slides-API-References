---
title: ChartCategory class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/chartcategory/
---
## ChartCategory คลาส

แสดงหมวดหมู่แผนภูมิ

ชนิด ChartCategory เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`use_cell`](/slides/python-net/th/aspose.slides.charts/chartcategory/use_cell/) | หากเป็น true แล้วคุณสมบัติ AsCell จะเป็นค่าใช้ได้จริง โดยอื่นคือ worksheet จะถูกใช้สำหรับ <br/>            การเก็บหมวดหมู่ (กรณีนี้รองรับหมวดหมู่หลายระดับ).<br/>            หากเป็น false แล้วคุณสมบัติ AsLiteral จะเป็นค่าใช้ได้จริง โดยอื่นคือ worksheet จะ **ไม่** ถูกใช้ <br/>            สำหรับการเก็บหมวดหมู่ (และกรณีนี้ไม่รองรับหมวดหมู่หลายระดับ).<br/>            อ่านอย่างเดียว **bool**. |
| [`as_cell`](/slides/python-net/th/aspose.slides.charts/chartcategory/as_cell/) | คืนค่า หรือ กำหนดวัตถุ IChartDataCell.<br/>            หากหมวดหมู่เป็นหลายระดับจะใช้วัตถุ IChartDataCell สำหรับระดับ "0".<br/>            อ่าน/เขียน [`IChartDataCell`](/slides/python-net/th/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/th/aspose.slides.charts/chartcategory/as_literal/) | คืนค่า หรือ กำหนดวัตถุ AsLiteral.<br/>            อ่าน/เขียน **any**. |
| [`value`](/slides/python-net/th/aspose.slides.charts/chartcategory/value/) | หาก UseCell เป็น true แล้วคุณสมบัตินี้จะแสดงคุณสมบัติ AsCell.Value.<br/>            หาก UseCell เป็น false แล้วคุณสมบัตินี้จะแสดงคุณสมบัติ AsLiteral.<br/>            อ่าน/เขียน **any**. |
| [`grouping_levels`](/slides/python-net/th/aspose.slides.charts/chartcategory/grouping_levels/) | คอนเทนเนอร์ที่จัดการค่าของระดับการจัดกลุ่มหมวดหมู่แผนภูมิ.<br/>            หมวดหมู่หลายระดับมีหลายระดับการจัดกลุ่ม.<br/>            ดัชนีระดับการจัดกลุ่มเริ่มจากศูนย์.<br/>            อ่านอย่างเดียว [`IChartCategoryLevelsManager`](/slides/python-net/th/aspose.slides.charts/ichartcategorylevelsmanager). |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`remove(self)`](/slides/python-net/th/aspose.slides.charts/chartcategory/remove/#) | ลบหมวดหมู่ออกจากแผนภูมิ. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)
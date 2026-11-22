---
title: IChartCategory class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/ichartcategory/
---
## IChartCategory คลาส

แสดงถึงประเภทของแผนภูมิ

ประเภท IChartCategory เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`use_cell`](/slides/python-net/th/aspose.slides.charts/ichartcategory/use_cell/) | ถ้าเป็นจริงแล้วคุณสมบัติ AsCell จะเป็นค่าจริง ในทางอื่นแผ่นงานจะใช้สำหรับ <br/>            การจัดเก็บหมวดหมู่ (กรณีนี้รองรับหมวดหมู่หลายระดับ).<br/>            ถ้าเป็นเท็จแล้วคุณสมบัติ AsLiteral จะเป็นค่าจริง ในทางอื่นแผ่นงาน **จะไม่**ใช้สำหรับ <br/>            การจัดเก็บหมวดหมู่ (และกรณีนี้ไม่รองรับหมวดหมู่หลายระดับ).<br/>            อ่านอย่างเดียว **bool**. |
| [`as_cell`](/slides/python-net/th/aspose.slides.charts/ichartcategory/as_cell/) | คืนหรือกำหนดอ็อบเจกต์ IChartDataCell.<br/>            หากหมวดหมู่เป็นหลายระดับจะใช้ IChartDataCell สำหรับระดับ "0".<br/>            อ่าน/เขียน [`IChartDataCell`](/slides/python-net/th/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/th/aspose.slides.charts/ichartcategory/as_literal/) | คืนหรือกำหนด AsLiteral หาก UseCell เป็นเท็จ.<br/>            อ่าน/เขียน **any**. |
| [`value`](/slides/python-net/th/aspose.slides.charts/ichartcategory/value/) | ถ้า UseCell เป็นจริงแล้วคุณสมบัตินี้แทนค่า AsCell.Value.<br/>            ถ้า UseCell เป็นเท็จแล้วคุณสมบัตินี้แทนค่า AsLiteral.<br/>            อ่าน/เขียน **any**. |
| [`cached_value`](/slides/python-net/th/aspose.slides.charts/ichartcategory/cached_value/) | รับค่าที่แคชของประเภทแผนภูมิ.<br/>            อ่านอย่างเดียว [`ICachedChartValue`](/slides/python-net/th/aspose.slides.charts/icachedchartvalue). |
| [`grouping_levels`](/slides/python-net/th/aspose.slides.charts/ichartcategory/grouping_levels/) | คอนเทนเนอร์ที่จัดการค่าของระดับการจัดกลุ่มประเภทแผนภูมิ.<br/>            ประเภทหลายระดับมีมากกว่าหนึ่งระดับการจัดกลุ่ม.<br/>            การจัดตำแหน่งระดับการจัดกลุ่มเริ่มจากศูนย์.<br/>            อ่านอย่างเดียว [`IChartCategoryLevelsManager`](/slides/python-net/th/aspose.slides.charts/ichartcategorylevelsmanager). |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`remove(self)`](/slides/python-net/th/aspose.slides.charts/ichartcategory/remove/#) | ลบประเภทออกจากแผนภูมิ. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)
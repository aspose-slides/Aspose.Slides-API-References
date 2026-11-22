---
title: ChartCategory class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/chartcategory/
---
## ChartCategory คลาส

แสดงถึงประเภทแผนภูมิ.

ประเภท ChartCategory เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`use_cell`](/slides/python-net/th/aspose.slides.charts/chartcategory/use_cell/) | หากเป็น true แล้วพร็อพเพอร์ตี้ AsCell จะเป็นค่าจริง ในทางอื่น worksheet จะใช้สำหรับ <br/>            การจัดเก็บประเภท (กรณีนี้สนับสนุนประเภทหลายระดับ).<br/>            หากเป็น false แล้วพร็อพเพอร์ตี้ AsLiteral จะเป็นค่าจริง ในทางอื่น worksheet **ไม่ได้**ใช้สำหรับ <br/>            การจัดเก็บประเภท (และกรณีนี้ไม่สนับสนุนประเภทหลายระดับ).<br/>            อ่านอย่างเดียว **bool**. |
| [`as_cell`](/slides/python-net/th/aspose.slides.charts/chartcategory/as_cell/) | คืนค่า หรือ กำหนดอ็อบเจกต์ IChartDataCell.<br/>            หากประเภทเป็นหลายระดับ จะใช้ IChartDataCell สำหรับระดับ "0".<br/>            อ่าน/เขียน [`IChartDataCell`](/slides/python-net/th/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/th/aspose.slides.charts/chartcategory/as_literal/) | คืนค่า หรือ กำหนดอ็อบเจกต์ AsLiteral.<br/>            อ่าน/เขียน **any**. |
| [`value`](/slides/python-net/th/aspose.slides.charts/chartcategory/value/) | หาก UseCell เป็น true แล้วพร็อพเพอร์ตี้นี้จะเป็นตัวแทนของพร็อพเพอร์ตี้ AsCell.Value.<br/>            หาก UseCell เป็น false แล้วพร็อพเพอร์ตี้นี้จะเป็นตัวแทนของพร็อพเพอร์ตี้ AsLiteral.<br/>            อ่าน/เขียน **any**. |
| [`grouping_levels`](/slides/python-net/th/aspose.slides.charts/chartcategory/grouping_levels/) | คอนเทนเนอร์ที่จัดการค่าของระดับการจัดกลุ่มประเภทแผนภูมิ.<br/>            ประเภทหลายระดับมีมากกว่าหนึ่งระดับการจัดกลุ่ม.<br/>            การจัดลำดับดัชนีระดับการจัดกลุ่มเริ่มที่ศูนย์.<br/>            อ่านอย่างเดียว [`IChartCategoryLevelsManager`](/slides/python-net/th/aspose.slides.charts/ichartcategorylevelsmanager). |
| [`cached_value`](/slides/python-net/th/aspose.slides.charts/chartcategory/cached_value/) | ได้รับค่าที่แคชของประเภทแผนภูมิ.<br/>            อ่านอย่างเดียว [`ICachedChartValue`](/slides/python-net/th/aspose.slides.charts/icachedchartvalue). |

## วิธีการ

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/th/aspose.slides.charts/chartcategory/remove/#) | ลบประเภทออกจากแผนภูมิ. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)
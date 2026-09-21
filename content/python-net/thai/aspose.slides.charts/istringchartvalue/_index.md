---
title: IStringChartValue class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.charts/istringchartvalue/
---
## IStringChartValue คลาส

แสดงค่าข้อความที่สามารถจัดเก็บในเอกสารการนำเสนอ pptx ได้สองวิธี:
            1) ในเซลล์/เซลล์ของ workbook ที่เกี่ยวข้องกับแผนภูมิ;
            2) เป็นค่าตัวอักษรโดยตรง.

ประเภท IStringChartValue เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`as_literal_string`](/slides/python-net/th/aspose.slides.charts/istringchartvalue/as_literal_string/) | คืนค่า หรือกำหนดสตริงลิเทอรัล หากคุณสมบัติ DataSourceType เป็น DataSourceType.StringLiterals.<br/>            อ่าน/เขียน **str**. |
| [`as_cells`](/slides/python-net/th/aspose.slides.charts/istringchartvalue/as_cells/) |  |
| [`data_source_type`](/slides/python-net/th/aspose.slides.charts/istringchartvalue/data_source_type/) |  |
| [`data`](/slides/python-net/th/aspose.slides.charts/istringchartvalue/data/) |  |

## เมธอด

| Method | Description |
| :- | :- |
| [`to_string(self)`](/slides/python-net/th/aspose.slides.charts/istringchartvalue/to_string/#) | คืนค่าการแสดงผลเป็นสตริง. |
| [`set_from_one_cell(self, cell)`](/slides/python-net/th/aspose.slides.charts/istringchartvalue/set_from_one_cell/#ichartdatacell) | กำหนดค่าจากเซลล์ที่ระบุ. |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/th/aspose.slides.charts/istringchartvalue/get_cells_address_in_workbook/#) | หากคุณสมบัติ DataSourceType เป็น DataSourceType.Worksheet แล้วเมธอดนี้จะคืนค่าที่อยู่<br/>            ของเซลล์ใน workbook ที่แสดงข้อมูลสตริง มิฉะนั้นจะคืนค่า<br/>            สตริงว่าง. |


### ดูเพิ่มเติม
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)
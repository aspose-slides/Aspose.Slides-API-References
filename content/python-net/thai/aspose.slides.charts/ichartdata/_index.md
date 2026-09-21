---
title: IChartData class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.charts/ichartdata/
---
## IChartData คลาส

แสดงถึงข้อมูลที่ใช้สำหรับการวาดแผนภูมิ

ประเภท IChartData เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/th/aspose.slides.charts/ichartdata/chart_data_workbook/) | รับ factory ของเซลล์เพื่อสร้างเซลล์ที่ใช้สำหรับ series หรือ categories ของแผนภูมิ<br/>            Read-only [`IChartDataWorkbook`](/slides/python-net/th/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/th/aspose.slides.charts/ichartdata/series/) | รับ series<br/>            Read-only [`IChartSeriesCollection`](/slides/python-net/th/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/th/aspose.slides.charts/ichartdata/series_groups/) | รับกลุ่มของ series<br/>            Read-only [`IChartSeriesGroupCollection`](/slides/python-net/th/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/categories/) | รับ categories หลัก (หรือทั้งหลักและรอง หากคุณสมบัติ [`IChartData.use_secondary_categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/use_secondary_categories) เป็น false)<br/>            Read-only [`IChartCategoryCollection`](/slides/python-net/th/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/use_secondary_categories/) | หาก false จะทำให้คุณสมบัติ [`IChartData.secondary_categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/secondary_categories) คืนค่า None และข้อมูลในคุณสมบัติ [`IChartData.categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/categories) จะถูกใช้ทั้งสำหรับ series หลักและรอง<br/>            หาก true จะใช้ข้อมูลในคุณสมบัติ [`IChartData.secondary_categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/secondary_categories) สำหรับ series รองและข้อมูลในคุณสมบัติ [`IChartData.categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/categories) สำหรับ series หลัก<br/>            Read/write **bool**. |
| [`secondary_categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/secondary_categories/) | รับ categories รองหากคุณสมบัติ [`IChartData.use_secondary_categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/use_secondary_categories) เป็น true<br/>            Read-only [`IChartCategoryCollection`](/slides/python-net/th/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/th/aspose.slides.charts/ichartdata/data_source_type/) | แสดงแหล่งข้อมูลของแผนภูมิ |
| [`external_workbook_path`](/slides/python-net/th/aspose.slides.charts/ichartdata/external_workbook_path/) | แสดงเส้นทางของ workbook ภายนอกหากแหล่งข้อมูลเป็นภายนอก, มิฉะนั้นเป็น None |
| [`embedded_workbook_type`](/slides/python-net/th/aspose.slides.charts/ichartdata/embedded_workbook_type/) | รับประเภทของ workbook ที่ฝังอยู่<br/>            คืนค่า [`WorkbookType.NOT_DEFINED`](/slides/python-net/th/aspose.slides.charts/workbooktype/NOT_DEFINED) หาก [`IChartData.data_source_type`](/slides/python-net/th/aspose.slides.charts/ichartdata/data_source_type) เป็น<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/th/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>            Read-only [`WorkbookType`](/slides/python-net/th/aspose.slides.charts/workbooktype). |

## เมธอด

| Method | Description |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/th/aspose.slides.charts/ichartdata/set_external_workbook/#str) | ตั้งค่า workbook ภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ. ข้อมูลแผนภูมิจะอัปเดตจาก workbook เป้าหมาย |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/th/aspose.slides.charts/ichartdata/set_external_workbook/#str-bool) | ตั้งค่า workbook ภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ |
| [`read_workbook_stream(self)`](/slides/python-net/th/aspose.slides.charts/ichartdata/read_workbook_stream/#) | เขียน workbook Excel ที่เก็บอยู่ภายในลงในสตรีมที่อยู่ในหน่วยความจำ |
| [`write_workbook_stream(self, ms)`](/slides/python-net/th/aspose.slides.charts/ichartdata/write_workbook_stream/#iorawiobase) | เริ่มต้น workbook Excel ที่เก็บอยู่ภายในด้วยค่าที่ผู้ใช้กำหนด |
| [`set_range(self, formula)`](/slides/python-net/th/aspose.slides.charts/ichartdata/set_range/#str) | กำหนดช่วงข้อมูลแผนภูมิ. series และ categories จะอัปเดตตามช่วงข้อมูลใหม่<br/>            หากจำนวน series ในช่วงข้อมูลมากกว่าจำนวน series ในข้อมูลแผนภูมิ จะเพิ่ม series เพิ่มเติมที่มีประเภทเดียวกันกับ series สุดท้ายในคอลเลกชันปัจจุบันที่ท้ายคอลเลกชัน |
| [`get_range(self)`](/slides/python-net/th/aspose.slides.charts/ichartdata/get_range/#) | รับช่วงข้อมูลแผนภูมิ |
| [`switch_row_column(self)`](/slides/python-net/th/aspose.slides.charts/ichartdata/switch_row_column/#) | สลับข้อมูลตามแกน<br/>            ข้อมูลที่แสดงบนแกน X จะย้ายไปยังแกน Y และในทางกลับกัน |

### ดูเพิ่มเติม
* module [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)
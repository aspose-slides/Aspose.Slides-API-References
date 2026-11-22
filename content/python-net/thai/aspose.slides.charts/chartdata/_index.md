---
title: ChartData class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET การอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/chartdata/
---
## ChartData คลาส

แสดงข้อมูลที่ใช้สำหรับการวาดแผนภูมิ.

ประเภท ChartData เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/th/aspose.slides.charts/chartdata/chart_data_workbook/) | รับ factory ของเซลล์เพื่อสร้างเซลล์ที่ใช้สำหรับ series หรือ categories ของแผนภูมิ.<br/>            อ่านอย่างเดียว [`IChartDataWorkbook`](/slides/python-net/th/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/th/aspose.slides.charts/chartdata/series/) | รับ series.<br/>            อ่านอย่างเดียว [`IChartSeriesCollection`](/slides/python-net/th/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/th/aspose.slides.charts/chartdata/series_groups/) | รับกลุ่มของ series.<br/>            อ่านอย่างเดียว [`IChartSeriesGroupCollection`](/slides/python-net/th/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/th/aspose.slides.charts/chartdata/categories/) | รับหมวดหมู่หลัก (หรือหมวดหมู่หลักและรองทั้งสอง <br/>            หากคุณสมบัติ [`ChartData.use_secondary_categories`](/slides/python-net/th/aspose.slides.charts/chartdata/use_secondary_categories) เป็น false).<br/>            อ่านอย่างเดียว [`IChartCategoryCollection`](/slides/python-net/th/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/th/aspose.slides.charts/chartdata/use_secondary_categories/) | หากเป็น false แล้วคุณสมบัติ [`ChartData.secondary_categories`](/slides/python-net/th/aspose.slides.charts/chartdata/secondary_categories) จะคืนค่า None และข้อมูล <br/>            ในคุณสมบัติ [`ChartData.categories`](/slides/python-net/th/aspose.slides.charts/chartdata/categories) จะใช้สำหรับ series หลักและรองทั้งสอง.<br/>            หากเป็น true แล้วข้อมูลในคุณสมบัติ [`ChartData.secondary_categories`](/slides/python-net/th/aspose.slides.charts/chartdata/secondary_categories) จะใช้สำหรับ series รองและข้อมูล <br/>            ในคุณสมบัติ [`ChartData.categories`](/slides/python-net/th/aspose.slides.charts/chartdata/categories) จะใช้สำหรับ series หลัก.<br/>            อ่าน/เขียน **bool**. |
| [`secondary_categories`](/slides/python-net/th/aspose.slides.charts/chartdata/secondary_categories/) | รับหมวดหมู่รอง หากคุณสมบัติ [`ChartData.use_secondary_categories`](/slides/python-net/th/aspose.slides.charts/chartdata/use_secondary_categories) เป็น true.<br/>            อ่านอย่างเดียว [`IChartCategoryCollection`](/slides/python-net/th/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/th/aspose.slides.charts/chartdata/data_source_type/) | แสดงเส้นทางของ workbook ภายนอกหากเป็นแหล่งข้อมูลภายนอก, มิฉะนั้นเป็น None |
| [`external_workbook_path`](/slides/python-net/th/aspose.slides.charts/chartdata/external_workbook_path/) | แสดงแหล่งข้อมูลของแผนภูมิ |
| [`embedded_workbook_type`](/slides/python-net/th/aspose.slides.charts/chartdata/embedded_workbook_type/) | รับประเภทของ workbook ที่ฝังอยู่.<br/>            คืนค่า [`WorkbookType.NOT_DEFINED`](/slides/python-net/th/aspose.slides.charts/workbooktype/NOT_DEFINED) หาก [`ChartData.data_source_type`](/slides/python-net/th/aspose.slides.charts/chartdata/data_source_type) เป็น <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/th/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>            อ่านอย่างเดียว [`WorkbookType`](/slides/python-net/th/aspose.slides.charts/workbooktype). |

## เมธอด

| Method | Description |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/th/aspose.slides.charts/chartdata/set_external_workbook/#str) | ตั้งค่า workbook ภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ. ข้อมูลแผนภูมิจะถูกอัพเดตจาก workbook เป้าหมาย. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/th/aspose.slides.charts/chartdata/set_external_workbook/#str-bool) | ตั้งค่า workbook ภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ. |
| [`read_workbook_stream(self)`](/slides/python-net/th/aspose.slides.charts/chartdata/read_workbook_stream/#) | เขียน Excel workbook ที่บรรจุภายในลงใน stream. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/th/aspose.slides.charts/chartdata/write_workbook_stream/#iorawiobase) | เริ่มต้น Excel workbook ที่บรรจุภายในด้วยค่าที่ผู้ใช้ระบุ. |
| [`get_range(self)`](/slides/python-net/th/aspose.slides.charts/chartdata/get_range/#) | รับช่วงข้อมูลของแผนภูมิ. |
| [`set_range(self, formula)`](/slides/python-net/th/aspose.slides.charts/chartdata/set_range/#str) | ตั้งค่าช่วงข้อมูลของแผนภูมิ. Series และ categories จะอัพเดตตามช่วงข้อมูลใหม่.<br/>            หากจำนวน series ในช่วงข้อมูลมากกว่าจำนวน series ใน chart data แล้วจะเพิ่ม series เพิ่มเติมที่มีประเภทเดียวกับ series สุดท้ายในคอลเลกชันปัจจุบันที่ส่วนท้ายของคอลเลกชัน. |
| [`refresh_data(self)`](/slides/python-net/th/aspose.slides.charts/chartdata/refresh_data/#) | รีเฟรชข้อมูลแผนภูมิโดยโหลดใหม่จาก workbook แหล่งข้อมูล. |
| [`switch_row_column(self)`](/slides/python-net/th/aspose.slides.charts/chartdata/switch_row_column/#) | สลับข้อมูลบนแกน.<br/>            ข้อมูลที่แสดงบนแกน X จะย้ายไปที่แกน Y และกลับกัน. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)
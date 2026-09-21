---
title: ChartData class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/chartdata/
---
## ChartData คลาส

แสดงข้อมูลที่ใช้สำหรับการพล็อตแผนภูมิ

ประเภท ChartData เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/th/aspose.slides.charts/chartdata/chart_data_workbook/) | ดึงตัวสร้างเซลล์เพื่อสร้างเซลล์ที่ใช้สำหรับชุดข้อมูลแผนภูมิหรือหมวดหมู่.<br/>            อ่านอย่างเดียว [`IChartDataWorkbook`](/slides/python-net/th/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/th/aspose.slides.charts/chartdata/series/) | ดึงชุดข้อมูล.<br/>            อ่านอย่างเดียว [`IChartSeriesCollection`](/slides/python-net/th/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/th/aspose.slides.charts/chartdata/series_groups/) | ดึงกลุ่มของชุดข้อมูล.<br/>            อ่านอย่างเดียว [`IChartSeriesGroupCollection`](/slides/python-net/th/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/th/aspose.slides.charts/chartdata/categories/) | ดึงหมวดหมู่หลัก (หรือทั้งหมวดหมู่หลักและรอง หาก [`ChartData.use_secondary_categories`](/slides/python-net/th/aspose.slides.charts/chartdata/use_secondary_categories) คุณสมบัติเป็น false).<br/>            อ่านอย่างเดียว [`IChartCategoryCollection`](/slides/python-net/th/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/th/aspose.slides.charts/chartdata/use_secondary_categories/) | ถ้า false แล้ว [`ChartData.secondary_categories`](/slides/python-net/th/aspose.slides.charts/chartdata/secondary_categories) คุณสมบัติคืนค่า None และข้อมูล<br/>            ใน [`ChartData.categories`](/slides/python-net/th/aspose.slides.charts/chartdata/categories) คุณสมบัติจะใช้สำหรับชุดข้อมูลหลักและรองทั้งคู่.<br/>            ถ้า true แล้วข้อมูลใน [`ChartData.secondary_categories`](/slides/python-net/th/aspose.slides.charts/chartdata/secondary_categories) คุณสมบัติจะใช้สำหรับชุดข้อมูลรองและข้อมูล<br/>            ใน [`ChartData.categories`](/slides/python-net/th/aspose.slides.charts/chartdata/categories) คุณสมบัติจะใช้สำหรับชุดข้อมูลหลัก.<br/>            อ่าน/เขียน **bool**. |
| [`secondary_categories`](/slides/python-net/th/aspose.slides.charts/chartdata/secondary_categories/) | ดึงหมวดหมู่รองหาก [`ChartData.use_secondary_categories`](/slides/python-net/th/aspose.slides.charts/chartdata/use_secondary_categories) คุณสมบัติเป็น true.<br/>            อ่านอย่างเดียว [`IChartCategoryCollection`](/slides/python-net/th/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/th/aspose.slides.charts/chartdata/data_source_type/) | แสดงเส้นทางของเวิร์กบุ๊กภายนอกหากเป็นแหล่งข้อมูลภายนอก, มิฉะนั้นเป็น None |
| [`external_workbook_path`](/slides/python-net/th/aspose.slides.charts/chartdata/external_workbook_path/) | แสดงแหล่งข้อมูลของแผนภูมิ |
| [`embedded_workbook_type`](/slides/python-net/th/aspose.slides.charts/chartdata/embedded_workbook_type/) | ดึงประเภทของเวิร์กบุ๊กที่ฝังอยู่.<br/>            คืนค่า [`WorkbookType.NOT_DEFINED`](/slides/python-net/th/aspose.slides.charts/workbooktype/NOT_DEFINED) หาก [`ChartData.data_source_type`](/slides/python-net/th/aspose.slides.charts/chartdata/data_source_type) คือ <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/th/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>            อ่านอย่างเดียว [`WorkbookType`](/slides/python-net/th/aspose.slides.charts/workbooktype). |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/th/aspose.slides.charts/chartdata/set_external_workbook/#str) | ตั้งค่าเวิร์กบุ๊กภายนอกรเป็นแหล่งข้อมูลสำหรับแผนภูมิ. ข้อมูลแผนภูมิจะได้รับการอัปเดตจากเวิร์กบุ๊กเป้าหมาย. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/th/aspose.slides.charts/chartdata/set_external_workbook/#str-bool) | ตั้งค่าเวิร์กบุ๊กภายนอกรเป็นแหล่งข้อมูลสำหรับแผนภูมิ. |
| [`read_workbook_stream(self)`](/slides/python-net/th/aspose.slides.charts/chartdata/read_workbook_stream/#) | เขียนเวิร์กบุ๊ก Excel ที่บรรจุอยู่ภายในลงในสตรีม. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/th/aspose.slides.charts/chartdata/write_workbook_stream/#iorawiobase) | เริ่มต้นเวิร์กบุ๊ก Excel ที่บรรจุอยู่ภายในด้วยค่าที่ผู้ใช้ระบุ. |
| [`get_range(self)`](/slides/python-net/th/aspose.slides.charts/chartdata/get_range/#) | ดึงช่วงข้อมูลแผนภูมิ. |
| [`set_range(self, formula)`](/slides/python-net/th/aspose.slides.charts/chartdata/set_range/#str) | ตั้งค่าช่วงข้อมูลแผนภูมิ. ชุดข้อมูลและหมวดหมู่จะได้รับการอัปเดตตามช่วงข้อมูลใหม่.<br/>            หากจำนวนชุดข้อมูลในช่วงข้อมูลมากกว่าจำนวนชุดข้อมูลในข้อมูลแผนภูมิ จะมีการเพิ่มชุดข้อมูลเพิ่มเติมที่มีประเภทเดียวกับชุดข้อมูลสุดท้ายในคอลเล็กชันปัจจุบันที่ปลายคอลเล็กชัน. |
| [`switch_row_column(self)`](/slides/python-net/th/aspose.slides.charts/chartdata/switch_row_column/#) | สลับข้อมูลผ่านแกน.<br/>            ข้อมูลที่แสดงบนแกน X จะย้ายไปที่แกน Y และในทางกลับกัน. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ห้องสมุด [`Aspose.Slides`](/slides/python-net)
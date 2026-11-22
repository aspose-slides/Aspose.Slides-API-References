---
title: IChartData class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/ichartdata/
---
## IChartData คลาส

แสดงข้อมูลที่ใช้สำหรับการพล็อตแผนภูมิ

ประเภท IChartData แสดงรายการสมาชิกดังต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/th/aspose.slides.charts/ichartdata/chart_data_workbook/) | รับตัวผลิตเซลล์เพื่อสร้างเซลล์ที่ใช้สำหรับซีรีส์หรือหมวดหมู่ของแผนภูมิ.<br/>            อ่านอย่างเดียว [`IChartDataWorkbook`](/slides/python-net/th/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/th/aspose.slides.charts/ichartdata/series/) | รับซีรีส์.<br/>            อ่านอย่างเดียว [`IChartSeriesCollection`](/slides/python-net/th/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/th/aspose.slides.charts/ichartdata/series_groups/) | รับกลุ่มของซีรีส์.<br/>            อ่านอย่างเดียว [`IChartSeriesGroupCollection`](/slides/python-net/th/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/categories/) | รับหมวดหมู่หลัก (หรือทั้งหมวดหมู่หลักและรอง <br/>            หากคุณสมบัติ [`IChartData.use_secondary_categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/use_secondary_categories) เป็น false).<br/>            อ่านอย่างเดียว [`IChartCategoryCollection`](/slides/python-net/th/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/use_secondary_categories/) | หากเป็น false แล้วคุณสมบัติ [`IChartData.secondary_categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/secondary_categories) จะคืนค่า None และข้อมูล<br/>            ในคุณสมบัติ [`IChartData.categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/categories) จะใช้ทั้งสำหรับซีรีส์หลักและรอง.<br/>            หากเป็น true แล้วข้อมูลในคุณสมบัติ [`IChartData.secondary_categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/secondary_categories) จะใช้สำหรับซีรีส์รองและข้อมูล<br/>            ในคุณสมบัติ [`IChartData.categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/categories) จะใช้สำหรับซีรีส์หลัก.<br/>            อ่าน/เขียน **bool**. |
| [`secondary_categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/secondary_categories/) | รับหมวดหมู่รองหากคุณสมบัติ [`IChartData.use_secondary_categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/use_secondary_categories) เป็น true.<br/>            อ่านอย่างเดียว [`IChartCategoryCollection`](/slides/python-net/th/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/th/aspose.slides.charts/ichartdata/data_source_type/) | แสดงแหล่งข้อมูลของแผนภูมิ |
| [`external_workbook_path`](/slides/python-net/th/aspose.slides.charts/ichartdata/external_workbook_path/) | แสดงเส้นทางของเวิร์กบุ๊กภายนอกหากแหล่งข้อมูลเป็นภายนอก, มิฉะนั้นเป็น None |
| [`embedded_workbook_type`](/slides/python-net/th/aspose.slides.charts/ichartdata/embedded_workbook_type/) | รับประเภทของเวิร์กบุ๊กที่ฝังไว้.<br/>            คืนค่า [`WorkbookType.NOT_DEFINED`](/slides/python-net/th/aspose.slides.charts/workbooktype/NOT_DEFINED) หาก [`IChartData.data_source_type`](/slides/python-net/th/aspose.slides.charts/ichartdata/data_source_type) เป็น <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/th/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>            อ่านอย่างเดียว [`WorkbookType`](/slides/python-net/th/aspose.slides.charts/workbooktype). |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/th/aspose.slides.charts/ichartdata/set_external_workbook/#str) | ตั้งค่าเวิร์กบุ๊กภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ. ข้อมูลแผนภูมิจะได้รับการอัปเดตจากเวิร์กบุ๊กเป้าหมาย. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/th/aspose.slides.charts/ichartdata/set_external_workbook/#str-bool) | ตั้งค่าเวิร์กบุ๊กภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ. |
| [`read_workbook_stream(self)`](/slides/python-net/th/aspose.slides.charts/ichartdata/read_workbook_stream/#) | เขียนเวิร์กบุ๊ก Excel ที่บรรจุภายในลงในสตรีมหน่วยความจำ. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/th/aspose.slides.charts/ichartdata/write_workbook_stream/#iorawiobase) | เริ่มต้นเวิร์กบุ๊ก Excel ที่บรรจุภายในด้วยค่าที่ผู้ใช้ระบุ. |
| [`set_range(self, formula)`](/slides/python-net/th/aspose.slides.charts/ichartdata/set_range/#str) | ตั้งช่วงข้อมูลแผนภูมิ. ซีรีส์และหมวดหมู่จะได้รับการอัปเดตตามช่วงข้อมูลใหม่.<br/>            หากจำนวนซีรีส์ในช่วงข้อมูลมากกว่าจำนวนซีรีส์ในข้อมูลแผนภูมิแล้ว ซีรีส์เพิ่มเติมที่มีประเภทเดียวกับซีรีส์สุดท้ายในคอลเลกชันปัจจุบันจะถูกเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชัน. |
| [`get_range(self)`](/slides/python-net/th/aspose.slides.charts/ichartdata/get_range/#) | รับช่วงข้อมูลแผนภูมิ. |
| [`switch_row_column(self)`](/slides/python-net/th/aspose.slides.charts/ichartdata/switch_row_column/#) | สลับข้อมูลบนแกน.<br/>            ข้อมูลที่แสดงบนแกน X จะย้ายไปยังแกน Y และในทางกลับกัน. |
| [`refresh_data(self)`](/slides/python-net/th/aspose.slides.charts/ichartdata/refresh_data/#) | รีเฟรชข้อมูลแผนภูมิโดยโหลดใหม่จากเวิร์กบุ๊กแหล่งข้อมูล. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)
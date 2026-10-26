---
title: ChartCategoryCollection class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.charts/chartcategorycollection/
---
## คลาส ChartCategoryCollection

แสดงถึงคอลเลกชันของ [`ChartCategory`](/slides/python-net/th/aspose.slides.charts/chartcategory)

ประเภท ChartCategoryCollection เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`use_cells`](/slides/python-net/th/aspose.slides.charts/chartcategorycollection/use_cells/) | ถ้าเป็น true แล้ว worksheet จะถูกใช้เพื่อเก็บหมวดหมู่ (กรณีนี้สนับสนุนหมวดหมู่หลายระดับ).<br/>            ถ้าเป็น false แล้ว worksheet จะ **ไม่** ถูกใช้เพื่อเก็บค่า (และกรณีนี้ไม่สนับสนุน<br/>            หมวดหมู่หลายระดับ).<br/>            อ่าน/เขียน **bool**. |
| [`grouping_level_count`](/slides/python-net/th/aspose.slides.charts/chartcategorycollection/grouping_level_count/) | ส่งกลับจำนวนระดับการจัดกลุ่มหมวดหมู่ที่ใช้.<br/>            มีค่ามากกว่าหนึ่งสำหรับหมวดหมู่หลายระดับ.<br/>            อ่านอย่างเดียว **int**. |

รับองค์ประกอบที่ตำแหน่งที่ระบุ.

## ดัชนี

| ชื่อ | คำอธิบาย |
| :- | :- |
| [`[index]`](/slides/python-net/th/aspose.slides.charts/chartcategorycollection/__getitem__/) |  |

## วิธีการ

| วิธีการ | คำอธิบาย |
| :- | :- |
| [`add(self, chart_data_cell)`](/slides/python-net/th/aspose.slides.charts/chartcategorycollection/add/#ichartdatacell) | ถ้าหมวดหมู่มีอยู่ในคอลเลกชันแล้วให้คืนค่ามัน. หากไม่มีก็สร้างหมวดหมู่กราฟใหม่จาก <br/>            [`IChartDataCell`](/slides/python-net/th/aspose.slides.charts/ichartdatacell) แล้วเพิ่มเข้าไปในคอลเลกชัน. |
| [`add(self, value)`](/slides/python-net/th/aspose.slides.charts/chartcategorycollection/add/#any) | สร้าง [`ChartCategory`](/slides/python-net/th/aspose.slides.charts/chartcategory) ใหม่จากค่าและเพิ่มเข้าไปในคอลเลกชัน. |
| [`index_of(self, value)`](/slides/python-net/th/aspose.slides.charts/chartcategorycollection/index_of/#ichartcategory) | ค้นหา [`ChartCategory`](/slides/python-net/th/aspose.slides.charts/chartcategory) ที่ระบุและส่งกลับดัชนีเริ่มจากศูนย์ของการพบแรกภายในคอลเลกชันทั้งหมด. |
| [`remove(self, value)`](/slides/python-net/th/aspose.slides.charts/chartcategorycollection/remove/#ichartcategory) | ลบค่าที่ระบุ. |
| [`remove_at(self, index)`](/slides/python-net/th/aspose.slides.charts/chartcategorycollection/remove_at/#int) | ลบองค์ประกอบที่ตำแหน่งที่กำหนด. |
| [`clear(self)`](/slides/python-net/th/aspose.slides.charts/chartcategorycollection/clear/#) | ลบทุกองค์ประกอบจากคอลเลกชัน. |


### ดูเพิ่มเติม
* คลาส [`ChartCategory`](/slides/python-net/th/aspose.slides.charts/chartcategory)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)
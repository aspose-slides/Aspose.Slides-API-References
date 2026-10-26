---
title: IChartCategoryCollection class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET การอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/ichartcategorycollection/
---
## IChartCategoryCollection คลาส

แสดงถึงชุดของ [`IChartCategory`](/slides/python-net/th/aspose.slides.charts/ichartcategory)

ประเภท IChartCategoryCollection เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`use_cells`](/slides/python-net/th/aspose.slides.charts/ichartcategorycollection/use_cells/) | หากเป็น true แล้ว worksheet จะถูกใช้เพื่อเก็บ category (กรณีนี้รองรับการจัดระดับหลายระดับ).<br/>            หากเป็น false แล้ว worksheet **ไม่** ถูกใช้เพื่อเก็บค่า (และกรณีนี้ไม่รองรับการจัดระดับหลายระดับ).<br/>            อ่าน/เขียน **bool**. |
| [`grouping_level_count`](/slides/python-net/th/aspose.slides.charts/ichartcategorycollection/grouping_level_count/) | คืนค่าจำนวนระดับการจัดกลุ่ม category ที่ใช้.<br/>            มีมากกว่าหนึ่งสำหรับ category หลายระดับ.<br/>            อ่านอย่างเดียว **int**. |

รับองค์ประกอบที่ตำแหน่ง index ที่ระบุ.

## ดัชนี

| ชื่อ | คำอธิบาย |
| :- | :- |
| [`[index]`](/slides/python-net/th/aspose.slides.charts/ichartcategorycollection/__getitem__/) |  |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`add(self, chart_data_cell)`](/slides/python-net/th/aspose.slides.charts/ichartcategorycollection/add/#ichartdatacell) | หาก category มีอยู่ใน collection จะคืนค่ามัน. หากไม่มีจะสร้าง chart category ใหม่จาก <br/>            [`IChartDataCell`](/slides/python-net/th/aspose.slides.charts/ichartdatacell) และเพิ่มเข้าไปใน collection. |
| [`add(self, value)`](/slides/python-net/th/aspose.slides.charts/ichartcategorycollection/add/#any) | สร้าง [`IChartCategory`](/slides/python-net/th/aspose.slides.charts/ichartcategory) ใหม่จากค่าและเพิ่มเข้าไปใน collection. |
| [`index_of(self, value)`](/slides/python-net/th/aspose.slides.charts/ichartcategorycollection/index_of/#ichartcategory) | ค้นหา [`IChartCategory`](/slides/python-net/th/aspose.slides.charts/ichartcategory) ที่ระบุและคืนค่าดัชนีแบบศูนย์ฐานของการพบครั้งแรกใน Collection ทั้งหมด |
| [`remove(self, value)`](/slides/python-net/th/aspose.slides.charts/ichartcategorycollection/remove/#ichartcategory) | ลบค่าที่ระบุ. |
| [`remove_at(self, index)`](/slides/python-net/th/aspose.slides.charts/ichartcategorycollection/remove_at/#int) | ลบองค์ประกอบที่ตำแหน่งที่กำหนด. |
| [`clear(self)`](/slides/python-net/th/aspose.slides.charts/ichartcategorycollection/clear/#) | ลบทุกองค์ประกอบจาก collection. |


### ดูเพิ่มเติม
* คลาส [`IChartCategory`](/slides/python-net/th/aspose.slides.charts/ichartcategory)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)
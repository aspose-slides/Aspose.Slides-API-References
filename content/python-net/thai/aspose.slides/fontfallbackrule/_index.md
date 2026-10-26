---
title: FontFallBackRule class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/fontfallbackrule/
---
## FontFallBackRule คลาส

แสดงกฎการสำรองแบบอักษร

ประเภท FontFallBackRule เปิดเผยสมาชิกต่อไปนี้:

## ตัวสร้าง

| Constructor | Description |
| :- | :- |
| [`__init__(self, start_index, end_index, font_names)`](/slides/python-net/th/aspose.slides/fontfallbackrule/__init__/#int-int-str) | สร้างอินสแตนซ์ใหม่. |
| [`__init__(self, start_index, end_index, font_names)`](/slides/python-net/th/aspose.slides/fontfallbackrule/__init__/#int-int-liststr) | สร้างอินสแตนซ์ใหม่. |

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`range_start_index`](/slides/python-net/th/aspose.slides/fontfallbackrule/range_start_index/) | รับดัชนีแรกของช่วง Unicode ที่ต่อเนื่อง. |
| [`range_end_index`](/slides/python-net/th/aspose.slides/fontfallbackrule/range_end_index/) | รับดัชนีสุดท้ายของช่วง Unicode ที่ต่อเนื่อง. |
| [`count`](/slides/python-net/th/aspose.slides/fontfallbackrule/count/) | รับจำนวนแบบอักษรที่กำหนดจริงสำหรับช่วง<br/>            อ่านอย่างเดียว **int**. |

รับชื่อแบบอักษรที่ดัชนีที่ระบุ.            อ่านอย่างเดียว [`IFontFallBackRule`](/slides/python-net/th/aspose.slides/ifontfallbackrule).

## ดัชนี

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/th/aspose.slides/fontfallbackrule/__getitem__/) |  |

## วิธีการ

| Method | Description |
| :- | :- |
| [`add_fall_back_fonts(self, font_name)`](/slides/python-net/th/aspose.slides/fontfallbackrule/add_fall_back_fonts/#str) | เพิ่มแบบอักษรใหม่(s) ไปยังรายการแบบอักษร FallBack. |
| [`add_fall_back_fonts(self, font_names)`](/slides/python-net/th/aspose.slides/fontfallbackrule/add_fall_back_fonts/#liststr) | เพิ่มแบบอักษรใหม่ไปยังรายการแบบอักษร FallBack. |
| [`to_array(self)`](/slides/python-net/th/aspose.slides/fontfallbackrule/to_array/#) | สร้างและคืนค่าอาเรย์ที่มีแบบอักษร FallBack ทั้งหมดสำหรับกฎนี้. |
| [`to_array(self, start_index, count)`](/slides/python-net/th/aspose.slides/fontfallbackrule/to_array/#int-int) | สร้างและคืนค่าอาเรย์ที่มีแบบอักษร FallBack ทั้งหมดจากช่วงที่ระบุในรายการ. |
| [`clear(self)`](/slides/python-net/th/aspose.slides/fontfallbackrule/clear/#) | ลบแบบอักษรทั้งหมดออกจากรายการ. |
| [`remove(self, font_name)`](/slides/python-net/th/aspose.slides/fontfallbackrule/remove/#str) | ลบการเกิดครั้งแรกของแบบอักษร FallBack เฉพาะจากรายการ. |
| [`remove_at(self, index)`](/slides/python-net/th/aspose.slides/fontfallbackrule/remove_at/#int) | ลบแบบอักษร FallBack ที่ดัชนีที่ระบุในรายการ. |
| [`index_of(self, font_name)`](/slides/python-net/th/aspose.slides/fontfallbackrule/index_of/#str) | คืนค่าดัชนีของกฎที่ระบุในคอลเลกชัน. |


### ดูเพิ่มเติม
* คลาส [`IFontFallBackRule`](/slides/python-net/th/aspose.slides/ifontfallbackrule)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)
---
title: ICommentCollection class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/icommentcollection/
---
## ICommentCollection คลาส

Represents a collection of comments of one author.

The ICommentCollection type exposes the following members:

Gets the element at the specified index.
            อ่านอย่างเดียว [`IComment`](/slides/python-net/th/aspose.slides/icomment).

## ดัชนี

| ชื่อ | คำอธิบาย |
| :- | :- |
| [`[index]`](/slides/python-net/th/aspose.slides/icommentcollection/__getitem__/) |  |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`to_array(self)`](/slides/python-net/th/aspose.slides/icommentcollection/to_array/#) | สร้างและคืนอาเรย์ที่มีคอมเมนต์ทั้งหมด. |
| [`to_array(self, start_index, count)`](/slides/python-net/th/aspose.slides/icommentcollection/to_array/#int-int) | สร้างและคืนอาเรย์ที่มีคอมเมนต์ทั้งหมดจากช่วงที่ระบุ. |
| [`add_comment(self, text, slide, position, creation_time)`](/slides/python-net/th/aspose.slides/icommentcollection/add_comment/#str-islide-asposepydrawingpointf-datetime) | เพิ่มคอมเมนต์ใหม่ที่ท้ายของคอลเลกชัน. |
| [`add_modern_comment(self, text, slide, shape, position, creation_time)`](/slides/python-net/th/aspose.slides/icommentcollection/add_modern_comment/#str-islide-ishape-asposepydrawingpointf-datetime) | เพิ่มคอมเมนต์สมัยใหม่ใหม่ที่ท้ายของคอลเลกชัน. |
| [`insert_comment(self, index, text, slide, position, creation_time)`](/slides/python-net/th/aspose.slides/icommentcollection/insert_comment/#int-str-islide-asposepydrawingpointf-datetime) | แทรกคอมเมนต์ใหม่ลงในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [`insert_modern_comment(self, index, text, slide, shape, position, creation_time)`](/slides/python-net/th/aspose.slides/icommentcollection/insert_modern_comment/#int-str-islide-ishape-asposepydrawingpointf-datetime) | แทรกคอมเมนต์สมัยใหม่ใหม่ลงในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [`remove_at(self, index)`](/slides/python-net/th/aspose.slides/icommentcollection/remove_at/#int) | ลบองค์ประกอบที่ตำแหน่งที่ระบุในคอลเลกชัน. |
| [`remove(self, comment)`](/slides/python-net/th/aspose.slides/icommentcollection/remove/#icomment) | ลบการปรากฏครั้งแรกของคอมเมนต์ที่ระบุในคอลเลกชัน. |
| [`clear(self)`](/slides/python-net/th/aspose.slides/icommentcollection/clear/#) | ลบคอมเมนต์ทั้งหมดจากคอลเลกชัน. |

### ดูเพิ่มเติม
* คลาส [`IComment`](/slides/python-net/th/aspose.slides/icomment)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)
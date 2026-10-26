---
title: PPImage class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/ppimage/
---
## คลาส PPImage

เป็นตัวแทนของภาพในงานนำเสนอ

ประเภท PPImage มีสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`binary_data`](/slides/python-net/th/aspose.slides/ppimage/binary_data/) | คืนสำเนาข้อมูลของภาพ<br/>            อ่านอย่างเดียว **int**[]. |
| [`image`](/slides/python-net/th/aspose.slides/ppimage/image/) | คืนสำเนาของภาพ<br/>            อ่านอย่างเดียว [`IImage`](/slides/python-net/th/aspose.slides/iimage). |
| [`svg_image`](/slides/python-net/th/aspose.slides/ppimage/svg_image/) | คืนหรือกำหนดออบเจ็กต์ ISvgImage [`ISvgImage`](/slides/python-net/th/aspose.slides/isvgimage) |
| [`content_type`](/slides/python-net/th/aspose.slides/ppimage/content_type/) | คืนชนิด MIME ของภาพที่เข้ารหัสใน [`PPImage.binary_data`](/slides/python-net/th/aspose.slides/ppimage/binary_data).<br/>            อ่านอย่างเดียว **str**. |
| [`width`](/slides/python-net/th/aspose.slides/ppimage/width/) | คืนความกว้างของภาพ<br/>            อ่านอย่างเดียว **int**. |
| [`height`](/slides/python-net/th/aspose.slides/ppimage/height/) | คืนความสูงของภาพ<br/>            อ่านอย่างเดียว **int**. |
| [`x`](/slides/python-net/th/aspose.slides/ppimage/x/) | คืนค่า X-offset ของภาพ<br/>            อ่านอย่างเดียว **int**. |
| [`y`](/slides/python-net/th/aspose.slides/ppimage/y/) | คืนค่า Y-offset ของภาพ<br/>            อ่านอย่างเดียว **int**. |

## วิธีการ

| เมธอด | คำอธิบาย |
| :- | :- |
| [`replace_image(self, new_image_data)`](/slides/python-net/th/aspose.slides/ppimage/replace_image/#bytes) | แทนที่ข้อมูลภาพ<br/>            ข้อมูลของภาพใหม่เมื่อพารามิเตอร์ newImageData เป็น None. |
| [`replace_image(self, new_image)`](/slides/python-net/th/aspose.slides/ppimage/replace_image/#iimage) | แทนที่ข้อมูลภาพ. คำเตือน: เมื่อ Image เป็น metafile - จะถูก rasterized. ใช้ ReplaceImage(byte[]) แทน<br/>            ภาพใหม่เมื่อพารามิเตอร์ newImage เป็น None. |
| [`replace_image(self, new_image)`](/slides/python-net/th/aspose.slides/ppimage/replace_image/#ippimage) | แทนที่ข้อมูลภาพ<br/>            IPPImage ใหม่เมื่อพารามิเตอร์ newImage เป็น None. |


### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)
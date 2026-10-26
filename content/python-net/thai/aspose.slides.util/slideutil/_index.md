---
title: SlideUtil class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.util/slideutil/
---
## SlideUtil คลาส

ให้เมธอดที่ช่วยค้นหารูปร่างและข้อความในงานนำเสนอ

ประเภท SlideUtil แสดงสมาชิกต่อไปนี้:

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`find_shape(pres, alt_text)`](/slides/python-net/th/aspose.slides.util/slideutil/find_shape/#ipresentation-str) | ค้นหารูปร่างโดยข้อความอธิบายแทนในงานนำเสนอ PPTX. |
| [`find_shape(slide, alt_text)`](/slides/python-net/th/aspose.slides.util/slideutil/find_shape/#ibaseslide-str) | ค้นหารูปร่างโดยข้อความอธิบายแทนบนสไลด์ในงานนำเสนอ PPTX. |
| [`align_shapes(alignment_type, align_to_slide, slide)`](/slides/python-net/th/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-ibaseslide) | เปลี่ยนตำแหน่งของรูปร่างทั้งหมดบนสไลด์ จัดตำแหน่งรูปร่างให้ชิดขอบหรือขอบของสไลด์<br/>            หรือจัดตำแหน่งโดยอิงจากกันและกัน. |
| [`align_shapes(alignment_type, align_to_slide, slide, shape_indexes)`](/slides/python-net/th/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-ibaseslide-listint) | เปลี่ยนตำแหน่งของรูปร่างที่เลือกบนสไลด์ จัดตำแหน่งรูปร่างให้ชิดขอบหรือขอบของสไลด์<br/>             หรือจัดตำแหน่งโดยอิงจากกันและกัน. |
| [`align_shapes(alignment_type, align_to_slide, group_shape)`](/slides/python-net/th/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-igroupshape) | เปลี่ยนตำแหน่งของรูปร่างทั้งหมดภายในกลุ่มรูปร่าง จัดตำแหน่งรูปร่างให้ชิดขอบหรือขอบของสไลด์<br/>            หรือจัดตำแหน่งโดยอิงจากกันและกัน. |
| [`align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes)`](/slides/python-net/th/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-igroupshape-listint) | เปลี่ยนตำแหน่งของรูปร่างที่เลือกภายในกลุ่มรูปร่าง จัดตำแหน่งรูปร่างให้ชิดขอบหรือขอบของสไลด์<br/>            หรือจัดตำแหน่งโดยอิงจากกันและกัน. |
| [`find_shapes_by_placeholder_type(slide, placeholder_type)`](/slides/python-net/th/aspose.slides.util/slideutil/find_shapes_by_placeholder_type/#ibaseslide-placeholdertype) | ค้นหารูปร่างทั้งหมดบนสไลด์ที่ระบุที่ตรงกับประเภท placeholder ที่กำหนด. |
| [`find_and_replace_text(presentation, with_masters, find, replace, format)`](/slides/python-net/th/aspose.slides.util/slideutil/find_and_replace_text/#ipresentation-bool-str-str-portionformat) | ค้นหาและแทนที่ข้อความในงานนำเสนอด้วยรูปแบบที่กำหนด |
| [`get_all_text_boxes(slide)`](/slides/python-net/th/aspose.slides.util/slideutil/get_all_text_boxes/#ibaseslide) | ส่งคืน text frames ทั้งหมดบนสไลด์ในงานนำเสนอ PPTX. |
| [`get_text_boxes_contains_text(slide, text, check_placeholder_text)`](/slides/python-net/th/aspose.slides.util/slideutil/get_text_boxes_contains_text/#ibaseslide-str-bool) | ส่งคืน text frames ทั้งหมดบนสไลด์ที่ระบุที่มีข้อความที่กำหนด. |
| [`get_all_text_frames(pres, with_masters)`](/slides/python-net/th/aspose.slides.util/slideutil/get_all_text_frames/#ipresentation-bool) | ส่งคืน text frames ทั้งหมดในงานนำเสนอ PPTX. |
| [`to_save_format(format)`](/slides/python-net/th/aspose.slides.util/slideutil/to_save_format/#sourceformat) | แปลงรูปแบบไฟล์ต้นฉบับเป็น [`SaveFormat`](/slides/python-net/th/aspose.slides.export/saveformat) ที่สอดคล้องกัน. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.util`](/slides/python-net/th/aspose.slides.util)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)
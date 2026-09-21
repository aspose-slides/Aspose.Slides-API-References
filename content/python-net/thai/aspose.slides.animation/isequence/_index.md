---
title: ISequence class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides.animation/isequence/
---
## ISequence คลาส

แสดงลำดับ (การรวบรวมของเอฟเฟกต์)

ประเภท ISequence เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`count`](/slides/python-net/th/aspose.slides.animation/isequence/count/) | ส่งคืนจำนวนเอฟเฟกต์ใน sequense.<br/>            อ่านอย่างเดียว **int**. |
| [`trigger_shape`](/slides/python-net/th/aspose.slides.animation/isequence/trigger_shape/) | ส่งคืนหรือกำหนดเป้าหมายรูปร่างสำหรับลำดับ INTERACTIVE.<br/>            หากลำดับไม่ใช่ interactive จะส่งคืน None.<br/>            อ่าน/เขียน [`IShape`](/slides/python-net/th/aspose.slides/ishape). |

ส่งคืนเอฟเฟกต์ที่ตำแหน่งที่ระบุ

## ดัชนี

| ชื่อ | คำอธิบาย |
| :- | :- |
| [`[index]`](/slides/python-net/th/aspose.slides.animation/isequence/__getitem__/) | ดัชนี |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`add_effect(self, shape, effect_type, subtype, trigger_type)`](/slides/python-net/th/aspose.slides.animation/isequence/add_effect/#ishape-effecttype-effectsubtype-effecttriggertype) | เพิ่มเอฟเฟกต์ใหม่ไปยังท้ายของลำดับ. |
| [`add_effect(self, paragraph, effect_type, subtype, trigger_type)`](/slides/python-net/th/aspose.slides.animation/isequence/add_effect/#iparagraph-effecttype-effectsubtype-effecttriggertype) | เพิ่มเอฟเฟกต์แอนิเมชันใหม่สำหรับย่อหน้าที่ท้ายของลำดับ. |
| [`add_effect(self, chart, type, index, effect_type, subtype, trigger_type)`](/slides/python-net/th/aspose.slides.animation/isequence/add_effect/#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype) | เพิ่มเอฟเฟกต์แอนิเมชันชาร์ตใหม่สำหรับหมวดหรือชุดข้อมูลที่ท้ายของลำดับ. |
| [`add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type)`](/slides/python-net/th/aspose.slides.animation/isequence/add_effect/#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype) | เพิ่มเอฟเฟกต์แอนิเมชันชาร์ตใหม่สำหรับองค์ประกอบในหมวดหรือชุดข้อมูลที่ท้ายของลำดับ. |
| [`remove(self, item)`](/slides/python-net/th/aspose.slides.animation/isequence/remove/#ieffect) | ลบเอฟเฟกต์ที่ระบุจากคอลเลกชัน. |
| [`remove_at(self, index)`](/slides/python-net/th/aspose.slides.animation/isequence/remove_at/#int) | ลบเอฟเฟกต์จากคอลเลกชัน. |
| [`clear(self)`](/slides/python-net/th/aspose.slides.animation/isequence/clear/#) | ลบเอฟเฟกต์ทั้งหมดจากคอลเลกชัน. |
| [`remove_by_shape(self, shape)`](/slides/python-net/th/aspose.slides.animation/isequence/remove_by_shape/#ishape) | ลบเอฟเฟกต์สำหรับรูปร่างที่ระบุ. |
| [`get_effects_by_shape(self, shape)`](/slides/python-net/th/aspose.slides.animation/isequence/get_effects_by_shape/#ishape) | ส่งคืนอาร์เรย์ของเอฟเฟกต์สำหรับรูปร่างที่ระบุ. |
| [`get_effects_by_paragraph(self, paragraph)`](/slides/python-net/th/aspose.slides.animation/isequence/get_effects_by_paragraph/#iparagraph) | ส่งคืนอาร์เรย์ของเอฟเฟกต์สำหรับย่อหน้าที่ระบุ. |
| [`get_count(self, shape)`](/slides/python-net/th/aspose.slides.animation/isequence/get_count/#ishape) | ส่งคืนจำนวนเอฟเฟกต์สำหรับรูปร่างที่ระบุ. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.animation`](/slides/python-net/th/aspose.slides.animation)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)
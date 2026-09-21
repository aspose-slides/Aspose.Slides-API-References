---
title: Sequence class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API อ้างอิง
description: 
type: docs
url: /th/aspose.slides.animation/sequence/
---
## คลาส Sequence

แทนความหมายของลำดับ (คอลเลกชันของเอฟเฟกต์)

ประเภท Sequence เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`count`](/slides/python-net/th/aspose.slides.animation/sequence/count/) | คืนจำนวนเอฟเฟกต์ในลำดับ.<br/>            อ่านอย่างเดียว **int**. |
| [`trigger_shape`](/slides/python-net/th/aspose.slides.animation/sequence/trigger_shape/) | คืนหรือกำหนดเป้าหมาย shape สำหรับลำดับ INTERACTIVE.<br/>            หากลำดับไม่ใช่ interactive แล้วจะคืนค่า None.<br/>            อ่าน/เขียน [`IShape`](/slides/python-net/th/aspose.slides/ishape). |

คืนเอฟเฟกต์ที่ตำแหน่งระบุ

## ดัชนี

| ชื่อ | คำอธิบาย |
| :- | :- |
| [`[index]`](/slides/python-net/th/aspose.slides.animation/sequence/__getitem__/) |  |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`add_effect(self, shape, effect_type, subtype, trigger_type)`](/slides/python-net/th/aspose.slides.animation/sequence/add_effect/#ishape-effecttype-effectsubtype-effecttriggertype) | เพิ่มเอฟเฟกต์ใหม่ที่ส่วนท้ายของลำดับ. |
| [`add_effect(self, paragraph, effect_type, subtype, trigger_type)`](/slides/python-net/th/aspose.slides.animation/sequence/add_effect/#iparagraph-effecttype-effectsubtype-effecttriggertype) | เพิ่มเอฟเฟกต์แอนิเมชันใหม่สำหรับย่อหน้าที่ส่วนท้ายของลำดับ. |
| [`add_effect(self, chart, type, index, effect_type, subtype, trigger_type)`](/slides/python-net/th/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype) | เพิ่มเอฟเฟกต์แอนิเมชันใหม่ของแผนภูมิสำหรับหมวดหรือซีรีส์ที่ส่วนท้ายของลำดับ. |
| [`add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type)`](/slides/python-net/th/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype) | เพิ่มเอฟเฟกต์แอนิเมชันใหม่ของแผนภูมิสำหรับองค์ประกอบในหมวดหรือซีรีส์ที่ส่วนท้ายของลำดับ. |
| [`remove(self, item)`](/slides/python-net/th/aspose.slides.animation/sequence/remove/#ieffect) | เอาเอฟเฟกต์ที่ระบุออกจากคอลเลกชัน. |
| [`remove_at(self, index)`](/slides/python-net/th/aspose.slides.animation/sequence/remove_at/#int) | เอาเอฟเฟกต์ออกจากคอลเลกชัน. |
| [`clear(self)`](/slides/python-net/th/aspose.slides.animation/sequence/clear/#) | เอาเอฟเฟกต์ทั้งหมดออกจากคอลเลกชัน. |
| [`remove_by_shape(self, shape)`](/slides/python-net/th/aspose.slides.animation/sequence/remove_by_shape/#ishape) | เอาเอฟเฟกต์ออกสำหรับ shape ที่ระบุ. |
| [`get_effects_by_shape(self, shape)`](/slides/python-net/th/aspose.slides.animation/sequence/get_effects_by_shape/#ishape) | คืนอาร์เรย์ของเอฟเฟกต์สำหรับ shape ที่ระบุ. |
| [`get_effects_by_paragraph(self, paragraph)`](/slides/python-net/th/aspose.slides.animation/sequence/get_effects_by_paragraph/#iparagraph) | คืนอาร์เรย์ของเอฟเฟกต์สำหรับย่อหน้าที่ระบุ. |
| [`get_count(self, shape)`](/slides/python-net/th/aspose.slides.animation/sequence/get_count/#ishape) | คืนจำนวนเอฟเฟกต์สำหรับ shape ที่ระบุ. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.animation`](/slides/python-net/th/aspose.slides.animation)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)
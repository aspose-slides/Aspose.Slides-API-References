---
title: add_effect method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides.animation/sequence/add_effect/
weight: 10
---
## add_effect(self, shape, effect_type, subtype, trigger_type) {#ishape-effecttype-effectsubtype-effecttriggertype}
เพิ่มเอฟเฟ็กต์ใหม่ไปที่ตำแหน่งสุดท้ายของลำดับ.

### Returns

New effect object [`IEffect`](/slides/python-net/th/aspose.slides.animation/ieffect)



```python
def add_effect(self, shape, effect_type, subtype, trigger_type):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| shape | [`IShape`](/slides/python-net/th/aspose.slides/ishape) | Shape วัตถุ [`IShape`](/slides/python-net/th/aspose.slides/ishape) สำหรับเพิ่มเอฟเฟ็กต์ |
| effect_type | [`EffectType`](/slides/python-net/th/aspose.slides.animation/effecttype) | ประเภทของเอฟเฟ็กต์แอนิเมชัน [`EffectType`](/slides/python-net/th/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/th/aspose.slides.animation/effectsubtype) | ชนิดย่อยของเอฟเฟ็กต์แอนิเมชัน [`EffectSubtype`](/slides/python-net/th/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/th/aspose.slides.animation/effecttriggertype) | ประเภทการกระตุ้นของเอฟเฟ็กต์ [`EffectTriggerType`](/slides/python-net/th/aspose.slides.animation/effecttriggertype) |


## add_effect(self, paragraph, effect_type, subtype, trigger_type) {#iparagraph-effecttype-effectsubtype-effecttriggertype}
เพิ่มเอฟเฟ็กต์แอนิเมชันใหม่สำหรับย่อหน้าที่ตำแหน่งสุดท้ายของลำดับ.

### Returns

New effect object [`IEffect`](/slides/python-net/th/aspose.slides.animation/ieffect)



```python
def add_effect(self, paragraph, effect_type, subtype, trigger_type):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| paragraph | [`IParagraph`](/slides/python-net/th/aspose.slides/iparagraph) | Paragraph วัตถุ [`IParagraph`](/slides/python-net/th/aspose.slides/iparagraph) |
| effect_type | [`EffectType`](/slides/python-net/th/aspose.slides.animation/effecttype) | ประเภทของเอฟเฟ็กต์แอนิเมชัน [`EffectType`](/slides/python-net/th/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/th/aspose.slides.animation/effectsubtype) | ชนิดย่อยของเอฟเฟ็กต์แอนิเมชัน [`EffectSubtype`](/slides/python-net/th/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/th/aspose.slides.animation/effecttriggertype) | ประเภทการกระตุ้นของเอฟเฟ็กต์ [`EffectTriggerType`](/slides/python-net/th/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype}
เพิ่มเอฟเฟ็กต์แอนิเมชันใหม่สำหรับแผนภูมิในหมวดหรือชุดข้อมูลไปที่ตำแหน่งสุดท้ายของลำดับ.

### Returns

New effect object [`IEffect`](/slides/python-net/th/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, index, effect_type, subtype, trigger_type):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/th/aspose.slides.charts/ichart) | Chart วัตถุ [`IChart`](/slides/python-net/th/aspose.slides.charts/ichart) |
| type | [`EffectChartMajorGroupingType`](/slides/python-net/th/aspose.slides.animation/effectchartmajorgroupingtype) | ประเภทของเอฟเฟ็กต์แอนิเมชัน [`EffectChartMinorGroupingType`](/slides/python-net/th/aspose.slides.animation/effectchartminorgroupingtype) |
| index | **int** | ดัชนี **int** |
| effect_type | [`EffectType`](/slides/python-net/th/aspose.slides.animation/effecttype) | ประเภทของเอฟเฟ็กต์แอนิเมชัน [`EffectType`](/slides/python-net/th/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/th/aspose.slides.animation/effectsubtype) | ชนิดย่อยของเอฟเฟ็กต์แอนิเมชัน [`EffectSubtype`](/slides/python-net/th/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/th/aspose.slides.animation/effecttriggertype) | ประเภทการกระตุ้นของเอฟเฟ็กต์ [`EffectTriggerType`](/slides/python-net/th/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype}
เพิ่มเอฟเฟ็กต์แอนิเมชันใหม่สำหรับองค์ประกอบในหมวดหรือชุดข้อมูลไปที่ตำแหน่งสุดท้ายของลำดับ.

### Returns

New effect object [`IEffect`](/slides/python-net/th/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/th/aspose.slides.charts/ichart) | Chart วัตถุ [`IChart`](/slides/python-net/th/aspose.slides.charts/ichart) |
| type | [`EffectChartMinorGroupingType`](/slides/python-net/th/aspose.slides.animation/effectchartminorgroupingtype) | ประเภทของเอฟเฟ็กต์แอนิเมชัน [`EffectChartMinorGroupingType`](/slides/python-net/th/aspose.slides.animation/effectchartminorgroupingtype) |
| series_index | **int** | ดัชนีของชุดข้อมูลแผนภูมิ **int** |
| categories_index | **int** | ดัชนีของหมวด **int** |
| effect_type | [`EffectType`](/slides/python-net/th/aspose.slides.animation/effecttype) | ประเภทของเอฟเฟ็กต์แอนิเมชัน [`EffectType`](/slides/python-net/th/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/th/aspose.slides.animation/effectsubtype) | ชนิดย่อยของเอฟเฟ็กต์แอนิเมชัน [`EffectSubtype`](/slides/python-net/th/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/th/aspose.slides.animation/effecttriggertype) | ประเภทการกระตุ้นของเอฟเฟ็กต์ [`EffectTriggerType`](/slides/python-net/th/aspose.slides.animation/effecttriggertype) |



### ดูเพิ่มเติม
* enumeration [`EffectChartMajorGroupingType`](/slides/python-net/th/aspose.slides.animation/effectchartmajorgroupingtype)
* enumeration [`EffectChartMinorGroupingType`](/slides/python-net/th/aspose.slides.animation/effectchartminorgroupingtype)
* enumeration [`EffectSubtype`](/slides/python-net/th/aspose.slides.animation/effectsubtype)
* enumeration [`EffectTriggerType`](/slides/python-net/th/aspose.slides.animation/effecttriggertype)
* enumeration [`EffectType`](/slides/python-net/th/aspose.slides.animation/effecttype)
* คลาส [`IChart`](/slides/python-net/th/aspose.slides.charts/ichart)
* คลาส [`IEffect`](/slides/python-net/th/aspose.slides.animation/ieffect)
* คลาส [`IParagraph`](/slides/python-net/th/aspose.slides/iparagraph)
* คลาส [`IShape`](/slides/python-net/th/aspose.slides/ishape)
* คลาส [`Sequence`](/slides/python-net/th/aspose.slides.animation/sequence)
* โมดูล [`aspose.slides.animation`](/slides/python-net/th/aspose.slides.animation)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)
---
title: add_effect method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.animation/isequence/add_effect/
weight: 10
---
## add_effect(self, shape, effect_type, subtype, trigger_type) {#ishape-effecttype-effectsubtype-effecttriggertype}
เพิ่มเอฟเฟ็กต์ใหม่ที่ท้ายลำดับ

### Returns

วัตถุเอฟเฟ็กต์ใหม่ [`IEffect`](/slides/python-net/th/aspose.slides.animation/ieffect)



```python
def add_effect(self, shape, effect_type, subtype, trigger_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shape | [`IShape`](/slides/python-net/th/aspose.slides/ishape) | วัตถุ Shape [`IShape`](/slides/python-net/th/aspose.slides/ishape) สำหรับเพิ่มเอฟเฟ็กต์ |
| effect_type | [`EffectType`](/slides/python-net/th/aspose.slides.animation/effecttype) | ประเภทของเอฟเฟ็กต์แอนิเมชัน [`EffectType`](/slides/python-net/th/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/th/aspose.slides.animation/effectsubtype) | ชนิดย่อยของเอฟเฟ็กต์แอนิเมชัน [`EffectSubtype`](/slides/python-net/th/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/th/aspose.slides.animation/effecttriggertype) | ประเภทการกระตุ้นของเอฟเฟ็กต์ [`EffectTriggerType`](/slides/python-net/th/aspose.slides.animation/effecttriggertype) |


## add_effect(self, paragraph, effect_type, subtype, trigger_type) {#iparagraph-effecttype-effectsubtype-effecttriggertype}
เพิ่มเอฟเฟ็กต์แอนิเมชันใหม่สำหรับย่อหน้าที่ท้ายลำดับ

### Returns

วัตถุเอฟเฟ็กต์ใหม่ [`IEffect`](/slides/python-net/th/aspose.slides.animation/ieffect)



```python
def add_effect(self, paragraph, effect_type, subtype, trigger_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| paragraph | [`IParagraph`](/slides/python-net/th/aspose.slides/iparagraph) | วัตถุ Paragraph [`IParagraph`](/slides/python-net/th/aspose.slides/iparagraph) |
| effect_type | [`EffectType`](/slides/python-net/th/aspose.slides.animation/effecttype) | ประเภทของเอฟเฟ็กต์แอนิเมชัน [`EffectType`](/slides/python-net/th/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/th/aspose.slides.animation/effectsubtype) | ชนิดย่อยของเอฟเฟ็กต์แอนิเมชัน [`EffectSubtype`](/slides/python-net/th/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/th/aspose.slides.animation/effecttriggertype) | ประเภทการกระตุ้นของเอฟเฟ็กต์ [`EffectTriggerType`](/slides/python-net/th/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype}
เพิ่มเอฟเฟ็กต์แอนิเมชันชาร์ตใหม่สำหรับหมวดหมู่หรือซีรีส์ที่ท้ายลำดับ

### Returns

วัตถุเอฟเฟ็กต์ใหม่ [`IEffect`](/slides/python-net/th/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, index, effect_type, subtype, trigger_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/th/aspose.slides.charts/ichart) | วัตถุ Chart [`IChart`](/slides/python-net/th/aspose.slides.charts/ichart) |
| type | [`EffectChartMajorGroupingType`](/slides/python-net/th/aspose.slides.animation/effectchartmajorgroupingtype) | ประเภทของเอฟเฟ็กต์แอนิเมชัน [`EffectChartMinorGroupingType`](/slides/python-net/th/aspose.slides.animation/effectchartminorgroupingtype) |
| index | **int** | Index **int** |
| effect_type | [`EffectType`](/slides/python-net/th/aspose.slides.animation/effecttype) | ประเภทของเอฟเฟ็กต์แอนิเมชัน [`EffectType`](/slides/python-net/th/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/th/aspose.slides.animation/effectsubtype) | ชนิดย่อยของเอฟเฟ็กต์แอนิเมชัน [`EffectSubtype`](/slides/python-net/th/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/th/aspose.slides.animation/effecttriggertype) | ประเภทการกระตุ้นของเอฟเฟ็กต์ [`EffectTriggerType`](/slides/python-net/th/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype}
เพิ่มเอฟเฟ็กต์แอนิเมชันชาร์ตใหม่สำหรับองค์ประกอบในหมวดหมู่หรือซีรีส์ที่ท้ายลำดับ

### Returns

วัตถุเอฟเฟ็กต์ใหม่ [`IEffect`](/slides/python-net/th/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/th/aspose.slides.charts/ichart) | วัตถุ Chart [`IChart`](/slides/python-net/th/aspose.slides.charts/ichart) |
| type | [`EffectChartMinorGroupingType`](/slides/python-net/th/aspose.slides.animation/effectchartminorgroupingtype) | ประเภทของเอฟเฟ็กต์แอนิเมชัน [`EffectChartMinorGroupingType`](/slides/python-net/th/aspose.slides.animation/effectchartminorgroupingtype) |
| series_index | **int** | Index of chart series **int** |
| categories_index | **int** | Index of category **int** |
| effect_type | [`EffectType`](/slides/python-net/th/aspose.slides.animation/effecttype) | ประเภทของเอฟเฟ็กต์แอนิเมชัน [`EffectType`](/slides/python-net/th/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/th/aspose.slides.animation/effectsubtype) | ชนิดย่อยของเอฟเฟ็กต์แอนิเมชัน [`EffectSubtype`](/slides/python-net/th/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/th/aspose.slides.animation/effecttriggertype) | ประเภทการกระตุ้นของเอฟเฟ็กต์ [`EffectTriggerType`](/slides/python-net/th/aspose.slides.animation/effecttriggertype) |



### See Also
* enumeration [`EffectChartMajorGroupingType`](/slides/python-net/th/aspose.slides.animation/effectchartmajorgroupingtype)
* enumeration [`EffectChartMinorGroupingType`](/slides/python-net/th/aspose.slides.animation/effectchartminorgroupingtype)
* enumeration [`EffectSubtype`](/slides/python-net/th/aspose.slides.animation/effectsubtype)
* enumeration [`EffectTriggerType`](/slides/python-net/th/aspose.slides.animation/effecttriggertype)
* enumeration [`EffectType`](/slides/python-net/th/aspose.slides.animation/effecttype)
* class [`IChart`](/slides/python-net/th/aspose.slides.charts/ichart)
* class [`IEffect`](/slides/python-net/th/aspose.slides.animation/ieffect)
* class [`IParagraph`](/slides/python-net/th/aspose.slides/iparagraph)
* class [`ISequence`](/slides/python-net/th/aspose.slides.animation/isequence)
* class [`IShape`](/slides/python-net/th/aspose.slides/ishape)
* module [`aspose.slides.animation`](/slides/python-net/th/aspose.slides.animation)
* library [`Aspose.Slides`](/slides/python-net)
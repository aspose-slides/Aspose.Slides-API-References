---
title: AddEffect()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: เพิ่มเอฟเฟกต์ใหม่ไปยังส่วนท้ายของลำดับ.
type: docs
weight: 144
url: /th/aspose.slides.animation/isequence/addeffect/
---
## ISequence::AddEffect(System::SharedPtr\<IShape\>, EffectType, EffectSubtype, EffectTriggerType) เมธอด


เพิ่มเอฟเฟกต์ใหม่ไปยังส่วนท้ายของลำดับ

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<IShape> shape, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) วัตถุ [IShape](../../../aspose.slides/ishape/) สำหรับเพิ่มเอฟเฟกต์ |
| effectType | [EffectType](../../effecttype/) | ประเภทของเอฟเฟกต์แอนิเมชัน [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | ประเภทย่อยของเอฟเฟกต์แอนิเมชัน [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | ประเภทการกระตุ้นของเอฟเฟกต์ [EffectTriggerType](../../effecttriggertype/) |

### ค่าที่ส่งกลับ

วัตถุเอฟเฟกต์ใหม่ [IEffect](../../ieffect/)

## ISequence::AddEffect(System::SharedPtr\<IParagraph\>, EffectType, EffectSubtype, EffectTriggerType) เมธอด


เพิ่มเอฟเฟกต์แอนิเมชันใหม่สำหรับย่อหน้าไปยังส่วนท้ายของลำดับ

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<IParagraph> paragraph, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| paragraph | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../../aspose.slides/iparagraph/)\> | [Paragraph](../../../aspose.slides/paragraph/) วัตถุ [IParagraph](../../../aspose.slides/iparagraph/) |
| effectType | [EffectType](../../effecttype/) | ประเภทของเอฟเฟกต์แอนิเมชัน [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | ประเภทย่อยของเอฟเฟกต์แอนิเมชัน [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | ประเภทการกระตุ้นของเอฟเฟกต์ [EffectTriggerType](../../effecttriggertype/) |

### ค่าที่ส่งกลับ

วัตถุเอฟเฟกต์ใหม่ [IEffect](../../ieffect/)
## หมายเหตุ




```cpp
auto presentation = System::MakeObject<Presentation>(path + u"input.pptx");
// เลือกย่อหน้าเพื่อเพิ่มเอฟเฟกต์
auto autoShape = System::ExplicitCast<IAutoShape>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto paragraph = autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0);
// เพิ่มเอฟเฟกต์แอนิเมชัน Fly ให้กับย่อหน้าที่เลือก
auto effect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->AddEffect(
     paragraph, 
     Animation::EffectType::Fly, 
     Animation::EffectSubtype::Left, 
     Animation::EffectTriggerType::OnClick);
```

## ISequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMajorGroupingType, int32_t, EffectType, EffectSubtype, EffectTriggerType) เมธอด


เพิ่มเอฟเฟ็กต์แอนิเมชันใหม่ของแผนภูมิสำหรับหมวดหมู่หรือชุดข้อมูลไปยังส่วนท้ายของลำดับ

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMajorGroupingType type, int32_t index, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | วัตถุแผนภูมิ [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/) | ประเภทของเอฟเฟกต์แอนิเมชัน [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| index | **int32_t** | ดัชนี **int32_t** |
| effectType | [EffectType](../../effecttype/) | ประเภทของเอฟเฟกต์แอนิเมชัน [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | ประเภทย่อยของเอฟเฟกต์แอนิเมชัน [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | ประเภทการกระตุ้นของเอฟเฟกต์ [EffectTriggerType](../../effecttriggertype/) |

### ค่าที่ส่งกลับ

วัตถุเอฟเฟกต์ใหม่ [IEffect](../../ieffect/)

## ISequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMinorGroupingType, int32_t, int32_t, EffectType, EffectSubtype, EffectTriggerType) เมธอด


เพิ่มเอฟเฟ็กต์แอนิเมชันใหม่ของแผนภูมิสำหรับองค์ประกอบในหมวดหมู่หรือชุดข้อมูลไปยังส่วนท้ายของลำดับ

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMinorGroupingType type, int32_t seriesIndex, int32_t categoriesIndex, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | วัตถุแผนภูมิ [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) | ประเภทของเอฟเฟกต์แอนิเมชัน [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| seriesIndex | **int32_t** | ดัชนีของชุดข้อมูลแผนภูมิ **int32_t** |
| categoriesIndex | **int32_t** | ดัชนีของหมวดหมู่ **int32_t** |
| effectType | [EffectType](../../effecttype/) | ประเภทของเอฟเฟกต์แอนิเมชัน [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | ประเภทย่อยของเอฟเฟกต์แอนิเมชัน [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | ประเภทการกระตุ้นของเอฟเฟกต์ [EffectTriggerType](../../effecttriggertype/) |

### ค่าที่ส่งกลับ

วัตถุเอฟเฟกต์ใหม่ [IEffect](../../ieffect/)

## ดูเพิ่มเติม

* เอนัม [EffectType](../../effecttype/)
* เอนัม [EffectSubtype](../../effectsubtype/)
* เอนัม [EffectTriggerType](../../effecttriggertype/)
* เอนัม [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/)
* เอนัม [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/)
* ไทป์เดฟ [SharedPtr](../../../system/sharedptr/)
* คลาส [IEffect](../../ieffect/)
* คลาส [IShape](../../../aspose.slides/ishape/)
* คลาส [ISequence](../)
* คลาส [IParagraph](../../../aspose.slides/iparagraph/)
* คลาส [IChart](../../../aspose.slides.charts/ichart/)
* เนมสเปซ [Aspose::Slides::Animation](../../)
* ไลบรารี [Aspose.Slides](../../../)
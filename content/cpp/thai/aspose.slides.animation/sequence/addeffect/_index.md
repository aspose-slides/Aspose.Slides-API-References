---
title: AddEffect()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เพิ่มเอฟเฟกต์ใหม่ที่ส่วนท้ายของลำดับ.
type: docs
weight: 157
url: /th/aspose.slides.animation/sequence/addeffect/
---
## Sequence::AddEffect(System::SharedPtr\<IShape\>, EffectType, EffectSubtype, EffectTriggerType) method

เพิ่มเอฟเฟกต์ใหม่ที่ส่วนท้ายของลำดับ.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<IShape> shape, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) อ็อบเจ็กต์ [IShape](../../../aspose.slides/ishape/) สำหรับการเพิ่มเอฟเฟกต์ |
| effectType | [EffectType](../../effecttype/) | ประเภทของเอฟเฟกต์การเคลื่อนไหว [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | ประเภทย่อยของเอฟเฟกต์การเคลื่อนไหว [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | ประเภททริกเกอร์ของเอฟเฟกต์ [EffectTriggerType](../../effecttriggertype/) |

### ค่าที่ส่งคืน

อ็อบเจ็กต์เอฟเฟกต์ใหม่ [IEffect](../../ieffect/)

## Sequence::AddEffect(System::SharedPtr\<IParagraph\>, EffectType, EffectSubtype, EffectTriggerType) method

เพิ่มเอฟเฟกต์การเคลื่อนไหวใหม่สำหรับย่อหน้าที่ส่วนท้ายของลำดับ.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<IParagraph> paragraph, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| paragraph | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../../aspose.slides/iparagraph/)\> | [Paragraph](../../../aspose.slides/paragraph/) อ็อบเจ็กต์ [IParagraph](../../../aspose.slides/iparagraph/) |
| effectType | [EffectType](../../effecttype/) | ประเภทของเอฟเฟกต์การเคลื่อนไหว [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | ประเภทย่อยของเอฟเฟกต์การเคลื่อนไหว [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | ประเภททริกเกอร์ของเอฟเฟ็กต์ [EffectTriggerType](../../effecttriggertype/) |

### ค่าที่ส่งคืน

อ็อบเจ็กต์เอฟเฟกต์ใหม่ [IEffect](../../ieffect/)

## หมายเหตุ




```cpp
auto presentation = System::MakeObject<Presentation>(path + u"input.pptx");
// เลือกย่อหน้าสำหรับเพิ่มเอฟเฟกต์
auto autoShape = System::ExplicitCast<Aspose::Slides::IAutoShape>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto paragraph = autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0);
// เพิ่มเอฟเฟกต์การเคลื่อนไหว Fly ให้กับย่อหน้าที่เลือก
auto effect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->AddEffect(
     paragraph, 
     Aspose::Slides::Animation::EffectType::Fly, 
     Aspose::Slides::Animation::EffectSubtype::Left, 
     Aspose::Slides::Animation::EffectTriggerType::OnClick);
```

## Sequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMajorGroupingType, int32_t, EffectType, EffectSubtype, EffectTriggerType) method

เพิ่มเอฟเฟกต์การเคลื่อนไหวใหม่ของแผนภูมิสำหรับประเภทหรือซีรีส์ที่ส่วนท้ายของลำดับ.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMajorGroupingType type, int32_t index, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | อ็อบเจ็กต์แผนภูมิ [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/) | ประเภทของเอฟเฟกต์การเคลื่อนไหว [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| index | **int32_t** | ดัชนี **int32_t** |
| effectType | [EffectType](../../effecttype/) | ประเภทของเอฟเฟกต์การเคลื่อนไหว [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | ประเภทย่อยของเอฟเฟกต์การเคลื่อนไหว [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | ประเภททริกเกอร์ของเอฟเฟกต์ [EffectTriggerType](../../effecttriggertype/) |

### ค่าที่ส่งคืน

อ็อบเจ็กต์เอฟเฟกต์ใหม่ [IEffect](../../ieffect/)

## Sequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMinorGroupingType, int32_t, int32_t, EffectType, EffectSubtype, EffectTriggerType) method

เพิ่มเอฟเฟกต์การเคลื่อนไหวใหม่ของแผนภูมิสำหรับองค์ประกอบในประเภทหรือซีรีส์ที่ส่วนท้ายของลำดับ.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMinorGroupingType type, int32_t seriesIndex, int32_t categoriesIndex, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | อ็อบเจ็กต์แผนภูมิ [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) | ประเภทของเอฟเฟกต์การเคลื่อนไหว [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| seriesIndex | **int32_t** | ดัชนีของซีรีส์แผนภูมิ **int32_t** |
| categoriesIndex | **int32_t** | ดัชนีของประเภท **int32_t** |
| effectType | [EffectType](../../effecttype/) | ประเภทของเอฟเฟกต์การเคลื่อนไหว [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | ประเภทย่อยของเอฟเฟกต์การเคลื่อนไหว [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | ประเภททริกเกอร์ของเอฟเฟกต์ [EffectTriggerType](../../effecttriggertype/) |

### ค่าที่ส่งคืน

อ็อบเจ็กต์เอฟเฟกต์ใหม่ [IEffect](../../ieffect/)

## ดูเพิ่มเติม

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/)
* Enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IEffect](../../ieffect/)
* คลาส [IShape](../../../aspose.slides/ishape/)
* คลาส [Sequence](../)
* คลาส [IParagraph](../../../aspose.slides/iparagraph/)
* คลาส [IChart](../../../aspose.slides.charts/ichart/)
* เนมสเปส [Aspose::Slides::Animation](../../)
* ไลบรารี [Aspose.Slides](../../../)
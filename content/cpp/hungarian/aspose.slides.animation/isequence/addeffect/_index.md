---
title: AddEffect()
second_title: Aspose.Slides C++ API Referencia
description: Új hatás hozzáadása a sorozat végéhez.
type: docs
weight: 144
url: /hu/aspose.slides.animation/isequence/addeffect/
---
## ISequence::AddEffect(System::SharedPtr\<IShape\>, EffectType, EffectSubtype, EffectTriggerType) metódus

Új hatást ad a szekvencia végéhez.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<IShape> shape, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) objektum [IShape](../../../aspose.slides/ishape/) az effektus hozzáadásához |
| effectType | [EffectType](../../effecttype/) | Animációs effektus típusa [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Animációs effektus altípusai [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Effektus aktiválási típusa [EffectTriggerType](../../effecttriggertype/) |

### Return Value

Új effektus objektum [IEffect](../../ieffect/)

## ISequence::AddEffect(System::SharedPtr\<IParagraph\>, EffectType, EffectSubtype, EffectTriggerType) metódus

Új animációs hatást ad a bekezdéshez a szekvencia végén.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<IParagraph> paragraph, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| paragraph | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../../aspose.slides/iparagraph/)\> | [Paragraph](../../../aspose.slides/paragraph/) objektum [IParagraph](../../../aspose.slides/iparagraph/) |
| effectType | [EffectType](../../effecttype/) | Animációs effektus típusa [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Animációs effektus altípusai [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Effektus aktiválási típusa [EffectTriggerType](../../effecttriggertype/) |

### Return Value

Új effektus objektum [IEffect](../../ieffect/)

## Remarks

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"input.pptx");
// válassza ki a bekezdést a hatás hozzáadásához
auto autoShape = System::ExplicitCast<IAutoShape>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto paragraph = autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0);
// adjon Fly animációs hatást a kiválasztott bekezdéshez
auto effect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->AddEffect(
     paragraph, 
     Animation::EffectType::Fly, 
     Animation::EffectSubtype::Left, 
     Animation::EffectTriggerType::OnClick);
```

## ISequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMajorGroupingType, int32_t, EffectType, EffectSubtype, EffectTriggerType) metódus

Új diagram animációs hatást ad a kategória vagy sorozat számára a szekvencia végéhez.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMajorGroupingType type, int32_t index, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | Diagram objektum [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/) | Animációs effektus típusa [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| index | **int32_t** | Index **int32_t** |
| effectType | [EffectType](../../effecttype/) | Animációs effektus típusa [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Animációs effektus altípusai [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Effektus aktiválási típusa [EffectTriggerType](../../effecttriggertype/) |

### Return Value

Új effektus objektum [IEffect](../../ieffect/)

## ISequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMinorGroupingType, int32_t, int32_t, EffectType, EffectSubtype, EffectTriggerType) metódus

Új diagram animációs hatást ad a kategória vagy sorozat elemeihez a szekvencia végéhez.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMinorGroupingType type, int32_t seriesIndex, int32_t categoriesIndex, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | Diagram objektum [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) | Animációs effektus típusa [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| seriesIndex | **int32_t** | Diagram sorozat indexe **int32_t** |
| categoriesIndex | **int32_t** | Kategória indexe **int32_t** |
| effectType | [EffectType](../../effecttype/) | Animációs effektus típusa [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Animációs effektus altípusai [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Effektus aktiválási típusa [EffectTriggerType](../../effecttriggertype/) |

### Return Value

Új effektus objektum [IEffect](../../ieffect/)

## See Also

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/)
* Enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IEffect](../../ieffect/)
* Osztály [IShape](../../../aspose.slides/ishape/)
* Osztály [ISequence](../)
* Osztály [IParagraph](../../../aspose.slides/iparagraph/)
* Osztály [IChart](../../../aspose.slides.charts/ichart/)
* Névterület [Aspose::Slides::Animation](../../)
* Könyvtár [Aspose.Slides](../../../)
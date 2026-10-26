---
title: AddEffect()
second_title: Aspose.Slides C++ API Referencia
description: Új hatást ad a sorozat végéhez.
type: docs
weight: 157
url: /hu/aspose.slides.animation/sequence/addeffect/
---
## Sequence::AddEffect(System::SharedPtr\<IShape\>, EffectType, EffectSubtype, EffectTriggerType) metódus

Új hatást ad a sorozat végéhez.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<IShape> shape, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) objektum [IShape](../../../aspose.slides/ishape/) az effektus hozzáadásához |
| effectType | [EffectType](../../effecttype/) | Az animációs effektus típusa [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Az animációs effektus alkategóriái [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Az effektus aktiválási típusa [EffectTriggerType](../../effecttriggertype/) |

### Visszatérési érték

Új effektus objektum [IEffect](../../ieffect/)

## Sequence::AddEffect(System::SharedPtr\<IParagraph\>, EffectType, EffectSubtype, EffectTriggerType) metódus

Új animációs effektust ad a bekezdéshez a sorozat végén.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<IParagraph> paragraph, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| paragraph | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../../aspose.slides/iparagraph/)\> | [Paragraph](../../../aspose.slides/paragraph/) objektum [IParagraph](../../../aspose.slides/iparagraph/) |
| effectType | [EffectType](../../effecttype/) | Az animációs effektus típusa [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Az animációs effektus alkategóriái [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Az effektus aktiválási típusa [EffectTriggerType](../../effecttriggertype/) |

### Visszatérési érték

Új effektus objektum [IEffect](../../ieffect/)

## Megjegyzések

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"input.pptx");
// válassza ki a bekezdést a hatás hozzáadásához
auto autoShape = System::ExplicitCast<Aspose::Slides::IAutoShape>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto paragraph = autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0);
// adja hozzá a Fly animációs hatást a kiválasztott bekezdéshez
auto effect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->AddEffect(
     paragraph, 
     Aspose::Slides::Animation::EffectType::Fly, 
     Aspose::Slides::Animation::EffectSubtype::Left, 
     Aspose::Slides::Animation::EffectTriggerType::OnClick);
```

## Sequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMajorGroupingType, int32_t, EffectType, EffectSubtype, EffectTriggerType) metódus

Új diagram animációs effektust ad a kategóriához vagy sorozathoz a sorozat végén.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMajorGroupingType type, int32_t index, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | Diagram objektum [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/) | Az animációs effektus típusa [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| index | **int32_t** | Index **int32_t** |
| effectType | [EffectType](../../effecttype/) | Az animációs effektus típusa [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Az animációs effektus alkategóriái [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Az effektus aktiválási típusa [EffectTriggerType](../../effecttriggertype/) |

### Visszatérési érték

Új effektus objektum [IEffect](../../ieffect/)

## Sequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMinorGroupingType, int32_t, int32_t, EffectType, EffectSubtype, EffectTriggerType) metódus

Új diagram animációs effektust ad a kategória vagy sorozat elemeihez a sorozat végén.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMinorGroupingType type, int32_t seriesIndex, int32_t categoriesIndex, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | Diagram objektum [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) | Az animációs effektus típusa [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| seriesIndex | **int32_t** | A diagram sorozat indexe **int32_t** |
| categoriesIndex | **int32_t** | A kategória indexe **int32_t** |
| effectType | [EffectType](../../effecttype/) | Az animációs effektus típusa [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Az animációs effektus alkategóriái [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Az effektus aktiválási típusa [EffectTriggerType](../../effecttriggertype/) |

### Visszatérési érték

Új effektus objektum [IEffect](../../ieffect/)

## See Also

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/)
* Enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEffect](../../ieffect/)
* Class [IShape](../../../aspose.slides/ishape/)
* Class [Sequence](../)
* Class [IParagraph](../../../aspose.slides/iparagraph/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)
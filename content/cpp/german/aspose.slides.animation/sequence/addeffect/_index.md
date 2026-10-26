---
title: AddEffect()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt einen neuen Effekt am Ende der Sequenz hinzu.
type: docs
weight: 157
url: /de/aspose.slides.animation/sequence/addeffect/
---
## Sequence::AddEffect(System::SharedPtr\<IShape\>, EffectType, EffectSubtype, EffectTriggerType) Methode


Fügt einen neuen Effekt am Ende der Sequenz hinzu.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<IShape> shape, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) Objekt [IShape](../../../aspose.slides/ishape/) zum Hinzufügen eines Effekts |
| effectType | [EffectType](../../effecttype/) | Typ eines Animationseffekts [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Untertypen des Animationseffekts [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Auslösertyp des Effekts [EffectTriggerType](../../effecttriggertype/) |

### Rückgabewert

Neues Effektobjekt [IEffect](../../ieffect/)

## Sequence::AddEffect(System::SharedPtr\<IParagraph\>, EffectType, EffectSubtype, EffectTriggerType) Methode


Fügt einen neuen Animationseffekt für einen Absatz am Ende der Sequenz hinzu.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<IParagraph> paragraph, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| paragraph | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../../aspose.slides/iparagraph/)\> | [Paragraph](../../../aspose.slides/paragraph/) Objekt [IParagraph](../../../aspose.slides/iparagraph/) |
| effectType | [EffectType](../../effecttype/) | Typ eines Animationseffekts [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Untertypen des Animationseffekts [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Auslösertyp des Effekts [EffectTriggerType](../../effecttriggertype/) |

### Rückgabewert

Neues Effektobjekt [IEffect](../../ieffect/)
## Hinweise




```cpp
auto presentation = System::MakeObject<Presentation>(path + u"input.pptx");
// paragraph auswählen, um Effekt hinzuzufügen
auto autoShape = System::ExplicitCast<Aspose::Slides::IAutoShape>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto paragraph = autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0);
// Fly-Animationseffekt zum ausgewählten paragraph hinzufügen
auto effect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->AddEffect(
     paragraph, 
     Aspose::Slides::Animation::EffectType::Fly, 
     Aspose::Slides::Animation::EffectSubtype::Left, 
     Aspose::Slides::Animation::EffectTriggerType::OnClick);
```

## Sequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMajorGroupingType, int32_t, EffectType, EffectSubtype, EffectTriggerType) Methode


Fügt den neuen Diagramm-Animationseffekt für Kategorie oder Serie am Ende der Sequenz hinzu.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMajorGroupingType type, int32_t index, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | Diagrammobjekt [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/) | Typ eines Animationseffekts [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| index | **int32_t** | Index **int32_t** |
| effectType | [EffectType](../../effecttype/) | Typ eines Animationseffekts [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Untertypen des Animationseffekts [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Auslösertyp des Effekts [EffectTriggerType](../../effecttriggertype/) |

### Rückgabewert

Neues Effektobjekt [IEffect](../../ieffect/)

## Sequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMinorGroupingType, int32_t, int32_t, EffectType, EffectSubtype, EffectTriggerType) Methode


Fügt den neuen Diagramm-Animationseffekt für Elemente in einer Kategorie oder Serie am Ende der Sequenz hinzu.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMinorGroupingType type, int32_t seriesIndex, int32_t categoriesIndex, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | Diagrammobjekt [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) | Typ eines Animationseffekts [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| seriesIndex | **int32_t** | Index der Diagrammserie **int32_t** |
| categoriesIndex | **int32_t** | Index der Kategorie **int32_t** |
| effectType | [EffectType](../../effecttype/) | Typ eines Animationseffekts [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Untertypen des Animationseffekts [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Auslösertyp des Effekts [EffectTriggerType](../../effecttriggertype/) |

### Rückgabewert

Neues Effektobjekt [IEffect](../../ieffect/)

## Siehe auch

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
---
title: AddEffect()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt einen neuen Effekt am Ende der Sequenz hinzu.
type: docs
weight: 144
url: /de/aspose.slides.animation/isequence/addeffect/
---
## ISequence::AddEffect(System::SharedPtr\<IShape\>, EffectType, EffectSubtype, EffectTriggerType) Methode


Fügt einen neuen Effekt am Ende der Sequenz hinzu.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<IShape> shape, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) Objekt [IShape](../../../aspose.slides/ishape/) zum Hinzufügen eines Effekts |
| effectType | [EffectType](../../effecttype/) | Typ eines Animations-effekts [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Untertypen des Animations-effekts [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Auslösertyp des Effekts [EffectTriggerType](../../effecttriggertype/) |

### Return Value

Neues Effekt-Objekt [IEffect](../../ieffect/)

## ISequence::AddEffect(System::SharedPtr\<IParagraph\>, EffectType, EffectSubtype, EffectTriggerType) Methode


Fügt einen neuen Animations-effekt für den Absatz am Ende der Sequenz hinzu.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<IParagraph> paragraph, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| paragraph | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../../aspose.slides/iparagraph/)\> | [Paragraph](../../../aspose.slides/paragraph/) Objekt [IParagraph](../../../aspose.slides/iparagraph/) |
| effectType | [EffectType](../../effecttype/) | Typ eines Animations-effekts [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Untertypen des Animations-effekts [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Auslösertyp des Effekts [EffectTriggerType](../../effecttriggertype/) |

### Return Value

Neues Effekt-Objekt [IEffect](../../ieffect/)
## Anmerkungen




```cpp
auto presentation = System::MakeObject<Presentation>(path + u"input.pptx");
// Absatz auswählen, um Effekt hinzuzufügen
auto autoShape = System::ExplicitCast<IAutoShape>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto paragraph = autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0);
// Fly-Animationseffekt zum ausgewählten Absatz hinzufügen
auto effect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->AddEffect(
     paragraph, 
     Animation::EffectType::Fly, 
     Animation::EffectSubtype::Left, 
     Animation::EffectTriggerType::OnClick);
```

## ISequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMajorGroupingType, int32_t, EffectType, EffectSubtype, EffectTriggerType) Methode


Fügt den neuen Diagramm-Animations-effekt für Kategorie oder Serie am Ende der Sequenz hinzu.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMajorGroupingType type, int32_t index, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | Chart-Objekt [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/) | Typ eines Animations-effekts [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| index | **int32_t** | Index **int32_t** |
| effectType | [EffectType](../../effecttype/) | Typ eines Animations-effekts [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Untertypen des Animations-effekts [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Auslösertyp des Effekts [EffectTriggerType](../../effecttriggertype/) |

### Return Value

Neues Effekt-Objekt [IEffect](../../ieffect/)

## ISequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMinorGroupingType, int32_t, int32_t, EffectType, EffectSubtype, EffectTriggerType) Methode


Fügt den neuen Diagramm-Animations-effekt für Elemente in Kategorie oder Serie am Ende der Sequenz hinzu.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMinorGroupingType type, int32_t seriesIndex, int32_t categoriesIndex, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | Chart-Objekt [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) | Typ eines Animations-effekts [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| seriesIndex | **int32_t** | Index der Diagramm-Serie **int32_t** |
| categoriesIndex | **int32_t** | Index der Kategorie **int32_t** |
| effectType | [EffectType](../../effecttype/) | Typ eines Animations-effekts [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Untertypen des Animations-effekts [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Auslösertyp des Effekts [EffectTriggerType](../../effecttriggertype/) |

### Return Value

Neues Effekt-Objekt [IEffect](../../ieffect/)

## Siehe auch

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/)
* Enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IEffect](../../ieffect/)
* Klasse [IShape](../../../aspose.slides/ishape/)
* Klasse [ISequence](../)
* Klasse [IParagraph](../../../aspose.slides/iparagraph/)
* Klasse [IChart](../../../aspose.slides.charts/ichart/)
* Namensraum [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)
---
title: AddEffect()
second_title: Aspose.Slides pro C++ – reference API
description: Přidá nový efekt na konec sekvence.
type: docs
weight: 157
url: /cs/aspose.slides.animation/sequence/addeffect/
---
## Sequence::AddEffect(System::SharedPtr\<IShape\>, EffectType, EffectSubtype, EffectTriggerType) method

Přidejte nový efekt na konec sekvence.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<IShape> shape, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) objekt [IShape](../../../aspose.slides/ishape/) pro přidání efektu |
| effectType | [EffectType](../../effecttype/) | Typ animačního efektu [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Podtypy animačního efektu [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Typ spouštěče efektu [EffectTriggerType](../../effecttriggertype/) |

### Návratová hodnota

Nový objekt efektu [IEffect](../../ieffect/)

## Sequence::AddEffect(System::SharedPtr\<IParagraph\>, EffectType, EffectSubtype, EffectTriggerType) method

Přidejte nový animační efekt pro odstavec na konec sekvence.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<IParagraph> paragraph, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| paragraph | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../../aspose.slides/iparagraph/)\> | [Paragraph](../../../aspose.slides/paragraph/) objekt [IParagraph](../../../aspose.slides/iparagraph/) |
| effectType | [EffectType](../../effecttype/) | Typ animačního efektu [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Podtypy animačního efektu [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Typ spouštěče efektu [EffectTriggerType](../../effecttriggertype/) |

### Návratová hodnota

Nový objekt efektu [IEffect](../../ieffect/)
## Poznámky

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"input.pptx");
// vyberte odstavec pro přidání efektu
auto autoShape = System::ExplicitCast<Aspose::Slides::IAutoShape>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto paragraph = autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0);
// přidejte animační efekt Fly do vybraného odstavce
auto effect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->AddEffect(
     paragraph, 
     Aspose::Slides::Animation::EffectType::Fly, 
     Aspose::Slides::Animation::EffectSubtype::Left, 
     Aspose::Slides::Animation::EffectTriggerType::OnClick);
```

## Sequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMajorGroupingType, int32_t, EffectType, EffectSubtype, EffectTriggerType) method

Přidá nový animační efekt grafu pro kategorii nebo řadu na konec sekvence.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMajorGroupingType type, int32_t index, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | Objekt grafu [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/) | Typ animačního efektu [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| index | **int32_t** | Index **int32_t** |
| effectType | [EffectType](../../effecttype/) | Typ animačního efektu [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Podtypy animačního efektu [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Typ spouštěče efektu [EffectTriggerType](../../effecttriggertype/) |

### Návratová hodnota

Nový objekt efektu [IEffect](../../ieffect/)

## Sequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMinorGroupingType, int32_t, int32_t, EffectType, EffectSubtype, EffectTriggerType) method

Přidá nový animační efekt grafu pro prvky v kategorii nebo řadě na konec sekvence.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMinorGroupingType type, int32_t seriesIndex, int32_t categoriesIndex, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | Objekt grafu [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) | Typ animačního efektu [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| seriesIndex | **int32_t** | Index řady grafu **int32_t** |
| categoriesIndex | **int32_t** | Index kategorie **int32_t** |
| effectType | [EffectType](../../effecttype/) | Typ animačního efektu [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Podtypy animačního efektu [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Typ spouštěče efektu [EffectTriggerType](../../effecttriggertype/) |

### Návratová hodnota

Nový objekt efektu [IEffect](../../ieffect/)

## Viz také

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/)
* Enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IEffect](../../ieffect/)
* Třída [IShape](../../../aspose.slides/ishape/)
* Třída [Sequence](../)
* Třída [IParagraph](../../../aspose.slides/iparagraph/)
* Třída [IChart](../../../aspose.slides.charts/ichart/)
* Jmenný prostor [Aspose::Slides::Animation](../../)
* Knihovna [Aspose.Slides](../../../)
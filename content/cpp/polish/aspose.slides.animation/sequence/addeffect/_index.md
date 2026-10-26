---
title: AddEffect()
second_title: Aspose.Slides dla C++ - Referencja API
description: Dodaj nowy efekt na koniec sekwencji.
type: docs
weight: 157
url: /pl/aspose.slides.animation/sequence/addeffect/
---
## Sequence::AddEffect(System::SharedPtr\<IShape\>, EffectType, EffectSubtype, EffectTriggerType) metoda


Dodaj nowy efekt na koniec sekwencji.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<IShape> shape, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) obiekt [IShape](../../../aspose.slides/ishape/) do dodawania efektu |
| effectType | [EffectType](../../effecttype/) | Typ efektu animacji [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Podtypy efektu animacji [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Typ wyzwalania efektu [EffectTriggerType](../../effecttriggertype/) |

### Wartość zwracana

Nowy obiekt efektu [IEffect](../../ieffect/)

## Sequence::AddEffect(System::SharedPtr\<IParagraph\>, EffectType, EffectSubtype, EffectTriggerType) metoda


Dodaj nowy efekt animacji dla akapitu na koniec sekwencji.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<IParagraph> paragraph, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| paragraph | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../../aspose.slides/iparagraph/)\> | [Paragraph](../../../aspose.slides/paragraph/) obiekt [IParagraph](../../../aspose.slides/iparagraph/) |
| effectType | [EffectType](../../effecttype/) | Typ efektu animacji [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Podtypy efektu animacji [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Typ wyzwalania efektu [EffectTriggerType](../../effecttriggertype/) |

### Wartość zwracana

Nowy obiekt efektu [IEffect](../../ieffect/)
## Sequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMajorGroupingType, int32_t, EffectType, EffectSubtype, EffectTriggerType) metoda


Dodaje nowy efekt animacji wykresu dla kategorii lub serii na koniec sekwencji.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMajorGroupingType type, int32_t index, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | Obiekt wykresu [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/) | Typ efektu animacji [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| index | **int32_t** | Indeks **int32_t** |
| effectType | [EffectType](../../effecttype/) | Typ efektu animacji [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Podtypy efektu animacji [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Typ wyzwalania efektu [EffectTriggerType](../../effecttriggertype/) |

### Wartość zwracana

Nowy obiekt efektu [IEffect](../../ieffect/)

## Sequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMinorGroupingType, int32_t, int32_t, EffectType, EffectSubtype, EffectTriggerType) metoda


Dodaje nowy efekt animacji wykresu dla elementów w kategorii lub serii na koniec sekwencji.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMinorGroupingType type, int32_t seriesIndex, int32_t categoriesIndex, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | Obiekt wykresu [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) | Typ efektu animacji [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| seriesIndex | **int32_t** | Indeks serii wykresu **int32_t** |
| categoriesIndex | **int32_t** | Indeks kategorii **int32_t** |
| effectType | [EffectType](../../effecttype/) | Typ efektu animacji [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Podtypy efektu animacji [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Typ wyzwalania efektu [EffectTriggerType](../../effecttriggertype/) |

### Wartość zwracana

Nowy obiekt efektu [IEffect](../../ieffect/)

## Uwagi




```cpp
auto presentation = System::MakeObject<Presentation>(path + u"input.pptx");
// wybierz akapit, aby dodać efekt
auto autoShape = System::ExplicitCast<Aspose::Slides::IAutoShape>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto paragraph = autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0);
// dodaj efekt animacji Fly do wybranego akapitu
auto effect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->AddEffect(
     paragraph, 
     Aspose::Slides::Animation::EffectType::Fly, 
     Aspose::Slides::Animation::EffectSubtype::Left, 
     Aspose::Slides::Animation::EffectTriggerType::OnClick);
```

## Zobacz także

* Wyliczenie [EffectType](../../effecttype/)
* Wyliczenie [EffectSubtype](../../effectsubtype/)
* Wyliczenie [EffectTriggerType](../../effecttriggertype/)
* Wyliczenie [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/)
* Wyliczenie [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IEffect](../../ieffect/)
* Klasa [IShape](../../../aspose.slides/ishape/)
* Klasa [Sequence](../)
* Klasa [IParagraph](../../../aspose.slides/iparagraph/)
* Klasa [IChart](../../../aspose.slides.charts/ichart/)
* Przestrzeń nazw [Aspose::Slides::Animation](../../)
* Biblioteka [Aspose.Slides](../../../)
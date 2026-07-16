---
title: AddEffect()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute un nouvel effet à la fin de la séquence.
type: docs
weight: 144
url: /fr/aspose.slides.animation/isequence/addeffect/
---
## ISequence::AddEffect(System::SharedPtr\<IShape\>, EffectType, EffectSubtype, EffectTriggerType) method


Ajoute un nouvel effet à la fin de la séquence.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<IShape> shape, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```


### Paramètres

| Parameter | Type | Description |
| --- | --- | --- |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) objet [IShape](../../../aspose.slides/ishape/) pour ajouter un effet |
| effectType | [EffectType](../../effecttype/) | Type d'un effet d'animation [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Sous-types d'effet d'animation [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Type de déclenchement de l'effet [EffectTriggerType](../../effecttriggertype/) |

### Valeur de retour

Nouvel objet d'effet [IEffect](../../ieffect/)

## ISequence::AddEffect(System::SharedPtr\<IParagraph\>, EffectType, EffectSubtype, EffectTriggerType) method


Ajoute un nouvel effet d'animation pour le paragraphe à la fin de la séquence.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<IParagraph> paragraph, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```


### Paramètres

| Parameter | Type | Description |
| --- | --- | --- |
| paragraph | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../../aspose.slides/iparagraph/)\> | [Paragraph](../../../aspose.slides/paragraph/) objet [IParagraph](../../../aspose.slides/iparagraph/) |
| effectType | [EffectType](../../effecttype/) | Type d'un effet d'animation [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Sous-types d'effet d'animation [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Type de déclenchement de l'effet [EffectTriggerType](../../effecttriggertype/) |

### Valeur de retour

Nouvel objet d'effet [IEffect](../../ieffect/)
## Remarques




```cpp
auto presentation = System::MakeObject<Presentation>(path + u"input.pptx");
// sélectionner le paragraphe pour ajouter l'effet
auto autoShape = System::ExplicitCast<IAutoShape>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto paragraph = autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0);
// ajouter l'effet d'animation Fly au paragraphe sélectionné
auto effect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->AddEffect(
     paragraph, 
     Animation::EffectType::Fly, 
     Animation::EffectSubtype::Left, 
     Animation::EffectTriggerType::OnClick);
```

## ISequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMajorGroupingType, int32_t, EffectType, EffectSubtype, EffectTriggerType) method


Ajoute le nouvel effet d'animation de graphique pour une catégorie ou une série à la fin de la séquence.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMajorGroupingType type, int32_t index, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```


### Paramètres

| Parameter | Type | Description |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | Objet de graphique [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/) | Type d'un effet d'animation [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| index | **int32_t** | Index **int32_t** |
| effectType | [EffectType](../../effecttype/) | Type d'un effet d'animation [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Sous-types d'effet d'animation [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Type de déclenchement de l'effet [EffectTriggerType](../../effecttriggertype/) |

### Valeur de retour

Nouvel objet d'effet [IEffect](../../ieffect/)

## ISequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMinorGroupingType, int32_t, int32_t, EffectType, EffectSubtype, EffectTriggerType) method


Ajoute le nouvel effet d'animation de graphique pour les éléments d'une catégorie ou d'une série à la fin de la séquence.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMinorGroupingType type, int32_t seriesIndex, int32_t categoriesIndex, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```


### Paramètres

| Parameter | Type | Description |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | Objet de graphique [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) | Type d'un effet d'animation [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| seriesIndex | **int32_t** | Indice de la série du graphique **int32_t** |
| categoriesIndex | **int32_t** | Indice de la catégorie **int32_t** |
| effectType | [EffectType](../../effecttype/) | Type d'un effet d'animation [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Sous-types d'effet d'animation [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Type de déclenchement de l'effet [EffectTriggerType](../../effecttriggertype/) |

### Valeur de retour

Nouvel objet d'effet [IEffect](../../ieffect/)

## Voir aussi

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/)
* Enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEffect](../../ieffect/)
* Class [IShape](../../../aspose.slides/ishape/)
* Class [ISequence](../)
* Class [IParagraph](../../../aspose.slides/iparagraph/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)
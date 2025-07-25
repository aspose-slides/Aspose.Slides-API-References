---
title: AddEffect
second_title: Aspose.Slides pour .NET Référence API
description: Ajouter un nouvel effet à la fin de la séquence.
type: docs
weight: 50
url: /fr/aspose.slides.animation/isequence/addeffect/
---

## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

Ajouter un nouvel effet à la fin de la séquence.

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| shape | IShape | Objet de forme [`IShape`](../../../aspose.slides/ishape) pour ajouter un effet |
| effectType | EffectType | Type d'un effet d'animation [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Sous-types d'effet d'animation [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Type de déclencheur d'effet [`EffectTriggerType`](../../effecttriggertype) |

### Valeur de retour

Nouvel objet effet [`IEffect`](../../ieffect)

### Voir Aussi

* interface [IEffect](../../ieffect)
* interface [IShape](../../../aspose.slides/ishape)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* interface [ISequence](../../isequence)
* namespace [Aspose.Slides.Animation](../../isequence)
* assembly [Aspose.Slides](../../../)

---

## AddEffect(IParagraph, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_2}

Ajouter un nouvel effet d'animation pour le paragraphe à la fin de la séquence.

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| paragraph | IParagraph | Objet paragraphe [`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | EffectType | Type d'un effet d'animation [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Sous-types d'effet d'animation [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Type de déclencheur d'effet [`EffectTriggerType`](../../effecttriggertype) |

### Valeur de retour

Nouvel objet effet [`IEffect`](../../ieffect)

### Exemples

```csharp
[C#]
using(Presentation presentation = new Presentation(path + "input.pptx"))
{        
   // sélectionner le paragraphe pour ajouter un effet
   IAutoShape autoShape = (IAutoShape)presentation.Slides[0].Shapes[0];
   IParagraph paragraph = autoShape.TextFrame.Paragraphs[0];

   // ajouter un effet d'animation de vol au paragraphe sélectionné
   IEffect effect = presentation.Slides[0].Timeline.MainSequence.AddEffect(
   paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
}
```

### Voir Aussi

* interface [IEffect](../../ieffect)
* interface [IParagraph](../../../aspose.slides/iparagraph)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* interface [ISequence](../../isequence)
* namespace [Aspose.Slides.Animation](../../isequence)
* assembly [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect}

Ajoute le nouvel effet d'animation pour le graphique pour catégories ou séries à la fin de la séquence.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| chart | IChart | Objet graphique [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMajorGroupingType | Type d'un effet d'animation [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Int32 | Index Int32 |
| effectType | EffectType | Type d'un effet d'animation [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Sous-types d'effet d'animation [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Type de déclencheur d'effet [`EffectTriggerType`](../../effecttriggertype) |

### Valeur de retour

Nouvel objet effet [`IEffect`](../../ieffect)

### Voir Aussi

* interface [IEffect](../../ieffect)
* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* interface [ISequence](../../isequence)
* namespace [Aspose.Slides.Animation](../../isequence)
* assembly [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_1}

Ajoute le nouvel effet d'animation pour les éléments dans la catégorie ou série à la fin de la séquence.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| chart | IChart | Objet graphique [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMinorGroupingType | Type d'un effet d'animation [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Int32 | Index de la série de graphique Int32 |
| categoriesIndex | Int32 | Index de catégorie Int32 |
| effectType | EffectType | Type d'un effet d'animation [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Sous-types d'effet d'animation [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Type de déclencheur d'effet [`EffectTriggerType`](../../effecttriggertype) |

### Valeur de retour

Nouvel objet effet [`IEffect`](../../ieffect)

### Voir Aussi

* interface [IEffect](../../ieffect)
* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* interface [ISequence](../../isequence)
* namespace [Aspose.Slides.Animation](../../isequence)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
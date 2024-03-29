---
title: ISequence
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente la séquence collection deffets.
type: docs
weight: 490
url: /fr/aspose.slides.animation/isequence/
---
## ISequence interface

Représente la séquence (collection d'effets).

```csharp
public interface ISequence : IEnumerable<IEffect>
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AsIEnumerable](../../aspose.slides.animation/isequence/asienumerable) { get; } | Permet d'obtenir l'interface IEnumerable de base. Lecture seuleIEnumerable . |
| [Count](../../aspose.slides.animation/isequence/count) { get; } | Renvoie le nombre d'effets dans une séquence. Lecture seuleInt32 . |
| [Item](../../aspose.slides.animation/isequence/item) { get; } | Renvoie un effet à l'index spécifié. |
| [TriggerShape](../../aspose.slides.animation/isequence/triggershape) { get; set; } | Renvoie ou définit la cible de forme pour la séquence INTERACTIVE. Si la séquence n'est pas interactive, renvoie null. Lecture/écriture[`IShape`](../../aspose.slides/ishape) . |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddEffect](../../aspose.slides.animation/isequence/addeffect#addeffect_2)(IParagraph, EffectType, EffectSubtype, EffectTriggerType) | Ajouter un nouvel effet d'animation pour le paragraphe à la fin de la séquence. |
| [AddEffect](../../aspose.slides.animation/isequence/addeffect#addeffect_3)(IShape, EffectType, EffectSubtype, EffectTriggerType) | Ajouter un nouvel effet à la fin de la séquence. |
| [AddEffect](../../aspose.slides.animation/isequence/addeffect#addeffect)(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) | Ajoute le nouvel effet d'animation graphique pour la catégorie ou la série à la fin de la séquence. |
| [AddEffect](../../aspose.slides.animation/isequence/addeffect#addeffect_1)(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) | Ajoute le nouvel effet d'animation graphique pour les éléments de catégorie ou de série à la fin de la séquence. |
| [Clear](../../aspose.slides.animation/isequence/clear)() | Supprime tous les effets d'une collection. |
| [GetCount](../../aspose.slides.animation/isequence/getcount)(IShape) | Renvoie le nombre d'effets pour la forme spécifiée. |
| [GetEffectsByParagraph](../../aspose.slides.animation/isequence/geteffectsbyparagraph)(IParagraph) | Renvoie un tableau d'effets pour le paragraphe spécifié. |
| [GetEffectsByShape](../../aspose.slides.animation/isequence/geteffectsbyshape)(IShape) | Renvoie un tableau d'effets pour la forme spécifiée. |
| [Remove](../../aspose.slides.animation/isequence/remove)(IEffect) | Supprime l'effet spécifié d'une collection. |
| [RemoveAt](../../aspose.slides.animation/isequence/removeat)(int) | Supprime un effet d'une collection. |
| [RemoveByShape](../../aspose.slides.animation/isequence/removebyshape)(IShape) | Supprimer l'effet pour la forme spécifiée. |

### Voir également

* interface [IEffect](../ieffect)
* espace de noms [Aspose.Slides.Animation](../../aspose.slides.animation)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->

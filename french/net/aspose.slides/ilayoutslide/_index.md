---
title: ILayoutSlide
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente une diapositive de mise en page.
type: docs
weight: 5690
url: /fr/net/aspose.slides/ilayoutslide/
---
## ILayoutSlide interface

Représente une diapositive de mise en page.

```csharp
public interface ILayoutSlide : IBaseSlide, IOverrideThemeable
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AsIBaseSlide](../../aspose.slides/ilayoutslide/asibaseslide) { get; } | Permet d'obtenir l'interface IBaseSlide de base. Lecture seule[`IBaseSlide`](../ibaseslide) . |
| [AsIOverrideThemeable](../../aspose.slides/ilayoutslide/asioverridethemeable) { get; } | Renvoie l'interface IOverrideThemeable. Lecture seule[`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable) . |
| [HasDependingSlides](../../aspose.slides/ilayoutslide/hasdependingslides) { get; } | Renvoie vrai s'il existe au moins une diapositive qui dépend de cette diapositive de mise en page. Lecture seuleBoolean . |
| [HeaderFooterManager](../../aspose.slides/ilayoutslide/headerfootermanager) { get; } | Renvoie le gestionnaire HeaderFooter de la diapositive de mise en page. Lecture seule[`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager) . |
| [LayoutType](../../aspose.slides/ilayoutslide/layouttype) { get; } | Renvoie le type de mise en page de cette diapositive de mise en page. Lecture seule[`SlideLayoutType`](../slidelayouttype) . |
| [MasterSlide](../../aspose.slides/ilayoutslide/masterslide) { get; set; } | Renvoie ou définit la diapositive principale d'une mise en page. Lecture/écriture[`IMasterSlide`](../imasterslide) . |

## Méthodes

| Nom | La description |
| --- | --- |
| [GetDependingSlides](../../aspose.slides/ilayoutslide/getdependingslides)() | Renvoie un tableau avec toutes les diapositives, qui dépendent de cette diapositive de mise en page. |
| [Remove](../../aspose.slides/ilayoutslide/remove)() | Supprime la mise en page de la présentation. |

### Voir également

* interface [IBaseSlide](../ibaseslide)
* interface [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* espace de noms [Aspose.Slides](../../aspose.slides)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
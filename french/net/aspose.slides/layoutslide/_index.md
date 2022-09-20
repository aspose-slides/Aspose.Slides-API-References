---
title: LayoutSlide
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente une diapositive de mise en page.
type: docs
weight: 6970
url: /fr/net/aspose.slides/layoutslide/
---
## LayoutSlide class

Représente une diapositive de mise en page.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Renvoie l'arrière-plan de la diapositive. Lecture seule[`IBackground`](../ibackground) . |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Renvoie la collection de contrôles ActiveX sur une diapositive. Lecture seule[`IControlCollection`](../icontrolcollection) . |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Renvoie les données personnalisées de la diapositive. Lecture seule[`ICustomData`](../icustomdata) . |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | Renvoie vrai s'il existe au moins une diapositive qui dépend de cette diapositive de mise en page. Lecture seuleBoolean . |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | Renvoie le gestionnaire HeaderFooter de la diapositive de mise en page. Lecture seule[`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager) . |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Fournit un accès facile aux hyperliens contenus. Lecture seule[`IHyperlinkQueries`](../ihyperlinkqueries) . |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | Renvoie le type de mise en page de cette diapositive de mise en page. Lecture seule[`SlideLayoutType`](../slidelayouttype) . |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | Renvoie ou définit la diapositive principale d'une mise en page. Lecture/écriture[`IMasterSlide`](../imasterslide) . |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Renvoie ou définit le nom d'une diapositive. Lecture/écritureString . |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Renvoie l'interface IPresentation. Lecture seule[`IPresentation`](../ipresentation) . |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Renvoie les formes d'une diapositive. Lecture seule[`IShapeCollection`](../ishapecollection) . |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | Spécifie si les formes de la diapositive principale doivent être affichées sur les diapositives ou non. Lecture/écritureBoolean . |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Renvoie l'ID d'une diapositive. Lecture seuleUInt32 . |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Renvoie l'objet Transition qui contient des informations sur la façon dont la diapositive spécifiée avance pendant un diaporama. Lecture seule[`ISlideShowTransition`](../islideshowtransition) . |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | Renvoie le gestionnaire de thème prioritaire. Lecture seule[`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager) . |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Renvoie l'objet de la chronologie de l'animation. Lecture seule[`IAnimationTimeLine`](../ianimationtimeline) . |

## Méthodes

| Nom | La description |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Renvoie un thème efficace pour cette diapositive. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Détermine si les deux instances IBaseSlide sont égales. La valeur renvoyée est calculée en fonction de la structure et du contenu statique de la diapositive. Deux diapositives sont égales si toutes les formes, styles, textes, animations et autres paramètres. etc. sont égaux. La comparaison ne prend pas en compte les valeurs d'identifiant uniques, par exemple SlideId et le contenu dynamique, par exemple la valeur de la date actuelle dans Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Trouve la première occurrence d'une forme avec le texte alternatif spécifié. |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | Renvoie un tableau avec toutes les diapositives, qui dépendent de cette diapositive de mise en page. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Les jointures s'exécutent avec le même formatage dans tous les paragraphes, toutes les formes acceptables. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Les jointures s'exécutent avec le même formatage dans tous les paragraphes dans toutes les formes acceptables. |
| [Remove](../../aspose.slides/layoutslide/remove)() | Supprime la mise en page de la présentation. |

### Voir également

* class [BaseSlide](../baseslide)
* interface [ILayoutSlide](../ilayoutslide)
* espace de noms [Aspose.Slides](../../aspose.slides)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->

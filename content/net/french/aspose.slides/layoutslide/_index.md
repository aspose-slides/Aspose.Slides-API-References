---
title: LayoutSlide
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente une diapositive de mise en page.
type: docs
weight: 7400
url: /fr/aspose.slides/layoutslide/
---

## Classe LayoutSlide

Représente une diapositive de mise en page.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Renvoie l'arrière-plan de la diapositive. Lecture seule [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Renvoie la collection de contrôles ActiveX sur une diapositive. Lecture seule [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Renvoie les données personnalisées de la diapositive. Lecture seule [`ICustomData`](../icustomdata). |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | Renvoie vrai s'il existe au moins une diapositive qui dépend de cette diapositive de mise en page. Lecture seule Booléen. |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | Renvoie le gestionnaire d'en-tête et de pied de page de la diapositive de mise en page. Lecture seule [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Fournit un accès facile aux hyperliens contenus. Lecture seule [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | Renvoie le type de mise en page de cette diapositive de mise en page. Lecture seule [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | Renvoie ou définit la diapositive maître pour une mise en page. Lecture/écriture [`IMasterSlide`](../imasterslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Renvoie ou définit le nom d'une diapositive. Lecture/écriture Chaîne. |
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | Renvoie le gestionnaire de zone de texte de la diapositive de mise en page. Lecture seule [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Renvoie l'interface IPresentation. Lecture seule [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Renvoie les formes d'une diapositive. Lecture seule [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | Spécifie si les formes sur la diapositive maître doivent être affichées sur les diapositives ou non. Lecture/écriture Booléen. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Renvoie l'ID d'une diapositive. Lecture seule UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Renvoie l'objet Transition qui contient des informations sur la manière dont la diapositive spécifiée avance pendant un diaporama. Lecture seule [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | Renvoie le gestionnaire de thèmes de substitution. Lecture seule [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Renvoie l'objet de chronologie d'animation. Lecture seule [`IAnimationTimeLine`](../ianimationtimeline). |

## Méthodes

| Nom | Description |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Renvoie un thème efficace pour cette diapositive. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Détermine si les deux instances IBaseSlide sont égales. La valeur de retour est calculée en fonction de la structure de la diapositive et du contenu statique. Deux diapositives sont égales si toutes les formes, styles, textes, animations et autres paramètres, etc. sont égaux. La comparaison ne prend pas en compte les valeurs d'identifiants uniques, par exemple, SlideId et contenu dynamique, par exemple, la valeur de la date actuelle dans la zone de texte de date. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Trouve la première occurrence d'une forme avec le texte alternatif spécifié. |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | Renvoie un tableau contenant toutes les diapositives qui dépendent de cette diapositive de mise en page. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Joint les portions avec le même formatage dans tous les paragraphes de toutes les formes acceptables. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Joint les portions avec le même formatage dans tous les paragraphes de toutes les formes acceptables. |
| [Remove](../../aspose.slides/layoutslide/remove)() | Supprime la mise en page de la présentation. |

### Voir aussi

* classe [BaseSlide](../baseslide)
* interface [ILayoutSlide](../ilayoutslide)
* espace de noms [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->

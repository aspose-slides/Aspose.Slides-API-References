---
title: MasterSlide
second_title: Référence API Aspose.Slides pour .NET
description: Représente une diapositive maître dans une présentation.
type: docs
weight: 7780
url: /fr/aspose.slides/masterslide/
---

## MasterSlide class

Représente une diapositive maître dans une présentation.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Retourne l'arrière-plan de la diapositive. Lecture seule [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | Retourne le style d'un texte de corps. Lecture seule [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Retourne la collection de contrôles ActiveX sur une diapositive. Lecture seule [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Retourne les données personnalisées de la diapositive. Lecture seule [`ICustomData`](../icustomdata). |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | Retourne true s'il existe au moins une diapositive qui dépend de cette diapositive maître. Lecture seule Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | Retourne le gestionnaire d'en-têtes et de pieds de page de la diapositive maître. Lecture seule [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Fournit un accès facile aux hyperliens contenus. Lecture seule [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | Retourne la collection de diapositives de disposition enfant pour cette diapositive maître. Lecture seule [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | Retourne ou définit le nom d'une diapositive maître. Lecture/écriture String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | Retourne le style d'un autre texte. Lecture seule [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Retourne l'interface IPresentation. Lecture seule [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | Détermine si le maître correspondant est supprimé lorsque toutes les diapositives qui suivent ce maître sont supprimées. Remarque : Aspose.Slides ne supprimera jamais de maîtres inutilisés par lui-même, pour supprimer réellement les maîtres inutilisés, appelez [`RemoveUnused`](../masterslidecollection/removeunused) Lecture/écriture Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Retourne les formes d'une diapositive. Lecture seule [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | Spécifie si les formes sur la diapositive maître doivent être affichées sur les diapositives ou non. Pour la diapositive maître elle-même, cette propriété retourne toujours `false`. Lecture/écriture Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Retourne l'ID d'une diapositive. Lecture seule UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Retourne l'objet Transition qui contient des informations sur la façon dont la diapositive spécifiée avance pendant un diaporama. Lecture seule [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | Retourne le gestionnaire de thème. Lecture seule [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Retourne l'objet de chronologie d'animation. Lecture seule [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | Retourne le style d'un texte de titre. Lecture seule [`ITextStyle`](../itextstyle). |

## Méthodes

| Nom | Description |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | Crée une nouvelle diapositive maître basée sur la diapositive actuelle, en appliquant un thème externe à celle-ci et applique la diapositive maître créée à toutes les diapositives dépendantes. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Retourne un thème efficace pour cette diapositive. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Détermine si les deux instances IBaseSlide sont égales. La valeur retournée est calculée en fonction de la structure de la diapositive et du contenu statique. Deux diapositives sont égales si toutes les formes, styles, textes, animations et autres réglages, etc. sont égaux. La comparaison ne prend pas en compte les valeurs d'identifiant unique, par exemple SlideId et le contenu dynamique, par exemple la valeur de date actuelle dans le champ Date. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Trouve la première occurrence d'une forme avec le texte alternatif spécifié. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | Retourne un tableau contenant toutes les diapositives qui dépendent de cette diapositive maître. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Unifie les éléments de même formatage dans tous les paragraphes de toutes les formes acceptables. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Unifie les éléments de même formatage dans tous les paragraphes de toutes les formes acceptables. |

### Voir également

* class [BaseSlide](../baseslide)
* interface [IMasterSlide](../imasterslide)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
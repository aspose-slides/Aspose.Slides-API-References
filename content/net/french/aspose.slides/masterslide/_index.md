---
title: MasterSlide
second_title: Référence API Aspose.Slides pour .NET
description: Représente une diapositive maître dans une présentation.
type: docs
weight: 7780
url: /fr/aspose.slides/masterslide/
---

## Classe MasterSlide

Représente une diapositive maître dans une présentation.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Renvoie l'arrière-plan de la diapositive. Lecture seule [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | Renvoie le style d'un texte de corps. Lecture seule [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Renvoie la collection de contrôles ActiveX sur une diapositive. Lecture seule [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Renvoie les données personnalisées de la diapositive. Lecture seule [`ICustomData`](../icustomdata). |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | Renvoie vrai s'il existe au moins une diapositive qui dépend de cette diapositive maître. Lecture seule Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | Renvoie le gestionnaire d'en-tête et de pied de page de la diapositive maître. Lecture seule [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Fournit un accès facile aux hyperliens contenus. Lecture seule [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | Renvoie la collection de diapositives de mise en page enfant pour cette diapositive maître. Lecture seule [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | Renvoie ou définit le nom d'une diapositive maître. Lecture/écriture String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | Renvoie le style d'un autre texte. Lecture seule [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Renvoie l'interface IPresentation. Lecture seule [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | Détermine si le maître correspondant est supprimé lorsque toutes les diapositives qui suivent ce maître sont supprimées. Remarque : Aspose.Slides ne supprimera jamais aucun maître inutilisé par lui-même, pour supprimer réellement des maîtres inutilisés, appelez [`RemoveUnused`](../masterslidecollection/removeunused) Lecture/écriture Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Renvoie les formes d'une diapositive. Lecture seule [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | Spécifie si les formes sur la diapositive maître doivent être affichées sur les diapositives ou non. Pour la diapositive maître elle-même, cette propriété renvoie toujours `false`. Lecture/écriture Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Renvoie l'ID d'une diapositive. Lecture seule UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Renvoie l'objet Transition qui contient des informations sur la façon dont la diapositive spécifiée avance lors d'un diaporama. Lecture seule [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | Renvoie le gestionnaire de thèmes. Lecture seule [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Renvoie l'objet chronologie d'animation. Lecture seule [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | Renvoie le style d'un texte de titre. Lecture seule [`ITextStyle`](../itextstyle). |

## Méthodes

| Nom | Description |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | Crée une nouvelle diapositive maître basée sur la diapositive actuelle, appliquant un thème externe et applique la diapositive maître créée à toutes les diapositives dépendantes. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Renvoie un thème efficace pour cette diapositive. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Détermine si les deux instances IBaseSlide sont égales. La valeur de retour est calculée en fonction de la structure et du contenu statique de la diapositive. Deux diapositives sont égales si toutes les formes, styles, textes, animations et autres paramètres, etc. sont égaux. La comparaison ne prend pas en compte les valeurs d'identificateur unique, par exemple SlideId et le contenu dynamique, par exemple la valeur actuelle de la date dans un espace réservé de date. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Trouve la première occurrence d'une forme avec le texte alternatif spécifié. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | Renvoie un tableau contenant toutes les diapositives qui dépendent de cette diapositive maître. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Joint les portions ayant le même formatage dans tous les paragraphes de toutes les formes acceptables. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Joint les portions ayant le même formatage dans tous les paragraphes de toutes les formes acceptables. |

### Voir aussi

* classe [BaseSlide](../baseslide)
* interface [IMasterSlide](../imasterslide)
* espace de noms [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
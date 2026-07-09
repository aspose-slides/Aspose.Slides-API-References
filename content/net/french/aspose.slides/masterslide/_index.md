---
title: MasterSlide
second_title: Référence de l'API Aspose.Sildes pour .NET
description: Représente une diapositive maître dans une présentation.
type: docs
weight: 8030
url: /fr/aspose.slides/masterslide/
---
## MasterSlide classe

Représente une diapositive maître dans une présentation.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Renvoie l'arrière-plan de la diapositive. Lecture seule [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | Renvoie le style d'un texte de corps. Lecture seule [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Renvoie la collection de contrôles ActiveX sur une diapositive. Lecture seule [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Renvoie les données personnalisées de la diapositive. Lecture seule [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/masterslide/drawingguides) { get; } | Renvoie une collection de repères de dessin pour la diapositive maître. Lecture seule [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | Renvoie true s'il existe au moins une diapositive qui dépend de cette diapositive maître. Lecture seule Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | Renvoie le gestionnaire HeaderFooter de la diapositive maître. Lecture seule [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Fournit un accès facile aux hyperliens contenus. Lecture seule [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | Renvoie la collection des diapositives de disposition enfant pour cette diapositive maître. Lecture seule [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | Renvoie ou définit le nom d'une diapositive maître. Lecture/écriture String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | Renvoie le style d'un autre texte. Lecture seule [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Renvoie l'interface IPresentation. Lecture seule [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | Détermine si le maître correspondant est supprimé lorsque toutes les diapositives qui suivent ce maître sont supprimées. Remarque : Aspose.Slides ne supprimera jamais aucun maître inutilisé de lui-même ; pour réellement supprimer les maîtres inutilisés, appelez [`RemoveUnused`](../masterslidecollection/removeunused) Lecture/écriture Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Renvoie les formes d'une diapositive. Lecture seule [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | Spécifie si les formes sur la diapositive maître doivent être affichées sur les diapositives ou non. Pour la diapositive maître elle-même, cette propriété renvoie toujours `false`. Lecture/écriture Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Renvoie l'ID d'une diapositive. Lecture seule UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Renvoie l'objet Transition qui contient des informations sur la manière dont la diapositive spécifiée avance pendant le diaporama. Lecture seule [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | Renvoie le gestionnaire de thème. Lecture seule [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Renvoie l'objet de chronologie d’animation. Lecture seule [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | Renvoie le style d'un texte de titre. Lecture seule [`ITextStyle`](../itextstyle). |

## Méthodes

| Nom | Description |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | Crée une nouvelle diapositive maître basée sur celle actuelle, en appliquant un thème externe et applique la diapositive maître créée à toutes les diapositives dépendantes. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Renvoie un thème effectif pour cette diapositive. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Détermine si les deux instances IBaseSlide sont égales. La valeur retournée est calculée en fonction de la structure de la diapositive et du contenu statique. Deux diapositives sont égales si toutes les formes, styles, textes, animations et autres paramètres, etc. sont égaux. La comparaison ne prend pas en compte les valeurs d'identifiants uniques, par ex. SlideId, ni le contenu dynamique, par ex. la valeur de date actuelle dans le champ Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Trouve la première occurrence d'une forme avec le texte alternatif spécifié. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | Renvoie un tableau contenant toutes les diapositives qui dépendent de cette diapositive maître. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Fusionne les runs avec le même formatage dans tous les paragraphes de toutes les formes acceptables. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Fusionne les runs avec le même formatage dans tous les paragraphes de toutes les formes acceptables. |

### Voir aussi

* classe [BaseSlide](../baseslide)
* interface [IMasterSlide](../imasterslide)
* espace de noms [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
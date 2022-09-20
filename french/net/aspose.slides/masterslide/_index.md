---
title: MasterSlide
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente une diapositive principale dans une présentation.
type: docs
weight: 7350
url: /fr/net/aspose.slides/masterslide/
---
## MasterSlide class

Représente une diapositive principale dans une présentation.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Renvoie l'arrière-plan de la diapositive. Lecture seule[`IBackground`](../ibackground) . |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | Renvoie le style d'un corps de texte. Lecture seule[`ITextStyle`](../itextstyle) . |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Renvoie la collection de contrôles ActiveX sur une diapositive. Lecture seule[`IControlCollection`](../icontrolcollection) . |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Renvoie les données personnalisées de la diapositive. Lecture seule[`ICustomData`](../icustomdata) . |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | Renvoie vrai s'il existe au moins une diapositive qui dépend de cette diapositive principale. Lecture seuleBoolean . |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | Renvoie le gestionnaire HeaderFooter de la diapositive principale. Lecture seule[`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager) . |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Fournit un accès facile aux hyperliens contenus. Lecture seule[`IHyperlinkQueries`](../ihyperlinkqueries) . |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | Renvoie la collection de diapositives de mise en page enfant pour cette diapositive principale. En lecture seule[`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection) . |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | Renvoie ou définit le nom d'une diapositive principale. Lecture/écritureString . |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | Renvoie le style d'un autre texte. Lecture seule[`ITextStyle`](../itextstyle) . |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Renvoie l'interface IPresentation. Lecture seule[`IPresentation`](../ipresentation) . |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | Détermine si le masque correspondant est supprimé lorsque toutes les diapositives qui suivent ce masque sont supprimées. Remarque : Aspose.Slides ne supprimera jamais aucun masque inutilisé par lui-même, pour supprimer réellement les appels de masques inutilisés[`RemoveUnused`](../masterslidecollection/removeunused) Lecture/écritureBoolean . |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Renvoie les formes d'une diapositive. Lecture seule[`IShapeCollection`](../ishapecollection) . |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | Spécifie si les formes de la diapositive principale doivent être affichées sur les diapositives ou non. Pour la diapositive principale elle-même, cette propriété renvoie toujours`faux` . Lecture/écritureBoolean . |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Renvoie l'ID d'une diapositive. Lecture seuleUInt32 . |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Renvoie l'objet Transition qui contient des informations sur la façon dont la diapositive spécifiée avance pendant un diaporama. Lecture seule[`ISlideShowTransition`](../islideshowtransition) . |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | Renvoie le gestionnaire de thèmes. Lecture seule[`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager) . |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Renvoie l'objet de la chronologie de l'animation. Lecture seule[`IAnimationTimeLine`](../ianimationtimeline) . |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | Renvoie le style d'un texte de titre. Lecture seule[`ITextStyle`](../itextstyle) . |

## Méthodes

| Nom | La description |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | Crée une nouvelle diapositive principale basée sur la diapositive actuelle, en lui appliquant un thème externe et applique la diapositive principale créée à toutes les diapositives dépendantes. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Renvoie un thème efficace pour cette diapositive. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Détermine si les deux instances IBaseSlide sont égales. La valeur renvoyée est calculée en fonction de la structure et du contenu statique de la diapositive. Deux diapositives sont égales si toutes les formes, styles, textes, animations et autres paramètres. etc. sont égaux. La comparaison ne prend pas en compte les valeurs d'identifiant uniques, par exemple SlideId et le contenu dynamique, par exemple la valeur de la date actuelle dans Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Trouve la première occurrence d'une forme avec le texte alternatif spécifié. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | Renvoie un tableau avec toutes les diapositives, qui dépendent de cette diapositive principale. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Les jointures s'exécutent avec le même formatage dans tous les paragraphes, toutes les formes acceptables. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Les jointures s'exécutent avec le même formatage dans tous les paragraphes dans toutes les formes acceptables. |

### Voir également

* class [BaseSlide](../baseslide)
* interface [IMasterSlide](../imasterslide)
* espace de noms [Aspose.Slides](../../aspose.slides)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->

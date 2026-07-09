---
title: Slide
second_title: Référence de l'API Aspose.Sildes pour .NET
description: Représente une diapositive dans une présentation.
type: docs
weight: 9960
url: /fr/aspose.slides/slide/
---
## Slide classe

Represents a slide in a presentation.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Renvoie l'arrière-plan du diapositive. Lecture seule [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Renvoie la collection des contrôles ActiveX sur une diapositive. Lecture seule [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Renvoie les données personnalisées du diapositive. Lecture seule [`ICustomData`](../icustomdata). |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | Renvoie le gestionnaire HeaderFooter du diapositive. Lecture seule [`ISlideHeaderFooterManager`](../islideheaderfootermanager). |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | Détermine si la diapositive spécifiée est masquée pendant le diaporama. Lecture/écriture Boolean. |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Fournit un accès facile aux hyperliens contenus. Lecture seule [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | Renvoie ou définit la diapositive de mise en page pour la diapositive actuelle. Lecture/écriture [`ILayoutSlide`](../ilayoutslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Renvoie ou définit le nom d'une diapositive. Lecture/écriture String. |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | Permet d'accéder à la diapositive de notes, de l'ajouter et de la supprimer. Lecture seule [`INotesSlideManager`](../inotesslidemanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Renvoie l'interface IPresentation. Lecture seule [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Renvoie les formes d'une diapositive. Lecture seule [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | Spécifie si les formes sur la diapositive maître doivent être affichées sur les diapositives ou non. Lecture/écriture Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Renvoie l'ID d'une diapositive. Lecture seule UInt32. |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | Renvoie le numéro d'une diapositive. L'index de la diapositive dans la collection [`Slides`](../presentation/slides) est toujours égal à SlideNumber - Presentation.FirstSlideNumber. Lecture/écriture Int32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Renvoie l'objet Transition qui contient des informations sur la façon dont la diapositive spécifiée progresse pendant le diaporama. Lecture seule [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | Renvoie le gestionnaire de thème de substitution. Lecture seule [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Renvoie l'objet de chronologie d'animation. Lecture seule [`IAnimationTimeLine`](../ianimationtimeline). |

## Méthodes

| Nom | Description |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Renvoie un thème effectif pour cette diapositive. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Détermine si les deux instances IBaseSlide sont égales. La valeur retournée est calculée en fonction de la structure de la diapositive et du contenu statique. Deux diapositives sont égales si toutes les formes, styles, textes, animations et autres paramètres, etc., sont égaux. La comparaison ne prend pas en compte les valeurs d'identifiant uniques, par ex. SlideId, ni le contenu dynamique, par ex. la valeur de date actuelle dans le champ Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Trouve la première occurrence d'une forme avec le texte alternatif spécifié. |
| [GetImage](../../aspose.slides/slide/getimage#getimage)() | Renvoie un objet Image miniature (20 % de la taille réelle). |
| [GetImage](../../aspose.slides/slide/getimage#getimage_1)(IRenderingOptions) | Renvoie un objet Image miniature. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_4)(ITiffOptions) | Renvoie un objet image TIFF miniature avec les paramètres spécifiés. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_6)(Size) | Renvoie un objet Image miniature avec la taille spécifiée. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_5)(float, float) | Renvoie un objet Image miniature avec un redimensionnement personnalisé. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_3)(IRenderingOptions, Size) | Renvoie un objet Image miniature avec la taille spécifiée. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_2)(IRenderingOptions, float, float) | Renvoie un objet Image miniature avec un redimensionnement personnalisé. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | Renvoie tous les commentaires de diapositive ajoutés par un auteur spécifique. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | Fusionne les fragments de texte avec le même formatage dans tous les paragraphes de toutes les formes admissibles. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Fusionne les fragments de texte avec le même formatage dans tous les paragraphes de toutes les formes admissibles. |
| [Remove](../../aspose.slides/slide/remove)() | Supprime la diapositive de la présentation. |
| [Reset](../../aspose.slides/slide/reset)() | Réinitialise la position, la taille et le format de chaque forme qui possède un prototype sur LayoutSlide. |
| [WriteAsEmf](../../aspose.slides/slide/writeasemf)(Stream) | Enregistre le contenu de la diapositive sous forme de fichier EMF. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | Enregistre le contenu de la diapositive sous forme de fichier SVG. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Enregistre le contenu de la diapositive sous forme de fichier SVG. |

### Voir aussi

* classe [BaseSlide](../baseslide)
* interface [ISlide](../islide)
* espace de noms [Aspose.Slides](../../aspose.slides)
* assemblage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
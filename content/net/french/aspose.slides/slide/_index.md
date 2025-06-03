---
title: Slide
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente une diapositive dans une présentation.
type: docs
weight: 9650
url: /fr/aspose.slides/slide/
---

## Classe Slide

Représente une diapositive dans une présentation.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Retourne l'arrière-plan de la diapositive. Lecture seule [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Retourne la collection de contrôles ActiveX sur une diapositive. Lecture seule [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Retourne les données personnalisées de la diapositive. Lecture seule [`ICustomData`](../icustomdata). |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | Retourne le gestionnaire d'en-tête et de pied de page de la diapositive. Lecture seule [`ISlideHeaderFooterManager`](../islideheaderfootermanager). |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | Détermine si la diapositive spécifiée est cachée pendant un diaporama. Lecture/écriture Booléen. |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Fournit un accès facile aux hyperliens contenus. Lecture seule [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | Retourne ou définit la diapositive de mise en page pour la diapositive actuelle. Lecture/écriture [`ILayoutSlide`](../ilayoutslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Retourne ou définit le nom d'une diapositive. Lecture/écriture Chaîne. |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | Permet d'accéder à la diapositive des notes, de l'ajouter et de la supprimer. Lecture seule [`INotesSlideManager`](../inotesslidemanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Retourne l'interface IPresentation. Lecture seule [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Retourne les formes d'une diapositive. Lecture seule [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | Spécifie si les formes sur la diapositive maître doivent être affichées ou non sur les diapositives. Lecture/écriture Booléen. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Retourne l'ID d'une diapositive. Lecture seule UInt32. |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | Retourne un numéro de diapositive. L'index de la diapositive dans la collection [`Slides`](../presentation/slides) est toujours égal à SlideNumber - Presentation.FirstSlideNumber. Lecture/écriture Int32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Retourne l'objet Transition qui contient des informations sur la façon dont la diapositive spécifiée progresse pendant un diaporama. Lecture seule [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | Retourne le gestionnaire de thème de remplacement. Lecture seule [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Retourne l'objet de chronologie d'animation. Lecture seule [`IAnimationTimeLine`](../ianimationtimeline). |

## Méthodes

| Nom | Description |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Retourne un thème effectif pour cette diapositive. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Détermine si les deux instances de IBaseSlide sont égales. La valeur de retour est calculée en fonction de la structure de la diapositive et du contenu statique. Deux diapositives sont égales si toutes les formes, styles, textes, animations et autres paramètres, etc. sont égaux. La comparaison ne prend pas en compte les valeurs d'identificateur uniques, par exemple SlideId et le contenu dynamique, par exemple la valeur de date actuelle dans le placeholder de date. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Trouve la première occurrence d'une forme avec le texte alternatif spécifié. |
| [GetImage](../../aspose.slides/slide/getimage#getimage)() | Retourne un objet d'image miniature (20 % de la taille réelle). |
| [GetImage](../../aspose.slides/slide/getimage#getimage_1)(IRenderingOptions) | Retourne un objet d'image miniature. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_4)(ITiffOptions) | Retourne un objet d'image TIFF miniature avec les paramètres spécifiés. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_6)(Size) | Retourne un objet d'image miniature avec la taille spécifiée. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_5)(float, float) | Retourne un objet d'image miniature avec un redimensionnement personnalisé. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_3)(IRenderingOptions, Size) | Retourne un objet d'image miniature avec la taille spécifiée. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_2)(IRenderingOptions, float, float) | Retourne un objet d'image miniature avec un redimensionnement personnalisé. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | Retourne tous les commentaires de la diapositive ajoutés par l'auteur spécifique. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | Joint les séquences avec le même format dans tous les paragraphes dans toutes les formes acceptables. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Joint les séquences avec le même format dans tous les paragraphes dans toutes les formes acceptables. |
| [Remove](../../aspose.slides/slide/remove)() | Supprime la diapositive de la présentation. |
| [Reset](../../aspose.slides/slide/reset)() | Réinitialise la position, la taille et le format de chaque forme qui a un prototype sur la diapositive de mise en page. |
| [WriteAsEmf](../../aspose.slides/slide/writeasemf)(Stream) | Enregistre le contenu de la diapositive sous forme de fichier EMF. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | Enregistre le contenu de la diapositive sous forme de fichier SVG. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Enregistre le contenu de la diapositive sous forme de fichier SVG. |

### Voir Également

* classe [BaseSlide](../baseslide)
* interface [ISlide](../islide)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
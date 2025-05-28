---
title: Slide
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente une diapositive dans une présentation.
type: docs
weight: 9210
url: /fr/aspose.slides/slide/
---
## Slide class

Représente une diapositive dans une présentation.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Renvoie l'arrière-plan de la diapositive. Lecture seule[`IBackground`](../ibackground) . |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Renvoie la collection de contrôles ActiveX sur une diapositive. Lecture seule[`IControlCollection`](../icontrolcollection) . |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Renvoie les données personnalisées de la diapositive. Lecture seule[`ICustomData`](../icustomdata) . |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | Renvoie le gestionnaire HeaderFooter de la diapositive. Lecture seule[`ISlideHeaderFooterManager`](../islideheaderfootermanager) . |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | Détermine si la diapositive spécifiée est masquée pendant un diaporama. Lecture/écritureBoolean . |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Fournit un accès facile aux hyperliens contenus. Lecture seule[`IHyperlinkQueries`](../ihyperlinkqueries) . |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | Renvoie ou définit la diapositive de mise en page pour la diapositive actuelle. Lecture/écriture[`ILayoutSlide`](../ilayoutslide) . |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Renvoie ou définit le nom d'une diapositive. Lecture/écritureString . |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | Autoriser l'accès à la diapositive de notes, l'ajouter et la supprimer. Lecture seule[`INotesSlideManager`](../inotesslidemanager) . |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Renvoie l'interface IPresentation. Lecture seule[`IPresentation`](../ipresentation) . |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Renvoie les formes d'une diapositive. Lecture seule[`IShapeCollection`](../ishapecollection) . |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | Spécifie si les formes de la diapositive principale doivent être affichées sur les diapositives ou non. Lecture/écritureBoolean . |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Renvoie l'ID d'une diapositive. Lecture seuleUInt32 . |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | Renvoie un numéro de diapositive. Index de diapositive dans[`Slides`](../presentation/slides) collection est toujours égal à SlideNumber - Presentation.FirstSlideNumber. Lecture/écritureInt32 . |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Renvoie l'objet Transition qui contient des informations sur la façon dont la diapositive spécifiée avance pendant un diaporama. Lecture seule[`ISlideShowTransition`](../islideshowtransition) . |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | Renvoie le gestionnaire de thème prioritaire. Lecture seule[`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager) . |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Renvoie l'objet de la chronologie de l'animation. Lecture seule[`IAnimationTimeLine`](../ianimationtimeline) . |

## Méthodes

| Nom | La description |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Renvoie un thème efficace pour cette diapositive. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Détermine si les deux instances IBaseSlide sont égales. La valeur renvoyée est calculée en fonction de la structure et du contenu statique de la diapositive. Deux diapositives sont égales si toutes les formes, styles, textes, animations et autres paramètres. etc. sont égaux. La comparaison ne prend pas en compte les valeurs d'identifiant uniques, par exemple SlideId et le contenu dynamique, par exemple la valeur de la date actuelle dans Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Trouve la première occurrence d'une forme avec le texte alternatif spécifié. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | Renvoie tous les commentaires de diapositive ajoutés par un auteur spécifique. |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail)() | Renvoie un objet Thumbnail Image (20 % de la taille réelle). |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail_4)(IRenderingOptions) | Renvoie un objet Thumbnail Bitmap. |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail_7)(ITiffOptions) | Renvoie un objet bitmap Thumbnail tiff avec les paramètres spécifiés. |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail_9)(Size) | Renvoie un objet Thumbnail Bitmap avec la taille spécifiée. |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail_8)(float, float) | Renvoie un objet Thumbnail Bitmap avec une mise à l'échelle personnalisée. |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail_6)(IRenderingOptions, Size) | Renvoie un objet Thumbnail Bitmap avec la taille spécifiée. |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail_5)(IRenderingOptions, float, float) | Renvoie un objet Thumbnail Bitmap avec une mise à l'échelle personnalisée. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | Les jointures s'exécutent avec le même formatage dans tous les paragraphes dans toutes les formes acceptables. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Les jointures s'exécutent avec le même formatage dans tous les paragraphes dans toutes les formes acceptables. |
| [Remove](../../aspose.slides/slide/remove)() | Supprime la diapositive de la présentation. |
| [RenderToGraphics](../../aspose.slides/slide/rendertographics#rendertographics_3)(IRenderingOptions, Graphics) | Rend certaines diapositives dans un objet Graphics. |
| [RenderToGraphics](../../aspose.slides/slide/rendertographics#rendertographics_5)(IRenderingOptions, Graphics, Size) | Rend certaines diapositives en un objet Graphics en utilisant la taille spécifiée. |
| [RenderToGraphics](../../aspose.slides/slide/rendertographics#rendertographics_4)(IRenderingOptions, Graphics, float, float) | Rend certaines diapositives en un objet Graphics avec une mise à l'échelle personnalisée. |
| [Reset](../../aspose.slides/slide/reset)() | Réinitialise la position, la taille et la mise en forme de chaque forme ayant un prototype sur LayoutSlide. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | Enregistre le contenu de la diapositive en tant que fichier SVG. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Enregistre le contenu de la diapositive en tant que fichier SVG. |

### Voir également

* class [BaseSlide](../baseslide)
* interface [ISlide](../islide)
* espace de noms [Aspose.Slides](../../aspose.slides)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->

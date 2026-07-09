---
title: ISlide
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une diapositive dans une présentation.
type: docs
url: /fr/com.aspose.slides/islide/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ISlide extends IBaseSlide, IOverrideThemeable
```

Représente une diapositive dans une présentation.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Renvoie le gestionnaire HeaderFooter de la diapositive. |
| [getSlideNumber()](#getSlideNumber--) | Renvoie le numéro de la diapositive. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Renvoie le numéro de la diapositive. |
| [getHidden()](#getHidden--) | Détermine si la diapositive spécifiée est masquée pendant le diaporama. |
| [setHidden(boolean value)](#setHidden-boolean-) | Détermine si la diapositive spécifiée est masquée pendant le diaporama. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Renvoie un objet image avec un redimensionnement personnalisé. |
| [getImage()](#getImage--) | Renvoie un objet Image miniature (20 % de la taille réelle). |
| [getImage(Size imageSize)](#getImage-com.aspose.slides.android.Size-) | Renvoie un objet image avec la taille spécifiée. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Renvoie un objet bitmap tiff miniature avec des paramètres spécifiés. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Renvoie un objet Bitmap miniature. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Renvoie un objet Bitmap miniature avec un redimensionnement personnalisé. |
| [getImage(IRenderingOptions options, Size imageSize)](#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Renvoie un objet Bitmap miniature avec la taille spécifiée. |
| [getLayoutSlide()](#getLayoutSlide--) | Renvoie ou définit la diapositive de mise en page pour la diapositive actuelle. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Renvoie ou définit la diapositive de mise en page pour la diapositive actuelle. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Permet d’accéder à la diapositive de notes, de l’ajouter et de la supprimer. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Renvoie tous les commentaires de diapositive ajoutés par un auteur spécifique. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Enregistre le contenu de la diapositive sous forme de fichier SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Enregistre le contenu de la diapositive sous forme de fichier SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Enregistre le contenu de la diapositive sous forme de fichier EMF. |
| [remove()](#remove--) | Supprime la diapositive de la présentation. |
| [reset()](#reset--) | Réinitialise la position, la taille et le formatage de chaque forme qui possède un prototype sur LayoutSlide. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ISSlideHeaderFooterManager getHeaderFooterManager()
```

Renvoie le gestionnaire HeaderFooter de la diapositive. Lecture seule [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Renvoie :**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)
### getSlideNumber() {#getSlideNumber--}
```
public abstract int getSlideNumber()
```

Renvoie le numéro de la diapositive. L'index de la diapositive dans la collection [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) est toujours égal à SlideNumber - 1. Lecture/écriture int.

**Renvoie :**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public abstract void setSlideNumber(int value)
```

Renvoie le numéro de la diapositive. L'index de la diapositive dans la collection [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) est toujours égal à SlideNumber - 1. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

Détermine si la diapositive spécifiée est masquée pendant le diaporama. Lecture/écriture booléen.

**Renvoie :**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

Détermine si la diapositive spécifiée est masquée pendant le diaporama. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```

Renvoie un objet image avec un redimensionnement personnalisé.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| scaleX | float | Valeur permettant de mettre à l'échelle cette miniature selon l'axe x. |
| scaleY | float | Valeur permettant de mettre à l'échelle cette miniature selon l'axe y. |

**Renvoie :**
[IImage](../../com.aspose.slides/iimage) - Image object android.graphics.Bitmap
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Renvoie un objet Image miniature (20 % de la taille réelle).

**Renvoie :**
[IImage](../../com.aspose.slides/iimage) - Image object android.graphics.Bitmap
### getImage(Size imageSize) {#getImage-com.aspose.slides.android.Size-}
```
public abstract IImage getImage(Size imageSize)
```

Renvoie un objet image avec la taille spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| imageSize | [Size](../../com.aspose.slides.android/size) | Taille de l'image à créer. |

**Renvoie :**
[IImage](../../com.aspose.slides/iimage) - Bitmap object.
### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public abstract IImage getImage(ITiffOptions options)
```

Renvoie un objet bitmap tiff miniature avec des paramètres spécifiés.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Options Tiff. |

**Renvoie :**
[IImage](../../com.aspose.slides/iimage) - Image object.
### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage getImage(IRenderingOptions options)
```

Renvoie un objet Bitmap miniature.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Options de rendu. |

**Renvoie :**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

Renvoie un objet Bitmap miniature avec un redimensionnement personnalisé.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Options de rendu. |
| scaleX | float | Valeur permettant de mettre à l'échelle cette miniature selon l'axe x. |
| scaleY | float | Valeur permettant de mettre à l'échelle cette miniature selon l'axe y. |

**Renvoie :**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getImage(IRenderingOptions options, Size imageSize) {#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage getImage(IRenderingOptions options, Size imageSize)
```

Renvoie un objet Bitmap miniature avec la taille spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Options de rendu. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Taille de l'image à créer. |

**Renvoie :**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getLayoutSlide() {#getLayoutSlide--}
```
public abstract ILayoutSlide getLayoutSlide()
```

Renvoie ou définit la diapositive de mise en page pour la diapositive actuelle. Lecture/écriture [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Renvoie :**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public abstract void setLayoutSlide(ILayoutSlide value)
```

Renvoie ou définit la diapositive de mise en page pour la diapositive actuelle. Lecture/écriture [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |
### getNotesSlideManager() {#getNotesSlideManager--}
```
public abstract INotesSlideManager getNotesSlideManager()
```

Permet d’accéder à la diapositive de notes, de l’ajouter et de la supprimer. Lecture seule [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Renvoie :**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public abstract IComment[] getSlideComments(ICommentAuthor author)
```

Renvoie tous les commentaires de diapositive ajoutés par un auteur spécifique.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Auteur des commentaires à rechercher ou null pour retourner tous les commentaires. |

**Renvoie :**
com.aspose.slides.IComment[] - Array of [IComment](../../com.aspose.slides/icomment).
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

Enregistre le contenu de la diapositive sous forme de fichier SVG.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Flux cible |
### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Enregistre le contenu de la diapositive sous forme de fichier SVG.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Flux cible |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Options de génération SVG |
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```

Enregistre le contenu de la diapositive sous forme de fichier EMF.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Flux cible |
### remove() {#remove--}
```
public abstract void remove()
```

Supprime la diapositive de la présentation.
### reset() {#reset--}
```
public abstract void reset()
```

Réinitialise la position, la taille et le formatage de chaque forme qui possède un prototype sur LayoutSlide.
---
title: Slide
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente une diapositive dans une présentation.
type: docs
url: /fr/com.aspose.slides/slide/
---
**Héritage:**  
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Toutes les interfaces implémentées :**  
[com.aspose.slides.ISlide](../../com.aspose.slides/islide)  
```
public final class Slide extends BaseSlide implements ISlide
```

Représente une diapositive dans une présentation.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Renvoie le gestionnaire HeaderFooter de la diapositive. |
| [getThemeManager()](#getThemeManager--) | Renvoie le gestionnaire de thème de remplacement. |
| [getSlideNumber()](#getSlideNumber--) | Renvoie le numéro de la diapositive. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Renvoie le numéro de la diapositive. |
| [getHidden()](#getHidden--) | Détermine si la diapositive spécifiée est masquée pendant le diaporama. |
| [setHidden(boolean value)](#setHidden-boolean-) | Détermine si la diapositive spécifiée est masquée pendant le diaporama. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Spécifie si les formes de la diapositive maître doivent être affichées sur les diapositives ou non. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Spécifie si les formes de la diapositive maître doivent être affichées sur les diapositives ou non. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Renvoie un objet Image miniature avec une mise à l'échelle personnalisée. |
| [getImage()](#getImage--) | Renvoie un objet Image miniature (20 % de la taille réelle). |
| [getImage(Dimension imageSize)](#getImage-java.awt.Dimension-) | Renvoie un objet Image miniature avec la taille spécifiée. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Renvoie un objet image tiff miniature avec les paramètres spécifiés. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Renvoie un objet Image miniature. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Renvoie un objet Image miniature avec une mise à l'échelle personnalisée. |
| [getImage(IRenderingOptions options, Dimension imageSize)](#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Renvoie un objet Image miniature avec la taille spécifiée. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Enregistre le contenu de la diapositive en tant que fichier SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Enregistre le contenu de la diapositive en tant que fichier SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Enregistre le contenu de la diapositive en tant que fichier EMF. |
| [remove()](#remove--) | Supprime la diapositive de la présentation. |
| [getLayoutSlide()](#getLayoutSlide--) | Renvoie ou définit la diapositive de mise en page pour la diapositive actuelle. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Renvoie ou définit la diapositive de mise en page pour la diapositive actuelle. |
| [reset()](#reset--) | Réinitialise la position, la taille et le formatage de chaque forme qui a un prototype sur LayoutSlide. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Permet d'accéder à la diapositive de notes, de l'ajouter et de la supprimer. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Renvoie tous les commentaires de diapositive ajoutés par un auteur spécifique. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Fusionne les portions avec le même formatage dans tous les paragraphes de toutes les formes acceptables. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ISlideHeaderFooterManager getHeaderFooterManager()
```

Renvoie le gestionnaire HeaderFooter de la diapositive. Lecture seule [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Renvoie :**  
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Renvoie le gestionnaire de thème de remplacement. Lecture seule [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Renvoie :**  
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)

### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```

Renvoie le numéro de la diapositive. L'index de la diapositive dans la collection [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) est toujours égal à SlideNumber - Presentation.FirstSlideNumber. Lecture/écriture int.

**Renvoie :**  
int

### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```

Renvoie le numéro de la diapositive. L'index de la diapositive dans la collection [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) est toujours égal à SlideNumber - Presentation.FirstSlideNumber. Lecture/écriture int.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

Détermine si la diapositive spécifiée est masquée pendant le diaporama. Lecture/écriture boolean.

**Renvoie :**  
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

Détermine si la diapositive spécifiée est masquée pendant le diaporama. Lecture/écriture boolean.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Spécifie si les formes de la diapositive maître doivent être affichées sur les diapositives ou non. Lecture/écriture boolean.

**Renvoie :**  
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Spécifie si les formes de la diapositive maître doivent être affichées sur les diapositives ou non. Lecture/écriture boolean.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```

Renvoie un objet Image miniature avec une mise à l'échelle personnalisée.

--------------------

> ```
> The following example shows how to generate thumbnails from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("ThumbnailFromSlide.pptx");
>  try {
>      // Accéder à la première diapositive
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Créer une image à pleine échelle
>      IImage bmp = sld.getImage(1f, 1f);
>      // Enregistrer l'image sur le disque au format JPEG
>      bmp.save("Thumbnail_out.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to converting slides to bitmap and saving the images in PNG.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Convertit la première diapositive de la présentation en objet Bitmap
>      IImage bmp = pres.getSlides().get_Item(0).getImage();
>      // Enregistre l'image au format PNG
>      bmp.save("Slide_0.png", ImageFormat.Png);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint PPT/PPTX to JPG.
>  
>  Presentation pres = new Presentation("PowerPoint-Presentation.ppt");
>  try {
>      for (ISlide sld : pres.getSlides())
>      {
>          // Créer une image à pleine échelle
>          IImage bmp = sld.getImage(1f, 1f);
>          // Enregistrer l'image sur le disque au format JPEG
>          bmp.save("Slide_"+sld.getSlideNumber()+"0.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint PPT/PPTX to JPG with customized dimensions.
>  
>  Presentation pres = new Presentation("PowerPoint-Presentation.pptx");
>  try {
>      // Définir les dimensions
>      int desiredX = 1200;
>      int desiredY = 800;
>      // Obtenir les valeurs mises à l'échelle de X et Y
>      float ScaleX = (float)(1.0 / pres.getSlideSize().getSize().getWidth()) * desiredX;
>      float ScaleY = (float)(1.0 / pres.getSlideSize().getSize().getHeight()) * desiredY;
>      for (ISlide sld : pres.getSlides())
>      {
>          // Créer une image à pleine échelle
>          IImage bmp = sld.getImage(ScaleX, ScaleY);
>          // Enregistrer l'image sur le disque au format JPEG
>          bmp.save("Slide.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
> ```


**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| scaleX | float | La valeur par laquelle mettre à l'échelle cette miniature selon l'axe x. |
| scaleY | float | La valeur par laquelle mettre à l'échelle cette miniature selon l'axe y. |

**Renvoie :**  
[IImage](../../com.aspose.slides/iimage) - IImage object.

### getImage() {#getImage--}
```
public final IImage getImage()
```

Renvoie un objet Image miniature (20 % de la taille réelle).

**Renvoie :**  
[IImage](../../com.aspose.slides/iimage)

### getImage(Dimension imageSize) {#getImage-java.awt.Dimension-}
```
public final IImage getImage(Dimension imageSize)
```

Renvoie un objet Image miniature avec la taille spécifiée.

--------------------

> ```
> The following example shows how to converting slides to images with custom sizes using C#.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Convertit la première diapositive de la présentation en Bitmap avec la taille spécifiée
>      IImage bmp = pres.getSlides().get_Item(0).getImage(new Dimension(1820, 1040));
>      // Enregistre l'image au format JPEG
>      bmp.save("Slide_0.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
> ```

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| imageSize | java.awt.Dimension | Taille de l'image à créer. |

**Renvoie :**  
[IImage](../../com.aspose.slides/iimage) - Image object.

### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public final IImage getImage(ITiffOptions options)
```

Renvoie un objet image tiff miniature avec les paramètres spécifiés.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Options Tiff. |

**Renvoie :**  
[IImage](../../com.aspose.slides/iimage) - Image object.

### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public final IImage getImage(IRenderingOptions options)
```

Renvoie un objet Image miniature.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Options de rendu. |

**Renvoie :**  
[IImage](../../com.aspose.slides/iimage) - Image object.

### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

Renvoie un objet Image miniature avec une mise à l'échelle personnalisée.

--------------------

> ```
> The following example shows how to converting slides With notes and comments to Images.
>  
>  Presentation pres = new Presentation("PresentationNotesComments.pptx");
>  try {
>      // Créer les options de rendu
>      IRenderingOptions options = new RenderingOptions();
>      // Créer les options de mise en page des notes et des commentaires
>      NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
>      // Définit la position des notes sur la page
>      notesCommentsLayouting.setNotesPosition(NotesPositions.BottomTruncated);
>      // Définit la position des commentaires sur la page
>      notesCommentsLayouting.setCommentsPosition(CommentsPositions.Right);
>      // Définit la largeur de la zone de sortie des commentaires
>      notesCommentsLayouting.setCommentsAreaWidth(500);
>      // Définit la couleur de la zone des commentaires
>      notesCommentsLayouting.setCommentsAreaColor(Color.WHITE);
>      // Définir les options de mise en page pour le rendu
>      options.setSlidesLayoutOptions(notesCommentsLayouting);
>      // Convertit la première diapositive de la présentation en objet BufferedImage
>      IImage image = pres.getSlides().get_Item(0).getImage(options, 2f, 2f);
>      // Enregistre l'image au format GIF
>      image.save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Options de rendu. |
| scaleX | float | La valeur par laquelle mettre à l'échelle cette miniature selon l'axe x. |
| scaleY | float | La valeur par laquelle mettre à l'échelle cette miniature selon l'axe y. |

**Renvoie :**  
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.

### getImage(IRenderingOptions options, Dimension imageSize) {#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public final IImage getImage(IRenderingOptions options, Dimension imageSize)
```

Renvoie un objet Image miniature avec la taille spécifiée.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Options de rendu. |
| imageSize | java.awt.Dimension | Taille de l'image à créer. |

**Renvoie :**  
[IImage](../../com.aspose.slides/iimage) - Image object.

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

Enregistre le contenu de la diapositive en tant que fichier SVG.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.svg");
>      {
>          // Enregistre la première diapositive en tant que fichier SVG
>          pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Flux cible |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Enregistre le contenu de la diapositive en tant que fichier SVG.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file with options.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide1.svg");
>      SVGOptions options = new SVGOptions();
>      options.setVectorizeText(true);
>      // Enregistre la première diapositive en tant que fichier SVG
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Flux cible |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Options de génération SVG |

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

Enregistre le contenu de la diapositive en tant que fichier EMF.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into a metafile.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.emf");
>      {
>          // Enregistre la première diapositive en tant que métafichier
>          pres.getSlides().get_Item(0).writeAsEmf(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Flux cible |

### remove() {#remove--}
```
public final void remove()
```

Supprime la diapositive de la présentation.

### getLayoutSlide() {#getLayoutSlide--}
```
public final ILayoutSlide getLayoutSlide()
```

Renvoie ou définit la diapositive de mise en page pour la diapositive actuelle. Lecture/écriture [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Renvoie :**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public final void setLayoutSlide(ILayoutSlide value)
```

Renvoie ou définit la diapositive de mise en page pour la diapositive actuelle. Lecture/écriture [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |

### reset() {#reset--}
```
public final void reset()
```

Réinitialise la position, la taille et le formatage de chaque forme qui a un prototype sur LayoutSlide.

### getNotesSlideManager() {#getNotesSlideManager--}
```
public final INotesSlideManager getNotesSlideManager()
```

Permet d'accéder à la diapositive de notes, de l'ajouter et de la supprimer. Lecture seule [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Renvoie :**  
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)

### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public final IComment[] getSlideComments(ICommentAuthor author)
```

Renvoie tous les commentaires de diapositive ajoutés par un auteur spécifique.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Auteur des commentaires à rechercher ou null pour retourner tous les commentaires. |

**Renvoie :**  
com.aspose.slides.IComment[] - Array of [Comment](../../com.aspose.slides/comment).

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

Fusionne les portions avec le même formatage dans tous les paragraphes de toutes les formes acceptables.
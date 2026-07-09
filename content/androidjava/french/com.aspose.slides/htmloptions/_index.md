---
title: HtmlOptions
second_title: Aspose.Slides pour Android via l'API Java Référence
description: Représente des options d'exportation HTML.
type: docs
url: /fr/com.aspose.slides/htmloptions/
---
**Héritage:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Toutes les interfaces implémentées:**  
[com.aspose.slides.IHtmlOptions](../../com.aspose.slides/ihtmloptions)  
```
public class HtmlOptions extends SaveOptions implements IHtmlOptions
```

Représente des options d'exportation HTML.  
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [HtmlOptions(ILinkEmbedController linkEmbedController)](#HtmlOptions-com.aspose.slides.ILinkEmbedController-) | Crée un nouvel objet HtmlOptions en spécifiant le rappel. |
| [HtmlOptions()](#HtmlOptions--) | Crée un nouvel objet HtmlOptions pour enregistrer dans un seul fichier HTML. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Fournit des options qui contrôlent l'apparence des objets Ink dans le document exporté. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Spécifie si le document généré doit inclure les diapositives masquées ou non. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Spécifie si le document généré doit inclure les diapositives masquées ou non. |
| [getHtmlFormatter()](#getHtmlFormatter--) | Renvoie ou définit le modèle HTML. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | Renvoie ou définit le modèle HTML. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Obtient ou définit une valeur indiquant si le texte est rendu sans utiliser de ligatures. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Obtient ou définit une valeur indiquant si le texte est rendu sans utiliser de ligatures. |
| [getSlideImageFormat()](#getSlideImageFormat--) | Renvoie ou définit les options de format d'image de diapositive. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | Renvoie ou définit les options de format d'image de diapositive. |
| [getJpegQuality()](#getJpegQuality--) | Renvoie ou définit une valeur déterminant la qualité des images JPEG dans le document PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Renvoie ou définit une valeur déterminant la qualité des images JPEG dans le document PDF. |
| [getPicturesCompression()](#getPicturesCompression--) | Représente le niveau de compression des images |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Représente le niveau de compression des images |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Un drapeau booléen indique si les parties recadrées restent dans le document. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Un drapeau booléen indique si les parties recadrées restent dans le document. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | Vrai pour exclure les attributs de largeur et de hauteur du conteneur svg - cela rendra la mise en page réactive. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | Vrai pour exclure les attributs de largeur et de hauteur du conteneur svg - cela rendra la mise en page réactive. |
### HtmlOptions(ILinkEmbedController linkEmbedController) {#HtmlOptions-com.aspose.slides.ILinkEmbedController-}
```
public HtmlOptions(ILinkEmbedController linkEmbedController)
```

Crée un nouvel objet HtmlOptions en spécifiant le rappel.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | Objet de rappel qui contrôle l'enregistrement du projet. |

### HtmlOptions() {#HtmlOptions--}
```
public HtmlOptions()
```

Crée un nouvel objet HtmlOptions pour enregistrer dans un seul fichier HTML.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


Gets or sets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Provides options that control the look of Ink objects in exported document. Read-only [IInkOptions](../../com.aspose.slides/iinkoptions)

**Returns:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Specifies whether the generated document should include hidden slides or not. Default is false.

**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Specifies whether the generated document should include hidden slides or not. Default is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public final IHtmlFormatter getHtmlFormatter()
```

Returns or sets HTML template. Read/write [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Returns:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public final void setHtmlFormatter(IHtmlFormatter value)
```

Returns or sets HTML template. Read/write [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

Gets or sets a value indicating whether text is rendered without using ligatures. When set to true, ligatures will be disabled in the rendered output. By default, this property is set to false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      options.setDisableFontLigatures(true);
>      pres.save("presentation.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

Gets or sets a value indicating whether text is rendered without using ligatures. When set to true, ligatures will be disabled in the rendered output. By default, this property is set to false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      options.setDisableFontLigatures(true);
>      pres.save("presentation.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public final ISlideImageFormat getSlideImageFormat()
```

Returns or sets slide image format options. Read/write [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Returns:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public final void setSlideImageFormat(ISlideImageFormat value)
```

Returns or sets slide image format options. Read/write [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

Returns or sets a value determining the quality of the JPEG images inside PDF document. Read/write byte.

--------------------

Has effect only when a document contains JPEG images.

Use this property to get or set the quality of the images inside a document when saving in PDF format. The value may vary from 0 to 100 where 0 means worst quality but maximum compression and 100 means best quality but minimum compression.

The default value is **95**.

**Returns:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

Returns or sets a value determining the quality of the JPEG images inside PDF document. Read/write byte.

--------------------

Has effect only when a document contains JPEG images.

Use this property to get or set the quality of the images inside a document when saving in PDF format. The value may vary from 0 to 100 where 0 means worst quality but maximum compression and 100 means best quality but minimum compression.

The default value is **95**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

Represents the pictures compression level

**Returns:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

Represents the pictures compression level

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped parts will removed, if false they will be serialized in the document (which can possible lead to a larger file)

**Returns:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped parts will removed, if false they will be serialized in the document (which can possible lead to a larger file)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public final boolean getSvgResponsiveLayout()
```

True to exclude width and height attributes from svg container - that will make layout responsive. False - otherwise. Read/write boolean.

**Returns:**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public final void setSvgResponsiveLayout(boolean value)

Vrai pour exclure les attributs de largeur et de hauteur du conteneur svg - cela rendra la mise en page réactive. Faux - autrement. Booléen en lecture/écriture.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
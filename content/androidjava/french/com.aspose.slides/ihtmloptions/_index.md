---
title: IHtmlOptions
second_title: Référence de l'API Aspose.Slides pour Android via Java
description: Représente des options d'exportation HTML.
type: docs
url: /fr/com.aspose.slides/ihtmloptions/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtmlOptions extends ISaveOptions
```

Représente des options d'exportation HTML.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getHtmlFormatter()](#getHtmlFormatter--) | Renvoie ou définit le modèle HTML. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | Renvoie ou définit le modèle HTML. |
| [getSlideImageFormat()](#getSlideImageFormat--) | Renvoie ou définit les options de format d'image de diapositive. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | Renvoie ou définit les options de format d'image de diapositive. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Indique si le document généré doit inclure les diapositives masquées ou non. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Indique si le document généré doit inclure les diapositives masquées ou non. |
| [getJpegQuality()](#getJpegQuality--) | Renvoie ou définit une valeur déterminant la qualité des images JPEG dans le document PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Renvoie ou définit une valeur déterminant la qualité des images JPEG dans le document PDF. |
| [getPicturesCompression()](#getPicturesCompression--) | Représente le niveau de compression des images Lecture/écriture [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Représente le niveau de compression des images Lecture/écriture [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Un indicateur booléen indique si les parties recadrées restent dans le document. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Un indicateur booléen indique si les parties recadrées restent dans le document. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | Vrai pour exclure les attributs de largeur et de hauteur du conteneur SVG - cela rendra la mise en page réactive. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | Vrai pour exclure les attributs de largeur et de hauteur du conteneur SVG - cela rendra la mise en page réactive. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Obtient ou définit une valeur indiquant si le texte est rendu sans ligatures. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Obtient ou définit une valeur indiquant si le texte est rendu sans ligatures. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Fournit des options qui contrôlent l'apparence des objets Ink dans le document exporté. |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public abstract IHtmlFormatter getHtmlFormatter()
```

Renvoie ou définit le modèle HTML. Lecture/écriture [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Renvoie :**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)

### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public abstract void setHtmlFormatter(IHtmlFormatter value)
```

Renvoie ou définit le modèle HTML. Lecture/écriture [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public abstract ISlideImageFormat getSlideImageFormat()
```

Renvoie ou définit les options de format d'image de diapositive. Lecture/écriture [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Renvoie :**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)

### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public abstract void setSlideImageFormat(ISlideImageFormat value)
```

Renvoie ou définit les options de format d'image de diapositive. Lecture/écriture [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Indique si le document généré doit inclure les diapositives masquées ou non. La valeur par défaut est false.

**Renvoie :**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Indique si le document généré doit inclure les diapositives masquées ou non. La valeur par défaut est false.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

Renvoie ou définit une valeur déterminant la qualité des images JPEG dans le document PDF. Lecture/écriture byte.

--------------------

N’a d’effet que lorsqu’un document contient des images JPEG.

Utilisez cette propriété pour obtenir ou définir la qualité des images dans un document lors de l'enregistrement au format PDF. La valeur peut varier de 0 à 100 où 0 signifie la pire qualité mais la compression maximale et 100 signifie la meilleure qualité mais la compression minimale.

La valeur par défaut est **95**.

**Renvoie :**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

Renvoie ou définit une valeur déterminant la qualité des images JPEG dans le document PDF. Lecture/écriture byte.

--------------------

N’a d’effet que lorsqu’un document contient des images JPEG.

Utilisez cette propriété pour obtenir ou définir la qualité des images dans un document lors de l'enregistrement au format PDF. La valeur peut varier de 0 à 100 où 0 signifie la pire qualité mais la compression maximale et 100 signifie la meilleure qualité mais la compression minimale.

La valeur par défaut est **95**.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

Représente le niveau de compression des images Lecture/écriture [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**Renvoie :**
int

### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

Représente le niveau de compression des images Lecture/écriture [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

Un indicateur booléen indique si les parties recadrées restent dans le document. Si true, les parties recadrées seront supprimées, si false elles seront sérialisées dans le document (ce qui peut éventuellement entraîner un fichier plus volumineux) Lecture/écriture boolean.

**Renvoie :**
boolean

### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

Un indicateur booléen indique si les parties recadrées restent dans le document. Si true, les parties recadrées seront supprimées, si false elles seront sérialisées dans le document (ce qui peut éventuellement entraîner un fichier plus volumineux) Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public abstract boolean getSvgResponsiveLayout()
```

Vrai pour exclure les attributs de largeur et de hauteur du conteneur SVG - cela rendra la mise en page réactive. Faux - sinon. Lecture/écriture boolean.

**Renvoie :**
boolean

### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public abstract void setSvgResponsiveLayout(boolean value)
```

Vrai pour exclure les attributs de largeur et de hauteur du conteneur SVG - cela rendra la mise en page réactive. Faux - sinon. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

Obtient ou définit une valeur indiquant si le texte est rendu sans ligatures. Lorsqu'il est défini sur true, les ligatures seront désactivées dans le rendu. Par défaut, cette propriété est définie sur false.

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
public abstract void setDisableFontLigatures(boolean value)
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

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Exemple:
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

**Renvoie :**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Gets or sets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      HandoffLayoutingOptions slidesLayoutOptions = new HandoffLayoutingOptions();
>      slidesLayoutOptions.setHandoff(HandoffType.Handoff4Horizontal);
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
public abstract IInkOptions getInkOptions()


Fournit des options qui contrôlent l'apparence des objets Ink dans le document exporté. Lecture seule [IInkOptions](../../com.aspose.slides/iinkoptions)

**Renvoie :**
[IInkOptions](../../com.aspose.slides/iinkoptions)
---
title: HtmlOptions
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente des options d'exportation HTML.
type: docs
url: /fr/com.aspose.slides/htmloptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**All Implemented Interfaces:**
[com.aspose.slides.IHtmlOptions](../../com.aspose.slides/ihtmloptions)
```
public class HtmlOptions extends SaveOptions implements IHtmlOptions
```

Représente des options d'exportation HTML.
## Constructeurs

| Constructor | Description |
| --- | --- |
| [HtmlOptions(ILinkEmbedController linkEmbedController)](#HtmlOptions-com.aspose.slides.ILinkEmbedController-) | Crée un nouvel objet HtmlOptions en spécifiant le rappel. |
| [HtmlOptions()](#HtmlOptions--) | Crée un nouvel objet HtmlOptions pour enregistrer dans un fichier HTML unique. |
## Méthodes

| Method | Description |
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
| [getJpegQuality()](#getJpegQuality--) | Renvoie ou définit une valeur déterminant la qualité des images JPEG à l'intérieur du document PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Renvoie ou définit une valeur déterminant la qualité des images JPEG à l'intérieur du document PDF. |
| [getPicturesCompression()](#getPicturesCompression--) | Représente le niveau de compression des images. |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Représente le niveau de compression des images. |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Un indicateur booléen indique si les parties recadrées restent faisant partie du document. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Un indicateur booléen indique si les parties recadrées restent faisant partie du document. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | Vrai pour exclure les attributs width et height du conteneur svg - cela rendra la mise en page réactive. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | Vrai pour exclure les attributs width et height du conteneur svg - cela rendra la mise en page réactive. |
### HtmlOptions(ILinkEmbedController linkEmbedController) {#HtmlOptions-com.aspose.slides.ILinkEmbedController-}
```
public HtmlOptions(ILinkEmbedController linkEmbedController)
```


Crée un nouvel objet HtmlOptions en spécifiant le rappel.

**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | Objet de rappel qui contrôle l'enregistrement du projet. |

### HtmlOptions() {#HtmlOptions--}
```
public HtmlOptions()
```


Crée un nouvel objet HtmlOptions pour enregistrer dans un fichier HTML unique.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
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
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
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

**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```


Fournit des options qui contrôlent l'apparence des objets Ink dans le document exporté. Lecture seule [IInkOptions](../../com.aspose.slides/iinkoptions)

**Renvoie :**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Spécifie si le document généré doit inclure les diapositives masquées ou non. La valeur par défaut est false.

**Renvoie :**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Spécifie si le document généré doit inclure les diapositives masquées ou non. La valeur par défaut est false.

**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public final IHtmlFormatter getHtmlFormatter()
```


Renvoie ou définit le modèle HTML. Lecture/écriture [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Renvoie :**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public final void setHtmlFormatter(IHtmlFormatter value)
```


Renvoie ou définit le modèle HTML. Lecture/écriture [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```


Obtient ou définit une valeur indiquant si le texte est rendu sans utiliser de ligatures. Lorsque la valeur est true, les ligatures seront désactivées dans la sortie rendue. Par défaut, cette propriété est false.

--------------------

> ```
> Exemple:
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

**Renvoie :**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```


Obtient ou définit une valeur indiquant si le texte est rendu sans utiliser de ligatures. Lorsque la valeur est true, les ligatures seront désactivées dans la sortie rendue. Par défaut, cette propriété est false.

--------------------

> ```
> Exemple:
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

**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public final ISlideImageFormat getSlideImageFormat()
```


Renvoie ou définit les options de format d'image de diapositive. Lecture/écriture [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Renvoie :**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public final void setSlideImageFormat(ISlideImageFormat value)
```


Renvoie ou définit les options de format d'image de diapositive. Lecture/écriture [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```


Renvoie ou définit une valeur déterminant la qualité des images JPEG à l'intérieur du document PDF. Lecture/écriture byte.

--------------------

Affecte seulement lorsqu'un document contient des images JPEG.

Utilisez cette propriété pour obtenir ou définir la qualité des images dans un document lors de l'enregistrement au format PDF. La valeur peut varier de 0 à 100 où 0 signifie la pire qualité mais la compression maximale et 100 signifie la meilleure qualité mais la compression minimale.

La valeur par défaut est **95**.

**Renvoie :**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```


Renvoie ou définit une valeur déterminant la qualité des images JPEG à l'intérieur du document PDF. Lecture/écriture byte.

--------------------

Affecte seulement lorsqu'un document contient des images JPEG.

Utilisez cette propriété pour obtenir ou définir la qualité des images dans un document lors de l'enregistrement au format PDF. La valeur peut varier de 0 à 100 où 0 signifie la pire qualité mais la compression maximale et 100 signifie la meilleure qualité mais la compression minimale.

La valeur par défaut est **95**.

**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```


Représente le niveau de compression des images

**Renvoie :**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```


Représente le niveau de compression des images

**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```


Un indicateur booléen indique si les parties recadrées restent faisant partie du document. Si true, les parties recadrées seront supprimées, si false elles seront sérialisées dans le document (ce qui peut éventuellement entraîner un fichier plus volumineux)

**Renvoie :**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```


Un indicateur booléen indique si les parties recadrées restent faisant partie du document. Si true, les parties recadrées seront supprimées, si false elles seront sérialisées dans le document (ce qui peut éventuellement entraîner un fichier plus volumineux)

**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public final boolean getSvgResponsiveLayout()
```


Vrai pour exclure les attributs width et height du conteneur svg - cela rendra la mise en page réactive. False - sinon. Lecture/écriture boolean.

**Renvoie :**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public final void setSvgResponsiveLayout(boolean value)
```


Vrai pour exclure les attributs width et height du conteneur svg - cela rendra la mise en page réactive. False - sinon. Lecture/écriture boolean.

**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
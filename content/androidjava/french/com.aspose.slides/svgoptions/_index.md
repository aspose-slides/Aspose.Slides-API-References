---
title: SVGOptions
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente des options SVG.
type: docs
url: /fr/com.aspose.slides/svgoptions/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Toutes les interfaces implémentées :**
[com.aspose.slides.ISVGOptions](../../com.aspose.slides/isvgoptions), java.lang.Cloneable
```
public final class SVGOptions extends SaveOptions implements ISVGOptions, Cloneable
```

Représente des options SVG.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SVGOptions()](#SVGOptions--) | Initialise une nouvelle instance de la classe SVGOptions. |
| [SVGOptions(ILinkEmbedController linkEmbedController)](#SVGOptions-com.aspose.slides.ILinkEmbedController-) | Initialise une nouvelle instance de la classe SVGOptions en spécifiant l'objet contrôleur d'intégration de lien. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Fournit des options qui contrôlent l'apparence des objets Ink dans le document exporté. |
| [getUseFrameSize()](#getUseFrameSize--) | Détermine si le cadre de texte sera inclus dans une zone de rendu ou non. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Détermine si le cadre de texte sera inclus dans une zone de rendu ou non. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Détermine s'il faut appliquer la rotation spécifiée de la forme lors du rendu ou non. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Détermine s'il faut appliquer la rotation spécifiée de la forme lors du rendu ou non. |
| [getVectorizeText()](#getVectorizeText--) | Détermine si le texte d'une diapositive sera enregistré sous forme de graphiques. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Détermine si le texte d'une diapositive sera enregistré sous forme de graphiques. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Renvoie ou définit la limite de résolution inférieure pour la rasterisation des métafichiers. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Renvoie ou définit la limite de résolution inférieure pour la rasterisation des métafichiers. |
| [getDisable3DText()](#getDisable3DText--) | Détermine si le texte 3D est désactivé dans le SVG. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Détermine si le texte 3D est désactivé dans le SVG. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Désactive la division des dégradés FromCornerX et FromCenter. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Désactive la division des dégradés FromCornerX et FromCenter. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 ne permet pas de définir des retraits pour les marqueurs. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 ne permet pas de définir des retraits pour les marqueurs. |
| [getDefault()](#getDefault--) | Renvoie les paramètres par défaut. |
| [getSimple()](#getSimple--) | Renvoie les paramètres pour la génération du fichier SVG le plus simple et le plus petit. |
| [getWYSIWYG()](#getWYSIWYG--) | Renvoie les paramètres pour la génération du fichier SVG la plus précise. |
| [getJpegQuality()](#getJpegQuality--) | Détermine la qualité d'encodage JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Détermine la qualité d'encodage JPEG. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Renvoie et définit une interface de rappel qui permet à l'utilisateur de contrôler la conversion des formes. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Renvoie et définit une interface de rappel qui permet à l'utilisateur de contrôler la conversion des formes. |
| [getPicturesCompression()](#getPicturesCompression--) | Représente le niveau de compression des images |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Représente le niveau de compression des images |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Un indicateur booléen indique si les parties recadrées restent dans le document. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Un indicateur booléen indique si les parties recadrées restent dans le document. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Détermine une méthode de gestion des polices chargées externement. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Détermine une méthode de gestion des polices chargées externement. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Obtient ou définit une valeur indiquant si le texte est rendu sans ligatures. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Obtient ou définit une valeur indiquant si le texte est rendu sans ligatures. |
### SVGOptions() {#SVGOptions--}
```
public SVGOptions()
```

Initialise une nouvelle instance de la classe SVGOptions.

### SVGOptions(ILinkEmbedController linkEmbedController) {#SVGOptions-com.aspose.slides.ILinkEmbedController-}
```
public SVGOptions(ILinkEmbedController linkEmbedController)
```

Initialise une nouvelle instance de la classe SVGOptions en spécifiant l'objet contrôleur d'intégration de lien.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | La référence du contrôleur d'intégration de lien. |

--------------------

Link embedding controller is a delegate object that is responsible for making decisions if resources (such as images) need to be embedded or referenced as external resources. |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Fournit des options qui contrôlent l'apparence des objets Ink dans le document exporté. Lecture seule [IInkOptions](../../com.aspose.slides/iinkoptions)

**Renvoie :**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getUseFrameSize() {#getUseFrameSize--}
```
public final boolean getUseFrameSize()
```

Détermine si le cadre de texte sera inclus dans une zone de rendu ou non. Lecture/écriture boolean . Valeur par défaut est false.

**Renvoie :**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public final void setUseFrameSize(boolean value)
```

Détermine si le cadre de texte sera inclus dans une zone de rendu ou non. Lecture/écriture boolean . Valeur par défaut est false.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public final boolean getUseFrameRotation()
```

Détermine s'il faut appliquer la rotation spécifiée de la forme lors du rendu ou non. Lecture/écriture boolean . Valeur par défaut est true.

**Renvoie :**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public final void setUseFrameRotation(boolean value)
```

Détermine s'il faut appliquer la rotation spécifiée de la forme lors du rendu ou non. Lecture/écriture boolean . Valeur par défaut est true.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getVectorizeText() {#getVectorizeText--}
```
public final boolean getVectorizeText()
```

Détermine si le texte d'une diapositive sera enregistré sous forme de graphiques. Lecture/écriture boolean.

**Renvoie :**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public final void setVectorizeText(boolean value)
```

Détermine si le texte d'une diapositive sera enregistré sous forme de graphiques. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public final int getMetafileRasterizationDpi()
```

Renvoie ou définit la limite de résolution inférieure pour la rasterisation des métafichiers. Lecture/écriture int.

**Renvoie :**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public final void setMetafileRasterizationDpi(int value)
```

Renvoie ou définit la limite de résolution inférieure pour la rasterisation des métafichiers. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public final boolean getDisable3DText()
```

Détermine si le texte 3D est désactivé dans le SVG. Lecture/écriture boolean.

**Renvoie :**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public final void setDisable3DText(boolean value)
```

Détermine si le texte 3D est désactivé dans le SVG. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public final boolean getDisableGradientSplit()
```

Désactive la division des dégradés FromCornerX et FromCenter. Lecture/écriture boolean.

**Renvoie :**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public final void setDisableGradientSplit(boolean value)
```

Désactive la division des dégradés FromCornerX et FromCenter. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public final boolean getDisableLineEndCropping()
```

SVG 1.1 ne permet pas de définir des retraits pour les marqueurs. Aspose.Slides SVG writing engine has workaround for that problem: it crops end of line with arrow, so, line doesn't overlap markers. This option switches off such behavior. Lecture/écriture boolean.

**Renvoie :**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public final void setDisableLineEndCropping(boolean value)
```

SVG 1.1 ne permet pas de définir des retraits pour les marqueurs. Aspose.Slides SVG writing engine has workaround for that problem: it crops end of line with arrow, so, line doesn't overlap markers. This option switches off such behavior. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDefault() {#getDefault--}
```
public static SVGOptions getDefault()
```

Renvoie les paramètres par défaut. Lecture seule [SVGOptions](../../com.aspose.slides/svgoptions).

**Renvoie :**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getSimple() {#getSimple--}
```
public static SVGOptions getSimple()
```

Renvoie les paramètres pour la génération du fichier SVG le plus simple et le plus petit. Lecture seule [SVGOptions](../../com.aspose.slides/svgoptions).

**Renvoie :**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getWYSIWYG() {#getWYSIWYG--}
```
public static SVGOptions getWYSIWYG()
```

Renvoie les paramètres pour la génération du fichier SVG la plus précise. Lecture seule [SVGOptions](../../com.aspose.slides/svgoptions).

**Renvoie :**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

Détermine la qualité d'encodage JPEG. Lecture/écriture int.

**Renvoie :**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

Détermine la qualité d'encodage JPEG. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public final ISvgShapeFormattingController getShapeFormattingController()
```

Renvoie et définit une interface de rappel qui permet à l'utilisateur de contrôler la conversion des formes. Lecture/écriture [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Renvoie :**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public final void setShapeFormattingController(ISvgShapeFormattingController value)
```

Renvoie et définit une interface de rappel qui permet à l'utilisateur de contrôler la conversion des formes. Lecture/écriture [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

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

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

Un indicateur booléen indique si les parties recadrées restent dans le document. Si true les parties recadrées seront supprimées, si false elles seront sérialisées dans le document (ce qui peut éventuellement conduire à un fichier plus volumineux)

**Renvoie :**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

Un indicateur booléen indique si les parties recadrées restent dans le document. Si true les parties recadrées seront supprimées, si false elles seront sérialisées dans le document (ce qui peut éventuellement conduire à un fichier plus volumineux)

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public final int getExternalFontsHandling()
```

Détermine une méthode de gestion des polices chargées externement. Lecture/écriture [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Renvoie :**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public final void setExternalFontsHandling(int value)
```

Détermine une méthode de gestion des polices chargées externement. Lecture/écriture [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

Obtient ou définit une valeur indiquant si le texte est rendu sans ligatures. Lorsqu'il est fixé à true, les ligatures seront désactivées dans la sortie rendue. Par défaut, cette propriété est définie sur false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SVGOptions options = new SVGOptions();
>      options.setDisableFontLigatures(true);
> 
>      FileOutputStream fileStream = new FileOutputStream("slide-0.svg");
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)

Obtient ou définit une valeur indiquant si le texte est rendu sans ligatures. Lorsqu'il est fixé à true, les ligatures seront désactivées dans la sortie rendue. Par défaut, cette propriété est définie sur false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SVGOptions options = new SVGOptions();
>      options.setDisableFontLigatures(true);
> 
>      FileOutputStream fileStream = new FileOutputStream("slide-0.svg");
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
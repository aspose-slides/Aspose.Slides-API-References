---
title: ISVGOptions
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente des options SVG.
type: docs
url: /fr/com.aspose.slides/isvgoptions/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISVGOptions extends ISaveOptions
```

Représente des options SVG.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getVectorizeText()](#getVectorizeText--) | Détermine si le texte d’une diapositive sera enregistré sous forme d’images. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Détermine si le texte d’une diapositive sera enregistré sous forme d’images. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Renvoie ou définit la limite de résolution inférieure pour la rasterisation des métafichiers. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Renvoie ou définit la limite de résolution inférieure pour la rasterisation des métafichiers. |
| [getDisable3DText()](#getDisable3DText--) | Détermine si le texte 3D est désactivé dans le SVG. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Détermine si le texte 3D est désactivé dans le SVG. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Désactive la division des dégradés FromCornerX et FromCenter. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Désactive la division des dégradés FromCornerX et FromCenter. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 ne permet pas de définir des retraits pour les marqueurs. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 ne permet pas de définir des retraits pour les marqueurs. |
| [getJpegQuality()](#getJpegQuality--) | Détermine la qualité d’encodage JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Détermine la qualité d’encodage JPEG. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Renvoie et définit une interface de rappel qui permet à l’utilisateur de contrôler la conversion des formes. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Renvoie et définit une interface de rappel qui permet à l’utilisateur de contrôler la conversion des formes. |
| [getPicturesCompression()](#getPicturesCompression--) | Représente le niveau de compression des images Lecture/écriture \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Représente le niveau de compression des images Lecture/écriture \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Un indicateur booléen indique si les parties recadrées restent présentes dans le document. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Un indicateur booléen indique si les parties recadrées restent présentes dans le document. |
| [getUseFrameSize()](#getUseFrameSize--) | Détermine si le cadre de texte sera inclus dans la zone de rendu ou non. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Détermine si le cadre de texte sera inclus dans la zone de rendu ou non. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Détermine s’il faut appliquer la rotation spécifiée de la forme lors du rendu ou non. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Détermine s’il faut appliquer la rotation spécifiée de la forme lors du rendu ou non. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Détermine la façon de gérer les polices chargées de manière externe. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Détermine la façon de gérer les polices chargées de manière externe. |
| [getInkOptions()](#getInkOptions--) | Fournit des options qui contrôlent l’apparence des objets d’encre dans le document exporté. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Obtient ou définit une valeur indiquant si le texte est rendu sans utiliser de ligatures. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Obtient ou définit une valeur indiquant si le texte est rendu sans utiliser de ligatures. |

### getVectorizeText() {#getVectorizeText--}
```
public abstract boolean getVectorizeText()
```

Détermine si le texte d’une diapositive sera enregistré sous forme d’images. Lecture/écriture booléen.

**Renvoie :**  
boolean

### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public abstract void setVectorizeText(boolean value)
```

Détermine si le texte d’une diapositive sera enregistré sous forme d’images. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public abstract int getMetafileRasterizationDpi()
```

Renvoie ou définit la limite de résolution inférieure pour la rasterisation des métafichiers. Lecture/écriture int.

**Renvoie :**  
int

### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public abstract void setMetafileRasterizationDpi(int value)
```

Renvoie ou définit la limite de résolution inférieure pour la rasterisation des métafichiers. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public abstract boolean getDisable3DText()
```

Détermine si le texte 3D est désactivé dans le SVG. Lecture/écriture booléen.

**Renvoie :**  
boolean

### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public abstract void setDisable3DText(boolean value)
```

Détermine si le texte 3D est désactivé dans le SVG. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public abstract boolean getDisableGradientSplit()
```

Désactive la division des dégradés FromCornerX et FromCenter. Lecture/écriture booléen.

**Renvoie :**  
boolean

### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public abstract void setDisableGradientSplit(boolean value)
```

Désactive la division des dégradés FromCornerX et FromCenter. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public abstract boolean getDisableLineEndCropping()
```

SVG 1.1 ne permet pas de définir des retraits pour les marqueurs. Le moteur d’écriture SVG d’Aspose.Slides contourne ce problème : il recadre l’extrémité de la ligne avec la flèche afin que la ligne ne chevauche pas les marqueurs. Cette option désactive ce comportement. Lecture/écriture booléen.

**Renvoie :**  
boolean

### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public abstract void setDisableLineEndCropping(boolean value)
```

SVG 1.1 ne permet pas de définir des retraits pour les marqueurs. Le moteur d’écriture SVG d’Aspose.Slides contourne ce problème : il recadre l’extrémité de la ligne avec la flèche afin que la ligne ne chevauche pas les marqueurs. Cette option désactive ce comportement. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

Détermine la qualité d’encodage JPEG. Lecture/écriture int.

**Renvoie :**  
int

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

Détermine la qualité d’encodage JPEG. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public abstract ISvgShapeFormattingController getShapeFormattingController()
```

Renvoie et définit une interface de rappel qui permet à l’utilisateur de contrôler la conversion des formes. Lecture/écriture [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Renvoie :**  
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)

### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public abstract void setShapeFormattingController(ISvgShapeFormattingController value)
```

Renvoie et définit une interface de rappel qui permet à l’utilisateur de contrôler la conversion des formes. Lecture/écriture [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

Représente le niveau de compression des images Lecture/écriture \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**Renvoie :**  
int

### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

Représente le niveau de compression des images Lecture/écriture \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

Un indicateur booléen indique si les parties recadrées restent présentes dans le document. Si vrai les parties recadrées seront supprimées, si faux elles seront sérialisées dans le document (ce qui peut éventuellement entraîner un fichier plus volumineux) Lecture/écriture booléen.

**Renvoie :**  
boolean

### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

Un indicateur booléen indique si les parties recadrées restent présentes dans le document. Si vrai les parties recadrées seront supprimées, si faux elles seront sérialisées dans le document (ce qui peut éventuellement entraîner un fichier plus volumineux) Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameSize() {#getUseFrameSize--}
```
public abstract boolean getUseFrameSize()
```

Détermine si le cadre de texte sera inclus dans la zone de rendu ou non. Lecture/écriture booléen. Valeur par défaut : false.

**Renvoie :**  
boolean

### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public abstract void setUseFrameSize(boolean value)
```

Détermine si le cadre de texte sera inclus dans la zone de rendu ou non. Lecture/écriture booléen. Valeur par défaut : false.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public abstract boolean getUseFrameRotation()
```

Détermine s’il faut appliquer la rotation spécifiée de la forme lors du rendu ou non. Lecture/écriture booléen. Valeur par défaut : true.

**Renvoie :**  
boolean

### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public abstract void setUseFrameRotation(boolean value)
```

Détermine s’il faut appliquer la rotation spécifiée de la forme lors du rendu ou non. Lecture/écriture booléen. Valeur par défaut : true.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public abstract int getExternalFontsHandling()
```

Détermine la façon de gérer les polices chargées de manière externe. Lecture/écriture [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Renvoie :**  
int

### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public abstract void setExternalFontsHandling(int value)
```

Détermine la façon de gérer les polices chargées de manière externe. Lecture/écriture [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Fournit des options qui contrôlent l’apparence des objets d’encre dans le document exporté. Lecture seule [IInkOptions](../../com.aspose.slides/iinkoptions)

**Renvoie :**  
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

Obtient ou définit une valeur indiquant si le texte est rendu sans utiliser de ligatures. Lorsque true, les ligatures seront désactivées dans la sortie rendue. Par défaut, cette propriété est false.

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
public abstract void setDisableFontLigatures(boolean value)
Obtient ou définit une valeur indiquant si le texte est rendu sans utiliser de ligatures. Lorsque true, les ligatures seront désactivées dans la sortie rendue. Par défaut, cette propriété est false.

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
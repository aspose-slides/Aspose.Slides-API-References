---
title: IPdfOptions
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Fournit des options qui contrôlent la façon dont une présentation est enregistrée au format Pdf.
type: docs
url: /fr/com.aspose.slides/ipdfoptions/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPdfOptions extends ISaveOptions
```

Fournit des options qui contrôlent la façon dont une présentation est enregistrée au format PDF.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getTextCompression()](#getTextCompression--) | Spécifie le type de compression à utiliser pour tout le contenu textuel du document. |
| [setTextCompression(int value)](#setTextCompression-int-) | Spécifie le type de compression à utiliser pour tout le contenu textuel du document. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Indique si la compression la plus efficace (au lieu de la compression par défaut) pour chaque image doit être sélectionnée automatiquement. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Indique si la compression la plus efficace (au lieu de la compression par défaut) pour chaque image doit être sélectionnée automatiquement. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | True pour incorporer les polices TrueType pour les caractères ASCII 32-127. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | True pour incorporer les polices TrueType pour les caractères ASCII 32-127. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Spécifie si le document généré doit inclure les diapositives masquées ou non. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Spécifie si le document généré doit inclure les diapositives masquées ou non. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Renvoie ou définit un tableau des noms de familles de polices définis par l'utilisateur que Aspose.Slides doit considérer comme communes. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Renvoie ou définit un tableau des noms de familles de polices définis par l'utilisateur que Aspose.Slides doit considérer comme communes. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Détermine si tous les caractères de la police doivent être incorporés ou seulement un sous-ensemble utilisé. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Détermine si tous les caractères de la police doivent être incorporés ou seulement un sous-ensemble utilisé. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Indique si le texte doit être rasterisé en bitmap et enregistré en PDF lorsque la police ne prend pas en charge le style gras. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Indique si le texte doit être rasterisé en bitmap et enregistré en PDF lorsque la police ne prend pas en charge le style gras. |
| [getJpegQuality()](#getJpegQuality--) | Renvoie ou définit une valeur déterminant la qualité des images JPEG dans le document PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Renvoie ou définit une valeur déterminant la qualité des images JPEG dans le document PDF. |
| [getCompliance()](#getCompliance--) | Niveau de conformité souhaité pour le document PDF généré. |
| [setCompliance(int value)](#setCompliance-int-) | Niveau de conformité souhaité pour le document PDF généré. |
| [getPassword()](#getPassword--) | Définition du mot de passe utilisateur pour protéger le document PDF. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Définition du mot de passe utilisateur pour protéger le document PDF. |
| [getAccessPermissions()](#getAccessPermissions--) | Contient un ensemble de drapeaux spécifiant quelles permissions d'accès doivent être accordées lorsqu'un utilisateur ouvre le document. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Contient un ensemble de drapeaux spécifiant quelles permissions d'accès doivent être accordées lorsqu'un utilisateur ouvre le document. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True pour convertir tous les métafichiers utilisés dans une présentation en images PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True pour convertir tous les métafichiers utilisés dans une présentation en images PNG. |
| [getSufficientResolution()](#getSufficientResolution--) | Renvoie ou définit une valeur déterminant la résolution des images dans le document PDF. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Renvoie ou définit une valeur déterminant la résolution des images dans le document PDF. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True pour dessiner un cadre noir autour de chaque diapositive. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True pour dessiner un cadre noir autour de chaque diapositive. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getImageTransparentColor()](#getImageTransparentColor--) | Obtient ou définit la couleur transparente de l'image. |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | Obtient ou définit la couleur transparente de l'image. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Applique la couleur transparente spécifiée à une image si true. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Applique la couleur transparente spécifiée à une image si true. |
| [getInkOptions()](#getInkOptions--) | Fournit des options qui contrôlent l'apparence des objets Ink dans le document exporté. |
| [getIncludeOleData()](#getIncludeOleData--) | True pour convertir toutes les données OLE de la présentation en fichiers incorporés dans le PDF résultant. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | True pour convertir toutes les données OLE de la présentation en fichiers incorporés dans le PDF résultant. |

### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```

Spécifie le type de compression à utiliser pour tout le contenu textuel du document. Lecture/écriture [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Valeur par défaut : [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Renvoie :**
int

### setTextCompression(int value) {#setTextCompression-int-}
```
public abstract void setTextCompression(int value)
```

Spécifie le type de compression à utiliser pour tout le contenu textuel du document. Lecture/écriture [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Valeur par défaut : [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public abstract boolean getBestImagesCompressionRatio()
```

Indique si la compression la plus efficace (au lieu de la compression par défaut) pour chaque image doit être sélectionnée automatiquement. Si la valeur est true, pour chaque image de la présentation, l'algorithme de compression le plus approprié sera choisi, ce qui entraînera une taille plus petite du document PDF résultant.

--------------------

La sélection du meilleur taux de compression d'image est coûteuse en calcul et consomme de la RAM supplémentaire, et cette option est false par défaut.

--------------------

Valeur par défaut : false.

**Renvoie :**
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```

Indique si la compression la plus efficace (au lieu de la compression par défaut) pour chaque image doit être sélectionnée automatiquement. Si la valeur est true, pour chaque image de la présentation, l'algorithme de compression le plus approprié sera choisi, ce qui entraînera une taille plus petite du document PDF résultant.

--------------------

La sélection du meilleur taux de compression d'image est coûteuse en calcul et consomme de la RAM supplémentaire, et cette option est false par défaut.

--------------------

Valeur par défaut : false.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public abstract boolean getEmbedTrueTypeFontsForASCII()
```

True pour incorporer les polices TrueType pour les caractères ASCII 32-127. Les polices pour les codes de caractères supérieurs à 127 sont toujours incorporées. Lecture/écriture boolean.

--------------------

Valeur par défaut : **true**.

**Renvoie :**
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```

True pour incorporer les polices TrueType pour les caractères ASCII 32-127. Les polices pour les codes de caractères supérieurs à 127 sont toujours incorporées. Lecture/écriture boolean.

--------------------

Valeur par défaut : **true**.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Spécifie si le document généré doit inclure les diapositives masquées ou non. Valeur par défaut : false.

**Renvoie :**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Spécifie si le document généré doit inclure les diapositives masquées ou non. Valeur par défaut : false.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public abstract String[] getAdditionalCommonFontFamilies()
```

Renvoie ou définit un tableau de noms de familles de polices définis par l'utilisateur que Aspose.Slides doit considérer comme communes. Lecture/écriture String[].

**Renvoie :**
java.lang.String[]

### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```

Renvoie ou définit un tableau de noms de familles de polices définis par l'utilisateur que Aspose.Slides doit considérer comme communes. Lecture/écriture String[].

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```

Détermine si tous les caractères de la police doivent être incorporés ou seulement un sous-ensemble utilisé. Lecture/écriture boolean.

--------------------

Valeur par défaut : **false**.

**Renvoie :**
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```

Détermine si tous les caractères de la police doivent être incorporés ou seulement un sous-ensemble utilisé. Lecture/écriture boolean.

--------------------

Valeur par défaut : **false**.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public abstract boolean getRasterizeUnsupportedFontStyles()
```

Indique si le texte doit être rasterisé en bitmap et enregistré en PDF lorsque la police ne prend pas en charge le style gras. Cette approche peut améliorer la qualité du texte dans le PDF résultant pour certaines polices. Lecture/écriture boolean.

--------------------

Valeur par défaut : **false**.

**Renvoie :**
boolean

### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public abstract void setRasterizeUnsupportedFontStyles(boolean value)
```

Indique si le texte doit être rasterisé en bitmap et enregistré en PDF lorsque la police ne prend pas en charge le style gras. Cette approche peut améliorer la qualité du texte dans le PDF résultant pour certaines polices. Lecture/écriture boolean.

--------------------

Valeur par défaut : **false**.

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

N'a d'effet que lorsqu'un document contient des images JPEG.

Utilisez cette propriété pour obtenir ou définir la qualité des images dans un document lors de l'enregistrement au format PDF. La valeur peut varier de 0 à 100 où 0 signifie la pire qualité mais la compression maximale et 100 signifie la meilleure qualité mais la compression minimale.

La valeur par défaut est **100**.

**Renvoie :**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

Renvoie ou définit une valeur déterminant la qualité des images JPEG dans le document PDF. Lecture/écriture byte.

--------------------

N'a d'effet que lorsqu'un document contient des images JPEG.

Utilisez cette propriété pour obtenir ou définir la qualité des images dans un document lors de l'enregistrement au format PDF. La valeur peut varier de 0 à 100 où 0 signifie la pire qualité mais la compression maximale et 100 signifie la meilleure qualité mais la compression minimale.

La valeur par défaut est **100**.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public abstract int getCompliance()
```

Niveau de conformité souhaité pour le document PDF généré. Lecture/écriture [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Valeur par défaut : [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Renvoie :**
int

### setCompliance(int value) {#setCompliance-int-}
```
public abstract void setCompliance(int value)
```

Niveau de conformité souhaité pour le document PDF généré. Lecture/écriture [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Valeur par défaut : [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

Définition du mot de passe utilisateur pour protéger le document PDF. Lecture/écriture String.

**Renvoie :**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

Définition du mot de passe utilisateur pour protéger le document PDF. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public abstract int getAccessPermissions()
```

Contient un ensemble de drapeaux spécifiant quelles permissions d'accès doivent être accordées lorsqu'un utilisateur ouvre le document. Voir [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setPassword("my_password");
>  pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>  Presentation presentation = new Presentation();
>  try
>  {
>      presentation.save(pdfFilePath, SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**Returns:**
int
### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public abstract void setAccessPermissions(int value)
```

Contains a set of flags specifying which access permissions should be granted when the document is opened with user access. See [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setPassword("my_password");
>  pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>  Presentation presentation = new Presentation();
>  try
>  {
>      presentation.save(pdfFilePath, SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

True to convert all metafiles used in a presentation to the PNG images. Read/write boolean.

--------------------

Default is **true**. Pdf document can contain vector graphics and raster images. If SaveMetafilesAsPng is set to true then source Metafile image is converted to Png format and saved to Pdf as a raster image. If SaveMetafilesAsPng is set to false then source Metafile is converted to Pdf vector graphics. Each approach has advantages and disadvantages. For example, if Metafile is converted to PNG, then some quality loss is possible during resulting document scaling. If Metafile is converted to Pdf vector graphics, then performance issues in Pdf viewing tool are possible.

**Returns:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

True to convert all metafiles used in a presentation to the PNG images. Read/write boolean.

--------------------

Default is **true**. Pdf document can contain vector graphics and raster images. If SaveMetafilesAsPng is set to true then source Metafile image is converted to Png format and saved to Pdf as a raster image. If SaveMetafilesAsPng is set to false then source Metafile is converted to Pdf vector graphics. Each approach has advantages and disadvantages. For example, if Metafile is converted to PNG, then some quality loss is possible during resulting document scaling. If Metafile is converted to Pdf vector graphics, then performance issues in Pdf viewing tool are possible.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```

Returns or sets a value determining resolution of images inside PDF document. Read/write float.

Value: Effect of this parameter depends on few factors. Algorithm tries to get best output image size according to the property value, source image size and image frame size. Using of similar property values may give the same result. Recommended to use step 16 or 32 to get visible effect.

--------------------

Property affects on file size, time of export and image quality.

The default value is **96**.

**Returns:**
float
### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```

Returns or sets a value determining resolution of images inside PDF document. Read/write float.

Value: Effect of this parameter depends on few factors. Algorithm tries to get best output image size according to the property value, source image size and image frame size. Using of similar property values may give the same result. Recommended to use step 16 or 32 to get visible effect.

--------------------

Property affects on file size, time of export and image quality.

The default value is **96**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```
True to draw black frame around each slide. Read/write boolean.

--------------------

Default is **false**.

**Returns:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

True to draw black frame around each slide. Read/write boolean.

--------------------

Default is **false**.

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
> Exemple :
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Renvoie:** 
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Exemple :
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public abstract Integer getImageTransparentColor()
```

Gets or sets the image transparent color.

Value: The color of the image transparent.

**Returns:**
java.lang.Integer
### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public abstract void setImageTransparentColor(Integer value)
```

Gets or sets the image transparent color.

Value: The color of the image transparent.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public abstract boolean getApplyImageTransparent()
```
Applies the specified transparent color to an image if true.

**Returns:**
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public abstract void setApplyImageTransparent(boolean value)
```
Applies the specified transparent color to an image if true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Provides options that control the look of Ink objects in exported document. Read-only [IInkOptions](../../com.aspose.slides/iinkoptions)

**Returns:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getIncludeOleData() {#getIncludeOleData--}
```
public abstract boolean getIncludeOleData()
```
True pour convertir toutes les données OLE de la présentation en fichiers incorporés dans le PDF résultant. Lecture/écriture  boolean .

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      options.setIncludeOleData(true);
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Valeur par défaut **false** .

**Renvoie :**
boolean
### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public abstract void setIncludeOleData(boolean value)


True pour convertir toutes les données OLE de la présentation en fichiers incorporés dans le PDF résultant. Lecture/écriture boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      options.setIncludeOleData(true);
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Valeur par défaut : **false**.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
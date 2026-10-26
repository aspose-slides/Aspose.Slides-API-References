---
title: IPdfOptions
second_title: Référence de l'API Aspose.Slides pour Java
description: Fournit des options qui contrôlent la façon dont une présentation est enregistrée au format PDF.
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
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Indique si la compression la plus efficace (au lieu de celle par défaut) pour chaque image doit être sélectionnée automatiquement. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Indique si la compression la plus efficace (au lieu de celle par défaut) pour chaque image doit être sélectionnée automatiquement. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | Vrai pour incorporer les polices TrueType pour les caractères ASCII 32-127. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | Vrai pour incorporer les polices TrueType pour les caractères ASCII 32-127. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Spécifie si le document généré doit inclure les diapositives masquées ou non. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Spécifie si le document généré doit inclure les diapositives masquées ou non. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Renvoie ou définit un tableau de noms de familles de polices définis par l'utilisateur que Aspose.Slides doit considérer comme communs. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Renvoie ou définit un tableau de noms de familles de polices définis par l'utilisateur que Aspose.Slides doit considérer comme communs. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Détermine si tous les caractères de la police doivent être incorporés ou seulement un sous-ensemble utilisé. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Détermine si tous les caractères de la police doivent être incorporés ou seulement un sous-ensemble utilisé. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Indique si le texte doit être rasterisé sous forme de bitmap et enregistré en PDF lorsque la police ne prend pas en charge le style gras. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Indique si le texte doit être rasterisé sous forme de bitmap et enregistré en PDF lorsque la police ne prend pas en charge le style gras. |
| [getJpegQuality()](#getJpegQuality--) | Renvoie ou définit une valeur déterminant la qualité des images JPEG à l'intérieur du document PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Renvoie ou définit une valeur déterminant la qualité des images JPEG à l'intérieur du document PDF. |
| [getCompliance()](#getCompliance--) | Niveau de conformité souhaité pour le document PDF généré. |
| [setCompliance(int value)](#setCompliance-int-) | Niveau de conformité souhaité pour le document PDF généré. |
| [getPassword()](#getPassword--) | Définition du mot de passe utilisateur pour protéger le document PDF. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Définition du mot de passe utilisateur pour protéger le document PDF. |
| [getAccessPermissions()](#getAccessPermissions--) | Contient un ensemble de drapeaux indiquant quelles autorisations d'accès doivent être accordées lorsque le document est ouvert avec un accès utilisateur. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Contient un ensemble de drapeaux indiquant quelles autorisations d'accès doivent être accordées lorsque le document est ouvert avec un accès utilisateur. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Vrai pour convertir tous les métafichiers utilisés dans une présentation en images PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Vrai pour convertir tous les métafichiers utilisés dans une présentation en images PNG. |
| [getSufficientResolution()](#getSufficientResolution--) | Renvoie ou définit une valeur déterminant la résolution des images à l'intérieur du document PDF. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Renvoie ou définit une valeur déterminant la résolution des images à l'intérieur du document PDF. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Vrai pour dessiner un cadre noir autour de chaque diapositive. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Vrai pour dessiner un cadre noir autour de chaque diapositive. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getImageTransparentColor()](#getImageTransparentColor--) | Obtient ou définit la couleur transparente de l'image. |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | Obtient ou définit la couleur transparente de l'image. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Applique la couleur transparente spécifiée à une image si vrai. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Applique la couleur transparente spécifiée à une image si vrai. |
| [getInkOptions()](#getInkOptions--) | Fournit des options qui contrôlent l'apparence des objets Ink dans le document exporté. |
| [getIncludeOleData()](#getIncludeOleData--) | Vrai pour convertir toutes les données OLE de la présentation en fichiers incorporés dans le PDF résultant. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | Vrai pour convertir toutes les données OLE de la présentation en fichiers incorporés dans le PDF résultant. |

### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```

Spécifie le type de compression à utiliser pour tout le contenu textuel du document. Lecture/écriture [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Valeur par défaut : [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Retour :**
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

Indique si la compression la plus efficace (au lieu de celle par défaut) pour chaque image doit être sélectionnée automatiquement. Si réglé sur vrai, pour chaque image de la présentation, l'algorithme de compression le plus approprié sera choisi, ce qui conduira à une taille plus petite du document PDF résultant.

--------------------

La sélection du meilleur taux de compression d'image est coûteuse en calcul et nécessite une quantité supplémentaire de RAM, et cette option est fausse par défaut.

--------------------

Valeur par défaut : false.

**Retour :**
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```

Indique si la compression la plus efficace (au lieu de celle par défaut) pour chaque image doit être sélectionnée automatiquement. Si réglé sur vrai, pour chaque image de la présentation, l'algorithme de compression le plus approprié sera choisi, ce qui conduira à une taille plus petite du document PDF résultant.

--------------------

La sélection du meilleur taux de compression d'image est coûteuse en calcul et nécessite une quantité supplémentaire de RAM, et cette option est fausse par défaut.

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

Vrai pour incorporer les polices TrueType pour les caractères ASCII 32-127. Les polices pour les codes de caractères supérieurs à 127 sont toujours incorporées. Lecture/écriture booléen.

--------------------

Valeur par défaut : **true**.

**Retour :**
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```

Vrai pour incorporer les polices TrueType pour les caractères ASCII 32-127. Les polices pour les codes de caractères supérieurs à 127 sont toujours incorporées. Lecture/écriture booléen.

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

**Retour :**
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

Renvoie ou définit un tableau de noms de familles de polices définis par l'utilisateur que Aspose.Slides doit considérer comme communs. Lecture/écriture String[].

**Retour :**
java.lang.String[]

### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```

Renvoie ou définit un tableau de noms de familles de polices définis par l'utilisateur que Aspose.Slides doit considérer comme communs. Lecture/écriture String[].

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```

Détermine si tous les caractères de la police doivent être incorporés ou seulement un sous-ensemble utilisé. Lecture/écriture booléen.

--------------------

Valeur par défaut : **false**.

**Retour :**
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```

Détermine si tous les caractères de la police doivent être incorporés ou seulement un sous-ensemble utilisé. Lecture/écriture booléen.

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

Indique si le texte doit être rasterisé sous forme de bitmap et enregistré en PDF lorsque la police ne prend pas en charge le style gras. Cette approche peut améliorer la qualité du texte dans le PDF résultant pour certaines polices. Lecture/écriture booléen.

--------------------

Valeur par défaut : **false**.

**Retour :**
boolean

### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public abstract void setRasterizeUnsupportedFontStyles(boolean value)
```

Indique si le texte doit être rasterisé sous forme de bitmap et enregistré en PDF lorsque la police ne prend pas en charge le style gras. Cette approche peut améliorer la qualité du texte dans le PDF résultant pour certaines polices. Lecture/écriture booléen.

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

Renvoie ou définit une valeur déterminant la qualité des images JPEG à l'intérieur du document PDF. Lecture/écriture byte.

--------------------

N’a d’effet que lorsqu’un document contient des images JPEG.

Utilisez cette propriété pour obtenir ou définir la qualité des images à l'intérieur d’un document lors de l’enregistrement au format PDF. La valeur peut varier de 0 à 100 où 0 signifie la pire qualité mais la compression maximale et 100 signifie la meilleure qualité mais la compression minimale.

La valeur par défaut est **100**.

**Retour :**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

Renvoie ou définit une valeur déterminant la qualité des images JPEG à l'intérieur du document PDF. Lecture/écriture byte.

--------------------

N’a d’effet que lorsqu’un document contient des images JPEG.

Utilisez cette propriété pour obtenir ou définir la qualité des images à l'intérieur d’un document lors de l’enregistrement au format PDF. La valeur peut varier de 0 à 100 où 0 signifie la pire qualité mais la compression maximale et 100 signifie la meilleure qualité mais la compression minimale.

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

**Retour :**
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

**Retour :**
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

Contient un ensemble de drapeaux indiquant quelles autorisations d'accès doivent être accordées lorsque le document est ouvert avec un accès utilisateur. Voir [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

**Retour :**
int

### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public abstract void setAccessPermissions(int value)
```

Contient un ensemble de drapeaux indiquant quelles autorisations d'accès doivent être accordées lorsque le document est ouvert avec un accès utilisateur. Voir [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

Vrai pour convertir tous les métafichiers utilisés dans une présentation en images PNG. Lecture/écriture boolean.

--------------------

Valeur par défaut : **true**. Le document PDF peut contenir des graphiques vectoriels et des images raster. Si SaveMetafilesAsPng est réglé sur vrai, l’image Métafichier source est convertie au format PNG et enregistrée dans le PDF comme image raster. Si SaveMetafilesAsPng est réglé sur faux, le Métafichier source est converti en graphiques vectoriels PDF. Chaque approche a des avantages et des inconvénients. Par exemple, si le Métafichier est converti en PNG, une perte de qualité peut se produire lors du redimensionnement du document résultant. Si le Métafichier est converti en graphiques vectoriels PDF, des problèmes de performances dans le visualiseur PDF sont possibles.

**Retour :**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

Vrai pour convertir tous les métafichiers utilisés dans une présentation en images PNG. Lecture/écriture boolean.

--------------------

Valeur par défaut : **true**. Le document PDF peut contenir des graphiques vectoriels et des images raster. Si SaveMetafilesAsPng est réglé sur vrai, l’image Métafichier source est convertie au format PNG et enregistrée dans le PDF comme image raster. Si SaveMetafilesAsPng est réglé sur faux, le Métafichier source est converti en graphiques vectoriels PDF. Chaque approche a des avantages et des inconvénients. Par exemple, si le Métafichier est converti en PNG, une perte de qualité peut se produire lors du redimensionnement du document résultant. Si le Métafichier est converti en graphiques vectoriels PDF, des problèmes de performances dans le visualiseur PDF sont possibles.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```

Renvoie ou définit une valeur déterminant la résolution des images à l'intérieur du document PDF. Lecture/écriture float.

Valeur : L’effet de ce paramètre dépend de plusieurs facteurs. L’algorithme tente d’obtenir la meilleure taille d’image de sortie en fonction de la valeur de la propriété, de la taille de l’image source et de la taille du cadre de l’image. L’utilisation de valeurs de propriété similaires peut donner le même résultat. Il est recommandé d’utiliser un pas de 16 ou 32 pour obtenir un effet visible.

--------------------

La propriété influence la taille du fichier, le temps d’exportation et la qualité de l’image.

La valeur par défaut est **96**.

**Retour :**
float

### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```

Renvoie ou définit une valeur déterminant la résolution des images à l'intérieur du document PDF. Lecture/écriture float.

Valeur : L’effet de ce paramètre dépend de plusieurs facteurs. L’algorithme tente d’obtenir la meilleure taille d’image de sortie en fonction de la valeur de la propriété, de la taille de l’image source et de la taille du cadre de l’image. L’utilisation de valeurs de propriété similaires peut donner le même résultat. Il est recommandé d’utiliser un pas de 16 ou 32 pour obtenir un effet visible.

--------------------

La propriété influence la taille du fichier, le temps d’exportation et la qualité de l’image.

La valeur par défaut est **96**.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

Vrai pour dessiner un cadre noir autour de chaque diapositive. Lecture/écriture boolean.

--------------------

Valeur par défaut : **false**.

**Retour :**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

Vrai pour dessiner un cadre noir autour de chaque diapositive. Lecture/écriture boolean.

--------------------

Valeur par défaut : **false**.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
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

**Retour :**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
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

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public abstract Color getImageTransparentColor()
```

Obtient ou définit la couleur transparente de l'image.

Valeur : La couleur transparente de l'image.

**Retour :**
java.awt.Color

### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public abstract void setImageTransparentColor(Color value)
```

Obtient ou définit la couleur transparente de l'image.

Valeur : La couleur transparente de l'image.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public abstract boolean getApplyImageTransparent()
```

Applique la couleur transparente spécifiée à une image si vrai.

**Retour :**
boolean

### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public abstract void setApplyImageTransparent(boolean value)
```

Applique la couleur transparente spécifiée à une image si vrai.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Fournit des options qui contrôlent l'apparence des objets Ink dans le document exporté. Lecture seule [IInkOptions](../../com.aspose.slides/iinkoptions)

**Retour :**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getIncludeOleData() {#getIncludeOleData--}
```
public abstract boolean getIncludeOleData()
```

Vrai pour convertir toutes les données OLE de la présentation en fichiers incorporés dans le PDF résultant. Lecture/écriture boolean.

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
>      if (pres != null) presentation.dispose();
>  }
> ```

--------------------

Valeur par défaut : **false**.

**Retour :**
boolean

### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public abstract void setIncludeOleData(boolean value)
```

Vrai pour convertir toutes les données OLE de la présentation en fichiers incorporés dans le PDF résultant. Lecture/écriture boolean.

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
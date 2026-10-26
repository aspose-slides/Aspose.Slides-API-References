---
title: PdfOptions
second_title: Référence de l'API Aspose.Slides pour Java
description: Fournit des options qui contrôlent la façon dont une présentation est enregistrée au format Pdf.
type: docs
url: /fr/com.aspose.slides/pdfoptions/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IPdfOptions](../../com.aspose.slides/ipdfoptions)
```
public class PdfOptions extends SaveOptions implements IPdfOptions
```

Fournit des options qui contrôlent la façon dont une présentation est enregistrée au format Pdf.

--------------------

> ```
> The following example shows how to convert PowerPoint to PDF with custom options.
>  
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Instancie la classe PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // Définit la qualité Jpeg
>      pdfOptions.setJpegQuality((byte)90);
>      // Définit le comportement des métafichiers
>      pdfOptions.setSaveMetafilesAsPng(true);
>      // Définit le niveau de compression du texte
>      pdfOptions.setTextCompression(PdfTextCompression.Flate);
>      // Définit la norme PDF
>      pdfOptions.setCompliance(PdfCompliance.Pdf15);
>      // Enregistre la présentation au format PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with hidden slides.
>  
>  // Instancie une classe Presentation qui représente un fichier PowerPoint
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Instancie la classe PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // Ajoute les diapositives masquées
>      pdfOptions.setShowHiddenSlides(true);
>      // Enregistre la présentation au format PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to password protected PDF.
>  
>  // Instancie un objet Presentation qui représente un fichier PowerPoint
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Instancie la classe PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // Définit le mot de passe PDF et les permissions d'accès
>      pdfOptions.setPassword("password");
>      pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>      // Enregistre la présentation au format PDF
>      pres.save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with notes.
>  
>  // Instancie un objet Presentation qui représente un fichier de présentation
>  Presentation pres = new Presentation("SelectedSlides.pptx");
>  try {
>      Presentation auxPres = new Presentation();
>      try {
>          ISlide slide = pres.getSlides().get_Item(0);
>          auxPres.getSlides().insertClone(0, slide);
>          // Définit le type et la taille de la diapositive
>          auxPres.getSlideSize().setSize(612F, 792F, SlideSizeScaleType.EnsureFit);
>          PdfOptions pdfOptions = new PdfOptions();
>          pdfOptions.getNotesCommentsLayouting().setNotesPosition(NotesPositions.BottomFull);
>          auxPres.save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
>      } finally {
>          if (auxPres != null) auxPres.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | Constructeur par défaut. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Fournit des options qui contrôlent l'apparence des objets Ink dans le document exporté. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Spécifie si le document généré doit inclure ou non les diapositives masquées. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Spécifie si le document généré doit inclure ou non les diapositives masquées. |
| [getTextCompression()](#getTextCompression--) | Spécifie le type de compression à utiliser pour tout le contenu textuel du document. |
| [setTextCompression(int value)](#setTextCompression-int-) | Spécifie le type de compression à utiliser pour tout le contenu textuel du document. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Indique si la compression la plus efficace (au lieu de celle par défaut) pour chaque image doit être sélectionnée automatiquement. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Indique si la compression la plus efficace (au lieu de celle par défaut) pour chaque image doit être sélectionnée automatiquement. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | Détermine si Aspose.Slides incorporera les polices communes pour le texte ASCII (plage de codes 33..127). |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | Détermine si Aspose.Slides incorporera les polices communes pour le texte ASCII (plage de codes 33..127). |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Renvoie ou définit un tableau de noms de familles de polices définis par l'utilisateur que Aspose.Slides doit considérer comme communes. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Renvoie ou définit un tableau de noms de familles de polices définis par l'utilisateur que Aspose.Slides doit considérer comme communes. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Détermine si tous les caractères de la police doivent être incorporés ou seulement un sous-ensemble utilisé. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Détermine si tous les caractères de la police doivent être incorporés ou seulement un sous-ensemble utilisé. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Indique si le texte doit être rasterisé en bitmap et enregistré en PDF lorsque la police ne supporte pas le style gras. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Indique si le texte doit être rasterisé en bitmap et enregistré en PDF lorsque la police ne supporte pas le style gras. |
| [getJpegQuality()](#getJpegQuality--) | Renvoie ou définit une valeur déterminant la qualité des images JPEG dans le document PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Renvoie ou définit une valeur déterminant la qualité des images JPEG dans le document PDF. |
| [getCompliance()](#getCompliance--) | Niveau de conformité souhaité pour le document PDF généré. |
| [setCompliance(int value)](#setCompliance-int-) | Niveau de conformité souhaité pour le document PDF généré. |
| [getPassword()](#getPassword--) | Définition du mot de passe utilisateur pour protéger le document PDF. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Définition du mot de passe utilisateur pour protéger le document PDF. |
| [getAccessPermissions()](#getAccessPermissions--) | Contient un ensemble de drapeaux spécifiant quelles autorisations d'accès doivent être accordées lorsque le document est ouvert avec un accès utilisateur. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Contient un ensemble de drapeaux spécifiant quelles autorisations d'accès doivent être accordées lorsque le document est ouvert avec un accès utilisateur. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Vrai pour convertir tous les métafichiers utilisés dans une présentation en images PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Vrai pour convertir tous les métafichiers utilisés dans une présentation en images PNG. |
| [getSufficientResolution()](#getSufficientResolution--) | Renvoie ou définit une valeur déterminant la résolution des images dans le document PDF. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Renvoie ou définit une valeur déterminant la résolution des images dans le document PDF. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Vrai pour dessiner un cadre noir autour de chaque diapositive. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Vrai pour dessiner un cadre noir autour de chaque diapositive. |
| [getImageTransparentColor()](#getImageTransparentColor--) | Obtient ou définit la couleur transparente de l'image. |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | Obtient ou définit la couleur transparente de l'image. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Applique la couleur transparente spécifiée à une image si vrai. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Applique la couleur transparente spécifiée à une image si vrai. |
| [getIncludeOleData()](#getIncludeOleData--) | Vrai pour convertir toutes les données OLE de la présentation en fichiers incorporés dans le PDF résultant. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | Vrai pour convertir toutes les données OLE de la présentation en fichiers incorporés dans le PDF résultant. |

### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```

Constructeur par défaut.

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

**Renvoie :**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
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

Spécifie si le document généré doit inclure ou non les diapositives masquées. Valeur par défaut : false.

**Renvoie :**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Spécifie si le document généré doit inclure ou non les diapositives masquées. Valeur par défaut : false.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTextCompression() {#getTextCompression--}
```
public final int getTextCompression()
```

Spécifie le type de compression à utiliser pour tout le contenu textuel du document. Lecture/écriture [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Valeur par défaut : [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Renvoie :**
int

### setTextCompression(int value) {#setTextCompression-int-}
```
public final void setTextCompression(int value)
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
public final boolean getBestImagesCompressionRatio()
```

Indique si la compression la plus efficace (au lieu de celle par défaut) pour chaque image doit être sélectionnée automatiquement. Si réglé sur true, pour chaque image de la présentation l'algorithme de compression le plus approprié sera choisi, ce qui entraînera une taille plus petite du document PDF résultant.

--------------------

La sélection du meilleur taux de compression d'image est coûteuse en calcul et nécessite une quantité supplémentaire de RAM, et cette option est false par défaut.

--------------------

Valeur par défaut : false.

**Renvoie :**
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public final void setBestImagesCompressionRatio(boolean value)
```

Indique si la compression la plus efficace (au lieu de celle par défaut) pour chaque image doit être sélectionnée automatiquement. Si réglé sur true, pour chaque image de la présentation l'algorithme de compression le plus approprié sera choisi, ce qui entraînera une taille plus petite du document PDF résultant.

--------------------

La sélection du meilleur taux de compression d'image est coûteuse en calcul et nécessite une quantité supplémentaire de RAM, et cette option est false par défaut.

--------------------

Valeur par défaut : false.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public final boolean getEmbedTrueTypeFontsForASCII()
```

Détermine si Aspose.Slides incorporera les polices communes pour le texte ASCII (plage de codes 33..127). Les polices pour les codes de caractères supérieurs à 127 sont toujours incorporées. La liste des polices communes comprend les 14 polices de base du PDF et les polices supplémentaires spécifiées par l'utilisateur. Lecture/écriture booléen.

--------------------

Valeur par défaut : **true**.

**Renvoie :**
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public final void setEmbedTrueTypeFontsForASCII(boolean value)
```

Détermine si Aspose.Slides incorporera les polices communes pour le texte ASCII (plage de codes 33..127). Les polices pour les codes de caractères supérieurs à 127 sont toujours incorporées. La liste des polices communes comprend les 14 polices de base du PDF et les polices supplémentaires spécifiées par l'utilisateur. Lecture/écriture booléen.

--------------------

Valeur par défaut : **true**.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public final String[] getAdditionalCommonFontFamilies()
```

Renvoie ou définit un tableau de noms de familles de polices définis par l'utilisateur que Aspose.Slides doit considérer comme communes. Lecture/écriture String[].

**Renvoie :**
java.lang.String[]

### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public final void setAdditionalCommonFontFamilies(String[] value)
```

Renvoie ou définit un tableau de noms de familles de polices définis par l'utilisateur que Aspose.Slides doit considérer comme communes. Lecture/écriture String[].

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public final boolean getEmbedFullFonts()
```

Détermine si tous les caractères de la police doivent être incorporés ou seulement un sous-ensemble utilisé. Lecture/écriture booléen.

--------------------

Valeur par défaut : **false**.

**Renvoie :**
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public final void setEmbedFullFonts(boolean value)
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
public final boolean getRasterizeUnsupportedFontStyles()
```

Indique si le texte doit être rasterisé en bitmap et enregistré en PDF lorsque la police ne supporte pas le style gras. Cette approche peut améliorer la qualité du texte dans le PDF résultant pour certaines polices. Lecture/écriture booléen.

--------------------

Valeur par défaut : **false**.

**Renvoie :**
boolean

### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public final void setRasterizeUnsupportedFontStyles(boolean value)
```

Indique si le texte doit être rasterisé en bitmap et enregistré en PDF lorsque la police ne supporte pas le style gras. Cette approche peut améliorer la qualité du texte dans le PDF résultant pour certaines polices. Lecture/écriture booléen.

--------------------

Valeur par défaut : **false**.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
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
public final void setJpegQuality(byte value)
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
public final int getCompliance()
```

Niveau de conformité souhaité pour le document PDF généré. Lecture/écriture [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Valeur par défaut : [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Renvoie :**
int

### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
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
public final String getPassword()
```

Définition du mot de passe utilisateur pour protéger le document PDF. Lecture/écriture String.

**Renvoie :**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

Définition du mot de passe utilisateur pour protéger le document PDF. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public final int getAccessPermissions()
```

Contient un ensemble de drapeaux spécifiant quelles autorisations d'accès doivent être accordées lorsque le document est ouvert avec un accès utilisateur. Voir [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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


**Renvoie :**
int

### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public final void setAccessPermissions(int value)
```

Contient un ensemble de drapeaux spécifiant quelles autorisations d'accès doivent être accordées lorsque le document est ouvert avec un accès utilisateur. Voir [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
public final boolean getSaveMetafilesAsPng()
```

Vrai pour convertir tous les métafichiers utilisés dans une présentation en images PNG. Lecture/écriture booléen.

--------------------

Valeur par défaut : **true**. Le document PDF peut contenir des graphiques vectoriels et des images raster. Si SaveMetafilesAsPng est réglé sur true, l'image métafichier source est convertie au format PNG et enregistrée dans le PDF comme image raster. Si SaveMetafilesAsPng est réglé sur false, le métafichier source est converti en graphiques vectoriels PDF. Chaque approche a ses avantages et inconvénients. Par exemple, si le métafichier est converti en PNG, une perte de qualité peut survenir lors du redimensionnement du document résultant. Si le métafichier est converti en graphiques vectoriels PDF, des problèmes de performance dans le visualiseur PDF sont possibles.

**Renvoie :**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

Vrai pour convertir tous les métafichiers utilisés dans une présentation en images PNG. Lecture/écriture booléen.

--------------------

Valeur par défaut : **true**. Le document PDF peut contenir des graphiques vectoriels et des images raster. Si SaveMetafilesAsPng est réglé sur true, l'image métafichier source est convertie au format PNG et enregistrée dans le PDF comme image raster. Si SaveMetafilesAsPng est réglé sur false, le métafichier source est converti en graphiques vectoriels PDF. Chaque approche a ses avantages et inconvénients. Par exemple, si le métafichier est converti en PNG, une perte de qualité peut survenir lors du redimensionnement du document résultant. Si le métafichier est converti en graphiques vectoriels PDF, des problèmes de performance dans le visualiseur PDF sont possibles.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public final float getSufficientResolution()
```

Renvoie ou définit une valeur déterminant la résolution des images dans le document PDF. Lecture/écriture float.

Valeur : L'effet de ce paramètre dépend de plusieurs facteurs. L'algorithme essaie d'obtenir la meilleure taille d'image de sortie en fonction de la valeur de la propriété, de la taille de l'image source et de la taille du cadre de l'image. L'utilisation de valeurs de propriété similaires peut donner le même résultat. Il est recommandé d'utiliser un pas de 16 ou 32 pour obtenir un effet visible.

--------------------

La propriété influence la taille du fichier, le temps d'exportation et la qualité de l'image.

La valeur par défaut est **96**.

**Renvoie :**
float

### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public final void setSufficientResolution(float value)
```

Renvoie ou définit une valeur déterminant la résolution des images dans le document PDF. Lecture/écriture float.

Valeur : L'effet de ce paramètre dépend de plusieurs facteurs. L'algorithme essaie d'obtenir la meilleure taille d'image de sortie en fonction de la valeur de la propriété, de la taille de l'image source et de la taille du cadre de l'image. L'utilisation de valeurs de propriété similaires peut donner le même résultat. Il est recommandé d'utiliser un pas de 16 ou 32 pour obtenir un effet visible.

--------------------

La propriété influence la taille du fichier, le temps d'exportation et la qualité de l'image.

La valeur par défaut est **96**.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

Vrai pour dessiner un cadre noir autour de chaque diapositive. Lecture/écriture booléen.

--------------------

Valeur par défaut : **false**.

**Renvoie :**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

Vrai pour dessiner un cadre noir autour de chaque diapositive. Lecture/écriture booléen.

--------------------

Valeur par défaut : **false**.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public final Color getImageTransparentColor()
```

Obtient ou définit la couleur transparente de l'image.

Valeur : La couleur de la transparence de l'image.

**Renvoie :**
java.awt.Color

### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public final void setImageTransparentColor(Color value)
```

Obtient ou définit la couleur transparente de l'image.

Valeur : La couleur de la transparence de l'image.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public final boolean getApplyImageTransparent()
```

Applique la couleur transparente spécifiée à une image si vrai.

**Renvoie :**
boolean

### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public final void setApplyImageTransparent(boolean value)
```

Applique la couleur transparente spécifiée à une image si vrai.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getIncludeOleData() {#getIncludeOleData--}
```
public final boolean getIncludeOleData()
```

Vrai pour convertir toutes les données OLE de la présentation en fichiers incorporés dans le PDF résultant. Lecture/écriture booléen.

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

**Renvoie :**
boolean

### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public final void setIncludeOleData(boolean value)
```

Vrai pour convertir toutes les données OLE de la présentation en fichiers incorporés dans le PDF résultant. Lecture/écriture booléen.

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
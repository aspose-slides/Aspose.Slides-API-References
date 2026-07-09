---
title: PdfOptions
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Fournit des options qui contrôlent la façon dont une présentation est enregistrée au format Pdf.
type: docs
url: /fr/com.aspose.slides/pdfoptions/
---
**Inheritance**:
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**All Implemented Interfaces**:
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
>      // Définit le comportement des metafiles
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
>      // Ajoute des diapositives masquées
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
>      // Définit le mot de passe PDF et les autorisations d'accès
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
>          // Définition du type et de la taille de la diapositive
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
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | Default constructor. |
## Methods

| Method | Description |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Gets or sets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Gets or sets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Provides options that control the look of Ink objects in exported document. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specifies whether the generated document should include hidden slides or not. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specifies whether the generated document should include hidden slides or not. |
| [getTextCompression()](#getTextCompression--) | Specifies compression type to be used for all textual content in the document. |
| [setTextCompression(int value)](#setTextCompression-int-) | Specifies compression type to be used for all textual content in the document. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Indicates if the most effective compression (instead of the default one) for each image must be selected automatically. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Indicates if the most effective compression (instead of the default one) for each image must be selected automatically. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | Determines if Aspose.Slides will embed common fonts for ASCII (33..127 code range) text. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | Determines if Aspose.Slides will embed common fonts for ASCII (33..127 code range) text. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Returns or sets an array of user-defined names of font families which Aspose.Slides should consider common. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Returns or sets an array of user-defined names of font families which Aspose.Slides should consider common. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Determines if all characters of font should be embedded or only used subset. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Determines if all characters of font should be embedded or only used subset. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Indicates whether text should be rasterized as a bitmap and saved to PDF when the font does not support bold styling. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Indicates whether text should be rasterized as a bitmap and saved to PDF when the font does not support bold styling. |
| [getJpegQuality()](#getJpegQuality--) | Returns or sets a value determining the quality of the JPEG images inside PDF document. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Returns or sets a value determining the quality of the JPEG images inside PDF document. |
| [getCompliance()](#getCompliance--) | Desired conformance level for generated PDF document. |
| [setCompliance(int value)](#setCompliance-int-) | Desired conformance level for generated PDF document. |
| [getPassword()](#getPassword--) | Setting user password to protect the PDF document. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Setting user password to protect the PDF document. |
| [getAccessPermissions()](#getAccessPermissions--) | Contains a set of flags specifying which access permissions should be granted when the document is opened with user access. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Contains a set of flags specifying which access permissions should be granted when the document is opened with user access. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True to convert all metafiles used in a presentation to the PNG images. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True to convert all metafiles used in a presentation to the PNG images. |
| [getSufficientResolution()](#getSufficientResolution--) | Returns or sets a value determining resolution of images inside PDF document. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Returns or sets a value determining resolution of images inside PDF document. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True to draw black frame around each slide. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True to draw black frame around each slide. |
| [getImageTransparentColor()](#getImageTransparentColor--) | Gets or sets the image transparent color. |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | Gets or sets the image transparent color. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Applies the specified transparent color to an image if true. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Applies the specified transparent color to an image if true. |
| [getIncludeOleData()](#getIncludeOleData--) | True to convert all OLE data from the presentation to embedded files in the resulting PDF. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | True to convert all OLE data from the presentation to embedded files in the resulting PDF. |
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```

Default constructor.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Gets or sets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

Spécifie si le document généré doit inclure des diapositives masquées ou non. La valeur par défaut est false.

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

### getTextCompression() {#getTextCompression--}
```
public final int getTextCompression()
```

Specifies compression type to be used for all textual content in the document. Read/write [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Default is [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Returns:**
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public final void setTextCompression(int value)
```

Spécifie le type de compression à utiliser pour tout le contenu textuel du document. Lecture/écriture [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

La valeur par défaut est [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public final boolean getBestImagesCompressionRatio()
```

Indique si la compression la plus efficace (au lieu de celle par défaut) pour chaque image doit être sélectionnée automatiquement. Si elle est à true, pour chaque image de la présentation l'algorithme de compression le plus approprié sera choisi, ce qui entraînera une taille plus petite du document PDF résultant.

--------------------

La sélection du meilleur ratio de compression d'image est coûteuse en calcul et requiert une quantité supplémentaire de RAM, et cette option est false par défaut.

--------------------

Par défaut, la valeur est false.

**Returns:**
boolean
### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public final void setBestImagesCompressionRatio(boolean value)
```

Indique si la compression la plus efficace (au lieu de celle par défaut) pour chaque image doit être sélectionnée automatiquement. Si elle est à true, pour chaque image de la présentation l'algorithme de compression le plus approprié sera choisi, ce qui entraînera une taille plus petite du document PDF résultant.

--------------------

La sélection du meilleur ratio de compression d'image est coûteuse en calcul et nécessite une quantité supplémentaire de RAM, et cette option est false par défaut.

--------------------

Par défaut, la valeur est false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public final boolean getEmbedTrueTypeFontsForASCII()
```

Détermine si Aspose.Slides incorporera les polices communes pour le texte ASCII (plage de codes 33..127). Les polices pour les codes de caractères supérieurs à 127 sont toujours incorporées. La liste des polices communes comprend les 14 polices de base du PDF et les polices supplémentaires spécifiées par l'utilisateur. Lecture/écriture boolean.

--------------------

La valeur par défaut est **true**.

**Returns:**
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public final void setEmbedTrueTypeFontsForASCII(boolean value)
```

Détermine si Aspose.Slides incorporera les polices communes pour le texte ASCII (plage de codes 33..127). Les polices pour les codes de caractères supérieurs à 127 sont toujours incorporées. La liste des polices communes comprend les 14 polices de base du PDF et les polices supplémentaires spécifiées par l'utilisateur. Lecture/écriture boolean.

--------------------

La valeur par défaut est **true**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public final String[] getAdditionalCommonFontFamilies()
```

Renvoie ou définit un tableau de noms de familles de polices définis par l'utilisateur que Aspose.Slides doit considérer comme communes. Lecture/écriture String[].

**Returns:**
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public final void setAdditionalCommonFontFamilies(String[] value)
```

Returns or sets an array of user-defined names of font families which Aspose.Slides should consider common. Read/write String[].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public final boolean getEmbedFullFonts()
```

Determines if all characters of font should be embedded or only used subset. Read/write boolean.

--------------------

Default is **false**.

**Returns:**
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public final void setEmbedFullFonts(boolean value)
```

Determines if all characters of font should be embedded or only used subset. Read/write boolean.

--------------------

Default is **false**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public final boolean getRasterizeUnsupportedFontStyles()
```

Indique si le texte doit être rasterisé en bitmap et enregistré en PDF lorsque la police ne prend pas en charge le style gras. Cette approche peut améliorer la qualité du texte dans le PDF résultant pour certaines polices. Lecture/écriture boolean.

--------------------

La valeur par défaut est **false**.

**Returns:**
boolean
### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public final void setRasterizeUnsupportedFontStyles(boolean value)
```

Indique si le texte doit être rasterisé en bitmap et enregistré au PDF lorsque la police ne prend pas en charge le style gras. Cette approche peut améliorer la qualité du texte dans le PDF résultant pour certaines polices. Lecture/écriture boolean.

--------------------

La valeur par défaut est **false**.

**Paramètres:**
| Parameter | Type | Description |
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

**Returns:**
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

Valeur par défaut est [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Returns:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```
Niveau de conformité souhaité pour le document PDF généré. Lecture/écriture [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

La valeur par défaut est [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

Setting user password to protect the PDF document. Read/write String.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```
Définition du mot de passe utilisateur pour protéger le document PDF. Lecture/écriture String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public final int getAccessPermissions()
```
Contient un ensemble de drapeaux spécifiant quelles permissions d'accès doivent être accordées lorsque le document est ouvert avec un accès utilisateur. Voir [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
public final void setAccessPermissions(int value)
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

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

True pour convertir toutes les métas fichiers utilisés dans une présentation en images PNG. Lecture/écriture boolean.

--------------------

La valeur par défaut est **true**. Le document PDF peut contenir des graphiques vectoriels et des images raster. Si SaveMetafilesAsPng est défini sur true alors l'image Metafile source est convertie au format Png et enregistrée dans le PDF comme image raster. Si SaveMetafilesAsPng est défini sur false alors la Metafile source est convertie en graphiques vectoriels PDF. Chaque approche a des avantages et des inconvénients. Par exemple, si la Metafile est convertie en PNG, une perte de qualité peut survenir lors du redimensionnement du document résultant. Si la Metafile est convertie en graphiques vectoriels PDF, des problèmes de performances dans l'outil de visualisation PDF sont possibles.

**Returns:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
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
public final float getSufficientResolution()
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
public final void setSufficientResolution(float value)
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
public final boolean getDrawSlidesFrame()
```

True to draw black frame around each slide. Read/write boolean.

--------------------

Default is **false**.

**Returns:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

True to draw black frame around each slide. Read/write boolean.

--------------------

Default is **false**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public final Integer getImageTransparentColor()
```

Gets or sets the image transparent color.

Value: The color of the image transparent.

**Returns:**
java.lang.Integer
### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public final void setImageTransparentColor(Integer value)
```

Gets or sets the image transparent color.

Value: The color of the image transparent.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public final boolean getApplyImageTransparent()
```

Applique la couleur transparente spécifiée à une image si vrai.

**Returns:**
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public final void setApplyImageTransparent(boolean value)
```


Applies the specified transparent color to an image if true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getIncludeOleData() {#getIncludeOleData--}
```
public final boolean getIncludeOleData()
```

True pour convertir toutes les données OLE de la présentation en fichiers incorporés dans le PDF résultant. Read/write  boolean .

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

Par défaut, la valeur est **false** .

**Returns:**
boolean
### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public final void setIncludeOleData(boolean value)

True pour convertir toutes les données OLE de la présentation en fichiers incorporés dans le PDF résultant. Lecture/écriture  boolean .

--------------------

Exemple :
 
 Presentation pres = new Presentation("pres.pptx");
 try {
     PdfOptions options = new PdfOptions();
     options.setIncludeOleData(true);
     pres.save("pres.pdf", SaveFormat.Pdf, options);
 } finally {
     if (pres != null) pres.dispose();
 }

--------------------

Par défaut, la valeur est **false** .

**Paramètres**:
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
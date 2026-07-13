---
title: IPdfOptions
second_title: Aspose.Slides voor Android via Java API-referentie
description: Biedt opties die bepalen hoe een presentatie wordt opgeslagen in Pdf-formaat.
type: docs
url: /nl/com.aspose.slides/ipdfoptions/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPdfOptions extends ISaveOptions
```

Biedt opties die bepalen hoe een presentatie wordt opgeslagen in Pdf-formaat.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getTextCompression()](#getTextCompression--) | Geeft het compressietype op dat moet worden gebruikt voor alle tekstuele inhoud in het document. |
| [setTextCompression(int value)](#setTextCompression-int-) | Geeft het compressietype op dat moet worden gebruikt voor alle tekstuele inhoud in het document. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Geeft aan of de meest effectieve compressie (in plaats van de standaardcompressie) voor elke afbeelding automatisch moet worden geselecteerd. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Geeft aan of de meest effectieve compressie (in plaats van de standaardcompressie) voor elke afbeelding automatisch moet worden geselecteerd. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | Waar om TrueType-lettertypen voor ASCII-tekens 32-127 in te sluiten. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | Waar om TrueType-lettertypen voor ASCII-tekens 32-127 in te sluiten. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Geeft aan of het gegenereerde document verborgen dia's moet bevatten of niet. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Geeft aan of het gegenereerde document verborgen dia's moet bevatten of niet. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Geeft een array van door de gebruiker gedefinieerde namen van lettertypefamilies terug of stelt deze in, die Aspose.Slides als algemeen moet beschouwen. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Geeft een array van door de gebruiker gedefinieerde namen van lettertypefamilies terug of stelt deze in, die Aspose.Slides als algemeen moet beschouwen. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Bepaalt of alle tekens van het lettertype moeten worden ingebed of alleen een subset. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Bepaalt of alle tekens van het lettertype moeten worden ingebed of alleen een subset. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Geeft aan of tekst moet worden gerasterd als een bitmap en opgeslagen in PDF wanneer het lettertype geen vetgedrukte stijl ondersteunt. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Geeft aan of tekst moet worden gerasterd als een bitmap en opgeslagen in PDF wanneer het lettertype geen vetgedrukte stijl ondersteunt. |
| [getJpegQuality()](#getJpegQuality--) | Geeft een waarde terug die de kwaliteit van de JPEG-afbeeldingen in het PDF-document bepaalt of stelt deze in. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Geeft een waarde terug die de kwaliteit van de JPEG-afbeeldingen in het PDF-document bepaalt of stelt deze in. |
| [getCompliance()](#getCompliance--) | Gewenst conformiteitsniveau voor het gegenereerde PDF-document. |
| [setCompliance(int value)](#setCompliance-int-) | Gewenst conformiteitsniveau voor het gegenereerde PDF-document. |
| [getPassword()](#getPassword--) | Instellen van gebruikerswachtwoord om het PDF-document te beveiligen. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Instellen van gebruikerswachtwoord om het PDF-document te beveiligen. |
| [getAccessPermissions()](#getAccessPermissions--) | Bevat een set vlaggen die aangeven welke toegangsrechten moeten worden toegekend wanneer het document wordt geopend met gebruikersrechten. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Bevat een set vlaggen die aangeven welke toegangsrechten moeten worden toegekend wanneer het document wordt geopend met gebruikersrechten. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Waar om alle metafiles die in een presentatie worden gebruikt om te zetten naar PNG-afbeeldingen. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Waar om alle metafiles die in een presentatie worden gebruikt om te zetten naar PNG-afbeeldingen. |
| [getSufficientResolution()](#getSufficientResolution--) | Geeft een waarde terug die de resolutie van afbeeldingen in het PDF-document bepaalt of stelt deze in. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Geeft een waarde terug die de resolutie van afbeeldingen in het PDF-document bepaalt of stelt deze in. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Waar om een zwart frame rond elke dia te tekenen. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Waar om een zwart frame rond elke dia te tekenen. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Haalt de modus op of stelt deze in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Haalt de modus op of stelt deze in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getImageTransparentColor()](#getImageTransparentColor--) | Haalt de transparante kleur van de afbeelding op of stelt deze in. |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | Haalt de transparante kleur van de afbeelding op of stelt deze in. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Past de opgegeven transparante kleur toe op een afbeelding indien waar. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Past de opgegeven transparante kleur toe op een afbeelding indien waar. |
| [getInkOptions()](#getInkOptions--) | Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document regelen. |
| [getIncludeOleData()](#getIncludeOleData--) | Waar om alle OLE-gegevens uit de presentatie om te zetten naar ingebedde bestanden in de resulterende PDF. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | Waar om alle OLE-gegevens uit de presentatie om te zetten naar ingebedde bestanden in de resulterende PDF. |

### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```

Geeft het compressietype op dat moet worden gebruikt voor alle tekstuele inhoud in het document. Lezen/schrijven [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Standaard is [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Retourwaarde:**
int

### setTextCompression(int value) {#setTextCompression-int-}
```
public abstract void setTextCompression(int value)
```

Geeft het compressietype op dat moet worden gebruikt voor alle tekstuele inhoud in het document. Lezen/schrijven [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Standaard is [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public abstract boolean getBestImagesCompressionRatio()
```

Geeft aan of de meest effectieve compressie (in plaats van de standaardcompressie) voor elke afbeelding automatisch moet worden geselecteerd. Als dit op true staat, wordt voor elke afbeelding in de presentatie het meest geschikte compressie-algoritme gekozen, wat leidt tot een kleiner PDF-document.

--------------------

Het selecteren van de beste compressieverhouding voor afbeeldingen is rekenintensief en verbruikt extra RAM, en deze optie is false by default.

--------------------

Standaard is false.

**Retourwaarde:**
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```

Geeft aan of de meest effectieve compressie (in plaats van de standaardcompressie) voor elke afbeelding automatisch moet worden geselecteerd. Als dit op true staat, wordt voor elke afbeelding in de presentatie het meest geschikte compressie-algoritme gekozen, wat leidt tot een kleiner PDF-document.

--------------------

Het selecteren van de beste compressieverhouding voor afbeeldingen is rekenintensief en verbruikt extra RAM, en deze optie is false by default.

--------------------

Standaard is false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public abstract boolean getEmbedTrueTypeFontsForASCII()
```

Waar om TrueType-lettertypen voor ASCII-tekens 32-127 in te sluiten. Lettertypen voor tekencodes groter dan 127 worden altijd ingebed. Lezen/schrijven boolean.

--------------------

Standaard is **true**.

**Retourwaarde:**
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```

Waar om TrueType-lettertypen voor ASCII-tekens 32-127 in te sluiten. Lettertypen voor tekencodes groter dan 127 worden altijd ingebed. Lezen/schrijven boolean.

--------------------

Standaard is **true**.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Geeft aan of het gegenereerde document verborgen dia's moet bevatten of niet. Standaard is false.

**Retourwaarde:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Geeft aan of het gegenereerde document verborgen dia's moet bevatten of niet. Standaard is false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public abstract String[] getAdditionalCommonFontFamilies()
```

Geeft een array van door de gebruiker gedefinieerde namen van lettertypefamilies terug of stelt deze in die Aspose.Slides als algemeen moet beschouwen. Lezen/schrijven String[].

**Retourwaarde:**
java.lang.String[]

### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```

Geeft een array van door de gebruiker gedefinieerde namen van lettertypefamilies terug of stelt deze in die Aspose.Slides als algemeen moet beschouwen. Lezen/schrijven String[].

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```

Bepaalt of alle tekens van het lettertype moeten worden ingebed of alleen een subset. Lezen/schrijven boolean.

--------------------

Standaard is **false**.

**Retourwaarde:**
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```

Bepaalt of alle tekens van het lettertype moeten worden ingebed of alleen een subset. Lezen/schrijven boolean.

--------------------

Standaard is **false**.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public abstract boolean getRasterizeUnsupportedFontStyles()
```

Geeft aan of tekst moet worden gerasterd als een bitmap en opgeslagen in PDF wanneer het lettertype geen vetgedrukte stijl ondersteunt. Deze aanpak kan de kwaliteit van tekst in de resulterende PDF voor bepaalde lettertypen verbeteren. Lezen/schrijven boolean.

--------------------

Standaard is **false**.

**Retourwaarde:**
boolean

### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public abstract void setRasterizeUnsupportedFontStyles(boolean value)
```

Geeft aan of tekst moet worden gerasterd als een bitmap en opgeslagen in PDF wanneer het lettertype geen vetgedrukte stijl ondersteunt. Deze aanpak kan de kwaliteit van tekst in de resulterende PDF voor bepaalde lettertypen verbeteren. Lezen/schrijven boolean.

--------------------

Standaard is **false**.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

Geeft een waarde terug die de kwaliteit van de JPEG-afbeeldingen in het PDF-document bepaalt of stelt deze in. Lezen/schrijven byte.

--------------------

Heeft alleen effect wanneer een document JPEG-afbeeldingen bevat.

Gebruik deze eigenschap om de kwaliteit van de afbeeldingen in een document bij het opslaan in PDF-formaat te krijgen of in te stellen. De waarde kan variëren van 0 tot 100 waarbij 0 de slechtste kwaliteit maar maximale compressie betekent en 100 de beste kwaliteit maar minimale compressie.

De standaardwaarde is **100**.

**Retourwaarde:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

Geeft een waarde terug die de kwaliteit van de JPEG-afbeeldingen in het PDF-document bepaalt of stelt deze in. Lezen/schrijven byte.

--------------------

Heeft alleen effect wanneer een document JPEG-afbeeldingen bevat.

Gebruik deze eigenschap om de kwaliteit van de afbeeldingen in een document bij het opslaan in PDF-formaat te krijgen of in te stellen. De waarde kan variëren van 0 tot 100 waarbij 0 de slechtste kwaliteit maar maximale compressie betekent en 100 de beste kwaliteit maar minimale compressie.

De standaardwaarde is **100**.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public abstract int getCompliance()
```

Gewenst conformiteitsniveau voor het gegenereerde PDF-document. Lezen/schrijven [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Standaard is [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Retourwaarde:**
int

### setCompliance(int value) {#setCompliance-int-}
```
public abstract void setCompliance(int value)
```

Gewenst conformiteitsniveau voor het gegenereerde PDF-document. Lezen/schrijven [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Standaard is [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

Instellen van gebruikerswachtwoord om het PDF-document te beveiligen. Lezen/schrijven String.

**Retourwaarde:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

Instellen van gebruikerswachtwoord om het PDF-document te beveiligen. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public abstract int getAccessPermissions()
```

Bevat een set vlaggen die aangeven welke toegangsrechten moeten worden toegekend wanneer het document wordt geopend met gebruikersrechten. Zie [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

**Retourwaarde:**
int

### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public abstract void setAccessPermissions(int value)
```

Bevat een set vlaggen die aangeven welke toegangsrechten moeten worden toegekend wanneer het document wordt geopend met gebruikersrechten. Zie [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

Waar om alle metafiles die in een presentatie worden gebruikt om te zetten naar PNG-afbeeldingen. Lezen/schrijven boolean.

--------------------

Standaard is **true**. Een PDF-document kan vectorafbeeldingen en rasterafbeeldingen bevatten. Als SaveMetafilesAsPng op true staat, wordt de bron-Metafile-afbeelding geconverteerd naar PNG-formaat en opgeslagen in PDF als een rasterafbeelding. Als SaveMetafilesAsPng op false staat, wordt de bron-Metafile geconverteerd naar PDF-vectorafbeeldingen. Elke aanpak heeft voor- en nadelen. Bijvoorbeeld, als Metafile wordt geconverteerd naar PNG, kan er kwaliteitsverlies optreden tijdens het schalen van het resulterende document. Als Metafile wordt geconverteerd naar PDF-vectorafbeeldingen, kunnen prestatieproblemen in de PDF-viewer optreden.

**Retourwaarde:**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

Waar om alle metafiles die in een presentatie worden gebruikt om te zetten naar PNG-afbeeldingen. Lezen/schrijven boolean.

--------------------

Standaard is **true**. Een PDF-document kan vectorafbeeldingen en rasterafbeeldingen bevatten. Als SaveMetafilesAsPng op true staat, wordt de bron-Metafile-afbeelding geconverteerd naar PNG-formaat en opgeslagen in PDF als een rasterafbeelding. Als SaveMetafilesAsPng op false staat, wordt de bron-Metafile geconverteerd naar PDF-vectorafbeeldingen. Elke aanpak heeft voor- en nadelen. Bijvoorbeeld, als Metafile wordt geconverteerd naar PNG, kan er kwaliteitsverlies optreden tijdens het schalen van het resulterende document. Als Metafile wordt geconverteerd naar PDF-vectorafbeeldingen, kunnen prestatieproblemen in de PDF-viewer optreden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```

Geeft een waarde terug die de resolutie van afbeeldingen in het PDF-document bepaalt of stelt deze in. Lezen/schrijven float.

Value: Effect of this parameter depends on few factors. Algorithm tries to get best output image size according to the property value, source image size and image frame size. Using of similar property values may give the same result. Recommended to use step 16 or 32 to get visible effect.

--------------------

Property affects on file size, time of export and image quality.

De standaardwaarde is **96**.

**Retourwaarde:**
float

### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```

Geeft een waarde terug die de resolutie van afbeeldingen in het PDF-document bepaalt of stelt deze in. Lezen/schrijven float.

Value: Effect of this parameter depends on few factors. Algorithm tries to get best output image size according to the property value, source image size and image frame size. Using of similar property values may give the same result. Recommended to use step 16 or 32 to get visible effect.

--------------------

Property affects on file size, time of export and image quality.

De standaardwaarde is **96**.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

Waar om een zwart frame rond elke dia te tekenen. Lezen/schrijven boolean.

--------------------

Standaard is **false**.

**Retourwaarde:**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

Waar om een zwart frame rond elke dia te tekenen. Lezen/schrijven boolean.

--------------------

Standaard is **false**.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Haalt de modus op of stelt deze in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**Retourwaarde:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Haalt de modus op of stelt deze in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public abstract Integer getImageTransparentColor()
```

Haalt de transparante kleur van de afbeelding op of stelt deze in.

Value: The color of the image transparent.

**Retourwaarde:**
java.lang.Integer

### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public abstract void setImageTransparentColor(Integer value)
```

Haalt de transparante kleur van de afbeelding op of stelt deze in.

Value: The color of the image transparent.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public abstract boolean getApplyImageTransparent()
```

Past de opgegeven transparante kleur toe op een afbeelding indien waar.

**Retourwaarde:**
boolean

### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public abstract void setApplyImageTransparent(boolean value)
```

Past de opgegeven transparante kleur toe op een afbeelding indien waar.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document regelen. Alleen-lezen [IInkOptions](../../com.aspose.slides/iinkoptions)

**Retourwaarde:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getIncludeOleData() {#getIncludeOleData--}
```
public abstract boolean getIncludeOleData()
```

Waar om alle OLE-gegevens uit de presentatie om te zetten naar ingebedde bestanden in de resulterende PDF. Lezen/schrijven boolean .

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

Standaard is **false** .

**Retourwaarde:**
boolean

### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public abstract void setIncludeOleData(boolean value)
```

Waar om alle OLE-gegevens uit de presentatie om te zetten naar ingebedde bestanden in de resulterende PDF. Lezen/schrijven boolean .

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

Standaard is **false** .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
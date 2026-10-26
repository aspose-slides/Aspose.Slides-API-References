---
title: IPdfOptions
second_title: Aspose.Slides voor Java API-referentie
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

| Method | Beschrijving |
| --- | --- |
| [getTextCompression()](#getTextCompression--) | Specificeert het compressietype dat gebruikt moet worden voor alle tekstuele inhoud in het document. |
| [setTextCompression(int value)](#setTextCompression-int-) | Specificeert het compressietype dat gebruikt moet worden voor alle tekstuele inhoud in het document. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Geeft aan of de meest effectieve compressie (in plaats van de standaard) voor elke afbeelding automatisch moet worden geselecteerd. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Geeft aan of de meest effectieve compressie (in plaats van de standaard) voor elke afbeelding automatisch moet worden geselecteerd. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | True om True type-lettertypen in te sluiten voor ASCII-tekens 32-127. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | True om True type-lettertypen in te sluiten voor ASCII-tekens 32-127. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Retourneert of stelt een array van door de gebruiker gedefinieerde namen van lettertypefamilies in die Aspose.Slides als algemeen moet beschouwen. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Retourneert of stelt een array van door de gebruiker gedefinieerde namen van lettertypefamilies in die Aspose.Slides als algemeen moet beschouwen. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Bepaalt of alle tekens van het lettertype moeten worden ingesloten of alleen een gebruikte subset. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Bepaalt of alle tekens van het lettertype moeten worden ingesloten of alleen een gebruikte subset. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Geeft aan of tekst moet worden gerasterd als een bitmap en opgeslagen in PDF wanneer het lettertype geen vetgedrukte stijl ondersteunt. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Geeft aan of tekst moet worden gerasterd als een bitmap en opgeslagen in PDF wanneer het lettertype geen vetgedrukte stijl ondersteunt. |
| [getJpegQuality()](#getJpegQuality--) | Retourneert of stelt een waarde in die de kwaliteit van de JPEG-afbeeldingen in het PDF-document bepaalt. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Retourneert of stelt een waarde in die de kwaliteit van de JPEG-afbeeldingen in het PDF-document bepaalt. |
| [getCompliance()](#getCompliance--) | Gewenst conformiteitsniveau voor het gegenereerde PDF-document. |
| [setCompliance(int value)](#setCompliance-int-) | Gewenst conformiteitsniveau voor het gegenereerde PDF-document. |
| [getPassword()](#getPassword--) | Instellen van gebruikerswachtwoord om het PDF-document te beveiligen. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Instellen van gebruikerswachtwoord om het PDF-document te beveiligen. |
| [getAccessPermissions()](#getAccessPermissions--) | Bevat een set vlaggen die specificeren welke toegangsrechten moeten worden verleend wanneer het document wordt geopend met gebruikersrechten. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Bevat een set vlaggen die specificeren welke toegangsrechten moeten worden verleend wanneer het document wordt geopend met gebruikersrechten. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True om alle metafiles die in een presentatie worden gebruikt om te zetten naar PNG-afbeeldingen. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True om alle metafiles die in een presentatie worden gebruikt om te zetten naar PNG-afbeeldingen. |
| [getSufficientResolution()](#getSufficientResolution--) | Retourneert of stelt een waarde in die de resolutie van afbeeldingen in het PDF-document bepaalt. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Retourneert of stelt een waarde in die de resolutie van afbeeldingen in het PDF-document bepaalt. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True om een zwart kader rond elke dia te tekenen. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True om een zwart kader rond elke dia te tekenen. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Haal of stel de modus in waarbij dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Haal of stel de modus in waarbij dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getImageTransparentColor()](#getImageTransparentColor--) | Haal of stel de transparante kleur van de afbeelding. |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | Haal of stel de transparante kleur van de afbeelding. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Past de opgegeven transparante kleur toe op een afbeelding als true. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Past de opgegeven transparante kleur toe op een afbeelding als true. |
| [getInkOptions()](#getInkOptions--) | Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document regelen. |
| [getIncludeOleData()](#getIncludeOleData--) | True om alle OLE-gegevens uit de presentatie om te zetten naar ingesloten bestanden in de gegenereerde PDF. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | True om alle OLE-gegevens uit de presentatie om te zetten naar ingesloten bestanden in de gegenereerde PDF. |

### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```

Specificeert het compressietype dat gebruikt moet worden voor alle tekstuele inhoud in het document. Lezen/schrijven [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Standaard is [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Retour:**
int

### setTextCompression(int value) {#setTextCompression-int-}
```
public abstract void setTextCompression(int value)
```

Specificeert het compressietype dat gebruikt moet worden voor alle tekstuele inhoud in het document. Lezen/schrijven [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

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

Geeft aan of de meest effectieve compressie (in plaats van de standaard) voor elke afbeelding automatisch moet worden geselecteerd. Indien true, wordt voor elke afbeelding in de presentatie het meest geschikte compressie-algoritme gekozen, wat leidt tot een kleinere PDF-grootte.

--------------------

Het automatisch kiezen van de beste compressieverhouding is rekenintensief en vereist extra RAM; standaard is deze optie false.

--------------------

Standaard is false.

**Retour:**
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```

Geeft aan of de meest effectieve compressie (in plaats van de standaard) voor elke afbeelding automatisch moet worden geselecteerd. Indien true, wordt voor elke afbeelding in de presentatie het meest geschikte compressie-algoritme gekozen, wat leidt tot een kleinere PDF-grootte.

--------------------

Het automatisch kiezen van de beste compressieverhouding is rekenintensief en vereist extra RAM; standaard is deze optie false.

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

True om TrueType-lettertypen in te sluiten voor ASCII-tekens 32-127. Lettertypen voor tekencodes groter dan 127 worden altijd ingesloten. Lezen/schrijven boolean.

--------------------

Standaard is **true**.

**Retour:**
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```

True om TrueType-lettertypen in te sluiten voor ASCII-tekens 32-127. Lettertypen voor tekencodes groter dan 127 worden altijd ingesloten. Lezen/schrijven boolean.

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

Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. Standaard is false.

**Retour:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. Standaard is false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public abstract String[] getAdditionalCommonFontFamilies()
```

Retourneert of stelt een array van door de gebruiker gedefinieerde namen van lettertypefamilies in die Aspose.Slides als algemeen moet beschouwen. Lezen/schrijven String[].

**Retour:**
java.lang.String[]

### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```

Retourneert of stelt een array van door de gebruiker gedefinieerde namen van lettertypefamilies in die Aspose.Slides als algemeen moet beschouwen. Lezen/schrijven String[].

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```

Bepaalt of alle tekens van het lettertype moeten worden ingesloten of alleen een gebruikte subset. Lezen/schrijven boolean.

--------------------

Standaard is **false**.

**Retour:**
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```

Bepaalt of alle tekens van het lettertype moeten worden ingesloten of alleen een gebruikte subset. Lezen/schrijven boolean.

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

**Retour:**
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

Retourneert of stelt een waarde in die de kwaliteit van de JPEG-afbeeldingen in het PDF-document bepaalt. Lezen/schrijven byte.

--------------------

Heeft alleen effect wanneer een document JPEG-afbeeldingen bevat.

Gebruik deze eigenschap om de kwaliteit van de afbeeldingen in een document bij het opslaan in PDF-formaat te krijgen of in te stellen. De waarde kan variëren van 0 tot 100, waarbij 0 de slechtste kwaliteit maar maximale compressie betekent en 100 de beste kwaliteit maar minimale compressie.

De standaardwaarde is **100**.

**Retour:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

Retourneert of stelt een waarde in die de kwaliteit van de JPEG-afbeeldingen in het PDF-document bepaalt. Lezen/schrijven byte.

--------------------

Heeft alleen effect wanneer een document JPEG-afbeeldingen bevat.

Gebruik deze eigenschap om de kwaliteit van de afbeeldingen in een document bij het opslaan in PDF-formaat te krijgen of in te stellen. De waarde kan variëren van 0 tot 100, waarbij 0 de slechtste kwaliteit maar maximale compressie betekent en 100 de beste kwaliteit maar minimale compressie.

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

**Retour:**
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

**Retour:**
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

Bevat een set vlaggen die specificeren welke toegangsrechten moeten worden verleend wanneer het document wordt geopend met gebruikersrechten. Zie [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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


**Retour:**
int

### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public abstract void setAccessPermissions(int value)
```

Bevat een set vlaggen die specificeren welke toegangsrechten moeten worden verleend wanneer het document wordt geopend met gebruikersrechten. Zie [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

True om alle metafiles die in een presentatie worden gebruikt om te zetten naar PNG-afbeeldingen. Lezen/schrijven boolean.

--------------------

Standaard is **true**. Een PDF-document kan vector-graphics en raster-afbeeldingen bevatten. Als SaveMetafilesAsPng true is, wordt de bron-Metafile-afbeelding geconverteerd naar PNG-formaat en als raster-afbeelding opgeslagen. Als SaveMetafilesAsPng false is, wordt de bron-Metafile geconverteerd naar PDF-vector-graphics. Beide benaderingen hebben voor- en nadelen. Bijvoorbeeld, bij conversie naar PNG kan er kwaliteitsverlies optreden bij het schalen van het document. Bij conversie naar PDF-vector-graphics kunnen prestatie-problemen in PDF-viewers ontstaan.

**Retour:**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

True om alle metafiles die in een presentatie worden gebruikt om te zetten naar PNG-afbeeldingen. Lezen/schrijven boolean.

--------------------

Standaard is **true**. Een PDF-document kan vector-graphics en raster-afbeeldingen bevatten. Als SaveMetafilesAsPng true is, wordt de bron-Metafile-afbeelding geconverteerd naar PNG-formaat en als raster-afbeelding opgeslagen. Als SaveMetafilesAsPng false is, wordt de bron-Metafile geconverteerd naar PDF-vector-graphics. Beide benaderingen hebben voor- en nadelen. Bijvoorbeeld, bij conversie naar PNG kan er kwaliteitsverlies optreden bij het schalen van het document. Bij conversie naar PDF-vector-graphics kunnen prestatie-problemen in PDF-viewers ontstaan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```

Retourneert of stelt een waarde in die de resolutie van afbeeldingen in het PDF-document bepaalt. Lezen/schrijven float.

Waarde: Het effect van deze parameter is afhankelijk van verschillende factoren. Het algoritme probeert de beste uitvoer-afbeeldingsgrootte te bepalen op basis van de eigenschapswaarde, de bron-afbeeldingsgrootte en de grootte van het afbeeldingsframe. Het gebruik van gelijke waarden kan hetzelfde resultaat opleveren. Aanbevolen wordt een stap van 16 of 32 te gebruiken voor een zichtbaar effect.

--------------------

De eigenschap beïnvloedt bestands-grootte, export-tijd en beeld-kwaliteit.

De standaardwaarde is **96**.

**Retour:**
float

### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```

Retourneert of stelt een waarde in die de resolutie van afbeeldingen in het PDF-document bepaalt. Lezen/schrijven float.

Waarde: Het effect van deze parameter is afhankelijk van verschillende factoren. Het algoritme probeert de beste uitvoer-afbeeldingsgrootte te bepalen op basis van de eigenschapswaarde, de bron-afbeeldingsgrootte en de grootte van het afbeeldingsframe. Het gebruik van gelijke waarden kan hetzelfde resultaat opleveren. Aanbevolen wordt een stap van 16 of 32 te gebruiken voor een zichtbaar effect.

--------------------

De eigenschap beïnvloedt bestands-grootte, export-tijd en beeld-kwaliteit.

De standaardwaarde is **96**.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

True om een zwart kader rond elke dia te tekenen. Lezen/schrijven boolean.

--------------------

Standaard is **false**.

**Retour:**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

True om een zwart kader rond elke dia te tekenen. Lezen/schrijven boolean.

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

Haal of stel de modus in waarbij dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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


**Retour:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Haal of stel de modus in waarbij dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public abstract Color getImageTransparentColor()
```

Haal of stel de transparante kleur van de afbeelding.

Waarde: De kleur van de transparante afbeelding.

**Retour:**
java.awt.Color

### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public abstract void setImageTransparentColor(Color value)
```

Haal of stel de transparante kleur van de afbeelding.

Waarde: De kleur van de transparante afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public abstract boolean getApplyImageTransparent()
```

Past de opgegeven transparante kleur toe op een afbeelding als true.

**Retour:**
boolean

### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public abstract void setApplyImageTransparent(boolean value)
```

Past de opgegeven transparante kleur toe op een afbeelding als true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document regelen. Alleen-lezen [IInkOptions](../../com.aspose.slides/iinkoptions)

**Retour:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getIncludeOleData() {#getIncludeOleData--}
```
public abstract boolean getIncludeOleData()
```

True om alle OLE-gegevens uit de presentatie om te zetten naar ingesloten bestanden in de resulterende PDF. Lezen/schrijven boolean.

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

Standaard is **false**.

**Retour:**
boolean

### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public abstract void setIncludeOleData(boolean value)
```

True om alle OLE-gegevens uit de presentatie om te zetten naar ingesloten bestanden in de resulterende PDF. Lezen/schrijven boolean.

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

Standaard is **false**.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
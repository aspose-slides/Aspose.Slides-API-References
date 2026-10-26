---
title: PdfOptions
second_title: Aspose.Slides voor Java API-referentie
description: Biedt opties die bepalen hoe een presentatie wordt opgeslagen in Pdf-formaat.
type: docs
url: /nl/com.aspose.slides/pdfoptions/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IPdfOptions](../../com.aspose.slides/ipdfoptions)
```
public class PdfOptions extends SaveOptions implements IPdfOptions
```

Biedt opties die bepalen hoe een presentatie wordt opgeslagen in Pdf-formaat.

--------------------

> ```
> The following example shows how to convert PowerPoint to PDF with custom options.
>  
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Instantieert de PdfOptions-klasse
>      PdfOptions pdfOptions = new PdfOptions();
>      // Stelt de JPEG-kwaliteit in
>      pdfOptions.setJpegQuality((byte)90);
>      // Stelt het gedrag voor metafiles in
>      pdfOptions.setSaveMetafilesAsPng(true);
>      // Stelt het compressieniveau voor tekst in
>      pdfOptions.setTextCompression(PdfTextCompression.Flate);
>      // Definieert de PDF-standaard
>      pdfOptions.setCompliance(PdfCompliance.Pdf15);
>      // Slaat de presentatie op als PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with hidden slides.
>  
>  // Instantieert een Presentation-klasse die een PowerPoint-bestand vertegenwoordigt
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Instantieert de PdfOptions-klasse
>      PdfOptions pdfOptions = new PdfOptions();
>      // Voegt verborgen dia's toe
>      pdfOptions.setShowHiddenSlides(true);
>      // Slaat de presentatie op als PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to password protected PDF.
>  
>  // Instantieert een Presentation-object dat een PowerPoint-bestand vertegenwoordigt
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Instantieert de PdfOptions-klasse
>      PdfOptions pdfOptions = new PdfOptions();
>      // Stelt het PDF-wachtwoord en de toegangsrechten in
>      pdfOptions.setPassword("password");
>      pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>      // Slaat de presentatie op als PDF
>      pres.save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with notes.
>  
>  // Instantieert een Presentation-object dat een presentatiebestand vertegenwoordigt
>  Presentation pres = new Presentation("SelectedSlides.pptx");
>  try {
>      Presentation auxPres = new Presentation();
>      try {
>          ISlide slide = pres.getSlides().get_Item(0);
>          auxPres.getSlides().insertClone(0, slide);
>          // Instellen van diatype en -grootte
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

| Constructor | Beschrijving |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | Standaardconstructor. |
## Methods

| Methode | Beschrijving |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Haalt op of stelt de modus in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Haalt op of stelt de modus in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document regelen. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Geeft aan of het gegenereerde document verborgen dia's moet bevatten of niet. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Geeft aan of het gegenereerde document verborgen dia's moet bevatten of niet. |
| [getTextCompression()](#getTextCompression--) | Specificeert het compressietype dat voor alle tekstuele inhoud in het document moet worden gebruikt. |
| [setTextCompression(int value)](#setTextCompression-int-) | Specificeert het compressietype dat voor alle tekstuele inhoud in het document moet worden gebruikt. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Geeft aan of de meest effectieve compressie (in plaats van de standaard) voor elke afbeelding automatisch moet worden geselecteerd. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Geeft aan of de meest effectieve compressie (in plaats van de standaard) voor elke afbeelding automatisch moet worden geselecteerd. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | Bepaalt of Aspose.Slides veelgebruikte lettertypen voor ASCII (33..127 codebereik) tekst zal insluiten. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | Bepaalt of Aspose.Slides veelgebruikte lettertypen voor ASCII (33..127 codebereik) tekst zal insluiten. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Retourneert of stelt een array in van door de gebruiker gedefinieerde namen van lettertypefamilies die Aspose.Slides als veelgebruikt moet beschouwen. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Retourneert of stelt een array in van door de gebruiker gedefinieerde namen van lettertypefamilies die Aspose.Slides als veelgebruikt moet beschouwen. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Bepaalt of alle tekens van het lettertype moeten worden ingesloten of alleen een gebruikte subset. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Bepaalt of alle tekens van het lettertype moeten worden ingesloten of alleen een gebruikte subset. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Geeft aan of tekst moet worden gerasterd als bitmap en naar PDF moet worden opgeslagen wanneer het lettertype geen vet gestileerde tekst ondersteunt. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Geeft aan of tekst moet worden gerasterd als bitmap en naar PDF moet worden opgeslagen wanneer het lettertype geen vet gestileerde tekst ondersteunt. |
| [getJpegQuality()](#getJpegQuality--) | Retourneert of stelt een waarde in die de kwaliteit van de JPEG-afbeeldingen in het PDF-document bepaalt. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Retourneert of stelt een waarde in die de kwaliteit van de JPEG-afbeeldingen in het PDF-document bepaalt. |
| [getCompliance()](#getCompliance--) | Gewenst conformiteitsniveau voor het gegenereerde PDF-document. |
| [setCompliance(int value)](#setCompliance-int-) | Gewenst conformiteitsniveau voor het gegenereerde PDF-document. |
| [getPassword()](#getPassword--) | Instellen van gebruikerswachtwoord om het PDF-document te beschermen. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Instellen van gebruikerswachtwoord om het PDF-document te beschermen. |
| [getAccessPermissions()](#getAccessPermissions--) | Bevat een set vlaggen die bepalen welke toegangsrechten moeten worden verleend wanneer het document wordt geopend met gebruikersrechten. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Bevat een set vlaggen die bepalen welke toegangsrechten moeten worden verleend wanneer het document wordt geopend met gebruikersrechten. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Waar om alle metafiles die in een presentatie worden gebruikt naar PNG-afbeeldingen te converteren. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Waar om alle metafiles die in een presentatie worden gebruikt naar PNG-afbeeldingen te converteren. |
| [getSufficientResolution()](#getSufficientResolution--) | Retourneert of stelt een waarde in die de resolutie van afbeeldingen in het PDF-document bepaalt. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Retourneert of stelt een waarde in die de resolutie van afbeeldingen in het PDF-document bepaalt. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Waar om een zwart kader rond elke dia te tekenen. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Waar om een zwart kader rond elke dia te tekenen. |
| [getImageTransparentColor()](#getImageTransparentColor--) | Haalt op of stelt de transparante kleur van de afbeelding in. |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | Haalt op of stelt de transparante kleur van de afbeelding in. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Past de opgegeven transparante kleur toe op een afbeelding indien waar. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Past de opgegeven transparante kleur toe op een afbeelding indien waar. |
| [getIncludeOleData()](#getIncludeOleData--) | Waar om alle OLE-gegevens uit de presentatie te converteren naar ingesloten bestanden in de resulterende PDF. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | Waar om alle OLE-gegevens uit de presentatie te converteren naar ingesloten bestanden in de resulterende PDF. |

### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```

Standaardconstructor.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Haalt op of stelt de modus in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**Retourneert:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Haalt op of stelt de modus in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document regelen. Alleen-lezen [IInkOptions](../../com.aspose.slides/iinkoptions)

**Retourneert:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Geeft aan of het gegenereerde document verborgen dia's moet bevatten of niet. Standaard is onwaar.

**Retourneert:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Geeft aan of het gegenereerde document verborgen dia's moet bevatten of niet. Standaard is onwaar.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTextCompression() {#getTextCompression--}
```
public final int getTextCompression()
```

Specificeert het compressietype dat voor alle tekstuele inhoud in het document moet worden gebruikt. Lezen/Schrijven [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Standaard is [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Retourneert:**
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public final void setTextCompression(int value)
```

Specificeert het compressietype dat voor alle tekstuele inhoud in het document moet worden gebruikt. Lezen/Schrijven [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Standaard is [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public final boolean getBestImagesCompressionRatio()
```

Geeft aan of de meest effectieve compressie (in plaats van de standaard) voor elke afbeelding automatisch moet worden geselecteerd. Indien ingesteld op waar, zal voor elke afbeelding in de presentatie het meest geschikte compressie-algoritme worden gekozen, wat zal leiden tot een kleinere omvang van het resulterende PDF-document.

--------------------

Het selecteren van de beste beeldcompressieverhouding is computationeel intensief en vergt extra RAM, en deze optie is standaard onwaar.

--------------------

Standaard is onwaar.

**Retourneert:**
boolean
### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public final void setBestImagesCompressionRatio(boolean value)
```

Geeft aan of de meest effectieve compressie (in plaats van de standaard) voor elke afbeelding automatisch moet worden geselecteerd. Indien ingesteld op waar, zal voor elke afbeelding in de presentatie het meest geschikte compressie-algoritme worden gekozen, wat zal leiden tot een kleinere omvang van het resulterende PDF-document.

--------------------

Het selecteren van de beste beeldcompressieverhouding is computationeel intensief en vergt extra RAM, en deze optie is standaard onwaar.

--------------------

Standaard is onwaar.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public final boolean getEmbedTrueTypeFontsForASCII()
```

Bepaalt of Aspose.Slides veelgebruikte lettertypen voor ASCII (33..127 codebereik) tekst zal insluiten. Lettertypen voor tekencodes groter dan 127 worden altijd ingesloten. De lijst met veelgebruikte lettertypen omvat de 14 basislettertypen van PDF en extra door de gebruiker opgegeven lettertypen. Lezen/Schrijven boolean.

--------------------

Standaard is **waar**.

**Retourneert:**
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public final void setEmbedTrueTypeFontsForASCII(boolean value)
```

Bepaalt of Aspose.Slides veelgebruikte lettertypen voor ASCII (33..127 codebereik) tekst zal insluiten. Lettertypen voor tekencodes groter dan 127 worden altijd ingesloten. De lijst met veelgebruikte lettertypen omvat de 14 basislettertypen van PDF en extra door de gebruiker opgegeven lettertypen. Lezen/Schrijven boolean.

--------------------

Standaard is **waar**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public final String[] getAdditionalCommonFontFamilies()
```

Retourneert of stelt een array in van door de gebruiker gedefinieerde namen van lettertypefamilies die Aspose.Slides als veelgebruikt moet beschouwen. Lezen/Schrijven String[].

**Retourneert:**
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public final void setAdditionalCommonFontFamilies(String[] value)
```

Retourneert of stelt een array in van door de gebruiker gedefinieerde namen van lettertypefamilies die Aspose.Slides als veelgebruikt moet beschouwen. Lezen/Schrijven String[].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public final boolean getEmbedFullFonts()
```

Bepaalt of alle tekens van het lettertype moeten worden ingesloten of alleen een gebruikte subset. Lezen/Schrijven boolean.

--------------------

Standaard is **onwaar**.

**Retourneert:**
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public final void setEmbedFullFonts(boolean value)
```

Bepaalt of alle tekens van het lettertype moeten worden ingesloten of alleen een gebruikte subset. Lezen/Schrijven boolean.

--------------------

Standaard is **onwaar**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public final boolean getRasterizeUnsupportedFontStyles()
```

Geeft aan of tekst moet worden gerasterd als bitmap en naar PDF moet worden opgeslagen wanneer het lettertype geen vette stijl ondersteunt. Deze benadering kan de kwaliteit van tekst in de resulterende PDF voor bepaalde lettertypen verbeteren. Lezen/Schrijven boolean.

--------------------

Standaard is **onwaar**.

**Retourneert:**
boolean
### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public final void setRasterizeUnsupportedFontStyles(boolean value)
```

Geeft aan of tekst moet worden gerasterd als bitmap en naar PDF moet worden opgeslagen wanneer het lettertype geen vette stijl ondersteunt. Deze benadering kan de kwaliteit van tekst in de resulterende PDF voor bepaalde lettertypen verbeteren. Lezen/Schrijven boolean.

--------------------

Standaard is **onwaar**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

Retourneert of stelt een waarde in die de kwaliteit van de JPEG-afbeeldingen in het PDF-document bepaalt. Lezen/Schrijven byte.

--------------------

Heeft alleen effect wanneer een document JPEG-afbeeldingen bevat.

Gebruik deze eigenschap om de kwaliteit van de afbeeldingen in een document te krijgen of in te stellen bij het opslaan in PDF-formaat. De waarde kan variëren van 0 tot 100 waarbij 0 de slechtste kwaliteit maar maximale compressie betekent en 100 de beste kwaliteit maar minimale compressie.

De standaardwaarde is **100**.

**Retourneert:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

Retourneert of stelt een waarde in die de kwaliteit van de JPEG-afbeeldingen in het PDF-document bepaalt. Lezen/Schrijven byte.

--------------------

Heeft alleen effect wanneer een document JPEG-afbeeldingen bevat.

Gebruik deze eigenschap om de kwaliteit van de afbeeldingen in een document te krijgen of in te stellen bij het opslaan in PDF-formaat. De waarde kan variëren van 0 tot 100 waarbij 0 de slechtste kwaliteit maar maximale compressie betekent en 100 de beste kwaliteit maar minimale compressie.

De standaardwaarde is **100**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public int ??  // Dit is een fout. Sorry ik kon dit niet vertieren 


```

Gewenst conformiteitsniveau voor het gegenereerde PDF-document. Lezen/Schrijven [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Standaard is [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Retourneert:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```

Gewenst conformiteitsniveau voor het gegenereerde PDF-document. Lezen/Schrijven [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Standaard is [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

Instellen van gebruikerswachtwoord om het PDF-document te beveiligen. Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

Instellen van gebruikerswachtwoord om het PDF-document te beveiligen. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public final int getAccessPermissions()
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

**Retourneert:**
int
### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public final void setAccessPermissions(int value)
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

Waar om alle metafiles die in een presentatie worden gebruikt naar PNG-afbeeldingen te converteren. Lezen/Schrijven boolean.

--------------------

Standaard is **waar**. Pdf-document kan vectorafbeeldingen en rasterafbeeldingen bevatten. Als SaveMetafilesAsPng is ingesteld op waar, wordt de bron Metafile-afbeelding geconverteerd naar PNG-formaat en als rasterafbeelding in Pdf opgeslagen. Als SaveMetafilesAsPng is ingesteld op onwaar, wordt de bron Metafile geconverteerd naar Pdf-vectorafbeeldingen. Elke benadering heeft voor- en nadelen. Bijvoorbeeld, als Metafile naar PNG wordt geconverteerd, kan enige kwaliteitsverlies optreden bij het schalen van het resulterende document. Als Metafile naar Pdf-vectorafbeeldingen wordt geconverteerd, kunnen er prestatieproblemen in de Pdf-viewer ontstaan.

**Retourneert:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

Waar om alle metafiles die in een presentatie worden gebruikt naar PNG-afbeeldingen te converteren. Lezen/Schrijven boolean.

--------------------

Standaard is **waar**. Pdf-document kan vectorafbeeldingen en rasterafbeeldingen bevatten. Als SaveMetafilesAsPng is ingesteld op waar, wordt de bron Metafile-afbeelding geconverteerd naar PNG-formaat en als rasterafbeelding in Pdf opgeslagen. Als SaveMetafilesAsPng is ingesteld op onwaar, wordt de bron Metafile geconverteerd naar Pdf-vectorafbeeldingen. Elke benadering heeft voor- en nadelen. Bijvoorbeeld, als Metafile naar PNG wordt geconverteerd, kan enige kwaliteitsverlies optreden bij het schalen van het resulterende document. Als Metafile naar Pdf-vectorafbeeldingen wordt geconverteerd, kunnen er prestatieproblemen in de Pdf-viewer ontstaan.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public final float getSufficientResolution()
```

Retourneert of stelt een waarde in die de resolutie van afbeeldingen in het PDF-document bepaalt. Lezen/Schrijven float.

Waarde: Het effect van deze parameter hangt af van een paar factoren. Het algoritme probeert de beste output-afbeeldingsgrootte te bepalen op basis van de eigenschapswaarde, de bronafbeeldingsgrootte en de afbeeldingsframegrootte. Het gebruik van vergelijkbare eigenschapswaarden kan hetzelfde resultaat opleveren. Het wordt aangeraden stap 16 of 32 te gebruiken om een zichtbaar effect te krijgen.

--------------------

Eigenschap beïnvloedt bestandsomvang, exporttijd en beeldkwaliteit.

De standaardwaarde is **96**.

**Retourneert:**
float
### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public final void setSufficientResolution(float value)
```

Retourneert of stelt een waarde in die de resolutie van afbeeldingen in het PDF-document bepaalt. Lezen/Schrijven float.

Waarde: Het effect van deze parameter hangt af van een paar factoren. Het algoritme probeert de beste output-afbeeldingsgrootte te bepalen op basis van de eigenschapswaarde, de bronafbeeldingsgrootte en de afbeeldingsframegrootte. Het gebruik van vergelijkbare eigenschapswaarden kan hetzelfde resultaat opleveren. Het wordt aangeraden stap 16 of 32 te gebruiken om een zichtbaar effect te krijgen.

--------------------

Eigenschap beïnvloedt bestandsomvang, exporttijd en beeldkwaliteit.

De standaardwaarde is **96**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

Waar om een zwart kader rond elke dia te tekenen. Lezen/Schrijven boolean.

--------------------

Standaard is **onwaar**.

**Retourneert:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

Waar om een zwart kader rond elke dia te tekenen. Lezen/Schrijven boolean.

--------------------

Standaard is **onwaar**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public final Color getImageTransparentColor()
```

Haalt op of stelt de transparante kleur van de afbeelding in.

Waarde: De kleur van de transparante afbeelding.

**Retourneert:**
java.awt.Color
### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public final void setImageTransparentColor(Color value)
```

Haalt op of stelt de transparante kleur van de afbeelding in.

Waarde: De kleur van de transparante afbeelding.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public final boolean getApplyImageTransparent()
```

Past de opgegeven transparante kleur toe op een afbeelding indien waar.

**Retourneert:**
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public final void setApplyImageTransparent(boolean value)
```

Past de opgegeven transparante kleur toe op een afbeelding indien waar.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getIncludeOleData() {#getIncludeOleData--}
```
public final boolean getIncludeOleData()
```

Waar om alle OLE-gegevens uit de presentatie te converteren naar ingesloten bestanden in de resulterende PDF. Lezen/Schrijven boolean.

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

Standaard is **onwaar**.

**Retourneert:**
boolean
### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public final void setIncludeOleData(boolean value)
```

Waar om alle OLE-gegevens uit de presentatie te converteren naar ingesloten bestanden in de resulterende PDF. Lezen/Schrijven boolean.

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

Standaard is **onwaar**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
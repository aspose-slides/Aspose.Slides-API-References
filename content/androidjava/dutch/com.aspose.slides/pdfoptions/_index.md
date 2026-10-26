---
title: PdfOptions
second_title: Aspose.Slides voor Android via Java API-referentie
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
> Het volgende voorbeeld laat zien hoe PowerPoint naar PDF te converteren met aangepaste opties.
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
> Het volgende voorbeeld laat zien hoe PowerPoint naar PDF te converteren met verborgen dia's.
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
> Het volgende voorbeeld laat zien hoe PowerPoint naar een met wachtwoord beveiligde PDF te converteren.
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
> Het volgende voorbeeld laat zien hoe PowerPoint naar PDF te converteren met notities.
>  
>  // Instantieert een Presentation-object dat een presentiebestand vertegenwoordigt
>  Presentation pres = new Presentation("SelectedSlides.pptx");
>  try {
>      Presentation auxPres = new Presentation();
>      try {
>          ISlide slide = pres.getSlides().get_Item(0);
>          auxPres.getSlides().insertClone(0, slide);
>          // Instellen van het dia-type en de grootte
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
```
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | Standaardconstructor. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Verkrijgt of stelt de modus in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Verkrijgt of stelt de modus in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document bepalen. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. |
| [getTextCompression()](#getTextCompression--) | Specificeert het compressietype dat moet worden gebruikt voor alle tekstuele inhoud in het document. |
| [setTextCompression(int value)](#setTextCompression-int-) | Specificeert het compressietype dat moet worden gebruikt voor alle tekstuele inhoud in het document. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Geeft aan of de meest effectieve compressie (in plaats van de standaardcompressie) voor elke afbeelding automatisch moet worden geselecteerd. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Geeft aan of de meest effectieve compressie (in plaats van de standaardcompressie) voor elke afbeelding automatisch moet worden geselecteerd. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | Bepaalt of Aspose.Slides veelvoorkomende lettertypen voor ASCII (codebereik 33..127) tekst zal insluiten. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | Bepaalt of Aspose.Slides veelvoorkomende lettertypen voor ASCII (codebereik 33..127) tekst zal insluiten. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Geeft een array met door de gebruiker gedefinieerde namen van lettertypefamilies terug of stelt deze in die Aspose.Slides als algemeen moet beschouwen. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Geeft een array met door de gebruiker gedefinieerde namen van lettertypefamilies terug of stelt deze in die Aspose.Slides als algemeen moet beschouwen. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Bepaalt of alle tekens van het lettertype moeten worden ingesloten of alleen een gebruikte subset. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Bepaalt of alle tekens van het lettertype moeten worden ingesloten of alleen een gebruikte subset. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Geeft aan of tekst moet worden gerasterd als bitmap en opgeslagen in PDF wanneer het lettertype geen vette opmaak ondersteunt. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Geeft aan of tekst moet worden gerasterd als bitmap en opgeslagen in PDF wanneer het lettertype geen vette opmaak ondersteunt. |
| [getJpegQuality()](#getJpegQuality--) | Geeft een waarde terug of stelt een waarde in die de kwaliteit van de JPEG-afbeeldingen in het PDF-document bepaalt. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Geeft een waarde terug of stelt een waarde in die de kwaliteit van de JPEG-afbeeldingen in het PDF-document bepaalt. |
| [getCompliance()](#getCompliance--) | Gewenst conformiteitsniveau voor het gegenereerde PDF-document. |
| [setCompliance(int value)](#setCompliance-int-) | Gewenst conformiteitsniveau voor het gegenereerde PDF-document. |
| [getPassword()](#getPassword--) | Instellen van gebruikerswachtwoord om het PDF-document te beveiligen. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Instellen van gebruikerswachtwoord om het PDF-document te beveiligen. |
| [getAccessPermissions()](#getAccessPermissions--) | Bevat een set vlaggen die specificeren welke toegangsrechten moeten worden verleend wanneer het document wordt geopend met gebruikersrechten. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Bevat een set vlaggen die specificeren welke toegangsrechten moeten worden verleend wanneer het document wordt geopend met gebruikersrechten. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Waar om alle metafiles die in een presentatie worden gebruikt te converteren naar PNG-afbeeldingen. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Waar om alle metafiles die in een presentatie worden gebruikt te converteren naar PNG-afbeeldingen. |
| [getSufficientResolution()](#getSufficientResolution--) | Geeft een waarde terug of stelt een waarde in die de resolutie van afbeeldingen in het PDF-document bepaalt. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Geeft een waarde terug of stelt een waarde in die de resolutie van afbeeldingen in het PDF-document bepaalt. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Waar om een zwart kader rond elke dia te tekenen. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Waar om een zwart kader rond elke dia te tekenen. |
| [getImageTransparentColor()](#getImageTransparentColor--) | Verkrijgt of stelt de transparante kleur van de afbeelding in. |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | Verkrijgt of stelt de transparante kleur van de afbeelding in. |
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

Verkrijgt of stelt de modus in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Voorbeeld:
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

Verkrijgt of stelt de modus in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Voorbeeld:
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

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document bepalen. Alleen-lezen [IInkOptions](../../com.aspose.slides/iinkoptions)

**Retourneert:**  
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. Standaard is false.

**Retourneert:**  
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. Standaard is false.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getTextCompression() {#getTextCompression--}
```
public final int getTextCompression()
```

Specificeert het compressietype dat moet worden gebruikt voor alle tekstuele inhoud in het document. Lezen/Schrijven [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Standaard is [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Retourneert:**  
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public final void setTextCompression(int value)
```

Specificeert het compressietype dat moet worden gebruikt voor alle tekstuele inhoud in het document. Lezen/Schrijven [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Standaard is [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public final boolean getBestImagesCompressionRatio()
```

Geeft aan of de meest effectieve compressie (in plaats van de standaardcompressie) voor elke afbeelding automatisch moet worden geselecteerd. Indien ingesteld op true, wordt voor elke afbeelding in de presentatie het meest geschikte compressie-algoritme gekozen, wat leidt tot een kleinere omvang van het resulterende PDF-document.

--------------------

Het automatisch selecteren van de beste compressieverhouding is rekenintensief en vereist extra RAM; deze optie is standaard false.

--------------------

Standaard is false.

**Retourneert:**  
boolean
### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public final void setBestImagesCompressionRatio(boolean value)
```

Geeft aan of de meest effectieve compressie (in plaats van de standaardcompressie) voor elke afbeelding automatisch moet worden geselecteerd. Indien ingesteld op true, wordt voor elke afbeelding in de presentatie het meest geschikte compressie-algoritme gekozen, wat leidt tot een kleinere omvang van het resulterende PDF-document.

--------------------

Het automatisch selecteren van de beste compressieverhouding is rekenintensief en vereist extra RAM; deze optie is standaard false.

--------------------

Standaard is false.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public final boolean getEmbedTrueTypeFontsForASCII()
```

Bepaalt of Aspose.Slides veelvoorkomende lettertypen voor ASCII (codebereik 33..127) tekst zal insluiten. Lettertypen voor tekens boven 127 worden altijd ingesloten. De lijst met veelvoorkomende lettertypen omvat de 14 basis-PDF-lettertypen en eventuele door de gebruiker opgegeven lettertypen. Lezen/Schrijven boolean.

--------------------

Standaard is **true**.

**Retourneert:**  
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public final void setEmbedTrueTypeFontsForASCII(boolean value)
```

Bepaalt of Aspose.Slides veelvoorkomende lettertypen voor ASCII (codebereik 33..127) tekst zal insluiten. Lettertypen voor tekens boven 127 worden altijd ingesloten. De lijst met veelvoorkomende lettertypen omvat de 14 basis-PDF-lettertypen en eventuele door de gebruiker opgegeven lettertypen. Lezen/Schrijven boolean.

--------------------

Standaard is **true**.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public final String[] getAdditionalCommonFontFamilies()
```

Geeft een array met door de gebruiker gedefinieerde namen van lettertypefamilies terug of stelt deze in die Aspose.Slides als algemeen moet beschouwen. Lezen/Schrijven String[].

**Retourneert:**  
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public final void setAdditionalCommonFontFamilies(String[] value)
```

Geeft een array met door de gebruiker gedefinieerde namen van lettertypefamilies terug of stelt deze in die Aspose.Slides als algemeen moet beschouwen. Lezen/Schrijven String[].

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public final boolean getEmbedFullFonts()
```

Bepaalt of alle tekens van het lettertype moeten worden ingesloten of alleen een gebruikte subset. Lezen/Schrijven boolean.

--------------------

Standaard is **false**.

**Retourneert:**  
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public final void setEmbedFullFonts(boolean value)
```

Bepaalt of alle tekens van het lettertype moeten worden ingesloten of alleen een gebruikte subset. Lezen/Schrijven boolean.

--------------------

Standaard is **false**.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public final boolean getRasterizeUnsupportedFontStyles()
```

Geeft aan of tekst moet worden gerasterd als bitmap en opgeslagen in PDF wanneer het lettertype geen vette opmaak ondersteunt. Deze aanpak kan de kwaliteit van de tekst in het resulterende PDF-document verbeteren voor bepaalde lettertypen. Lezen/Schrijven boolean.

--------------------

Standaard is **false**.

**Retourneert:**  
boolean
### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public final void setRasterizeUnsupportedFontStyles(boolean value)
```

Geeft aan of tekst moet worden gerasterd als bitmap en opgeslagen in PDF wanneer het lettertype geen vette opmaak ondersteunt. Deze aanpak kan de kwaliteit van de tekst in het resulterende PDF-document verbeteren voor bepaalde lettertypen. Lezen/Schrijven boolean.

--------------------

Standaard is **false**.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

Geeft een waarde terug of stelt een waarde in die de kwaliteit van de JPEG-afbeeldingen in het PDF-document bepaalt. Lezen/Schrijven byte.

--------------------

Heeft alleen effect wanneer een document JPEG-afbeeldingen bevat.

Gebruik deze eigenschap om de kwaliteit van de afbeeldingen in een document te krijgen of in te stellen bij het opslaan in PDF-formaat. De waarde kan variëren van 0 tot 100, waarbij 0 de slechtste kwaliteit maar maximale compressie aangeeft en 100 de beste kwaliteit maar minimale compressie.

De standaardwaarde is **100**.

**Retourneert:**  
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

Geeft een waarde terug of stelt een waarde in die de kwaliteit van de JPEG-afbeeldingen in het PDF-document bepaalt. Lezen/Schrijven byte.

--------------------

Heeft alleen effect wanneer een document JPEG-afbeeldingen bevat.

Gebruik deze eigenschap om de kwaliteit van de afbeeldingen in een document te krijgen of in te stellen bij het opslaan in PDF-formaat. De waarde kan variëren van 0 tot 100, waarbij 0 de slechtste kwaliteit maar maximale compressie aangeeft en 100 de beste kwaliteit maar minimale compressie.

De standaardwaarde is **100**.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
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
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

Waar om alle metafiles die in een presentatie worden gebruikt te converteren naar PNG-afbeeldingen. Lezen/Schrijven boolean.

--------------------

Standaard is **true**. Een PDF-document kan vector-grafische elementen en raster-afbeeldingen bevatten. Als SaveMetafilesAsPng true is, wordt de bron-Metafile geconverteerd naar PNG-formaat en opgeslagen in de PDF als raster-afbeelding. Als SaveMetafilesAsPng false is, wordt de bron-Metafile geconverteerd naar vector-grafiek in de PDF. Elke aanpak heeft voor- en nadelen. Bijvoorbeeld, bij conversie naar PNG kan er kwaliteitsverlies optreden bij schaalvergroting van het document. Bij conversie naar vector-grafiek kunnen weergave-prestaties van de PDF-viewer worden beïnvloed.

**Retourneert:**  
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

Waar om alle metafiles die in een presentatie worden gebruikt te converteren naar PNG-afbeeldingen. Lezen/Schrijven boolean.

--------------------

Standaard is **true**. Een PDF-document kan vector-grafische elementen en raster-afbeeldingen bevatten. Als SaveMetafilesAsPng true is, wordt de bron-Metafile geconverteerd naar PNG-formaat en opgeslagen in de PDF als raster-afbeelding. Als SaveMetafilesAsPng false is, wordt de bron-Metafile geconverteerd naar vector-grafiek in de PDF. Elke aanpak heeft voor- en nadelen. Bijvoorbeeld, bij conversie naar PNG kan er kwaliteitsverlies optreden bij schaalvergroting van het document. Bij conversie naar vector-grafiek kunnen weergave-prestaties van de PDF-viewer worden beïnvloed.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public final float getSufficientResolution()
```

Geeft een waarde terug of stelt een waarde in die de resolutie van afbeeldingen in het PDF-document bepaalt. Lezen/Schrijven float.

Waarde: Het effect van deze parameter hangt af van verschillende factoren. Het algoritme probeert de optimale uitvoerafbeeldingsgrootte te bepalen op basis van de eigenschapswaarde, bron-afbeeldingsgrootte en frame-grootte. Het gebruik van gelijkaardige waardes kan hetzelfde resultaat opleveren. Aanbevolen wordt een stap van 16 of 32 te gebruiken voor een zichtbaar effect.

--------------------

De eigenschap beïnvloedt bestandsgrootte, exporttijd en beeldkwaliteit.

De standaardwaarde is **96**.

**Retourneert:**  
float
### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public final void setSufficientResolution(float value)
```

Geeft een waarde terug of stelt een waarde in die de resolutie van afbeeldingen in het PDF-document bepaalt. Lezen/Schrijven float.

Waarde: Het effect van deze parameter hangt af van verschillende factoren. Het algoritme probeert de optimale uitvoerafbeeldingsgrootte te bepalen op basis van de eigenschapswaarde, bron-afbeeldingsgrootte en frame-grootte. Het gebruik van gelijkaardige waardes kan hetzelfde resultaat opleveren. Aanbevolen wordt een stap van 16 of 32 te gebruiken voor een zichtbaar effect.

--------------------

De eigenschap beïnvloedt bestandsgrootte, exporttijd en beeldkwaliteit.

De standaardwaarde is **96**.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

Waar om een zwart kader rond elke dia te tekenen. Lezen/Schrijven boolean.

--------------------

Standaard is **false**.

**Retourneert:**  
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

Waar om een zwart kader rond elke dia te tekenen. Lezen/Schrijven boolean.

--------------------

Standaard is **false**.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public final Integer getImageTransparentColor()
```

Verkrijgt of stelt de transparante kleur van de afbeelding in.

Waarde: De transparante kleur van de afbeelding.

**Retourneert:**  
java.lang.Integer
### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public final void setImageTransparentColor(Integer value)
```

Verkrijgt of stelt de transparante kleur van de afbeelding in.

Waarde: De transparante kleur van de afbeelding.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.Integer |  |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getIncludeOleData() {#getIncludeOleData--}
```
public final boolean getIncludeOleData()
```

Waar om alle OLE-gegevens uit de presentatie te converteren naar ingesloten bestanden in de resulterende PDF. Lezen/Schrijven boolean.

--------------------

> ```
> Voorbeeld:
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

Standaard is **false**.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
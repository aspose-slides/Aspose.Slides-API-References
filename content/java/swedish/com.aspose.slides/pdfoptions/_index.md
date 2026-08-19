---
title: PdfOptions
second_title: Aspose.Slides för Java API-referens
description: Tillhandahåller alternativ som styr hur en presentation sparas i PDF-format.
type: docs
url: /sv/com.aspose.slides/pdfoptions/
---
**Arv:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IPdfOptions](../../com.aspose.slides/ipdfoptions)
```
public class PdfOptions extends SaveOptions implements IPdfOptions
```

Tillhandahåller alternativ som styr hur en presentation sparas i PDF-format.

--------------------

> ```
> The following example shows how to convert PowerPoint to PDF with custom options.
>  
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Instansierar PdfOptions-klassen
>      PdfOptions pdfOptions = new PdfOptions();
>      // Ställer in Jpeg-kvaliteten
>      pdfOptions.setJpegQuality((byte)90);
>      // Ställer in beteendet för metafiler
>      pdfOptions.setSaveMetafilesAsPng(true);
>      // Ställer in textkomprimeringsnivån
>      pdfOptions.setTextCompression(PdfTextCompression.Flate);
>      // Definierar PDF-standarden
>      pdfOptions.setCompliance(PdfCompliance.Pdf15);
>      // Sparar presentationen som en PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with hidden slides.
>  
>  // Instansierar en Presentation-klass som representerar en PowerPoint-fil
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Instansierar PdfOptions-klassen
>      PdfOptions pdfOptions = new PdfOptions();
>      // Lägger till dolda bilder
>      pdfOptions.setShowHiddenSlides(true);
>      // Sparar presentationen som en PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to password protected PDF.
>  
>  // Instansierar ett Presentation-objekt som representerar en PowerPoint-fil
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Instansierar PdfOptions-klassen
>      PdfOptions pdfOptions = new PdfOptions();
>      // Ställer in PDF-lösenord och åtkomstbehörigheter
>      pdfOptions.setPassword("password");
>      pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>      // Sparar presentationen som en PDF
>      pres.save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with notes.
>  
>  // Instansierar ett Presentation-objekt som representerar en presentationsfil
>  Presentation pres = new Presentation("SelectedSlides.pptx");
>  try {
>      Presentation auxPres = new Presentation();
>      try {
>          ISlide slide = pres.getSlides().get_Item(0);
>          auxPres.getSlides().insertClone(0, slide);
>          // Ställer in bildtyp och storlek
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

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | Standardkonstruktor. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Hämtar eller anger läget där bilder placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Hämtar eller anger läget där bilder placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Tillhandahåller alternativ som styr utseendet på bläckobjekt i exporterade dokument. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. |
| [getTextCompression()](#getTextCompression--) | Anger kompressionstyp som ska användas för allt textinnehåll i dokumentet. |
| [setTextCompression(int value)](#setTextCompression-int-) | Anger kompressionstyp som ska användas för allt textinnehåll i dokumentet. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Indikerar om den mest effektiva kompressionen (istället för standard) för varje bild ska väljas automatiskt. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Indikerar om den mest effektiva kompressionen (istället för standard) för varje bild ska väljas automatiskt. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | Bestämmer om Aspose.Slides kommer att bädda in vanliga teckensnitt för ASCII (33..127 kodområde) text. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | Bestämmer om Aspose.Slides kommer att bädda in vanliga teckensnitt för ASCII (33..127 kodområde) text. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Returnerar eller anger en array av användardefinierade namn på teckensnittsfamiljer som Aspose.Slides bör betrakta som vanliga. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Returnerar eller anger en array av användardefinierade namn på teckensnittsfamiljer som Aspose.Slides bör betrakta som vanliga. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Bestämmer om alla tecken i teckensnittet ska bäddas in eller bara använda en delmängd. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Bestämmer om alla tecken i teckensnittet ska bäddas in eller bara använda en delmängd. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Indikerar om text ska rasteriseras som en bitmap och sparas till PDF när teckensnittet inte stödjer fet stil. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Indikerar om text ska rasteriseras som en bitmap och sparas till PDF när teckensnittet inte stödjer fet stil. |
| [getJpegQuality()](#getJpegQuality--) | Returnerar eller anger ett värde som bestämmer kvaliteten på JPEG-bilder i PDF-dokumentet. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Returnerar eller anger ett värde som bestämmer kvaliteten på JPEG-bilder i PDF-dokumentet. |
| [getCompliance()](#getCompliance--) | Önskad kompatibilitetsnivå för genererat PDF-dokument. |
| [setCompliance(int value)](#setCompliance-int-) | Önskad kompatibilitetsnivå för genererat PDF-dokument. |
| [getPassword()](#getPassword--) | Ställer in användarlösenord för att skydda PDF-dokumentet. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Ställer in användarlösenord för att skydda PDF-dokumentet. |
| [getAccessPermissions()](#getAccessPermissions--) | Innehåller en uppsättning flaggor som specificerar vilka åtkomstbehörigheter som ska beviljas när dokumentet öppnas med användarbehörighet. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Innehåller en uppsättning flaggor som specificerar vilka åtkomstbehörigheter som ska beviljas när dokumentet öppnas med användarbehörighet. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Sant för att konvertera alla metafiler som används i en presentation till PNG-bilder. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Sant för att konvertera alla metafiler som används i en presentation till PNG-bilder. |
| [getSufficientResolution()](#getSufficientResolution--) | Returnerar eller anger ett värde som bestämmer upplösningen för bilder i PDF-dokumentet. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Returnerar eller anger ett värde som bestämmer upplösningen för bilder i PDF-dokumentet. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Sant för att rita en svart ram runt varje bild. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Sant för att rita en svart ram runt varje bild. |
| [getImageTransparentColor()](#getImageTransparentColor--) | Hämtar eller anger bildens transparenta färg. |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | Hämtar eller anger bildens transparenta färg. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Tillämpar den angivna transparenta färgen på en bild om sant. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Tillämpar den angivna transparenta färgen på en bild om sant. |
| [getIncludeOleData()](#getIncludeOleData--) | Sant för att konvertera all OLE-data från presentationen till inbäddade filer i den resulterande PDF. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | Sant för att konvertera all OLE-data från presentationen till inbäddade filer i den resulterande PDF. |

### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```

Standardkonstruktor.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Hämtar eller anger läget där bilder placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**Returnerar:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Hämtar eller anger läget där bilder placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Tillhandahåller alternativ som styr utseendet på bläckobjekt i exporterade dokument. Skrivskyddad [IInkOptions](../../com.aspose.slides/iinkoptions)

**Returnerar:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. Standard är falskt.

**Returnerar:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. Standard är falskt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getTextCompression() {#getTextCompression--}
```
public final int getTextCompression()
```

Anger kompressionstyp som ska användas för allt textinnehåll i dokumentet. Läs/skriv [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Standard är [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Returnerar:**
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public final void setTextCompression(int value)
```

Anger kompressionstyp som ska användas för allt textinnehåll i dokumentet. Läs/skriv [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Standard är [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public final boolean getBestImagesCompressionRatio()
```

Indikerar om den mest effektiva kompressionen (istället för standard) för varje bild ska väljas automatiskt. Om inställd på sant kommer den mest lämpliga komprimeringsalgoritmen att väljas för varje bild i presentationen, vilket leder till en mindre PDF-fil.

--------------------

Val av bästa bildkomprimeringsförhållande är beräkningstungt och kräver extra RAM, och detta alternativ är falskt som standard.

--------------------

Standard är falskt.

**Returnerar:**
boolean
### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public final void setBestImagesCompressionRatio(boolean value)
```

Indikerar om den mest effektiva kompressionen (istället för standard) för varje bild ska väljas automatiskt. Om inställd på sant kommer den mest lämpliga komprimeringsalgoritmen att väljas för varje bild i presentationen, vilket leder till en mindre PDF-fil.

--------------------

Val av bästa bildkomprimeringsförhållande är beräkningstungt och kräver extra RAM, och detta alternativ är falskt som standard.

--------------------

Standard är falskt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public final boolean getEmbedTrueTypeFontsForASCII()
```

Bestämmer om Aspose.Slides kommer att bädda in vanliga teckensnitt för ASCII (33..127 kodområde) text. Teckensnitt för teckenkoder över 127 bäddas alltid in. Listan med vanliga teckensnitt innehåller PDF:s grundläggande 14 teckensnitt samt ytterligare användarspecificerade teckensnitt. Läs/skriv boolean.

--------------------

Standard är **Sant**.

**Returnerar:**
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public final void setEmbedTrueTypeFontsForASCII(boolean value)
```

Bestämmer om Aspose.Slides kommer att bädda in vanliga teckensnitt för ASCII (33..127 kodområde) text. Teckensnitt för teckenkoder över 127 bäddas alltid in. Listan med vanliga teckensnitt innehåller PDF:s grundläggande 14 teckensnitt samt ytterligare användarspecificerade teckensnitt. Läs/skriv boolean.

--------------------

Standard är **Sant**.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public final String[] getAdditionalCommonFontFamilies()
```

Returnerar eller anger en array av användardefinierade namn på teckensnittsfamiljer som Aspose.Slides bör betrakta som vanliga. Läs/skriv String[].

**Returnerar:**
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public final void setAdditionalCommonFontFamilies(String[] value)
```

Returnerar eller anger en array av användardefinierade namn på teckensnittsfamiljer som Aspose.Slides bör betrakta som vanliga. Läs/skriv String[].

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public final boolean getEmbedFullFonts()
```

Bestämmer om alla tecken i teckensnittet ska bäddas in eller bara använda en delmängd. Läs/skriv boolean.

--------------------

Standard är **Falskt**.

**Returnerar:**
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public final void setEmbedFullFonts(boolean value)
```

Bestämmer om alla tecken i teckensnittet ska bäddas in eller bara använda en delmängd. Läs/skriv boolean.

--------------------

Standard är **Falskt**.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public final boolean getRasterizeUnsupportedFontStyles()
```

Indikerar om text ska rasteriseras som en bitmap och sparas till PDF när teckensnittet inte stödjer fet stil. Detta tillvägagångssätt kan förbättra textkvaliteten i den resulterande PDF för vissa teckensnitt. Läs/skriv boolean.

--------------------

Standard är **Falskt**.

**Returnerar:**
boolean
### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public final void setRasterizeUnsupportedFontStyles(boolean value)
```

Indikerar om text ska rasteriseras som en bitmap och sparas till PDF när teckensnittet inte stödjer fet stil. Detta tillvägagångssätt kan förbättra textkvaliteten i den resulterande PDF för vissa teckensnitt. Läs/skriv boolean.

--------------------

Standard är **Falskt**.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

Returnerar eller anger ett värde som bestämmer kvaliteten på JPEG-bilder i PDF-dokumentet. Läs/skriv byte.

--------------------

Har effekt endast när ett dokument innehåller JPEG-bilder.

Använd denna egenskap för att hämta eller ange kvaliteten på bilderna i ett dokument vid sparande i PDF-format. Värdet kan variera från 0 till 100 där 0 betyder sämst kvalitet men maximal kompression och 100 betyder bästa kvalitet men minimal kompression.

Standardvärdet är **100**.

**Returnerar:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

Returnerar eller anger ett värde som bestämmer kvaliteten på JPEG-bilder i PDF-dokumentet. Läs/skriv byte.

--------------------

Har effekt endast när ett dokument innehåller JPEG-bilder.

Använd denna egenskap för att hämta eller ange kvaliteten på bilderna i ett dokument vid sparande i PDF-format. Värdet kan variera från 0 till 100 där 0 betyder sämst kvalitet men maximal kompression och 100 betyder bästa kvalitet men minimal kompression.

Standardvärdet är **100**.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```

Önskad kompatibilitetsnivå för genererat PDF-dokument. Läs/skriv [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Standard är [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Returnerar:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```

Önskad kompatibilitetsnivå för genererat PDF-dokument. Läs/skriv [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Standard är [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

Ställer in användarlösenord för att skydda PDF-dokumentet. Läs/skriv String.

**Returnerar:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

Ställer in användarlösenord för att skydda PDF-dokumentet. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public final int getAccessPermissions()
```

Innehåller en uppsättning flaggor som specificerar vilka åtkomstbehörigheter som ska beviljas när dokumentet öppnas med användarbehörighet. Se [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

**Returnerar:**
int
### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public final void setAccessPermissions(int value)
```

Innehåller en uppsättning flaggor som specificerar vilka åtkomstbehörigheter som ska beviljas när dokumentet öppnas med användarbehörighet. Se [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

Sant för att konvertera alla metafiler som används i en presentation till PNG-bilder. Läs/skriv boolean.

--------------------

Standard är **Sant**. PDF-dokument kan innehålla vektorgrafik och rasterbilder. Om SaveMetafilesAsPng är sant konverteras källmetafilen till PNG-format och sparas i PDF som en rasterbild. Om SaveMetafilesAsPng är falskt konverteras källmetafilen till PDF-vektorgrafik. Båda tillvägagångssätten har för- och nackdelar. Till exempel kan konvertering till PNG medföra viss kvalitetsförlust vid skalning av det resulterande dokumentet. Konvertering till PDF-vektorgrafik kan leda till prestandaproblem i PDF-visningsprogram.

**Returnerar:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

Sant för att konvertera alla metafiler som används i en presentation till PNG-bilder. Läs/skriv boolean.

--------------------

Standard är **Sant**. PDF-dokument kan innehålla vektorgrafik och rasterbilder. Om SaveMetafilesAsPng är sant konverteras källmetafilen till PNG-format och sparas i PDF som en rasterbild. Om SaveMetafilesAsPng är falskt konverteras källmetafilen till PDF-vektorgrafik. Båda tillvägagångssätten har för- och nackdelar. Till exempel kan konvertering till PNG medföra viss kvalitetsförlust vid skalning av det resulterande dokumentet. Konvertering till PDF-vektorgrafik kan leda till prestandaproblem i PDF-visningsprogram.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public final float getSufficientResolution()
```

Returnerar eller anger ett värde som bestämmer upplösningen för bilder i PDF-dokumentet. Läs/skriv float.

Värde: Effekten av denna parameter beror på flera faktorer. Algoritmen försöker finna optimal bildstorlek baserat på egenskapsvärdet, källbildens storlek och bildramens storlek. Användning av liknande värden kan ge samma resultat. Rekommenderas att använda steg 16 eller 32 för att se en märkbar effekt.

--------------------

Egenskapen påverkar filstorlek, exporttid och bildkvalitet.

Standardvärdet är **96**.

**Returnerar:**
float
### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public final void setSufficientResolution(float value)
```

Returnerar eller anger ett värde som bestämmer upplösningen för bilder i PDF-dokumentet. Läs/skriv float.

Värde: Effekten av denna parameter beror på flera faktorer. Algoritmen försöker finna optimal bildstorlek baserat på egenskapsvärdet, källbildens storlek och bildramens storlek. Användning av liknande värden kan ge samma resultat. Rekommenderas att använda steg 16 eller 32 för att se en märkbar effekt.

--------------------

Egenskapen påverkar filstorlek, exporttid och bildkvalitet.

Standardvärdet är **96**.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

Sant för att rita en svart ram runt varje bild. Läs/skriv boolean.

--------------------

Standard är **Falskt**.

**Returnerar:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

Sant för att rita en svart ram runt varje bild. Läs/skriv boolean.

--------------------

Standard är **Falskt**.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public final Color getImageTransparentColor()
```

Hämtar eller anger bildens transparenta färg.

Värde: Den transparenta färgen för bilden.

**Returnerar:**
java.awt.Color
### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public final void setImageTransparentColor(Color value)
```

Hämtar eller anger bildens transparenta färg.

Värde: Den transparenta färgen för bilden.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public final boolean getApplyImageTransparent()
```

Tillämpar den angivna transparenta färgen på en bild om sant.

**Returnerar:**
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public final void setApplyImageTransparent(boolean value)
```

Tillämpar den angivna transparenta färgen på en bild om sant.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getIncludeOleData() {#getIncludeOleData--}
```
public final boolean getIncludeOleData()
```

Sant för att konvertera all OLE-data från presentationen till inbäddade filer i den resulterande PDF. Läs/skriv  boolean .

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

Standard är **Falskt**.

**Returnerar:**
boolean
### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public final void setIncludeOleData(boolean value)
```

Sant för att konvertera all OLE-data från presentationen till inbäddade filer i den resulterande PDF. Läs/skriv  boolean .

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

Standard är **Falskt**.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
---
title: IPdfOptions
second_title: Aspose.Slides för Android via Java API-referens
description: Tillhandahåller alternativ som styr hur en presentation sparas i PDF-format.
type: docs
url: /sv/com.aspose.slides/ipdfoptions/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPdfOptions extends ISaveOptions
```

Tillhandahåller alternativ som styr hur en presentation sparas i PDF-format.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getTextCompression()](#getTextCompression--) | Anger kompressionstyp som ska användas för allt textinnehåll i dokumentet. |
| [setTextCompression(int value)](#setTextCompression-int-) | Anger kompressionstyp som ska användas för allt textinnehåll i dokumentet. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Indikerar om den mest effektiva kompressionen (istället för standard) för varje bild ska väljas automatiskt. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Indikerar om den mest effektiva kompressionen (istället för standard) för varje bild ska väljas automatiskt. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | Sant för att bädda in TrueType-teckensnitt för ASCII-tecken 32-127. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | Sant för att bädda in TrueType-teckensnitt för ASCII-tecken 32-127. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Returnerar eller anger en array av användardefinierade namn på teckensnittsfamiljer som Aspose.Slides ska betrakta som gemensamma. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Returnerar eller anger en array av användardefinierade namn på teckensnittsfamiljer som Aspose.Slides ska betrakta som gemensamma. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Bestämmer om alla teckensnittskaraktärer ska bäddas in eller endast en delmängd bör användas. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Bestämmer om alla teckensnittskaraktärer ska bäddas in eller endast en delmängd bör användas. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Indikerar om text ska rasteriseras som en bitmap och sparas till PDF när teckensnittet inte stöder fet stil. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Indikerar om text ska rasteriseras som en bitmap och sparas till PDF när teckensnittet inte stöder fet stil. |
| [getJpegQuality()](#getJpegQuality--) | Returnerar eller anger ett värde som bestämmer kvaliteten på JPEG-bilderna i PDF-dokumentet. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Returnerar eller anger ett värde som bestämmer kvaliteten på JPEG-bilderna i PDF-dokumentet. |
| [getCompliance()](#getCompliance--) | Önskad efterlevnadsnivå för genererat PDF-dokument. |
| [setCompliance(int value)](#setCompliance-int-) | Önskad efterlevnadsnivå för genererat PDF-dokument. |
| [getPassword()](#getPassword--) | Ställer in användarlösenord för att skydda PDF-dokumentet. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Ställer in användarlösenord för att skydda PDF-dokumentet. |
| [getAccessPermissions()](#getAccessPermissions--) | Innehåller en uppsättning flaggor som specificerar vilka åtkomstbehörigheter som ska beviljas när dokumentet öppnas med användaråtkomst. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Innehåller en uppsättning flaggor som specificerar vilka åtkomstbehörigheter som ska beviljas när dokumentet öppnas med användaråtkomst. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Sant för att konvertera alla metafiler som används i en presentation till PNG-bilder. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Sant för att konvertera alla metafiler som används i en presentation till PNG-bilder. |
| [getSufficientResolution()](#getSufficientResolution--) | Returnerar eller anger ett värde som bestämmer upplösningen på bilder i PDF-dokumentet. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Returnerar eller anger ett värde som bestämmer upplösningen på bilder i PDF-dokumentet. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Sant för att rita en svart ram runt varje bild. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Sant för att rita en svart ram runt varje bild. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Hämtar eller anger läget där bilder placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Hämtar eller anger läget där bilder placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getImageTransparentColor()](#getImageTransparentColor--) | Hämtar eller anger bildens transparenta färg. |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | Hämtar eller anger bildens transparenta färg. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Tillämpar den angivna transparenta färgen på en bild om sant. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Tillämpar den angivna transparenta färgen på en bild om sant. |
| [getInkOptions()](#getInkOptions--) | Tillhandahåller alternativ som styr utseendet på Ink-objekt i exporterade dokument. |
| [getIncludeOleData()](#getIncludeOleData--) | Sant för att konvertera all OLE-data från presentationen till inbäddade filer i den resulterande PDF. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | Sant för att konvertera all OLE-data från presentationen till inbäddade filer i den resulterande PDF. |

### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```

Anger kompressionstyp som ska användas för allt textinnehåll i dokumentet. Läs/skriv [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Standardvärdet är [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Returnerar:**
int

### setTextCompression(int value) {#setTextCompression-int-}
```
public abstract void setTextCompression(int value)
```

Anger kompressionstyp som ska användas för allt textinnehåll i dokumentet. Läs/skriv [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Standardvärdet är [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public abstract boolean getBestImagesCompressionRatio()
```

Indikerar om den mest effektiva kompressionen (istället för standard) för varje bild ska väljas automatiskt. Om sant kommer den mest lämpliga komprimeringsalgoritmen att väljas för varje bild i presentationen, vilket leder till en mindre PDF-fil.

--------------------

Valet av bästa bildkompressionsförhållande är beräkningsmässigt krävande och förbrukar extra RAM, och detta alternativ är falskt som standard.

--------------------

Standardvärdet är false.

**Returnerar:**
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```

Indikerar om den mest effektiva kompressionen (istället för standard) för varje bild ska väljas automatiskt. Om sant kommer den mest lämpliga komprimeringsalgoritmen att väljas för varje bild i presentationen, vilket leder till en mindre PDF-fil.

--------------------

Valet av bästa bildkompressionsförhållande är beräkningsmässigt krävande och förbrukar extra RAM, och detta alternativ är falskt som standard.

--------------------

Standardvärdet är false.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public abstract boolean getEmbedTrueTypeFontsForASCII()
```

Sant för att bädda in TrueType-teckensnitt för ASCII-tecken 32-127. Teckensnitt för teckenkoder större än 127 är alltid inbäddade. Läs/skriv boolean.

--------------------

Standardvärdet är **true**.

**Returnerar:**
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```

Sant för att bädda in TrueType-teckensnitt för ASCII-tecken 32-127. Teckensnitt för teckenkoder större än 127 är alltid inbäddade. Läs/skriv boolean.

--------------------

Standardvärdet är **true**.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. Standardvärdet är false.

**Returnerar:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. Standardvärdet är false.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public abstract String[] getAdditionalCommonFontFamilies()
```

Returnerar eller anger en array av användardefinierade namn på teckensnittsfamiljer som Aspose.Slides ska betrakta som gemensamma. Läs/skriv String[].

**Returnerar:**
java.lang.String[]

### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```

Returnerar eller anger en array av användardefinierade namn på teckensnittsfamiljer som Aspose.Slides ska betrakta som gemensamma. Läs/skriv String[].

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```

Bestämmer om alla teckensnittskaraktärer ska bäddas in eller endast en delmängd bör användas. Läs/skriv boolean.

--------------------

Standardvärdet är **false**.

**Returnerar:**
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```

Bestämmer om alla teckensnittskaraktärer ska bäddas in eller endast en delmängd bör användas. Läs/skriv boolean.

--------------------

Standardvärdet är **false**.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public abstract boolean getRasterizeUnsupportedFontStyles()
```

Indikerar om text ska rasteriseras som en bitmap och sparas till PDF när teckensnittet inte stöder fet stil. Detta kan förbättra textkvaliteten i den resulterande PDF för vissa teckensnitt. Läs/skriv boolean.

--------------------

Standardvärdet är **false**.

**Returnerar:**
boolean

### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public abstract void setRasterizeUnsupportedFontStyles(boolean value)
```

Indikerar om text ska rasteriseras som en bitmap och sparas till PDF när teckensnittet inte stöder fet stil. Detta kan förbättra textkvaliteten i den resulterande PDF för vissa teckensnitt. Läs/skriv boolean.

--------------------

Standardvärdet är **false**.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

Returnerar eller anger ett värde som bestämmer kvaliteten på JPEG-bilderna i PDF-dokumentet. Läs/skriv byte.

--------------------

Har effekt endast när ett dokument innehåller JPEG-bilder.

Använd denna egendom för att få eller sätta kvaliteten på bilderna i ett dokument vid sparande i PDF-format. Värdet kan variera från 0 till 100 där 0 betyder sämst kvalitet men maximal kompression och 100 betyder bästa kvalitet men minimal kompression.

Standardvärdet är **100**.

**Returnerar:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

Returnerar eller anger ett värde som bestämmer kvaliteten på JPEG-bilderna i PDF-dokumentet. Läs/skriv byte.

--------------------

Har effekt endast när ett dokument innehåller JPEG-bilder.

Använd denna egendom för att få eller sätta kvaliteten på bilderna i ett dokument vid sparande i PDF-format. Värdet kan variera från 0 till 100 där 0 betyder sämst kvalitet men maximal kompression och 100 betyder bästa kvalitet men minimal kompression.

Standardvärdet är **100**.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public abstract int getCompliance()
```

Önskad efterlevnadsnivå för genererat PDF-dokument. Läs/skriv [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Standardvärdet är [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Returnerar:**
int

### setCompliance(int value) {#setCompliance-int-}
```
public abstract void setCompliance(int value)
```

Önskad efterlevnadsnivå för genererat PDF-dokument. Läs/skriv [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Standardvärdet är [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

Ställer in användarlösenord för att skydda PDF-dokumentet. Läs/skriv String.

**Returnerar:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

Ställer in användarlösenord för att skydda PDF-dokumentet. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public abstract int getAccessPermissions()
```

Innehåller en uppsättning flaggor som specificerar vilka åtkomstbehörigheter som ska beviljas när dokumentet öppnas med användaråtkomst. Se [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
public abstract void setAccessPermissions(int value)
```

Innehåller en uppsättning flaggor som specificerar vilka åtkomstbehörigheter som ska beviljas när dokumentet öppnas med användaråtkomst. Se [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
public abstract boolean getSaveMetafilesAsPng()
```

Sant för att konvertera alla metafiler som används i en presentation till PNG-bilder. Läs/skriv boolean.

--------------------

Standardvärdet är **true**. Pdf-dokument kan innehålla vektorgrafik och rasterbilder. Om SaveMetafilesAsPng är true konverteras käll-Metafile-bilden till PNG-format och sparas i Pdf som en rasterbild. Om SaveMetafilesAsPng är false konverteras käll-Metafile till Pdf-vektorgrafik. Båda tillvägagångssätten har för- och nackdelar. Till exempel kan konvertering till PNG leda till viss kvalitetsförlust vid skalning av det resulterande dokumentet. Om Metafile konverteras till Pdf-vektorgrafik kan prestandaproblem i Pdf-visningsverktyg uppstå.

**Returnerar:**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

Sant för att konvertera alla metafiler som används i en presentation till PNG-bilder. Läs/skriv boolean.

--------------------

Standardvärdet är **true**. Pdf-dokument kan innehålla vektorgrafik och rasterbilder. Om SaveMetafilesAsPng är true konverteras käll-Metafile-bilden till PNG-format och sparas i Pdf som en rasterbild. Om SaveMetafilesAsPng är false konverteras käll-Metafile till Pdf-vektorgrafik. Båda tillvägagångssätten har för- och nackdelar. Till exempel kan konvertering till PNG leda till viss kvalitetsförlust vid skalning av det resulterande dokumentet. Om Metafile konverteras till Pdf-vektorgrafik kan prestandaproblem i Pdf-visningsverktyg uppstå.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```

Returnerar eller anger ett värde som bestämmer upplösningen på bilder i PDF-dokumentet. Läs/skriv float.

Värde: Effekten av denna parameter beror på några faktorer. Algoritmen försöker få bästa möjliga bildstorlek utifrån egenskapsvärdet, källbildens storlek och bildramens storlek. Användning av liknande egenskapsvärden kan ge samma resultat. Rekommenderas att använda steg 16 eller 32 för att se en märkbar effekt.

--------------------

Egenskapen påverkar filstorlek, exporttid och bildkvalitet.

Standardvärdet är **96**.

**Returnerar:**
float

### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```

Returnerar eller anger ett värde som bestämmer upplösningen på bilder i PDF-dokumentet. Läs/skriv float.

Värde: Effekten av denna parameter beror på några faktorer. Algoritmen försöker få bästa möjliga bildstorlek utifrån egenskapsvärdet, källbildens storlek och bildramens storlek. Användning av liknande egenskapsvärden kan ge samma resultat. Rekommenderas att använda steg 16 eller 32 för att se en märkbar effekt.

--------------------

Egenskapen påverkar filstorlek, exporttid och bildkvalitet.

Standardvärdet är **96**.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

Sant för att rita en svart ram runt varje bild. Läs/skriv boolean.

--------------------

Standardvärdet är **false**.

**Returnerar:**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

Sant för att rita en svart ram runt varje bild. Läs/skriv boolean.

--------------------

Standardvärdet är **false**.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
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

### getImageTransparentColor() {#getImageTransparentColor--}
```
public abstract Integer getImageTransparentColor()
```

Hämtar eller anger bildens transparenta färg.

Värde: Bildens transparenta färg.

**Returnerar:**
java.lang.Integer

### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public abstract void setImageTransparentColor(Integer value)
```

Hämtar eller anger bildens transparenta färg.

Värde: Bildens transparenta färg.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public abstract boolean getApplyImageTransparent()
```

Tillämpar den angivna transparenta färgen på en bild om sant.

**Returnerar:**
boolean

### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public abstract void setApplyImageTransparent(boolean value)
```

Tillämpar den angivna transparenta färgen på en bild om sant.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Tillhandahåller alternativ som styr utseendet på Ink-objekt i exporterade dokument. Endast läsning [IInkOptions](../../com.aspose.slides/iinkoptions)

**Returnerar:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getIncludeOleData() {#getIncludeOleData--}
```
public abstract boolean getIncludeOleData()
```

Sant för att konvertera all OLE-data från presentationen till inbäddade filer i den resulterande PDF. Läs/skriv boolean.

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

Standardvärdet är **false**.

**Returnerar:**
boolean

### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public abstract void setIncludeOleData(boolean value)
```

Sant för att konvertera all OLE-data från presentationen till inbäddade filer i den resulterande PDF. Läs/skriv boolean.

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

Standardvärdet är **false**.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
---
title: PdfOptions
second_title: Aspose.Slides pro Java API Reference
description: Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu PDF.
type: docs
url: /cs/com.aspose.slides/pdfoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**All Implemented Interfaces:**
[com.aspose.slides.IPdfOptions](../../com.aspose.slides/ipdfoptions)
```
public class PdfOptions extends SaveOptions implements IPdfOptions
```

Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu PDF.

--------------------

> ```
> The following example shows how to convert PowerPoint to PDF with custom options.
>  
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Vytvoří instanci třídy PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // Nastaví kvalitu JPEG
>      pdfOptions.setJpegQuality((byte)90);
>      // Nastaví chování pro metafily
>      pdfOptions.setSaveMetafilesAsPng(true);
>      // Nastaví úroveň komprese textu
>      pdfOptions.setTextCompression(PdfTextCompression.Flate);
>      // Definuje standard PDF
>      pdfOptions.setCompliance(PdfCompliance.Pdf15);
>      // Uloží prezentaci jako PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with hidden slides.
>  
>  // Vytvoří instanci třídy Presentation, která představuje soubor PowerPoint
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Vytvoří instanci třídy PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // Přidá skryté snímky
>      pdfOptions.setShowHiddenSlides(true);
>      // Uloží prezentaci jako PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to password protected PDF.
>  
>  // Vytvoří instanci objektu Presentation, který představuje soubor PowerPoint
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Vytvoří instanci třídy PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // Nastaví heslo PDF a přístupová oprávnění
>      pdfOptions.setPassword("password");
>      pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>      // Uloží prezentaci jako PDF
>      pres.save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with notes.
>  
>  // Vytvoří instanci objektu Presentation, který představuje soubor prezentace
>  Presentation pres = new Presentation("SelectedSlides.pptx");
>  try {
>      Presentation auxPres = new Presentation();
>      try {
>          ISlide slide = pres.getSlides().get_Item(0);
>          auxPres.getSlides().insertClone(0, slide);
>          // Nastavování typu a velikosti snímku
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

## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | Výchozí konstruktor. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Získává nebo nastavuje režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Získává nebo nastavuje režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Poskytuje možnosti, které řídí vzhled objektů Ink v exportovaném dokumentu. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Určuje, zda má vygenerovaný dokument zahrnovat skryté snímky, nebo ne. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Určuje, zda má vygenerovaný dokument zahrnovat skryté snímky, nebo ne. |
| [getTextCompression()](#getTextCompression--) | Určuje typ komprese, který se použije pro veškerý textový obsah v dokumentu. |
| [setTextCompression(int value)](#setTextCompression-int-) | Určuje typ komprese, který se použije pro veškerý textový obsah v dokumentu. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Indikuje, zda má být pro každý obrázek automaticky vybrána nejúčinnější komprese (místo výchozí). |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Indikuje, zda má být pro každý obrázek automaticky vybrána nejúčinnější komprese (místo výchozí). |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | Určuje, zda Aspose.Slides vloží běžné fonty pro ASCII (rozsah kódů 33..127) text. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | Určuje, zda Aspose.Slides vloží běžné fonty pro ASCII (rozsah kódů 33..127) text. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Vrací nebo nastavuje pole uživatelem definovaných názvů rodin písem, které by měly být Aspose.Slides považovány za běžné. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Vrací nebo nastavuje pole uživatelem definovaných názvů rodin písem, které by měly být Aspose.Slides považovány za běžné. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Určuje, zda mají být vloženy všechny znaky fontu, nebo pouze použita podmnožina. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Určuje, zda mají být vloženy všechny znaky fontu, nebo pouze použita podmnožina. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Indikuje, zda by měl být text rasterizován jako bitmapa a uložen do PDF, když font nepodporuje tučné písmo. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Indikuje, zda by měl být text rasterizován jako bitmapa a uložen do PDF, když font nepodporuje tučné písmo. |
| [getJpegQuality()](#getJpegQuality--) | Vrací nebo nastavuje hodnotu určující kvalitu JPEG obrázků v PDF dokumentu. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Vrací nebo nastavuje hodnotu určující kvalitu JPEG obrázků v PDF dokumentu. |
| [getCompliance()](#getCompliance--) | Požadovaná úroveň souladu pro generovaný PDF dokument. |
| [setCompliance(int value)](#setCompliance-int-) | Požadovaná úroveň souladu pro generovaný PDF dokument. |
| [getPassword()](#getPassword--) | Nastavení uživatelského hesla pro ochranu PDF dokumentu. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Nastavení uživatelského hesla pro ochranu PDF dokumentu. |
| [getAccessPermissions()](#getAccessPermissions--) | Obsahuje sadu příznaků určujících, která přístupová oprávnění mají být při otevření dokumentu s uživatelským přístupem poskytnuta. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Obsahuje sadu příznaků určujících, která přístupová oprávnění mají být při otevření dokumentu s uživatelským přístupem poskytnuta. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True, pokud se mají všechny metafily použité v prezentaci převést na PNG obrázky. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True, pokud se mají všechny metafily použité v prezentaci převést na PNG obrázky. |
| [getSufficientResolution()](#getSufficientResolution--) | Vrací nebo nastavuje hodnotu určující rozlišení obrázků v PDF dokumentu. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Vrací nebo nastavuje hodnotu určující rozlišení obrázků v PDF dokumentu. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True, pokud má být kolem každého snímku nakreslen černý rámeček. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True, pokud má být kolem každého snímku nakreslen černý rámeček. |
| [getImageTransparentColor()](#getImageTransparentColor--) | Získává nebo nastavuje transparentní barvu obrázku. |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | Získává nebo nastavuje transparentní barvu obrázku. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Aplikuje určenou transparentní barvu na obrázek, pokud je true. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Aplikuje určenou transparentní barvu na obrázek, pokud je true. |
| [getIncludeOleData()](#getIncludeOleData--) | True, pokud má být všechna data OLE z prezentace převedena na vložené soubory v výsledném PDF. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | True, pokud má být všechna data OLE z prezentace převedena na vložené soubory v výsledném PDF. |

### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```

Výchozí konstruktor.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Získává nebo nastavuje režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**Vrací:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Získává nebo nastavuje režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Poskytuje možnosti, které řídí vzhled objektů Ink v exportovaném dokumentu. Pouze pro čtení [IInkOptions](../../com.aspose.slides/iinkoptions)

**Vrací:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Určuje, zda má vygenerovaný dokument zahrnovat skryté snímky, nebo ne. Výchozí hodnota je false.

**Vrací:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Určuje, zda má vygenerovaný dokument zahrnovat skryté snímky, nebo ne. Výchozí hodnota je false.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getTextCompression() {#getTextCompression--}
```
public final int getTextCompression()
```

Určuje typ komprese, který se použije pro veškerý textový obsah v dokumentu. Čtení/zápis [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Výchozí hodnota je [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Vrací:**
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public final void setTextCompression(int value)
```

Určuje typ komprese, který se použije pro veškerý textový obsah v dokumentu. Čtení/zápis [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Výchozí hodnota je [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public final boolean getBestImagesCompressionRatio()
```

Indikuje, zda má být pro každý obrázek automaticky vybrána nejúčinnější komprese (místo výchozí). Pokud je nastaveno na true, pro každý obrázek v prezentaci bude vybrán nejvhodnější kompresní algoritmus, což povede k menší velikosti výsledného PDF dokumentu.

--------------------

Výběr nejlepšího kompresního poměru je výpočetně náročný a vyžaduje další množství RAM; výchozí hodnota je false.

--------------------

Výchozí hodnota je false.

**Vrací:**
boolean
### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public final void setBestImagesCompressionRatio(boolean value)
```

Indikuje, zda má být pro každý obrázek automaticky vybrána nejúčinnější komprese (místo výchozí). Pokud je nastaveno na true, pro každý obrázek v prezentaci bude vybrán nejvhodnější kompresní algoritmus, což povede k menší velikosti výsledného PDF dokumentu.

--------------------

Výběr nejlepšího kompresního poměru je výpočetně náročný a vyžaduje další množství RAM; výchozí hodnota je false.

--------------------

Výchozí hodnota je false.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public final boolean getEmbedTrueTypeFontsForASCII()
```

Určuje, zda Aspose.Slides vloží běžné fonty pro ASCII (rozsah kódů 33..127) text. Fonty pro kódy vyšší než 127 jsou vždy vloženy. Seznam běžných fontů zahrnuje základních 14 fontů PDF a další uživatelem určené fonty. Čtení/zápis boolean.

--------------------

Výchozí hodnota je **true**.

**Vrací:**
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public final void setEmbedTrueTypeFontsForASCII(boolean value)
```

Určuje, zda Aspose.Slides vloží běžné fonty pro ASCII (rozsah kódů 33..127) text. Fonty pro kódy vyšší než 127 jsou vždy vloženy. Seznam běžných fontů zahrnuje základních 14 fontů PDF a další uživatelem určené fonty. Čtení/zápis boolean.

--------------------

Výchozí hodnota je **true**.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public final String[] getAdditionalCommonFontFamilies()
```

Vrací nebo nastavuje pole uživatelem definovaných názvů rodin písem, které by měly být Aspose.Slides považovány za běžné. Čtení/zápis String[].

**Vrací:**
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public final void setAdditionalCommonFontFamilies(String[] value)
```

Vrací nebo nastavuje pole uživatelem definovaných názvů rodin písem, které by měly být Aspose.Slides považovány za běžné. Čtení/zápis String[].

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public final boolean getEmbedFullFonts()
```

Určuje, zda mají být vloženy všechny znaky fontu, nebo pouze použita podmnožina. Čtení/zápis boolean.

--------------------

Výchozí hodnota je **false**.

**Vrací:**
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public final void setEmbedFullFonts(boolean value)
```

Určuje, zda mají být vloženy všechny znaky fontu, nebo pouze použita podmnožina. Čtení/zápis boolean.

--------------------

Výchozí hodnota je **false**.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public final boolean getRasterizeUnsupportedFontStyles()
```

Indikuje, zda by měl být text rasterizován jako bitmapa a uložen do PDF, když font nepodporuje tučné písmo. Tento přístup může zlepšit kvalitu textu v výsledném PDF u některých fontů. Čtení/zápis boolean.

--------------------

Výchozí hodnota je **false**.

**Vrací:**
boolean
### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public final void setRasterizeUnsupportedFontStyles(boolean value)
```

Indikuje, zda by měl být text rasterizován jako bitmapa a uložen do PDF, když font nepodporuje tučné písmo. Tento přístup může zlepšit kvalitu textu v výsledném PDF u některých fontů. Čtení/zápis boolean.

--------------------

Výchozí hodnota je **false**.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

Vrací nebo nastavuje hodnotu určující kvalitu JPEG obrázků v PDF dokumentu. Čtení/zápis byte.

--------------------

Má vliv pouze, pokud dokument obsahuje JPEG obrázky.

Použijte tuto vlastnost pro získání nebo nastavení kvality obrázků v dokumentu při ukládání ve formátu PDF. Hodnota může být od 0 do 100, kde 0 znamená nejhorší kvalitu s maximální kompresí a 100 nejlepší kvalitu s minimální kompresí.

Výchozí hodnota je **100**.

**Vrací:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

Vrací nebo nastavuje hodnotu určující kvalitu JPEG obrázků v PDF dokumentu. Čtení/zápis byte.

--------------------

Má vliv pouze, pokud dokument obsahuje JPEG obrázky.

Použijte tuto vlastnost pro získání nebo nastavení kvality obrázků v dokumentu při ukládání ve formátu PDF. Hodnota může být od 0 do 100, kde 0 znamená nejhorší kvalitu s maximální kompresí a 100 nejlepší kvalitu s minimální kompresí.

Výchozí hodnota je **100**.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```

Požadovaná úroveň souladu pro generovaný PDF dokument. Čtení/zápis [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Výchozí hodnota je [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Vrací:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```

Požadovaná úroveň souladu pro generovaný PDF dokument. Čtení/zápis [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Výchozí hodnota je [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

Nastavení uživatelského hesla pro ochranu PDF dokumentu. Čtení/zápis String.

**Vrací:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

Nastavení uživatelského hesla pro ochranu PDF dokumentu. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public final int getAccessPermissions()
```

Obsahuje sadu příznaků určujících, která přístupová oprávnění mají být při otevření dokumentu s uživatelským přístupem poskytnuta. Viz [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

**Vrací:**
int
### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public final void setAccessPermissions(int value)
```

Obsahuje sadu příznaků určujících, která přístupová oprávnění mají být při otevření dokumentu s uživatelským přístupem poskytnuta. Viz [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

True, pokud se mají všechny metafily použité v prezentaci převést na PNG obrázky. Čtení/zápis boolean.

--------------------

Výchozí hodnota je **true**. PDF dokument může obsahovat vektorovou grafiku i rastrové obrázky. Pokud je SaveMetafilesAsPng nastaveno na true, zdrojový metafile je převeden do formátu PNG a uložen do PDF jako rastrový obrázek. Pokud je nastaveno na false, zdrojový metafile je převeden na vektorovou grafiku PDF. Každý přístup má výhody i nevýhody. Například při převodu na PNG může dojít ke ztrátě kvality při škálování výsledného dokumentu. Při převodu na vektorovou grafiku PDF mohou nastat výkonnostní problémy při prohlížení PDF.

**Vrací:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

True, pokud se mají všechny metafily použité v prezentaci převést na PNG obrázky. Čtení/zápis boolean.

--------------------

Výchozí hodnota je **true**. PDF dokument může obsahovat vektorovou grafiku i rastrové obrázky. Pokud je SaveMetafilesAsPng nastaveno na true, zdrojový metafile je převeden do formátu PNG a uložen do PDF jako rastrový obrázek. Pokud je nastaveno na false, zdrojový metafile je převeden na vektorovou grafiku PDF. Každý přístup má výhody i nevýhody. Například při převodu na PNG může dojít ke ztrátě kvality při škálování výsledného dokumentu. Při převodu na vektorovou grafiku PDF mohou nastat výkonnostní problémy při prohlížení PDF.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public final float getSufficientResolution()
```

Vrací nebo nastavuje hodnotu určující rozlišení obrázků v PDF dokumentu. Čtení/zápis float.

Hodnota: Efekt tohoto parametru závisí na několika faktorech. Algoritmus se snaží získat nejlepší velikost výstupního obrázku podle hodnoty vlastnosti, velikosti zdrojového obrázku a velikosti rámce obrázku. Použití podobných hodnot může dát stejný výsledek. Doporučuje se krok 16 nebo 32 pro patrný efekt.

--------------------

Vlastnost ovlivňuje velikost souboru, dobu exportu a kvalitu obrázku.

Výchozí hodnota je **96**.

**Vrací:**
float
### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public final void setSufficientResolution(float value)
```

Vrací nebo nastavuje hodnotu určující rozlišení obrázků v PDF dokumentu. Čtení/zápis float.

Hodnota: Efekt tohoto parametru závisí na několika faktorech. Algoritmus se snaží získat nejlepší velikost výstupního obrázku podle hodnoty vlastnosti, velikosti zdrojového obrázku a velikosti rámce obrázku. Použití podobných hodnot může dát stejný výsledek. Doporučuje se krok 16 nebo 32 pro patrný efekt.

--------------------

Vlastnost ovlivňuje velikost souboru, dobu exportu a kvalitu obrázku.

Výchozí hodnota je **96**.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

True, pokud má být kolem každého snímku nakreslen černý rámeček. Čtení/zápis boolean.

--------------------

Výchozí hodnota je **false**.

**Vrací:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

True, pokud má být kolem každého snímku nakreslen černý rámeček. Čtení/zápis boolean.

--------------------

Výchozí hodnota je **false**.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public final Color getImageTransparentColor()
```

Získává nebo nastavuje transparentní barvu obrázku.

Hodnota: Transparentní barva obrázku.

**Vrací:**
java.awt.Color
### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public final void setImageTransparentColor(Color value)
```

Získává nebo nastavuje transparentní barvu obrázku.

Hodnota: Transparentní barvu obrázku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public final boolean getApplyImageTransparent()
```

Aplikuje určenou transparentní barvu na obrázek, pokud je true.

**Vrací:**
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public final void setApplyImageTransparent(boolean value)
```

Aplikuje určenou transparentní barvu na obrázek, pokud je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getIncludeOleData() {#getIncludeOleData--}
```
public final boolean getIncludeOleData()
```

True, pokud má být všechna data OLE z prezentace převedena na vložené soubory v výsledném PDF. Čtení/zápis boolean.

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

Výchozí hodnota je **false**.

**Vrací:**
boolean
### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public final void setIncludeOleData(boolean value)
```

True, pokud má být všechna data OLE z prezentace převedena na vložené soubory v výsledném PDF. Čtení/zápis boolean.

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

Výchozí hodnota je **false**.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
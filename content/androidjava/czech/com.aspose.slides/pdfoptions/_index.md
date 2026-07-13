---
title: PdfOptions
second_title: Aspose.Slides pro Android prostřednictvím Java API
description: Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu Pdf.
type: docs
url: /cs/com.aspose.slides/pdfoptions/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IPdfOptions](../../com.aspose.slides/ipdfoptions)
```
public class PdfOptions extends SaveOptions implements IPdfOptions
```

Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu Pdf.

--------------------

> ```
> The following example shows how to convert PowerPoint to PDF with custom options.
>  
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Instancuje třídu PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // Nastavuje kvalitu JPEG
>      pdfOptions.setJpegQuality((byte)90);
>      // Nastavuje chování metafiles
>      pdfOptions.setSaveMetafilesAsPng(true);
>      // Nastavuje úroveň komprese textu
>      pdfOptions.setTextCompression(PdfTextCompression.Flate);
>      // Definuje standard PDF
>      pdfOptions.setCompliance(PdfCompliance.Pdf15);
>      // Ukládá prezentaci jako PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with hidden slides.
>  
>  // Instancuje třídu Presentation, která představuje soubor PowerPoint
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Instancuje třídu PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // Přidává skryté snímky
>      pdfOptions.setShowHiddenSlides(true);
>      // Ukládá prezentaci jako PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to password protected PDF.
>  
>  // Instancuje objekt Presentation, který představuje soubor PowerPoint
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Instancuje třídu PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // Nastavuje heslo PDF a přístupová oprávnění
>      pdfOptions.setPassword("password");
>      pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>      // Ukládá prezentaci jako PDF
>      pres.save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with notes.
>  
>  // Instancuje objekt Presentation, který představuje soubor prezentace
>  Presentation pres = new Presentation("SelectedSlides.pptx");
>  try {
>      Presentation auxPres = new Presentation();
>      try {
>          ISlide slide = pres.getSlides().get_Item(0);
>          auxPres.getSlides().insertClone(0, slide);
>          // Nastavuje typ a velikost snímku
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
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Získá nebo nastaví režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Získá nebo nastaví režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Poskytuje možnosti, které řídí vzhled objektů Ink v exportovaném dokumentu. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Určuje, zda má vygenerovaný dokument zahrnovat skryté snímky, nebo ne. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Určuje, zda má vygenerovaný dokument zahrnovat skryté snímky, nebo ne. |
| [getTextCompression()](#getTextCompression--) | Určuje typ komprese, který se použije pro veškerý textový obsah v dokumentu. |
| [setTextCompression(int value)](#setTextCompression-int-) | Určuje typ komprese, který se použije pro veškerý textový obsah v dokumentu. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Indikuje, zda má být pro každý obrázek automaticky vybrána nejúčinnější komprese (místo výchozí). |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Indikuje, zda má být pro každý obrázek automaticky vybrána nejúčinnější komprese (místo výchozí). |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | Určuje, zda Aspose.Slides vloží běžná písma pro ASCII (rozsah kódů 33..127) text. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | Určuje, zda Aspose.Slides vloží běžná písma pro ASCII (rozsah kódů 33..127) text. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Vrací nebo nastavuje pole uživatelem definovaných názvů rodin písem, které by Aspose.Slides mělo považovat za běžná. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Vrací nebo nastavuje pole uživatelem definovaných názvů rodin písem, které by Aspose.Slides mělo považovat za běžná. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Určuje, zda mají být do dokumentu vloženy všechny znaky písma, nebo jen použita podmnožina. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Určuje, zda mají být do dokumentu vloženy všechny znaky písma, nebo jen použita podmnožina. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Indikuje, zda by měl být text rasterizován jako bitmapa a uložen do PDF, pokud písmo nepodporuje tučné stylování. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Indikuje, zda by měl být text rasterizován jako bitmapa a uložen do PDF, pokud písmo nepodporuje tučné stylování. |
| [getJpegQuality()](#getJpegQuality--) | Vrací nebo nastavuje hodnotu určující kvalitu JPEG obrázků v PDF dokumentu. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Vrací nebo nastavuje hodnotu určující kvalitu JPEG obrázků v PDF dokumentu. |
| [getCompliance()](#getCompliance--) | Požadovaná úroveň souladu pro vygenerovaný PDF dokument. |
| [setCompliance(int value)](#setCompliance-int-) | Požadovaná úroveň souladu pro vygenerovaný PDF dokument. |
| [getPassword()](#getPassword--) | Nastavení uživatelského hesla pro ochranu PDF dokumentu. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Nastavení uživatelského hesla pro ochranu PDF dokumentu. |
| [getAccessPermissions()](#getAccessPermissions--) | Obsahuje sadu příznaků určujících, jaká přístupová oprávnění mají být při otevření dokumentu s uživatelským přístupem udělena. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Obsahuje sadu příznaků určujících, jaká přístupová oprávnění mají být při otevření dokumentu s uživatelským přístupem udělena. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True pro převod všech metafiles použitých v prezentaci na PNG obrázky. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True pro převod všech metafiles použitých v prezentaci na PNG obrázky. |
| [getSufficientResolution()](#getSufficientResolution--) | Vrací nebo nastavuje hodnotu určující rozlišení obrázků v PDF dokumentu. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Vrací nebo nastavuje hodnotu určící rozlišení obrázků v PDF dokumentu. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True pro vykreslení černého rámečku kolem každého snímku. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True pro vykreslení černého rámečku kolem každého snímku. |
| [getImageTransparentColor()](#getImageTransparentColor--) | Získá nebo nastaví průhlednou barvu obrázku. |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | Získá nebo nastaví průhlednou barvu obrázku. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Použije zadanou průhlednou barvu na obrázek, pokud je true. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Použije zadanou průhlednou barvu na obrázek, pokud je true. |
| [getIncludeOleData()](#getIncludeOleData--) | True pro konverzi všech OLE dat z prezentace na vložené soubory ve výsledném PDF. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | True pro konverzi všech OLE dat z prezentace na vložené soubory ve výsledném PDF. |
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```

Výchozí konstruktor.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Získá nebo nastaví režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

Získá nebo nastaví režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Poskytuje možnosti, které řídí vzhled objektů Ink v exportovaném dokumentu. **Pouze pro čtení** [IInkOptions](../../com.aspose.slides/iinkoptions)

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTextCompression() {#getTextCompression--}
```
public final int getTextCompression()
```

Určuje typ komprese, který se použije pro veškerý textový obsah v dokumentu. **Čtení/Zápis** [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Výchozí hodnota je [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Vrací:**
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public final void setTextCompression(int value)
```

Určuje typ komprese, který se použije pro veškerý textový obsah v dokumentu. **Čtení/Zápis** [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Výchozí hodnota je [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public final boolean getBestImagesCompressionRatio()
```

Indikuje, zda má být pro každý obrázek automaticky vybrána nejúčinnější komprese (místo výchozí). Pokud je nastaveno na true, pro každý obrázek v prezentaci bude zvolen nejvhodnější kompresní algoritmus, což povede k menší velikosti výsledného PDF dokumentu.

--------------------

Výběr nejlepšího poměru komprese obrázků je výpočetně náročný a vyžaduje další paměť RAM; tato volba je ve výchozím nastavení false.

--------------------

Výchozí hodnota je false.

**Vrací:**
boolean
### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public final void setBestImagesCompressionRatio(boolean value)
```

Indikuje, zda má být pro každý obrázek automaticky vybrána nejúčinnější komprese (místo výchozí). Pokud je nastaveno na true, pro každý obrázek v prezentaci bude zvolen nejvhodnější kompresní algoritmus, což povede k menší velikosti výsledného PDF dokumentu.

--------------------

Výběr nejlepšího poměru komprese obrázků je výpočetně náročný a vyžaduje další paměť RAM; tato volba je ve výchozím nastavení false.

--------------------

Výchozí hodnota je false.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public final boolean getEmbedTrueTypeFontsForASCII()
```

Určuje, zda Aspose.Slides vloží běžná písma pro ASCII (rozsah kódů 33..127) text. Písma pro kódy vyšší než 127 jsou vždy vkládána. Seznam běžných písem zahrnuje 14 základních PDF písem a další uživatelem specifikovaná písma. **Čtení/Zápis** boolean.

--------------------

Výchozí hodnota je **true**.

**Vrací:**
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public final void setEmbedTrueTypeFontsForASCII(boolean value)
```

Určuje, zda Aspose.Slides vloží běžná písma pro ASCII (rozsah kódů 33..127) text. Písma pro kódy vyšší než 127 jsou vždy vkládána. Seznam běžných písem zahrnuje 14 základních PDF písem a další uživatelem specifikovaná písma. **Čtení/Zápis** boolean.

--------------------

Výchozí hodnota je **true**.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public final String[] getAdditionalCommonFontFamilies()
```

Vrací nebo nastavuje pole uživatelem definovaných názvů rodin písem, které by Aspose.Slides mělo považovat za běžná. **Čtení/Zápis** String[].

**Vrací:**
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public final void setAdditionalCommonFontFamilies(String[] value)
```

Vrací nebo nastavuje pole uživatelem definovaných názvů rodin písem, které by Aspose.Slides mělo považovat za běžná. **Čtení/Zápis** String[].

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public final boolean getEmbedFullFonts()
```

Určuje, zda mají být do dokumentu vloženy všechny znaky písma, nebo jen použita podmnožina. **Čtení/Zápis** boolean.

--------------------

Výchozí hodnota je **false**.

**Vrací:**
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public final void setEmbedFullFonts(boolean value)
```

Určuje, zda mají být do dokumentu vloženy všechny znaky písma, nebo jen použita podmnožina. **Čtení/Zápis** boolean.

--------------------

Výchozí hodnota je **false**.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public final boolean getRasterizeUnsupportedFontStyles()
```

Indikuje, zda by měl být text rasterizován jako bitmapa a uložen do PDF, pokud písmo nepodporuje tučné stylování. Tento přístup může zlepšit kvalitu textu v výsledném PDF pro některá písma. **Čtení/Zápis** boolean.

--------------------

Výchozí hodnota je **false**.

**Vrací:**
boolean
### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public final void setRasterizeUnsupportedFontStyles(boolean value)
```

Indikuje, zda by měl být text rasterizován jako bitmapa a uložen do PDF, pokud písmo nepodporuje tučné stylování. Tento přístup může zlepšit kvalitu textu v výsledném PDF pro některá písma. **Čtení/Zápis** boolean.

--------------------

Výchozí hodnota je **false**.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

Vrací nebo nastavuje hodnotu určující kvalitu JPEG obrázků v PDF dokumentu. **Čtení/Zápis** byte.

--------------------

Má vliv pouze, pokud dokument obsahuje JPEG obrázky.

Použijte tuto vlastnost k získání nebo nastavení kvality obrázků v dokumentu při ukládání do PDF formátu. Hodnota může být od 0 do 100, kde 0 znamená nejhorší kvalitu, ale maximální kompresi, a 100 nejlepší kvalitu, ale minimální kompresi.

Výchozí hodnota je **100**.

**Vrací:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

Vrací nebo nastavuje hodnotu určující kvalitu JPEG obrázků v PDF dokumentu. **Čtení/Zápis** byte.

--------------------

Má vliv pouze, pokud dokument obsahuje JPEG obrázky.

Použijte tuto vlastnost k získání nebo nastavení kvality obrázků v dokumentu při ukládání do PDF formátu. Hodnota může být od 0 do 100, kde 0 znamená nejhorší kvalitu, ale maximální kompresi, a 100 nejlepší kvalitu, ale minimální kompresi.

Výchozí hodnota je **100**.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```

Požadovaná úroveň souladu pro vygenerovaný PDF dokument. **Čtení/Zápis** [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Výchozí hodnota je [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Vrací:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```

Požadovaná úroveň souladu pro vygenerovaný PDF dokument. **Čtení/Zápis** [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Výchozí hodnota je [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

Nastavení uživatelského hesla pro ochranu PDF dokumentu. **Čtení/Zápis** String.

**Vrací:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

Nastavení uživatelského hesla pro ochranu PDF dokumentu. **Čtení/Zápis** String.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public final int getAccessPermissions()
```

Obsahuje sadu příznaků určujících, jaká přístupová oprávnění mají být při otevření dokumentu s uživatelským přístupem udělena. Viz [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

Obsahuje sadu příznaků určujících, jaká přístupová oprávnění mají být při otevření dokumentu s uživatelským přístupem udělena. Viz [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

True pro převod všech metafiles použitých v prezentaci na PNG obrázky. **Čtení/Zápis** boolean.

--------------------

Výchozí hodnota je **true**. PDF dokument může obsahovat vektorovou grafiku i rastrové obrázky. Pokud je SaveMetafilesAsPng nastaveno na true, zdrojový Metafile obrázek je převeden do formátu PNG a uložen do PDF jako rastrový obrázek. Pokud je SaveMetafilesAsPng nastaveno na false, zdrojový Metafile je převeden na PDF vektorovou grafiku. Každý přístup má výhody i nevýhody. Například při konverzi Metafile na PNG může během škálování výsledného dokumentu dojít ke ztrátě kvality. Při konverzi Metafile na PDF vektorovou grafiku mohou nastat výkonnostní problémy v PDF prohlížeči.

**Vrací:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

True pro převod všech metafiles použitých v prezentaci na PNG obrázky. **Čtení/Zápis** boolean.

--------------------

Výchozí hodnota je **true**. PDF dokument může obsahovat vektorovou grafiku i rastrové obrázky. Pokud je SaveMetafilesAsPng nastaveno na true, zdrojový Metafile obrázek je převeden do formátu PNG a uložen do PDF jako rastrový obrázek. Pokud je SaveMetafilesAsPng nastaveno na false, zdrojový Metafile je převeden na PDF vektorovou grafiku. Každý přístup má výhody i nevýhody. Například při konverzi Metafile na PNG může během škálování výsledného dokumentu dojít ke ztrátě kvality. Při konverzi Metafile na PDF vektorovou grafiku mohou nastat výkonnostní problémy v PDF prohlížeči.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public final float getSufficientResolution()
```

Vrací nebo nastavuje hodnotu určující rozlišení obrázků v PDF dokumentu. **Čtení/Zápis** float.

Hodnota: Efekt tohoto parametru závisí na několika faktorech. Algoritmus se snaží získat nejlepší velikost výstupního obrazu podle hodnoty vlastnosti, velikosti zdrojového obrazu a velikosti rámečku obrazu. Použití podobných hodnot může dát stejný výsledek. Doporučuje se použít krok 16 nebo 32 pro viditelný efekt.

--------------------

Vlastnost ovlivňuje velikost souboru, dobu exportu a kvalitu obrazu.

Výchozí hodnota je **96**.

**Vrací:**
float
### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public  

```

Vrací nebo nastavuje hodnotu určující rozlišení obrázků v PDF dokumentu. **Čtení/Zápis** float.

Hodnota: Efekt tohoto parametru závisí na několika faktorech. Algoritmus se snaží získat nejlepší velikost výstupního obrazu podle hodnoty vlastnosti, velikosti zdrojového obrazu a velikosti rámečku obrazu. Použití podobných hodnot může dát stejný výsledek. Doporučuje se použít krok 16 nebo 32 pro viditelný efekt.

--------------------

Vlastnost ovlivňuje velikost souboru, dobu exportu a kvalitu obrazu.

Výchozí hodnota je **96**.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

True pro vykreslení černého rámečku kolem každého snímku. **Čtení/Zápis** boolean.

--------------------

Výchozí hodnota je **false**.

**Vrací:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

True pro vykreslení černého rámečku kolem každého snímku. **Čtení/Zápis** boolean.

--------------------

Výchozí hodnota je **false**.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public final Integer getImageTransparentColor()
```

Získá nebo nastaví průhlednou barvu obrázku.

Hodnota: Barva průhlednosti obrázku.

**Vrací:**
java.lang.Integer
### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public final void setImageTransparentColor(Integer value)
```

Získá nebo nastaví průhlednou barvu obrázku.

Hodnota: Barva průhlednosti obrázku.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public final boolean getApplyImageTransparent()
```

Použije zadanou průhlednou barvu na obrázek, pokud je true.

**Vrací:**
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public final void setApplyImageTransparent(boolean value)
```

Použije zadanou průhlednou barvu na obrázek, pokud je true.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getIncludeOleData() {#getIncludeOleData--}
```
public final boolean getIncludeOleData()
```

True pro konverzi všech OLE dat z prezentace na vložené soubory ve výsledném PDF. **Čtení/Zápis**  boolean .

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

Výchozí hodnota je  **false** .

**Vrací:**
boolean
### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public final void setIncludeOleData(boolean value)
```

True pro konverzi všech OLE dat z prezentace na vložené soubory ve výsledném PDF. **Čtení/Zápis**  boolean .

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

Výchozí hodnota je  **false** .

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
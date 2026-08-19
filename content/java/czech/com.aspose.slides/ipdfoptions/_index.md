---
title: IPdfOptions
second_title: Aspose.Slides pro Java API Reference
description: Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu PDF.
type: docs
url: /cs/com.aspose.slides/ipdfoptions/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPdfOptions extends ISaveOptions
```

Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu PDF.
## Metody

| Metoda | Popis |
| --- | --- |
| [getTextCompression()](#getTextCompression--) | Určuje typ komprese, který se použije pro veškerý textový obsah v dokumentu. |
| [setTextCompression(int value)](#setTextCompression-int-) | Určuje typ komprese, který se použije pro veškerý textový obsah v dokumentu. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Určuje, zda má být pro každý obrázek automaticky vybrána nejúčinnější komprese (místo výchozí). |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Určuje, zda má být pro každý obrázek automaticky vybrána nejúčinnější komprese (místo výchozí). |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | True k vložení TrueType písem pro ASCII znaky 32-127. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | True k vložení TrueType písem pro ASCII znaky 32-127. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Určuje, zda má vygenerovaný dokument obsahovat skryté snímky, nebo ne. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Určuje, zda má vygenerovaný dokument obsahovat skryté snímky, nebo ne. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Vrací nebo nastavuje pole uživatelem definovaných názvů rodin písem, které má Aspose.Slides považovat za společné. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Vrací nebo nastavuje pole uživatelem definovaných názvů rodin písem, které má Aspose.Slides považovat za společné. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Určuje, zda mají být vloženy všechny znaky písma, nebo jen použitá podmnožina. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Určuje, zda mají být vloženy všechny znaky písma, nebo jen použitá podmnožina. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Určuje, zda má být text rasterizován jako bitmapa a uložen do PDF, když písmo nepodporuje tučné styly. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Určuje, zda má být text rasterizován jako bitmapa a uložen do PDF, když písmo nepodporuje tučné styly. |
| [getJpegQuality()](#getJpegQuality--) | Vrací nebo nastavuje hodnotu určující kvalitu JPEG obrázků v dokumentu PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Vrací nebo nastavuje hodnotu určující kvalitu JPEG obrázků v dokumentu PDF. |
| [getCompliance()](#getCompliance--) | Požadovaná úroveň souladu pro vygenerovaný PDF dokument. |
| [setCompliance(int value)](#setCompliance-int-) | Požadovaná úroveň souladu pro vygenerovaný PDF dokument. |
| [getPassword()](#getPassword--) | Nastavení uživatelského hesla pro ochranu PDF dokumentu. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Nastavení uživatelského hesla pro ochranu PDF dokumentu. |
| [getAccessPermissions()](#getAccessPermissions--) | Obsahuje sadu příznaků určujících, která přístupová oprávnění mají být při otevření dokumentu uživatelem povolena. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Obsahuje sadu příznaků určujících, která přístupová oprávnění mají být při otevření dokumentu uživatelem povolena. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True k převodu všech metafilek použitých v prezentaci na PNG obrázky. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True k převodu všech metafilek použitých v prezentaci na PNG obrázky. |
| [getSufficientResolution()](#getSufficientResolution--) | Vrací nebo nastavuje hodnotu určující rozlišení obrázků v PDF dokumentu. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Vrací nebo nastavuje hodnotu určující rozlišení obrázků v PDF dokumentu. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True k vykreslení černého okraje kolem každého snímku. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True k vykreslení černého okraje kolem každého snímku. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Získá nebo nastaví režim, ve kterém jsou snímky umísťovány na stránku při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Získá nebo nastaví režim, ve kterém jsou snímky umísťovány na stránku při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getImageTransparentColor()](#getImageTransparentColor--) | Získá nebo nastaví průhlednou barvu obrázku. |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | Získá nebo nastaví průhlednou barvu obrázku. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Použije zadanou průhlednou barvu na obrázek, pokud je true. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Použije zadanou průhlednou barvu na obrázek, pokud je true. |
| [getInkOptions()](#getInkOptions--) | Poskytuje možnosti, které řídí vzhled Ink objektů v exportovaném dokumentu. |
| [getIncludeOleData()](#getIncludeOleData--) | True k převodu všech OLE dat z prezentace na vložené soubory ve výsledném PDF. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | True k převodu všech OLE dat z prezentace na vložené soubory ve výsledném PDF. |

### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```

Určuje typ komprese, který se použije pro veškerý textový obsah v dokumentu. Čtení/Zápis [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Výchozí hodnota je [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Vrací:**
int

### setTextCompression(int value) {#setTextCompression-int-}
```
public abstract void setTextCompression(int value)
```

Určuje typ komprese, který se použije pro veškerý textový obsah v dokumentu. Čtení/Zápis [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Výchozí hodnota je [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public abstract boolean getBestImagesCompressionRatio()
```

Určuje, zda má být pro každý obrázek automaticky vybrána nejúčinnější komprese (místo výchozí). Pokud je nastavena na true, pro každý obrázek v prezentaci bude zvolen nejvhodnější kompresní algoritmus, což povede k menší velikosti výsledného PDF dokumentu.

--------------------

Výběr nejlepšího poměru komprese obrázku je výpočetně náročný a vyžaduje další paměť RAM, a tato volba je ve výchozím nastavení false.

--------------------

Výchozí hodnota je false.

**Vrací:**
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```

Určuje, zda má být pro každý obrázek automaticky vybrána nejúčinnější komprese (místo výchozí). Pokud je nastavena na true, pro každý obrázek v prezentaci bude zvolen nejvhodnější kompresní algoritmus, což povede k menší velikosti výsledného PDF dokumentu.

--------------------

Výběr nejlepšího poměru komprese obrázku je výpočetně náročný a vyžaduje další paměť RAM, a tato volba je ve výchozím nastavení false.

--------------------

Výchozí hodnota je false.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public abstract boolean getEmbedTrueTypeFontsForASCII()
```

True k vložení TrueType písem pro ASCII znaky 32-127. Písma pro kódy znaků vyšší než 127 jsou vždy vložena. Čtení/Zápis boolean.

--------------------

Výchozí hodnota je **true**.

**Vrací:**
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```

True k vložení TrueType písem pro ASCII znaky 32-127. Písma pro kódy znaků vyšší než 127 jsou vždy vložena. Čtení/Zápis boolean.

--------------------

Výchozí hodnota je **true**.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Určuje, zda má vygenerovaný dokument obsahovat skryté snímky, nebo ne. Výchozí hodnota je false.

**Vrací:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Určuje, zda má vygenerovaný dokument obsahovat skryté snímky, nebo ne. Výchozí hodnota je false.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public abstract String[] getAdditionalCommonFontFamilies()
```

Vrací nebo nastavuje pole uživatelem definovaných názvů rodin písem, které má Aspose.Slides považovat za společné. Čtení/Zápis String[].

**Vrací:**
java.lang.String[]

### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```

Vrací nebo nastavuje pole uživatelem definovaných názvů rodin písem, které má Aspose.Slides považovat za společné. Čtení/Zápis String[].

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```

Určuje, zda mají být vloženy všechny znaky písma, nebo jen použita podmnožina. Čtení/Zápis boolean.

--------------------

Výchozí hodnota je **false**.

**Vrací:**
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```

Určuje, zda mají být vloženy všechny znaky písma, nebo jen použita podmnožina. Čtení/Zápis boolean.

--------------------

Výchozí hodnota je **false**.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public abstract boolean getRasterizeUnsupportedFontStyles()
```

Určuje, zda má být text rasterizován jako bitmapa a uložen do PDF, když písmo nepodporuje tučné styly. Tento přístup může zlepšit kvalitu textu ve výsledném PDF pro určitá písma. Čtení/Zápis boolean.

--------------------

Výchozí hodnota je **false**.

**Vrací:**
boolean

### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public abstract void setRasterizeUnsupportedFontStyles(boolean value)
```

Určuje, zda má být text rasterizován jako bitmapa a uložen do PDF, když písmo nepodporuje tučné styly. Tento přístup může zlepšit kvalitu textu ve výsledném PDF pro určitá písma. Čtení/Zápis boolean.

--------------------

Výchozí hodnota je **false**.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

Vrací nebo nastavuje hodnotu určující kvalitu JPEG obrázků v PDF dokumentu. Čtení/Zápis byte.

--------------------

Má účinek pouze když dokument obsahuje JPEG obrázky.

Použijte tuto vlastnost k získání nebo nastavení kvality obrázků v dokumentu při ukládání do formátu PDF. Hodnota se může pohybovat od 0 do 100, kde 0 znamená nejhorší kvalitu, ale maximální kompresi, a 100 nejlepší kvalitu, ale minimální kompresi.

Výchozí hodnota je **100**.

**Vrací:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

Vrací nebo nastavuje hodnotu určující kvalitu JPEG obrázků v PDF dokumentu. Čtení/Zápis byte.

--------------------

Má účinek pouze když dokument obsahuje JPEG obrázky.

Použijte tuto vlastnost k získání nebo nastavení kvality obrázků v dokumentu při ukládání do formátu PDF. Hodnota se může pohybovat od 0 do 100, kde 0 znamená nejhorší kvalitu, ale maximální kompresi, a 100 nejlepší kvalitu, ale minimální kompresi.

Výchozí hodnota je **100**.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public abstract int getCompliance()
```

Požadovaná úroveň souladu pro vygenerovaný PDF dokument. Čtení/Zápis [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Výchozí hodnota je [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Vrací:**
int

### setCompliance(int value) {#setCompliance-int-}
```
public abstract void setCompliance(int value)
```

Požadovaná úroveň souladu pro vygenerovaný PDF dokument. Čtení/Zápis [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Výchozí hodnota je [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

Nastavení uživatelského hesla pro ochranu PDF dokumentu. Čtení/Zápis String.

**Vrací:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

Nastavení uživatelského hesla pro ochranu PDF dokumentu. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public abstract int getAccessPermissions()
```

Obsahuje sadu příznaků určujících, která přístupová oprávnění mají být při otevření dokumentu uživatelem povolena. Viz [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
public abstract void setAccessPermissions(int value)
```

Obsahuje sadu příznaků určujících, která přístupová oprávnění mají být při otevření dokumentu uživatelem povolena. Viz [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
public abstract boolean getSaveMetafilesAsPng()
```

True k převodu všech metafilek použitých v prezentaci na PNG obrázky. Čtení/Zápis boolean.

--------------------

Výchozí hodnota je **true**. Pdf dokument může obsahovat vektorovou grafiku i rastrové obrázky. Pokud je SaveMetafilesAsPng nastaveno na true, pak je zdrojový Metafile obrázek převeden do formátu PNG a uložen do PDF jako rastrový obrázek. Pokud je SaveMetafilesAsPng nastaveno na false, pak je zdrojový Metafile převeden na vektorovou grafiku PDF. Každý přístup má své výhody i nevýhody. Například při převodu Metafile na PNG může dojít ke ztrátě kvality během škálování výsledného dokumentu. Při převodu Metafile na vektorovou grafiku PDF mohou nastat výkonnostní problémy v prohlížeči PDF.

**Vrací:**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

True k převodu všech metafilek použitých v prezentaci na PNG obrázky. Čtení/Zápis boolean.

--------------------

Výchozí hodnota je **true**. Pdf dokument může obsahovat vektorovou grafiku i rastrové obrázky. Pokud je SaveMetafilesAsPng nastaveno na true, pak je zdrojový Metafile obrázek převeden do formátu PNG a uložen do PDF jako rastrový obrázek. Pokud je SaveMetafilesAsPng nastaveno na false, pak je zdrojový Metafile převeden na vektorovou grafiku PDF. Každý přístup má své výhody i nevýhody. Například při převodu Metafile na PNG může dojít ke ztrátě kvality během škálování výsledného dokumentu. Při převodu Metafile na vektorovou grafiku PDF mohou nastat výkonnostní problémy v prohlížeči PDF.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```

Vrací nebo nastavuje hodnotu určující rozlišení obrázků v PDF dokumentu. Čtení/Zápis float.

Hodnota: Efekt tohoto parametru závisí na několika faktorech. Algoritmus se snaží získat nejlepší výstupní velikost obrázku podle hodnoty vlastnosti, velikosti zdrojového obrázku a velikosti rámečku obrázku. Použití podobných hodnot vlastnosti může vést ke stejnému výsledku. Doporučuje se použít krok 16 nebo 32 pro dosažení viditelného efektu.

Vlastnost ovlivňuje velikost souboru, dobu exportu a kvalitu obrázku.

Výchozí hodnota je **96**.

**Vrací:**
float

### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```

Vrací nebo nastavuje hodnotu určující rozlišení obrázků v PDF dokumentu. Čtení/Zápis float.

Hodnota: Efekt tohoto parametru závisí na několika faktorech. Algoritmus se snaží získat nejlepší výstupní velikost obrázku podle hodnoty vlastnosti, velikosti zdrojového obrázku a velikosti rámečku obrázku. Použití podobných hodnot vlastnosti může vést ke stejnému výsledku. Doporučuje se použít krok 16 nebo 32 pro dosažení viditelného efektu.

Vlastnost ovlivňuje velikost souboru, dobu exportu a kvalitu obrázku.

Výchozí hodnota je **96**.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

True k vykreslení černého rámce kolem každého snímku. Čtení/Zápis boolean.

--------------------

Výchozí hodnota je **false**.

**Vrací:**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

True k vykreslení černého rámce kolem každého snímku. Čtení/Zápis boolean.

--------------------

Výchozí hodnota je **false**.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Získá nebo nastaví režim, ve kterém jsou snímky umísťovány na stránku při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Získá nebo nastaví režim, ve kterém jsou snímky umísťovány na stránku při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

### getImageTransparentColor() {#getImageTransparentColor--}
```
public abstract Color getImageTransparentColor()
```

Získá nebo nastaví průhlednou barvu obrázku.

Hodnota: Barva průhlednosti obrázku.

**Vrací:**
java.awt.Color
### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public abstract void setImageTransparentColor(Color value)
```

Získá nebo nastaví průhlednou barvu obrázku.

Hodnota: Barva průhlednosti obrázku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public abstract boolean getApplyImageTransparent()
```

Použije zadanou průhlednou barvu na obrázek, pokud je true.

**Vrací:**
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public abstract void setApplyImageTransparent(boolean value)
```

Použije zadanou průhlednou barvu na obrázek, pokud je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Poskytuje možnosti, které řídí vzhled Ink objektů v exportovaném dokumentu. Pouze pro čtení [IInkOptions](../../com.aspose.slides/iinkoptions)

**Vrací:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getIncludeOleData() {#getIncludeOleData--}
```
public abstract boolean getIncludeOleData()
```

True k převodu všech OLE dat z prezentace na vložené soubory ve výsledném PDF. Čtení/Zápis  boolean .

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
public abstract void setIncludeOleData(boolean value)
```

True k převodu všech OLE dat z prezentace na vložené soubory ve výsledném PDF. Čtení/Zápis  boolean .

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
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
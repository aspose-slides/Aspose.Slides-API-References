---
title: PdfOptions
second_title: Aspose.Slides for Java API referencia
description: Lehetőségeket biztosít, amelyek szabályozzák, hogy egy bemutató PDF formátumban hogyan legyen mentve.
type: docs
url: /hu/com.aspose.slides/pdfoptions/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Az összes implementált interfész:**
[com.aspose.slides.IPdfOptions](../../com.aspose.slides/ipdfoptions)
```
public class PdfOptions extends SaveOptions implements IPdfOptions
```

Lehetőségeket biztosít, amelyek szabályozzák, hogy a bemutató PDF formátumban hogyan legyen mentve.

--------------------

> ```
> The following example shows how to convert PowerPoint to PDF with custom options.
>  
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Létrehozza a PdfOptions osztályt
>      PdfOptions pdfOptions = new PdfOptions();
>      // Beállítja a JPEG minőséget
>      pdfOptions.setJpegQuality((byte)90);
>      // Beállítja a metafájlok viselkedését
>      pdfOptions.setSaveMetafilesAsPng(true);
>      // Beállítja a szöveg tömörítési szintjét
>      pdfOptions.setTextCompression(PdfTextCompression.Flate);
>      // Meghatározza a PDF szabványt
>      pdfOptions.setCompliance(PdfCompliance.Pdf15);
>      // Mentés PDF-ként
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with hidden slides.
>  
>  // Létrehozza a Presentation osztályt, amely egy PowerPoint fájlt képvisel
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Létrehozza a PdfOptions osztályt
>      PdfOptions pdfOptions = new PdfOptions();
>      // Hozzáadja a rejtett diákat
>      pdfOptions.setShowHiddenSlides(true);
>      // Mentés PDF-ként
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to password protected PDF.
>  
>  // Létrehozza a Presentation objektumot, amely egy PowerPoint fájlt képvisel
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Létrehozza a PdfOptions osztályt
>      PdfOptions pdfOptions = new PdfOptions();
>      // Beállítja a PDF jelszót és a hozzáférési jogosultságokat
>      pdfOptions.setPassword("password");
>      pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>      // Mentés PDF-ként
>      pres.save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with notes.
>  
>  // Létrehozza a Presentation objektumot, amely egy prezentációs fájlt képvisel
>  Presentation pres = new Presentation("SelectedSlides.pptx");
>  try {
>      Presentation auxPres = new Presentation();
>      try {
>          ISlide slide = pres.getSlides().get_Item(0);
>          auxPres.getSlides().insertClone(0, slide);
>          // Diatípus és méret beállítása
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

## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | Alapértelmezett konstruktor. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Megkapja vagy beállítja azt a módot, ahogyan a diák az oldalon elhelyezésre kerülnek a bemutató exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Megkapja vagy beállítja azt a módot, ahogyan a diák az oldalon elhelyezésre kerülnek a bemutató exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Lehetőségeket biztosít, amelyek szabályozzák az Ink objektumok megjelenését az exportált dokumentumban. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Megadja, hogy a generált dokumentumban legyenek-e rejtett diák vagy sem. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Megadja, hogy a generált dokumentumban legyenek-e rejtett diák vagy sem. |
| [getTextCompression()](#getTextCompression--) | Megadja a dokumentumban minden szöveges tartalomra alkalmazandó tömörítési típust. |
| [setTextCompression(int value)](#setTextCompression-int-) | Megadja a dokumentumban minden szöveges tartalomra alkalmazandó tömörítési típust. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Jelzi, hogy minden egyes képre automatikusan a leghatékonyabb (az alapértelmezett helyett) tömörítés legyen kiválasztva. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Jelzi, hogy minden egyes képre automatikusan a leghatékonyabb (az alapértelmezett helyett) tömörítés legyen kiválasztva. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | Meghatározza, hogy az Aspose.Slides beágyazza-e a gyakori betűtípusokat az ASCII (33-..127 kódtartomány) szöveghez. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | Meghatározza, hogy az Aspose.Slides beágyazza-e a gyakori betűtípusokat az ASCII (33-..127 kódtartomány) szöveghez. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Visszaad vagy beállít egy tömböt a felhasználó által megadott betűcsaládnevekkel, amelyeket az Aspose.Slides gyakoriaknak tekint. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Visszaad vagy beállít egy tömböt a felhasználó által megadott betűcsaládnevekkel, amelyeket az Aspose.Slides gyakoriaknak tekint. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Meghatározza, hogy a betűtípus összes karaktere be legyen ágyazva, vagy csak a használt részhalmaz. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Meghatározza, hogy a betűtípus összes karaktere be legyen ágyazva, vagy csak a használt részhalmaz. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Jelzi, hogy a szöveget bitmapként kell-e rasterizálni és PDF-be menteni, ha a betűtípus nem támogatja a félkövér stílust. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Jelzi, hogy a szöveget bitmapként kell-e rasterizálni és PDF-be menteni, ha a betűtípus nem támogatja a félkövér stílust. |
| [getJpegQuality()](#getJpegQuality--) | Visszaad vagy beállít egy értéket, amely meghatározza a JPEG-képek minőségét a PDF-dokumentumban. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Visszaad vagy beállít egy értéket, amely meghatározza a JPEG-képek minőségét a PDF-dokumentumban. |
| [getCompliance()](#getCompliance--) | A generált PDF-dokumentum kívánt megfelelőségi szintje. |
| [setCompliance(int value)](#setCompliance-int-) | A generált PDF-dokumentum kívánt megfelelőségi szintje. |
| [getPassword()](#getPassword--) | A felhasználói jelszó beállítása a PDF-dokumentum védelméhez. |
| [setPassword(String value)](#setPassword-java.lang.String-) | A felhasználói jelszó beállítása a PDF-dokumentum védelméhez. |
| [getAccessPermissions()](#getAccessPermissions--) | Tartalmaz egy zászlókészletet, amely meghatározza, mely hozzáférési jogosultságok legyenek megadva, amikor a dokumentum felhasználói hozzáféréssel nyílik meg. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Tartalmaz egy zászlókészletet, amely meghatározza, mely hozzáférési jogosultságok legyenek megadva, amikor a dokumentum felhasználói hozzáféréssel nyílik meg. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Igaz, ha a bemutatóban használt összes metafájlt PNG-képekké kívánja konvertálni. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Igaz, ha a bemutatóban használt összes metafájlt PNG-képekké kívánja konvertálni. |
| [getSufficientResolution()](#getSufficientResolution--) | Visszaad vagy beállít egy értéket, amely meghatározza a képek felbontását a PDF-dokumentumban. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Visszaad vagy beállít egy értéket, amely meghatározza a képek felbontását a PDF-dokumentumban. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Igaz, ha minden dia köré fekete keretet szeretne rajzolni. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Igaz, ha minden dia köré fekete keretet szeretne rajzolni. |
| [getImageTransparentColor()](#getImageTransparentColor--) | Megkapja vagy beállítja a kép átlátszó színét. |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | Megkapja vagy beállítja a kép átlátszó színét. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Alkalmazza a megadott átlátszó színt egy képre, ha igaz. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Alkalmazza a megadott átlátszó színt egy képre, ha igaz. |
| [getIncludeOleData()](#getIncludeOleData--) | Igaz, ha az összes OLE-adatot a bemutatóból beágyazott fájlokként kívánja a PDF-ben tárolni. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | Igaz, ha az összes OLE-adatot a bemutatóból beágyazott fájlokként kívánja a PDF-ben tárolni. |

### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```

Alapértelmezett konstruktor.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Megkapja vagy beállítja azt a módot, ahogyan a diák az oldalon elhelyezésre kerülnek a bemutató exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**Visszatérési érték:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Megkapja vagy beállítja azt a módot, ahogyan a diák az oldalon elhelyezésre kerülnek a bemutató exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Lehetőségeket biztosít, amelyek szabályozzák az Ink objektumok megjelenését az exportált dokumentumban. **Csak olvasható** [IInkOptions](../../com.aspose.slides/iinkoptions)

**Visszatérési érték:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Megadja, hogy a generált dokumentumban legyenek-e rejtett diák vagy sem. Alapértelmezett érték: false.

**Visszatérési érték:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Megadja, hogy a generált dokumentumban legyenek-e rejtett diák vagy sem. Alapértelmezett érték: false.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTextCompression() {#getTextCompression--}
```
public final int getTextCompression()
```

Megadja a dokumentumban minden szöveges tartalomra alkalmazandó tömörítési típust. **Olvasás/írás** [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Alapértelmezett [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Visszatérési érték:**
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public final void setTextCompression(int value)
```

Megadja a dokumentumban minden szöveges tartalomra alkalmazandó tömörítési típust. **Olvasás/írás** [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Alapértelmezett [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public final boolean getBestImagesCompressionRatio()
```

Jelzi, hogy minden egyes képre automatikusan a leghatékonyabb (az alapértelmezett helyett) tömörítés legyen kiválasztva. Ha igazra van állítva, a bemutató minden képe a legmegfelelőbb tömörítési algoritmust kapja, ami kisebb PDF-méretet eredményez.

--------------------

A legjobb képtömörítési arány kiválasztása számításigényes, további RAM-ot igényel, és ez a beállítás alapértelmezésben false.

--------------------

Alapértelmezett false.

**Visszatérési érték:**
boolean
### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public final void setBestImagesCompressionRatio(boolean value)
```

Jelzi, hogy minden egyes képre automatikusan a leghatékonyabb (az alapértelmezett helyett) tömörítés legyen kiválasztva. Ha igazra van állítva, a bemutató minden képe a legmegfelelőbb tömörítési algoritmust kapja, ami kisebb PDF-méretet eredményez.

--------------------

A legjobb képtömörítési arány kiválasztása számításigényes, további RAM-ot igényel, és ez a beállítás alapértelmezésben false.

--------------------

Alapértelmezett false.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public final boolean getEmbedTrueTypeFontsForASCII()
```

Meghatározza, hogy az Aspose.Slides beágyazza-e a gyakori betűtípusokat az ASCII (33-..127 kódtartomány) szöveghez. A 127-nél nagyobb karakterkódokhoz a betűtípusok mindig be vannak ágyazva. A gyakori betűtípusok listája tartalmazza a PDF alap-14 betűtípusát és a felhasználó által megadottakat. **Olvasás/írás** boolean.

--------------------

Alapértelmezett **true**.

**Visszatérési érték:**
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public final void setEmbedTrueTypeFontsForASCII(boolean value)
```

Meghatározza, hogy az Aspose.Slides beágyazza-e a gyakori betűtípusokat az ASCII (33-..127 kódtartomány) szöveghez. A 127-nél nagyobb karakterkódokhoz a betűtípusok mindig be vannak ágyazva. A gyakori betűtípusok listája tartalmazza a PDF alap-14 betűtípusát és a felhasználó által megadottakat. **Olvasás/írás** boolean.

--------------------

Alapértelmezett **true**.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public final String[] getAdditionalCommonFontFamilies()
```

Visszaad vagy beállít egy tömböt a felhasználó által megadott betűcsaládnevekkel, amelyeket az Aspose.Slides gyakoriaknak tekint. **Olvasás/írás** String[].

**Visszatérési érték:**
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public final void setAdditionalCommonFontFamilies(String[] value)
```

Visszaad vagy beállít egy tömböt a felhasználó által megadott betűcsaládnevekkel, amelyeket az Aspose.Slides gyakoriaknak tekint. **Olvasás/írás** String[].

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public final boolean getEmbedFullFonts()
```

Meghatározza, hogy a betűtípus összes karaktere be legyen ágyazva, vagy csak a használt részhalmaz. **Olvasás/írás** boolean.

--------------------

Alapértelmezett **false**.

**Visszatérési érték:**
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public final void setEmbedFullFonts(boolean value)
```

Meghatározza, hogy a betűtípus összes karaktere be legyen ágyazva, vagy csak a használt részhalmaz. **Olvasás/írás** boolean.

--------------------

Alapértelmezett **false**.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public final boolean getRasterizeUnsupportedFontStyles()
```

Jelzi, hogy a szöveget bitmapként kell-e rasterizálni és PDF-be menteni, ha a betűtípus nem támogatja a félkövér stílust. Ez a megközelítés javíthatja a szöveg minőségét a PDF-ben bizonyos betűtípusok esetén. **Olvasás/írás** boolean.

--------------------

Alapértelmezett **false**.

**Visszatérési érték:**
boolean
### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public final void setRasterizeUnsupportedFontStyles(boolean value)
```

Jelzi, hogy a szöveget bitmapként kell-e rasterizálni és PDF-be menteni, ha a betűtípus nem támogatja a félkövér stílust. Ez a megközelítés javíthatja a szöveg minőségét a PDF-ben bizonyos betűtípusok esetén. **Olvasás/írás** boolean.

--------------------

Alapértelmezett **false**.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

Visszaad vagy beállít egy értéket, amely meghatározza a JPEG-képek minőségét a PDF-dokumentumban. **Olvasás/írás** byte.

--------------------

Csak akkor hat, ha a dokumentum JPEG-képeket tartalmaz.

Használja ezt a tulajdonságot a képek minőségének beállításához PDF-formátumban való mentéskor. Az érték 0-tól 100-ig terjed, ahol 0 a legrosszabb minőség, de maximális tömörítés, 100 pedig a legjobb minőség, de minimális tömörítés.

Az alapértelmezett érték **100**.

**Visszatérési érték:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

Visszaad vagy beállít egy értéket, amely meghatározza a JPEG-képek minőségét a PDF-dokumentumban. **Olvasás/írás** byte.

--------------------

Csak akkor hat, ha a dokumentum JPEG-képeket tartalmaz.

Használja ezt a tulajdonságot a képek minőségének beállításához PDF-formátumban való mentéskor. Az érték 0-tól 100-ig terjed, ahol 0 a legrosszabb minőség, de maximális tömörítés, 100 pedig a legjobb minőség, de minimális tömörítés.

Az alapértelmezett érték **100**.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```

A generált PDF-dokumentum kívánt megfelelőségi szintje. **Olvasás/írás** [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Alapértelmezett [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Visszatérési érték:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```

A generált PDF-dokumentum kívánt megfelelőségi szintje. **Olvasás/írás** [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Alapértelmezett [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

A felhasználói jelszó beállítása a PDF-dokumentum védelméhez. **Olvasás/írás** String.

**Visszatérési érték:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

A felhasználói jelszó beállítása a PDF-dokumentum védelméhez. **Olvasás/írás** String.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public final int getAccessPermissions()
```

Tartalmaz egy zászlókészletet, amely meghatározza, mely hozzáférési jogosultságok legyenek megadva, amikor a dokumentum felhasználói hozzáféréssel nyílik meg. Lásd [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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


**Visszatérési érték:**
int
### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public final void setAccessPermissions(int value)
```

Tartalmaz egy zászlókészletet, amely meghatározza, mely hozzáférési jogosultságok legyenek megadva, amikor a dokumentum felhasználói hozzáféréssel nyílik meg. Lásd [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

Igaz, ha a bemutatóban használt összes metafájlt PNG-képekké kívánja konvertálni. **Olvasás/írás** boolean.

--------------------

Alapértelmezett **true**. A PDF-dokumentum tartalmazhat vektoros grafikát és raszter képeket. Ha a SaveMetafilesAsPng true, akkor a forrás Metafile képet PNG-formátumba konvertálja, és raszter képként menti a PDF-be. Ha false, a forrás Metafile vektoros grafikává alakul. Mindkét megközelítésnek vannak előnyei és hátrányai. Például PNG-re konvertálás esetén a dokumentum méretezésekor minőségromlás léphet fel. Vektoros grafikára konvertálás esetén a PDF-megjelenítő teljesítményével kapcsolatos problémák merülhetnek fel.

**Visszatérési érték:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

Igaz, ha a bemutatóban használt összes metafájlt PNG-képekké kívánja konvertálni. **Olvasás/írás** boolean.

--------------------

Alapértelmezett **true**. A PDF-dokumentum tartalmazhat vektoros grafikát és raszter képeket. Ha a SaveMetafilesAsPng true, akkor a forrás Metafile képet PNG-formátumba konvertálja, és raszter képként menti a PDF-be. Ha false, a forrás Metafile vektoros grafikává alakul. Mindkét megközelítésnek vannak előnyei és hátrányai. Például PNG-re konvertálás esetén a dokumentum méretezésekor minőségromlás léphet fel. Vektoros grafikára konvertálás esetén a PDF-megjelenítő teljesítményével kapcsolatos problémák merülhetnek fel.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public final float getSufficientResolution()
```

Visszaad vagy beállít egy értéket, amely meghatározza a képek felbontását a PDF-dokumentumban. **Olvasás/írás** float.

Érték: Ennek a paraméternek a hatása több tényezőtől függ. Az algoritmus a tulajdonság értéke, a forrás kép mérete és a képkeret mérete alapján a legjobb kimeneti képméretet próbálja elérni. Hasonló értékek használata ugyanazt az eredményt hozhatja. Javasolt 16 vagy 32 lépésben használni a hatás láthatóságához.

--------------------

A tulajdonság hat a fájlméretre, az exportálási időre és a képminőségre.

Az alapértelmezett érték **96**.

**Visszatérési érték:**
float
### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public final void setSufficientResolution(float value)
```

Visszaad vagy beállít egy értéket, amely meghatározza a képek felbontását a PDF-dokumentumban. **Olvasás/írás** float.

Érték: Ennek a paraméternek a hatása több tényezőtől függ. Az algoritmus a tulajdonság értéke, a forrás kép mérete és a képkeret mérete alapján a legjobb kimeneti képméretet próbálja elérni. Hasonló értékek használata ugyanazt az eredményt hozhatja. Javasolt 16 vagy 32 lépésben használni a hatás láthatóságához.

--------------------

A tulajdonság hat a fájlméretre, az exportálási időre és a képminőségre.

Az alapértelmezett érték **96**.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

Igaz, ha minden dia köré fekete keretet szeretne rajzolni. **Olvasás/írás** boolean.

--------------------

Alapértelmezett **false**.

**Visszatérési érték:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

Igaz, ha minden dia köré fekete keretet szeretne rajzolni. **Olvasás/írás** boolean.

--------------------

Alapértelmezett **false**.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public final Color getImageTransparentColor()
```

Megkapja vagy beállítja a kép átlátszó színét.

Érték: A kép átlátszó színének színe.

**Visszatérési érték:**
java.awt.Color
### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public final void setImageTransparentColor(Color value)
```

Megkapja vagy beállítja a kép átlátszó színét.

Érték: A kép átlátszó színének színe.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public final boolean getApplyImageTransparent()
```

Alkalmazza a megadott átlátszó színt egy képre, ha igaz.

**Visszatérési érték:**
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public final void setApplyImageTransparent(boolean value)
```

Alkalmazza a megadott átlátszó színt egy képre, ha igaz.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getIncludeOleData() {#getIncludeOleData--}
```
public final boolean getIncludeOleData()
```

Igaz, ha a bemutatóból az összes OLE-adatot beágyazott fájlokként kívánja a PDF-ben tárolni. **Olvasás/írás**  boolean .

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

Alapértelmezett **false**.

**Visszatérési érték:**
boolean
### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public final void setIncludeOleData(boolean value)
```

Igaz, ha a bemutatóból az összes OLE-adatot beágyazott fájlokként kívánja a PDF-ben tárolni. **Olvasás/írás**  boolean .

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

Alapértelmezett **false**.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
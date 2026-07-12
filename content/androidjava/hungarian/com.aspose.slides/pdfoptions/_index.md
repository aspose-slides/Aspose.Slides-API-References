---
title: PdfOptions
second_title: Aspose.Slides Android számára a Java API hivatkozásban
description: Lehetőségeket biztosít, amelyek szabályozzák, hogyan mentődik egy prezentáció Pdf formátumban.
type: docs
url: /hu/com.aspose.slides/pdfoptions/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Minden megvalósított interfész:**
[com.aspose.slides.IPdfOptions](../../com.aspose.slides/ipdfoptions)
```
public class PdfOptions extends SaveOptions implements IPdfOptions
```

Lehetővé teszi azokat a beállításokat, amelyek szabályozzák, hogyan mentődik egy prezentáció PDF formátumban.

--------------------

> ```
> The following example shows how to convert PowerPoint to PDF with custom options.
>  
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Példányosítja a PdfOptions osztályt
>      PdfOptions pdfOptions = new PdfOptions();
>      // Beállítja a JPEG minőséget
>      pdfOptions.setJpegQuality((byte)90);
>      // Beállítja a metafájlok viselkedését
>      pdfOptions.setSaveMetafilesAsPng(true);
>      // Beállítja a szövegtömörítés szintjét
>      pdfOptions.setTextCompression(PdfTextCompression.Flate);
>      // Meghatározza a PDF szabványt
>      pdfOptions.setCompliance(PdfCompliance.Pdf15);
>      // Mentés a prezentációt PDF-ként
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with hidden slides.
>  
>  // PowerPoint fájlt reprezentáló Presentation osztály példányosítása
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Példányosítja a PdfOptions osztályt
>      PdfOptions pdfOptions = new PdfOptions();
>      // Rejtett diákat ad hozzá
>      pdfOptions.setShowHiddenSlides(true);
>      // A prezentációt PDF-ként menti
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to password protected PDF.
>  
>  // PowerPoint fájlt reprezentáló Presentation objektum példányosítása
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Példányosítja a PdfOptions osztályt
>      PdfOptions pdfOptions = new PdfOptions();
>      // Beállítja a PDF jelszót és a hozzáférési jogosultságokat
>      pdfOptions.setPassword("password");
>      pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>      // A prezentációt PDF-ként menti
>      pres.save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with notes.
>  
>  // Prezentációfájlt reprezentáló Presentation objektum példányosítása
>  Presentation pres = new Presentation("SelectedSlides.pptx");
>  try {
>      Presentation auxPres = new Presentation();
>      try {
>          ISlide slide = pres.getSlides().get_Item(0);
>          auxPres.getSlides().insertClone(0, slide);
>          // Dia típusának és méretének beállítása
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
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Lekérdezi vagy beállítja a diák oldalra helyezésének módját a prezentáció [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) exportálásakor. |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Lekérdezi vagy beállítja a diák oldalra helyezésének módját a prezentáció [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) exportálásakor. |
| [getInkOptions()](#getInkOptions--) | Lehetővé teszi az opciókat, amelyek szabályozzák az Ink objektumok megjelenését az exportált dokumentumban. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákat vagy sem. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákat vagy sem. |
| [getTextCompression()](#getTextCompression--) | Megadja a dokumentumban lévő összes szöveges tartalomhoz használandó tömörítési típust. |
| [setTextCompression(int value)](#setTextCompression-int-) | Megadja a dokumentumban lévő összes szöveges tartalomhoz használandó tömörítési típust. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Jelzi, hogy az egyes képekhez a leghatékonyabb tömörítés (az alapértelmezett helyett) automatikusan ki legyen választva. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Jelzi, hogy az egyes képekhez a leghatékonyabb tömörítés (az alapértelmezett helyett) automatikusan ki legyen választva. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | Meghatározza, hogy az Aspose.Slides beágyazza-e a közös betűtípusokat az ASCII (33..127 kódtartomány) szövegekhez. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | Meghatározza, hogy az Aspose.Slides beágyazza-e a közös betűtípusokat az ASCII (33..127 kódtartomány) szövegekhez. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Lekérdezi vagy beállítja a felhasználó által definiált betűcsaládnevek tömbjét, amelyeket az Aspose.Slides közösnek tekint. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Lekérdezi vagy beállítja a felhasználó által definiált betűcsaládnevek tömbjét, amelyeket az Aspose.Slides közösnek tekint. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Meghatározza, hogy a betűtípus minden karaktere be legyen-e ágyazva vagy csak egy részhalmaz. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Meghatározza, hogy a betűtípus minden karaktere be legyen-e ágyazva vagy csak egy részhalmaz. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Jelzi, hogy a szöveget bitmapként kell-e rasterizálni és PDF-be menteni, ha a betűtípus nem támogatja a félkövér stílust. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Jelzi, hogy a szöveget bitmapként kell-e rasterizálni és PDF-be menteni, ha a betűtípus nem támogatja a félkövér stílust. |
| [getJpegQuality()](#getJpegQuality--) | Lekérdezi vagy beállítja a PDF-dokumentumban lévő JPEG képek minőségét meghatározó értéket. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Lekérdezi vagy beállítja a PDF-dokumentumban lévő JPEG képek minőségét meghatározó értéket. |
| [getCompliance()](#getCompliance--) | A generált PDF-dokumentum kívánt megfelelőségi szintje. |
| [setCompliance(int value)](#setCompliance-int-) | A generált PDF-dokumentum kívánt megfelelőségi szintje. |
| [getPassword()](#getPassword--) | Felhasználói jelszó beállítása a PDF-dokumentum védelméhez. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Felhasználói jelszó beállítása a PDF-dokumentum védelméhez. |
| [getAccessPermissions()](#getAccessPermissions--) | Tartalmaz egy zászlók halmazát, amely meghatározza, milyen hozzáférési jogosultságokat kell adni, amikor a dokumentum felhasználói hozzáféréssel nyílik meg. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Tartalmaz egy zászlók halmazát, amely meghatározza, milyen hozzáférési jogosultságokat kell adni, amikor a dokumentum felhasználói hozzáféréssel nyílik meg. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Igaz, ha minden prezentációban használt metafájl PNG képekre konvertálódik. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Igaz, ha minden prezentációban használt metafájl PNG képekre konvertálódik. |
| [getSufficientResolution()](#getSufficientResolution--) | Lekérdezi vagy beállítja a PDF-dokumentumban lévő képek felbontását meghatározó értéket. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Lekérdezi vagy beállítja a PDF-dokumentumban lévő képek felbontását meghatározó értéket. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Igaz, ha minden dia körül fekete keretet rajzol. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Igaz, ha minden dia körül fekete keretet rajzol. |
| [getImageTransparentColor()](#getImageTransparentColor--) | Lekérdezi vagy beállítja a kép átlátszó színét. |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | Lekérdezi vagy beállítja a kép átlátszó színét. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Alkalmazza a megadott átlátszó színt egy képre, ha igaz. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Alkalmazza a megadott átlátszó színt egy képre, ha igaz. |
| [getIncludeOleData()](#getIncludeOleData--) | Igaz, ha az összes OLE adat a prezentációból beágyazott fájlokká konvertálódik az eredmény PDF-ben. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | Igaz, ha az összes OLE adat a prezentációból beágyazott fájlokká konvertálódik az eredmény PDF-ben. |

### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```

Alapértelmezett konstruktor.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Lekérdezi vagy beállítja a diák oldalra helyezésének módját a prezentáció [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) exportálásakor.

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

**Visszatér:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Lekérdezi vagy beállítja a diák oldalra helyezésének módját a prezentáció [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) exportálásakor.

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
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Lehetővé teszi az opciókat, amelyek szabályozzák az Ink objektumok megjelenését az exportált dokumentumban. Csak olvasható [IInkOptions](../../com.aspose.slides/iinkoptions)

**Visszatér:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Megadja, hogy a generált dokumentumban legyenek-e rejtett diák vagy sem. Alapértelmezett érték: false.

**Visszatér:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Megadja, hogy a generált dokumentumban legyenek-e rejtett diák vagy sem. Alapértelmezett érték: false.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getTextCompression() {#getTextCompression--}
```
public final int getTextCompression()
```

Megadja a dokumentumban lévő összes szöveges tartalomhoz használandó tömörítési típust. Olvasás/írás [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Alapértelmezett érték: [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Visszatér:**
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public final void setTextCompression(int value)
```

Megadja a dokumentumban lévő összes szöveges tartalomhoz használandó tömörítési típust. Olvasás/írás [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Alapértelmezett érték: [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public final boolean getBestImagesCompressionRatio()
```

Jelzi, hogy az egyes képekhez a leghatékonyabb tömörítés (az alapértelmezett helyett) automatikusan ki legyen választva. Ha igazra van állítva, minden prezentációs kép esetén a legmegfelelőbb tömörítési algoritmus lesz kiválasztva, ami az eredmény PDF dokumentum kisebb méretéhez vezet.

--------------------

A legjobb képtömörítési arány kiválasztása számításigényes és további RAM-ot igényel, és ez a beállítás alapértelmezés szerint hamis.

--------------------

Alapértelmezett érték: false.

**Visszatér:**
boolean
### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public final void setBestImagesCompressionRatio(boolean value)
```

Jelzi, hogy az egyes képekhez a leghatékonyabb tömörítés (az alapértelmezett helyett) automatikusan ki legyen választva. Ha igazra van állítva, minden prezentációs kép esetén a legmegfelelőbb tömörítési algoritmus lesz kiválasztva, ami az eredmény PDF dokumentum kisebb méretéhez vezet.

--------------------

A legjobb képtömörítési arány kiválasztása számításigényes és további RAM-ot igényel, és ez a beállítás alapértelmezés szerint hamis.

--------------------

Alapértelmezett érték: false.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public final boolean getEmbedTrueTypeFontsForASCII()
```

Meghatározza, hogy az Aspose.Slides beágyazza-e a közös betűtípusokat az ASCII (33..127 kódtartomány) szöveghez. 127 fölötti karakterkódok esetén a betűtípusok mindig be vannak ágyazva. A közös betűtípusok listája tartalmazza a PDF alap 14 betűtípusát és a felhasználó által megadott további betűtípusokat. Olvasás/írás boolean.

--------------------

Alapértelmezett érték: **true**.

**Visszatér:**
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public final void setEmbedTrueTypeFontsForASCII(boolean value)
```

Meghatározza, hogy az Aspose.Slides beágyazza-e a közös betűtípusokat az ASCII (33..127 kódtartomány) szöveghez. 127 fölötti karakterkódok esetén a betűtípusok mindig be vannak ágyazva. A közös betűtípusok listája tartalmazza a PDF alap 14 betűtípusát és a felhasználó által megadott további betűtípusokat. Olvasás/írás boolean.

--------------------

Alapértelmezett érték: **true**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public final String[] getAdditionalCommonFontFamilies()
```

Lekérdezi vagy beállítja a felhasználó által definiált betűcsaládnevek tömbjét, amelyeket az Aspose.Slides közösnek tekint. Olvasás/írás String[].

**Visszatér:**
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public final void setAdditionalCommonFontFamilies(String[] value)
```

Lekérdezi vagy beállítja a felhasználó által definiált betűcsaládnevek tömbjét, amelyeket az Aspose.Slides közösnek tekint. Olvasás/írás String[].

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public final boolean getEmbedFullFonts()
```

Meghatározza, hogy a betűtípus minden karaktere be legyen-e ágyazva vagy csak egy részhalmaz. Olvasás/írás boolean.

--------------------

Alapértelmezett érték: **false**.

**Visszatér:**
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public final void setEmbedFullFonts(boolean value)
```

Meghatározza, hogy a betűtípus minden karaktere be legyen-e ágyazva vagy csak egy részhalmaz. Olvasás/írás boolean.

--------------------

Alapértelmezett érték: **false**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public final boolean getRasterizeUnsupportedFontStyles()
```

Jelzi, hogy a szöveget bitmapként kell-e rasterizálni és PDF-be menteni, ha a betűtípus nem támogatja a félkövér stílust. Ez a megközelítés bizonyos betűtípusok esetén javíthatja a szöveg minőségét az eredmény PDF-ben. Olvasás/írás boolean.

--------------------

Alapértelmezett érték: **false**.

**Visszatér:**
boolean
### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public final void setRasterizeUnsupportedFontStyles(boolean value)
```

Jelzi, hogy a szöveget bitmapként kell-e rasterizálni és PDF-be menteni, ha a betűtípus nem támogatja a félkövér stílust. Ez a megközelítés bizonyos betűtípusok esetén javíthatja a szöveg minőségét az eredmény PDF-ben. Olvasás/írás boolean.

--------------------

Alapértelmezett érték: **false**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

Lekérdezi vagy beállítja a PDF-dokumentumban lévő JPEG képek minőségét meghatározó értéket. Olvasás/írás byte.

--------------------

Csak akkor hat, ha a dokumentum JPEG képeket tartalmaz.

Ezt a tulajdonságot használhatja a képek minőségének lekérdezésére vagy beállítására egy dokumentumban PDF formátumban történő mentéskor. Az érték 0 és 100 között változhat, ahol 0 a legrosszabb minőséget, de a maximális tömörítést jelent, és 100 a legjobb minőséget, de a minimális tömörítést.

Az alapértelmezett érték **100**.

**Visszatér:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

Lekérdezi vagy beállítja a PDF-dokumentumban lévő JPEG képek minőségét meghatározó értéket. Olvasás/írás byte.

--------------------

Csak akkor hat, ha a dokumentum JPEG képeket tartalmaz.

Ezt a tulajdonságot használhatja a képek minőségének lekérdezésére vagy beállítására egy dokumentumban PDF formátumban történő mentéskor. Az érték 0 és 100 között változhat, ahol 0 a legrosszabb minőséget, de a maximális tömörítést jelent, és 100 a legjobb minőséget, de a minimális tömörítést.

Az alapértelmezett érték **100**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```

A generált PDF-dokumentum kívánt megfelelőségi szintje. Olvasás/írás [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Alapértelmezett érték: [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Visszatér:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```

A generált PDF-dokumentum kívánt megfelelőségi szintje. Olvasás/írás [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Alapértelmezett érték: [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

Felhasználói jelszó beállítása a PDF-dokumentum védelméhez. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

Felhasználói jelszó beállítása a PDF-dokumentum védelméhez. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public final int getAccessPermissions()
```

Tartalmaz egy zászlók halmazát, amely meghatározza, milyen hozzáférési jogosultságokat kell biztosítani, amikor a dokumentum felhasználói hozzáféréssel nyílik meg. Lásd [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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


**Visszatér:**
int
### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public final void setAccessPermissions(int value)
```

Tartalmaz egy zászlók halmazát, amely meghatározza, milyen hozzáférési jogosultságokat kell biztosítani, amikor a dokumentum felhasználói hozzáféréssel nyílik meg. Lásd [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

Igaz, ha minden prezentációban használt metafájl PNG képekké konvertálódik. Olvasás/írás boolean.

--------------------

Alapértelmezett érték: **true**. A PDF-dokumentum tartalmazhat vektorgrafikákat és raszteres képeket. Ha a SaveMetafilesAsPng igazra van állítva, akkor a forrás metafájl kép PNG formátumba konvertálódik, és raszteres képként kerül a PDF-be. Ha a SaveMetafilesAsPng hamisra van állítva, akkor a forrás metafájl PDF vektorgrafikává konvertálódik. Minden megközelítésnek megvannak az előnyei és hátrányai. Például, ha a Metafile PNG-re konvertálódik, bizonyos minőségveszteség fordulhat elő a dokumentum méretezése során. Ha a Metafile PDF vektorgrafikává konvertálódik, akkor teljesítményproblémák merülhetnek fel a PDF-megtekintő eszközben.

**Visszatér:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

Igaz, ha minden prezentációban használt metafájl PNG képekké konvertálódik. Olvasás/írás boolean.

--------------------

Alapértelmezett érték: **true**. A PDF-dokumentum tartalmazhat vektorgrafikákat és raszteres képeket. Ha a SaveMetafilesAsPng igazra van állítva, akkor a forrás metafájl kép PNG formátumba konvertálódik, és raszteres képként kerül a PDF-be. Ha a SaveMetafilesAsPng hamisra van állítva, akkor a forrás metafájl PDF vektorgrafikává konvertálódik. Minden megközelítésnek megvannak az előnyei és hátrányai. Például, ha a Metafile PNG-re konvertálódik, bizonyos minőségveszteség fordulhat elő a dokumentum méretezése során. Ha a Metafile PDF vektorgrafikává konvertálódik, akkor teljesítményproblémák merülhetnek fel a PDF-megtekintő eszközben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public final float getSufficientResolution()
```

Lekérdezi vagy beállítja a PDF-dokumentumban lévő képek felbontását meghatározó értéket. Olvasás/írás float.

Érték: Ennek a paraméternek a hatása néhány tényezőtől függ. Az algoritmus megpróbálja a legjobb kimeneti képméretet elérni a tulajdonság értéke, a forráskép mérete és a képkeret mérete alapján. Hasonló tulajdonságértékek használata ugyanazt az eredményt adhatja. Ajánlott 16 vagy 32 lépést használni a látható hatás érdekében.

--------------------

A tulajdonság hatással van a fájlméretre, az export időtartamára és a képminőségre.

Az alapértelmezett érték **96**.

**Visszatér:**
float
### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public final void setSufficientResolution(float value)
```

Lekérdezi vagy beállítja a PDF-dokumentumban lévő képek felbontását meghatározó értéket. Olvasás/írás float.

Érték: Ennek a paraméternek a hatása néhány tényezőtől függ. Az algoritmus megpróbálja a legjobb kimeneti képméretet elérni a tulajdonság értéke, a forráskép mérete és a képkeret mérete alapján. Hasonló tulajdonságértékek használata ugyanazt az eredményt adhatja. Ajánlott 16 vagy 32 lépést használni a látható hatás érdekében.

--------------------

A tulajdonság hatással van a fájlméretre, az export időtartamára és a képminőségre.

Az alapértelmezett érték **96**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

Igaz, ha minden dia körül fekete keretet rajzol. Olvasás/írás boolean.

--------------------

Alapértelmezett érték: **false**.

**Visszatér:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

Igaz, ha minden dia körül fekete keretet rajzol. Olvasás/írás boolean.

--------------------

Alapértelmezett érték: **false**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public final Integer getImageTransparentColor()
```

Lekérdezi vagy beállítja a kép átlátszó színét.

Érték: A kép átlátszó színe.

**Visszatér:**
java.lang.Integer
### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public final void setImageTransparentColor(Integer value)
```

Lekérdezi vagy beállítja a kép átlátszó színét.

Érték: A kép átlátszó színe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public final boolean getApplyImageTransparent()
```

Alkalmazza a megadott átlátszó színt egy képre, ha igaz.

**Visszatér:**
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public final void setApplyImageTransparent(boolean value)
```

Alkalmazza a megadott átlátszó színt egy képre, ha igaz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getIncludeOleData() {#getIncludeOleData--}
```
public final boolean getIncludeOleData()
```

Igaz, ha az összes OLE adat a prezentációból beágyazott fájlokká konvertálódik az eredmény PDF-ben. Olvasás/írás boolean.

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

Alapértelmezett érték: **false**.

**Visszatér:**
boolean
### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public final void setIncludeOleData(boolean value)
```

Igaz, ha az összes OLE adat a prezentációból beágyazott fájlokká konvertálódik az eredmény PDF-ben. Olvasás/írás boolean.

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

Alapértelmezett érték: **false**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
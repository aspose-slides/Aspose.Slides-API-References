---
title: IPdfOptions
second_title: Aspose.Slides Java API Referencia
description: Lehetőségeket biztosít, amelyek szabályozzák, hogyan mentődik el egy prezentáció PDF formátumban.
type: docs
url: /hu/com.aspose.slides/ipdfoptions/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPdfOptions extends ISaveOptions
```

Lehetőségeket biztosít, amelyek szabályozzák, hogyan mentődik el egy prezentáció PDF formátumban.

## Módszerek

| Method | Description |
| --- | --- |
| [getTextCompression()](#getTextCompression--) | Meghatározza a dokumentumban az összes szöveges tartalomhoz használandó tömörítési típust. |
| [setTextCompression(int value)](#setTextCompression-int-) | Meghatározza a dokumentumban az összes szöveges tartalomhoz használandó tömörítési típust. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Megadja, hogy minden képnél a leghatékonyabb tömörítés (az alapértelmezett helyett) automatikusan ki legyen választva. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Megadja, hogy minden képnél a leghatékonyabb tömörítés (az alapértelmezett helyett) automatikusan ki legyen választva. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | Igaz, ha true type betűket ágyaz be az ASCII 32-127 karakterekhez. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | Igaz, ha true type betűket ágyaz be az ASCII 32-127 karakterekhez. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákot vagy sem. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákot vagy sem. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Visszaad vagy beállít egy tömböt a felhasználó által megadott betűcsaládnevekből, amelyeket az Aspose.Slides közösnek tekint. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Visszaad vagy beállít egy tömböt a felhasználó által megadott betűcsaládnevekből, amelyeket az Aspose.Slides közösnek tekint. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Meghatározza, hogy a betűtípus összes karaktere be legyen-e ágyazva vagy csak egy részhalmaz. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Meghatározza, hogy a betűtípus összes karaktere be legyen-e ágyazva vagy csak egy részhalmaz. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Megadja, hogy a szöveget bitmapként kell-e raszterizálni és PDF-be menteni, ha a betűtípus nem támogatja a félkövér formázást. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Megadja, hogy a szöveget bitmapként kell-e raszterizálni és PDF-be menteni, ha a betűtípus nem támogatja a félkövér formázást. |
| [getJpegQuality()](#getJpegQuality--) | Visszaad vagy beállít egy értéket, amely meghatározza a JPEG képek minőségét a PDF dokumentumban. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Visszaad vagy beállít egy értéket, amely meghatározza a JPEG képek minőségét a PDF dokumentumban. |
| [getCompliance()](#getCompliance--) | Kívánt megfelelőségi szint a generált PDF dokumentumhoz. |
| [setCompliance(int value)](#setCompliance-int-) | Kívánt megfelelőségi szint a generált PDF dokumentumhoz. |
| [getPassword()](#getPassword--) | Felhasználói jelszó beállítása a PDF dokumentum védelméhez. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Felhasználói jelszó beállítása a PDF dokumentum védelméhez. |
| [getAccessPermissions()](#getAccessPermissions--) | Tartalmaz egy zászlók halmazát, amely meghatározza, hogy milyen hozzáférési jogosultságok legyenek engedélyezve a dokumentum felhasználói hozzáféréssel történő megnyitásakor. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Tartalmaz egy zászlók halmazát, amely meghatározza, hogy milyen hozzáférési jogosultságok legyenek engedélyezve a dokumentum felhasználói hozzáféréssel történő megnyitásakor. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Igaz, ha a prezentációban használt összes metafájl PNG képekké konvertálódik. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Igaz, ha a prezentációban használt összes metafájl PNG képekké konvertálódik. |
| [getSufficientResolution()](#getSufficientResolution--) | Visszaad vagy beállít egy értéket, amely meghatározza a képek felbontását a PDF dokumentumban. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Visszaad vagy beállít egy értéket, amely meghatározza a képek felbontását a PDF dokumentumban. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Igaz, ha minden dia köré fekete keretet rajzol. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Igaz, ha minden dia köré fekete keretet rajzol. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Lekéri vagy beállítja azt a módot, ahogyan a diák az oldalra kerülnek a prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Lekéri vagy beállítja azt a módot, ahogyan a diák az oldalra kerülnek a prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getImageTransparentColor()](#getImageTransparentColor--) | Lekéri vagy beállítja a kép átlátszó színét. |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | Lekéri vagy beállítja a kép átlátszó színét. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Alkalmazza a megadott átlátszó színt a képre, ha igaz. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Alkalmazza a megadott átlátszó színt a képre, ha igaz. |
| [getInkOptions()](#getInkOptions--) | Lehetőségeket biztosít, amelyek szabályozzák az Ink objektumok megjelenését az exportált dokumentumban. |
| [getIncludeOleData()](#getIncludeOleData--) | Igaz, ha az összes OLE adatot a prezentációból beágyazott fájlokká konvertálja a létrejövő PDF-ben. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | Igaz, ha az összes OLE adatot a prezentációból beágyazott fájlokká konvertálja a létrejövő PDF-ben. |

### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```

Meghatározza a dokumentumban az összes szöveges tartalomhoz használandó tömörítési típust. Olvasás/írás [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Alapértelmezett érték [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Visszatér:**  
int

### setTextCompression(int value) {#setTextCompression-int-}
```
public abstract void setTextCompression(int value)
```

Meghatározza a dokumentumban az összes szöveges tartalomhoz használandó tömörítési típust. Olvasás/írás [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Alapértelmezett érték [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public abstract boolean getBestImagesCompressionRatio()
```

Megadja, hogy minden képnél a leghatékonyabb tömörítés (az alapértelmezett helyett) automatikusan ki legyen választva. Ha igaz, minden képnél a legmegfelelőbb tömörítési algoritmus kerül kiválasztásra, ami kisebb méretű PDF-et eredményez.

--------------------

A legjobb képtömörítési arány kiválasztása számításigényes és további RAM-ot igényel, alapértelmezés szerint ez a beállítás hamis.

--------------------

Alapértelmezett érték hamis.

**Visszatér:**  
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```

Megadja, hogy minden képnél a leghatékonyabb tömörítés (az alapértelmezett helyett) automatikusan ki legyen választva. Ha igaz, minden képnél a legmegfelelőbb tömörítési algoritmus kerül kiválasztásra, ami kisebb méretű PDF-et eredményez.

--------------------

A legjobb képtömörítési arány kiválasztása számításigényes és további RAM-ot igényel, alapértelmezés szerint ez a beállítás hamis.

--------------------

Alapértelmezett érték hamis.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public abstract boolean getEmbedTrueTypeFontsForASCII()
```

Igaz, ha true type betűket ágyaz be az ASCII 32-127 karakterekhez. A 127-nél nagyobb karakterkódok betűi mindig be vannak ágyazva. Olvasás/írás boolean.

--------------------

Alapértelmezett érték **true**.

**Visszatér:**  
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```

Igaz, ha true type betűket ágyaz be az ASCII 32-127 karakterekhez. A 127-nél nagyobb karakterkódok betűi mindig be vannak ágyazva. Olvasás/írás boolean.

--------------------

Alapértelmezett érték **true**.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákot vagy sem. Alapértelmezett érték hamis.

**Visszatér:**  
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákot vagy sem. Alapértelmezett érték hamis.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public abstract String[] getAdditionalCommonFontFamilies()
```

Visszaad vagy beállít egy tömböt a felhasználó által megadott betűcsaládnevekből, amelyeket az Aspose.Slides közösnek tekint. Olvasás/írás String[].

**Visszatér:**  
java.lang.String[]

### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```

Visszaad vagy beállít egy tömböt a felhasználó által megadott betűcsaládnevekből, amelyeket az Aspose.Slides közösnek tekint. Olvasás/írás String[].

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```

Meghatározza, hogy a betűtípus összes karaktere be legyen-e ágyazva vagy csak egy részhalmaz. Olvasás/írás boolean.

--------------------

Alapértelmezett érték **false**.

**Visszatér:**  
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```

Meghatározza, hogy a betűtípus összes karaktere be legyen-e ágyazva vagy csak egy részhalmaz. Olvasás/írás boolean.

--------------------

Alapértelmezett érték **false**.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public abstract boolean getRasterizeUnsupportedFontStyles()
```

Megadja, hogy a szöveget bitmapként kell-e raszterizálni és PDF-be menteni, ha a betűtípus nem támogatja a félkövér formázást. Ez a megközelítés javíthatja a szöveg minőségét a létrejövő PDF-ben bizonyos betűtípusok esetén. Olvasás/írás boolean.

--------------------

Alapértelmezett érték **false**.

**Visszatér:**  
boolean

### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public abstract void setRasterizeUnsupportedFontStyles(boolean value)
```

Megadja, hogy a szöveget bitmapként kell-e raszterizálni és PDF-be menteni, ha a betűtípus nem támogatja a félkövér formázást. Ez a megközelítés javíthatja a szöveg minőségét a létrejövő PDF-ben bizonyos betűtípusok esetén. Olvasás/írás boolean.

--------------------

Alapértelmezett érték **false**.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

Visszaad vagy beállít egy értéket, amely meghatározza a JPEG képek minőségét a PDF dokumentumban. Olvasás/írás byte.

--------------------

Csak akkor van hatása, ha a dokumentum JPEG képeket tartalmaz.

Ezzel a tulajdonsággal a képek minőségét állíthatja be PDF formátumban történő mentéskor. Az érték 0 és 100 között változhat, ahol a 0 a legrosszabb minőséget, legnagyobb tömörítést, a 100 a legjobb minőséget, legkisebb tömörítést jelenti.

Az alapértelmezett érték **100**.

**Visszatér:**  
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

Visszaad vagy beállít egy értéket, amely meghatározza a JPEG képek minőségét a PDF dokumentumban. Olvasás/írás byte.

--------------------

Csak akkor van hatása, ha a dokumentum JPEG képeket tartalmaz.

Ezzel a tulajdonsággal a képek minőségét állíthatja be PDF formátumban történő mentéskor. Az érték 0 és 100 között változhat, ahol a 0 a legrosszabb minőséget, legnagyobb tömörítést, a 100 a legjobb minőséget, legkisebb tömörítést jelenti.

Az alapértelmezett érték **100**.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public abstract int getCompliance()
```

Kívánt megfelelőségi szint a generált PDF dokumentumhoz. Olvasás/írás [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Alapértelmezett érték [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Visszatér:**  
int

### setCompliance(int value) {#setCompliance-int-}
```
public abstract void setCompliance(int value)
```

Kívánt megfelelőségi szint a generált PDF dokumentumhoz. Olvasás/írás [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Alapértelmezett érték [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

Felhasználói jelszó beállítása a PDF dokumentum védelméhez. Olvasás/írás String.

**Visszatér:**  
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

Felhasználói jelszó beállítása a PDF dokumentum védelméhez. Olvasás/írás String.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public abstract int getAccessPermissions()
```

Tartalmaz egy zászlók halmazát, amely meghatározza, hogy milyen hozzáférési jogosultságok legyenek engedélyezve a dokumentum felhasználói hozzáféréssel történő megnyitásakor. Lásd [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
public abstract void setAccessPermissions(int value)
```

Tartalmaz egy zászlók halmazát, amely meghatározza, hogy milyen hozzáférési jogosultságok legyenek engedélyezve a dokumentum felhasználói hozzáféréssel történő megnyitásakor. Lásd [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
public abstract boolean getSaveMetafilesAsPng()
```

Igaz, ha a prezentációban használt összes metafájl PNG képekké konvertálódik. Olvasás/írás boolean.

--------------------

Alapértelmezett érték **true**. A PDF dokumentum tartalmazhat vektoros grafikát és raszteres képeket. Ha a SaveMetafilesAsPng igaz, a forrás Metafile kép PNG formátumba konvertálódik és raszteres képként kerül be a PDF-be. Ha hamis, a forrás Metafile PDF vektoros grafikává alakul. Mindkét megközelítésnek vannak előnyei és hátrányai. Például PNG-re konvertálva minőségvesztés fordulhat elő a dokumentum nagyításakor, míg vektoros grafika nagyobb teljesítményigényt jelenthet a PDF-nézőben.

**Visszatér:**  
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

Igaz, ha a prezentációban használt összes metafájl PNG képekké konvertálódik. Olvasás/írás boolean.

--------------------

Alapértelmezett érték **true**. A PDF dokumentum tartalmazhat vektoros grafikát és raszteres képeket. Ha a SaveMetafilesAsPng igaz, a forrás Metafile kép PNG formátumba konvertálódik és raszteres képként kerül be a PDF-be. Ha hamis, a forrás Metafile PDF vektoros grafikává alakul. Mindkét megközelítésnek vannak előnyei és hátrányai. Például PNG-re konvertálva minőségvesztés fordulhat elő a dokumentum nagyításakor, míg vektoros grafika nagyobb teljesítményigényt jelenthet a PDF-nézőben.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```

Visszaad vagy beállít egy értéket, amely meghatározza a képek felbontását a PDF dokumentumban. Olvasás/írás float.

Érték: Ennek a paraméternek a hatása több tényezőtől függ. Az algoritmus a megadott érték, a forráskép mérete és a képkocka mérete alapján kísérli meg a legjobb kimeneti méretet. Hasonló értékek hasonló eredményt adhatnak. Javasolt 16 vagy 32 lépésben használni a látható hatás érdekében.

--------------------

A tulajdonság befolyásolja a fájlméretet, az exportálási időt és a képminőséget.

Az alapértelmezett érték **96**.

**Visszatér:**  
float

### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```

Visszaad vagy beállít egy értéket, amely meghatározza a képek felbontását a PDF dokumentumban. Olvasás/írás float.

Érték: Ennek a paraméternek a hatása több tényezőtől függ. Az algoritmus a megadott érték, a forráskép mérete és a képkocka mérete alapján kísérli meg a legjobb kimeneti méretet. Hasonló értékek hasonló eredményt adhatnak. Javasolt 16 vagy 32 lépésben használni a látható hatás érdekében.

--------------------

A tulajdonság befolyásolja a fájlméretet, az exportálási időt és a képminőséget.

Az alapértelmezett érték **96**.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

Igaz, ha minden dia köré fekete keretet rajzol. Olvasás/írás boolean.

--------------------

Alapértelmezett érték **false**.

**Visszatér:**  
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

Igaz, ha minden dia köré fekete keretet rajzol. Olvasás/írás boolean.

--------------------

Alapértelmezett érték **false**.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Lekéri vagy beállítja azt a módot, ahogyan a diák az oldalra kerülnek a prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Lekéri vagy beállítja azt a módot, ahogyan a diák az oldalra kerülnek a prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

### getImageTransparentColor() {#getImageTransparentColor--}
```
public abstract Color getImageTransparentColor()
```

Lekéri vagy beállítja a kép átlátszó színét.

Érték: A kép átlátszó színe.

**Visszatér:**  
java.awt.Color

### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public abstract void setImageTransparentColor(Color value)
```

Lekéri vagy beállítja a kép átlátszó színét.

Érték: A kép átlátszó színe.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public abstract boolean getApplyImageTransparent()
```

Alkalmazza a megadott átlátszó színt a képre, ha igaz.

**Visszatér:**  
boolean

### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public abstract void setApplyImageTransparent(boolean value)
```

Alkalmazza a megadott átlátszó színt a képre, ha igaz.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Lehetőségeket biztosít, amelyek szabályozzák az Ink objektumok megjelenését az exportált dokumentumban. Csak olvasás [IInkOptions](../../com.aspose.slides/iinkoptions)

**Visszatér:**  
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getIncludeOleData() {#getIncludeOleData--}
```
public abstract boolean getIncludeOleData()
```

Igaz, ha az összes OLE adatot a prezentációból beágyazott fájlokká konvertálja a létrejövő PDF-ben. Olvasás/írás boolean.

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

Alapértelmezett érték **false**.

**Visszatér:**  
boolean

### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public abstract void setIncludeOleData(boolean value)
```

Igaz, ha az összes OLE adatot a prezentációból beágyazott fájlokká konvertálja a létrejövő PDF-ben. Olvasás/írás boolean.

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

Alapértelmezett érték **false**.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
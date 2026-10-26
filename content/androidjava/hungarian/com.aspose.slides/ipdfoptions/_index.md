---
title: IPdfOptions
second_title: Aspose.Slides Android-hoz Java API hivatkozás
description: Opciókat biztosít, amelyek szabályozzák, hogyan ment egy prezentációt PDF formátumban.
type: docs
url: /hu/com.aspose.slides/ipdfoptions/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPdfOptions extends ISaveOptions
```

Provides options that control how a presentation is saved in Pdf format.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getTextCompression()](#getTextCompression--) | Megadja a dokumentumban használandó összes szöveges tartalom tömörítési típusát. |
| [setTextCompression(int value)](#setTextCompression-int-) | Megadja a dokumentumban használandó összes szöveges tartalom tömörítési típusát. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Jelzi, hogy minden kép esetén a leghatékonyabb tömörítést (az alapértelmezett helyett) automatikusan ki kell-e választani. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Jelzi, hogy minden kép esetén a leghatékonyabb tömörítést (az alapértelmezett helyett) automatikusan ki kell-e választani. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | Igaz, ha a 32-127 ASCII karakterekhez TrueType betűket kell beágyazni. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | Igaz, ha a 32-127 ASCII karakterekhez TrueType betűket kell beágyazni. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Megadja, hogy a generált dokumentumban legyenek-e rejtett diák. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Megadja, hogy a generált dokumentumban legyenek-e rejtett diák. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Visszaad vagy beállít egy tömböt a felhasználó által meghatározott betűcsaládnevekkel, amelyeket az Aspose.Slides közösnek tekint. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Visszaad vagy beállít egy tömböt a felhasználó által meghatározott betűcsaládnevekkel, amelyeket az Aspose.Slides közösnek tekint. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Meghatározza, hogy a betűtípus összes karakterét be kell-e ágyazni, vagy csak a használt részhalmazt. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Meghatározza, hogy a betűtípus összes karakterét be kell-e ágyazni, vagy csak a használt részhalmazt. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Jelzi, hogy a szöveget bitmapként kell-e rasterizálni és PDF-be menteni, ha a betűtípus nem támogatja a félkövér stílust. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Jelzi, hogy a szöveget bitmapként kell-e rasterizálni és PDF-be menteni, ha a betűtípus nem támogatja a félkövér stílust. |
| [getJpegQuality()](#getJpegQuality--) | Visszaad vagy beállít egy értéket, amely meghatározza a JPEG képek minőségét a PDF dokumentumban. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Visszaad vagy beállít egy értéket, amely meghatározza a JPEG képek minőségét a PDF dokumentumban. |
| [getCompliance()](#getCompliance--) | A generált PDF dokumentum kívánt megfelelőségi szintje. |
| [setCompliance(int value)](#setCompliance-int-) | A generált PDF dokumentum kívánt megfelelőségi szintje. |
| [getPassword()](#getPassword--) | Felhasználói jelszó beállítása a PDF dokumentum védelméhez. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Felhasználói jelszó beállítása a PDF dokumentum védelméhez. |
| [getAccessPermissions()](#getAccessPermissions--) | Tartalmaz egy zászlók halmazát, amelyek meghatározzák, hogy milyen hozzáférési jogosultságokat kell megadni, amikor a dokumentum felhasználói hozzáféréssel nyílik meg. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Tartalmaz egy zászlók halmazát, amelyek meghatározzák, hogy milyen hozzáférési jogosultságokat kell megadni, amikor a dokumentum felhasználói hozzáféréssel nyílik meg. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Igaz, ha a prezentációban használt összes metafájlt PNG képekké kell konvertálni. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Igaz, ha a prezentációban használt összes metafájlt PNG képekké kell konvertálni. |
| [getSufficientResolution()](#getSufficientResolution--) | Visszaad vagy beállít egy értéket, amely meghatározza a képek felbontását a PDF dokumentumban. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Visszaad vagy beállít egy értéket, amely meghatározza a képek felbontását a PDF dokumentumban. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Igaz, ha minden dia köré fekete keretet kell rajzolni. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Igaz, ha minden dia köré fekete keretet kell rajzolni. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Lekéri vagy beállítja azt a módot, amelyben a diák az oldalon helyezkednek el prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Lekéri vagy beállítja azt a módot, amelyben a diák az oldalon helyezkednek el prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getImageTransparentColor()](#getImageTransparentColor--) | Lekéri vagy beállítja a kép átlátszó színét. |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | Lekéri vagy beállítja a kép átlátszó színét. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | A megadott átlátszó színt alkalmazza a képre, ha igaz. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | A megadott átlátszó színt alkalmazza a képre, ha igaz. |
| [getInkOptions()](#getInkOptions--) | Olyan beállításokat biztosít, amelyek szabályozzák a tintával készült objektumok megjelenését az exportált dokumentumban. |
| [getIncludeOleData()](#getIncludeOleData--) | Igaz, ha a prezentáció összes OLE adatát beágyazott fájlokká kell konvertálni a keletkező PDF-ben. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | Igaz, ha a prezentáció összes OLE adatát beágyazott fájlokká kell konvertálni a keletkező PDF-ben. |

### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```

Megadja a dokumentumban használandó összes szöveges tartalom tömörítési típusát. Olvasás/írás [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Alapértelmezett: [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Visszatérési érték:**
int

### setTextCompression(int value) {#setTextCompression-int-}
```
public abstract void setTextCompression(int value)
```

Megadja a dokumentumban használandó összes szöveges tartalom tömörítési típusát. Olvasás/írás [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Alapértelmezett: [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public abstract boolean getBestImagesCompressionRatio()
```

Jelzi, hogy minden kép esetén a leghatékonyabb tömörítést (az alapértelmezett helyett) automatikusan ki kell-e választani. Ha igazra van állítva, a prezentáció minden képe számára a legmegfelelőbb tömörítési algoritmus kerül kiválasztásra, ami a keletkező PDF dokumentum kisebb méretéhez vezet.

--------------------

Az optimális képtömörítési arány kiválasztása számításigényes, további RAM-ot igényel, és ez az opció alapértelmezés szerint hamis.

--------------------

Alapértelmezett: hamis.

**Visszatérési érték:**
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```

Jelzi, hogy minden kép esetén a leghatékonyabb tömörítést (az alapértelmezett helyett) automatikusan ki kell-e választani. Ha igazra van állítva, a prezentáció minden képe számára a legmegfelelőbb tömörítési algoritmus kerül kiválasztásra, ami a keletkező PDF dokumentum kisebb méretéhez vezet.

--------------------

Az optimális képtömörítési arány kiválasztása számításigényes, további RAM-ot igényel, és ez az opció alapértelmezés szerint hamis.

--------------------

Alapértelmezett: hamis.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public abstract boolean getEmbedTrueTypeFontsForASCII()
```

Igaz, ha a 32-127 ASCII karakterekhez TrueType betűket kell beágyazni. A 127-nél nagyobb karakterkódok betűi mindig be vannak ágyazva. Olvasás/írás boolean.

--------------------

Alapértelmezett: **true**.

**Visszatérési érték:**
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```

Igaz, ha a 32-127 ASCII karakterekhez TrueType betűket kell beágyazni. A 127-nél nagyobb karakterkódok betűi mindig be vannak ágyazva. Olvasás/írás boolean.

--------------------

Alapértelmezett: **true**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Megadja, hogy a generált dokumentumban legyenek-e rejtett diák. Alapértelmezett: hamis.

**Visszatérési érték:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Megadja, hogy a generált dokumentumban legyenek-e rejtett diák. Alapértelmezett: hamis.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public abstract String[] getAdditionalCommonFontFamilies()
```

Visszaad vagy beállít egy tömböt a felhasználó által meghatározott betűcsaládnevekkel, amelyeket az Aspose.Slides közösnek tekint. Olvasás/írás String[].

**Visszatérési érték:**
java.lang.String[]

### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```

Visszaad vagy beállít egy tömböt a felhasználó által meghatározott betűcsaládnevekkel, amelyeket az Aspose.Slides közösnek tekint. Olvasás/írás String[].

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```

Meghatározza, hogy a betűtípus összes karakterét be kell-e ágyazni, vagy csak a használt részhalmazt. Olvasás/írás boolean.

--------------------

Alapértelmezett: **false**.

**Visszatérési érték:**
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```

Meghatározza, hogy a betűtípus összes karakterét be kell-e ágyazni, vagy csak a használt részhalmazt. Olvasás/írás boolean.

--------------------

Alapértelmezett: **false**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public abstract boolean getRasterizeUnsupportedFontStyles()
```

Jelzi, hogy a szöveget bitmapként kell-e rasterizálni és PDF-be menteni, ha a betűtípus nem támogatja a félkövér stílust. Ez a megközelítés bizonyos betűtípusok esetén javíthatja a szöveg minőségét a keletkező PDF-ben. Olvasás/írás boolean.

--------------------

Alapértelmezett: **false**.

**Visszatérési érték:**
boolean

### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public abstract void setRasterizeUnsupportedFontStyles(boolean value)
```

Jelzi, hogy a szöveget bitmapként kell-e rasterizálni és PDF-be menteni, ha a betűtípus nem támogatja a félkövér stílust. Ez a megközelítés bizonyos betűtípusok esetén javíthatja a szöveg minőségét a keletkező PDF-ben. Olvasás/írás boolean.

--------------------

Alapértelmezett: **false**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

Visszaad vagy beállít egy értéket, amely meghatározza a JPEG képek minőségét a PDF dokumentumban. Olvasás/írás byte.

--------------------

Csak akkor hat, ha a dokumentum JPEG képeket tartalmaz.

Használd ezt a tulajdonságot a képek minőségének beállításához PDF formátumba mentéskor. Az érték 0 és 100 között változhat, ahol 0 a legrosszabb minőség, de maximális tömörítés, 100 pedig a legjobb minőség, de legkisebb tömörítés.

Az alapértelmezett érték **100**.

**Visszatérési érték:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

Visszaad vagy beállít egy értéket, amely meghatározza a JPEG képek minőségét a PDF dokumentumban. Olvasás/írás byte.

--------------------

Csak akkor hat, ha a dokumentum JPEG képeket tartalmaz.

Használd ezt a tulajdonságot a képek minőségének beállításához PDF formátumba mentéskor. Az érték 0 és 100 között változhat, ahol 0 a legrosszabb minőség, de maximális tömörítés, 100 pedig a legjobb minőség, de legkisebb tömörítés.

Az alapértelmezett érték **100**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public abstract int getCompliance()
```

A generált PDF dokumentum kívánt megfelelőségi szintje. Olvasás/írás [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Alapértelmezett: [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Visszatérési érték:**
int

### setCompliance(int value) {#setCompliance-int-}
```
public abstract void setCompliance(int value)
```

A generált PDF dokumentum kívánt megfelelőségi szintje. Olvasás/írás [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Alapértelmezett: [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

Felhasználói jelszó beállítása a PDF dokumentum védelméhez. Olvasás/írás String.

**Visszatérési érték:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

Felhasználói jelszó beállítása a PDF dokumentum védelméhez. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public abstract int getAccessPermissions()
```

Tartalmaz egy zászlók halmazát, amelyek meghatározzák, hogy milyen hozzáférési jogosultságokat kell megadni, amikor a dokumentum felhasználói hozzáféréssel nyílik meg. Lásd [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
public abstract void setAccessPermissions(int value)
```

Tartalmaz egy zászlók halmazát, amelyek meghatározzák, hogy milyen hozzáférési jogosultságokat kell megadni, amikor a dokumentum felhasználói hozzáféréssel nyílik meg. Lásd [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
public abstract boolean getSaveMetafilesAsPng()
```

Igaz, ha a prezentációban használt összes metafájlt PNG képekké kell konvertálni. Olvasás/írás boolean.

--------------------

Alapértelmezett: **true**. Pdf dokumentum tartalmazhat vektoros grafikát és raszteres képeket. Ha SaveMetafilesAsPng igazra van állítva, a forrás Metafile kép PNG formátumba konvertálódik és raszteres képként kerül mentésre a Pdf-be. Ha SaveMetafilesAsPng hamisra van állítva, a forrás Metafile vektoros grafikává alakul a Pdf-ben. Mindkét megközelítésnek vannak előnyei és hátrányai. Például, ha a Metafile PNG-re konvertálódik, a dokumentum méretezése közben minőségveszteség léphet fel. Ha a Metafile vektoros grafikává alakul, a Pdf-néző eszköz teljesítményproblémákat tapasztalhat.

**Visszatérési érték:**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

Igaz, ha a prezentációban használt összes metafájlt PNG képekké kell konvertálni. Olvasás/írás boolean.

--------------------

Alapértelmezett: **true**. Pdf dokumentum tartalmazhat vektoros grafikát és raszteres képeket. Ha SaveMetafilesAsPng igazra van állítva, a forrás Metafile kép PNG formátumba konvertálódik és raszteres képként kerül mentésre a Pdf-be. Ha SaveMetafilesAsPng hamisra van állítva, a forrás Metafile vektoros grafikává alakul a Pdf-ben. Mindkét megközelítésnek vannak előnyei és hátrányai. Például, ha a Metafile PNG-re konvertálódik, a dokumentum méretezése közben minőségveszteség léphet fel. Ha a Metafile vektoros grafikává alakul, a Pdf-néző eszköz teljesítményproblémákat tapasztalhat.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```

Visszaad vagy beállít egy értéket, amely meghatározza a képek felbontását a PDF dokumentumban. Olvasás/írás float.

Value: Ennek a paraméternek a hatása néhány tényezőtől függ. Az algoritmus a legjobb kimeneti képméretet próbálja elérni az érték, a forráskép mérete és a képkeret mérete alapján. Hasonló értékek használata ugyanazt az eredményt hozhatja. Javasolt 16-os vagy 32-as lépést használni a látható hatás érdekében.

--------------------

A tulajdonság hat a fájlméretre, az exportálási időre és a képminőségre.

Az alapértelmezett érték **96**.

**Visszatérési érték:**
float

### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```

Visszaad vagy beállít egy értéket, amely meghatározza a képek felbontását a PDF dokumentumban. Olvasás/írás float.

Value: Ennek a paraméternek a hatása néhány tényezőtől függ. Az algoritmus a legjobb kimeneti képméretet próbálja elérni az érték, a forráskép mérete és a képkeret mérete alapján. Hasonló értékek használata ugyanazt az eredményt hozhatja. Javasolt 16-os vagy 32-as lépést használni a látható hatás érdekében.

--------------------

A tulajdonság hat a fájlméretre, az exportálási időre és a képminőségre.

Az alapértelmezett érték **96**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

Igaz, ha minden dia köré fekete keretet kell rajzolni. Olvasás/írás boolean.

--------------------

Alapértelmezett: **false**.

**Visszatérési érték:**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

Igaz, ha minden dia köré fekete keretet kell rajzolni. Olvasás/írás boolean.

--------------------

Alapértelmezett: **false**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Lekéri vagy beállítja azt a módot, amelyben a diák az oldalon helyezkednek el prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Lekéri vagy beállítja azt a módot, amelyben a diák az oldalon helyezkednek el prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

### getImageTransparentColor() {#getImageTransparentColor--}
```
public abstract Integer getImageTransparentColor()
```

Lekéri vagy beállítja a kép átlátszó színét.

Value: A kép átlátszó színe.

**Visszatérési érték:**
java.lang.Integer

### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public abstract void setImageTransparentColor(Integer value)
```

Lekéri vagy beállítja a kép átlátszó színét.

Value: A kép átlátszó színe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public abstract boolean getApplyImageTransparent()
```

A megadott átlátszó színt alkalmazza a képre, ha igaz.

**Visszatérési érték:**
boolean

### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public abstract void setApplyImageTransparent(boolean value)
```

A megadott átlátszó színt alkalmazza a képre, ha igaz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Olyan beállításokat biztosít, amelyek szabályozzák a tintával készült objektumok megjelenését az exportált dokumentumban. Csak olvasás [IInkOptions](../../com.aspose.slides/iinkoptions)

**Visszatérési érték:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getIncludeOleData() {#getIncludeOleData--}
```
public abstract boolean getIncludeOleData()
```

Igaz, ha a prezentáció összes OLE adatát beágyazott fájlokká kell konvertálni a keletkező PDF-ben. Olvasás/írás boolean.

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

Alapértelmezett: **false**.

**Visszatérési érték:**
boolean

### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public abstract void setIncludeOleData(boolean value)
```

Igaz, ha a prezentáció összes OLE adatát beágyazott fájlokká kell konvertálni a keletkező PDF-ben. Olvasás/írás boolean.

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

Alapértelmezett: **false**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
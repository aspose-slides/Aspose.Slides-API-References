---
title: MarkdownSaveOptions
second_title: Aspose.Slides Androidhoz – Java API hivatkozás
description: Az opciókat képviseli, amelyek szabályozzák, hogyan kell a prezentációt markdown formátumba menteni.
type: docs
url: /hu/com.aspose.slides/markdownsaveoptions/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)
```
public class MarkdownSaveOptions extends SaveOptions
```

A prezentáció markdown formátumba mentését szabályozó opciókat képviseli.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation(presentationFileName);
>  try {
>      FileOutputStream stream = new FileOutputStream("MdFileForGitHubFlavor");
>      try {
>          MarkdownSaveOptions markdownSaveOptions = new MarkdownSaveOptions();
>          markdownSaveOptions.setShowHiddenSlides(true);
>          markdownSaveOptions.setShowSlideNumber(true);
>          markdownSaveOptions.setFlavor(Flavor.Github);
>          markdownSaveOptions.setExportType(MarkdownExportType.Sequential);
>          markdownSaveOptions.setNewLineType(NewLineType.Windows);
>          markdownSaveOptions.setBasePath(documentResourcesPath);
> 
>          pres.save(stream, new int[]{1, 2, 3, 4, 5, 6, 7, 8, 9}, SaveFormat.Md, markdownSaveOptions);
>      } finally {
>          if (stream != null) stream.close();
>      }
>  } catch (Exception e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) | Konstruktor. |
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getExportType()](#getExportType--) | Megadja a markdown specifikációt a prezentáció konvertálásához. |
| [setExportType(int value)](#setExportType-int-) | Megadja a markdown specifikációt a prezentáció konvertálásához. |
| [getBasePath()](#getBasePath--) | Megadja az alapútvonalat, ahol a forrásokkal együtt a dokumentum mentésre kerül. |
| [setBasePath(String value)](#setBasePath-java.lang.String-) | Megadja az alapútvonalat, ahol a forrásokkal együtt a dokumentum mentésre kerül. |
| [getImagesSaveFolderName()](#getImagesSaveFolderName--) | Megadja a képek mentéséhez használandó mappa nevét. |
| [setImagesSaveFolderName(String value)](#setImagesSaveFolderName-java.lang.String-) | Megadja a képek mentéséhez használandó mappa nevét. |
| [getNewLineType()](#getNewLineType--) | Megadja, hogy a generált dokumentumban milyen sorvégeket kell használni: \\\\r (Macintosh), \\\\n (Unix) vagy \\\\r\\\\n (Windows). |
| [setNewLineType(int value)](#setNewLineType-int-) | Megadja, hogy a generált dokumentumban milyen sorvégeket kell használni: \\\\r (Macintosh), \\\\n (Unix) vagy \\\\r\\\\n (Windows). |
| [getShowComments()](#getShowComments--) | Megadja, hogy a generált dokumentumban megjelenjenek-e a megjegyzések vagy sem. |
| [setShowComments(boolean value)](#setShowComments-boolean-) | Megadja, hogy a generált dokumentumban megjelenjenek-e a megjegyzések vagy sem. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Megadja, hogy a generált dokumentumban legyenek-e rejtett diák vagy sem. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Megadja, hogy a generált dokumentumban legyenek-e rejtett diák vagy sem. |
| [getShowSlideNumber()](#getShowSlideNumber--) | Megadja, hogy a generált dokumentumban megjelenjen-e minden dia száma vagy sem. |
| [setShowSlideNumber(boolean value)](#setShowSlideNumber-boolean-) | Megadja, hogy a generált dokumentumban megjelenjen-e minden dia száma vagy sem. |
| [getFlavor()](#getFlavor--) | Megadja a markdown specifikációt a prezentáció konvertálásához. |
| [setFlavor(int value)](#setFlavor-int-) | Megadja a markdown specifikációt a prezentáció konvertálásához. |
| [getSlideNumberFormat()](#getSlideNumberFormat--) | Lekéri vagy beállítja a diá számfejlécének formátumkarakterláncát a Markdown kimenetben. |
| [setSlideNumberFormat(String value)](#setSlideNumberFormat-java.lang.String-) | Lekéri vagy beállítja a diá számfejlécének formátumkarakterláncát a Markdown kimenetben. |
| [getHandleRepeatedSpaces()](#getHandleRepeatedSpaces--) | Megadja, hogyan kell kezelni az ismétlődő szóköz karaktereket a Markdown exportálása során. |
| [setHandleRepeatedSpaces(int value)](#setHandleRepeatedSpaces-int-) | Megadja, hogyan kell kezelni az ismétlődő szóköz karaktereket a Markdown exportálása során. |
| [getRemoveEmptyLines()](#getRemoveEmptyLines--) | Ha igazra van állítva, eltávolítja az üres vagy csak szóközt tartalmazó sorokat a végső Markdown kimenetből. |
| [setRemoveEmptyLines(boolean value)](#setRemoveEmptyLines-boolean-) | Ha igazra van állítva, eltávolítja az üres vagy csak szóközt tartalmazó sorokat a végső Markdown kimenetből. |
| [setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)](#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-) | Minden nem-SVG kép (bitmap vagy metafájl) esetén esemény keletkezik a Markdown exportálása során. |
| [setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)](#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-) | Minden SVG kép esetén esemény keletkezik a Markdown exportálása során. |
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```

Konstruktor.

### getExportType() {#getExportType--}
```
public final int getExportType()
```

Megadja a markdown specifikációt a prezentáció konvertálásához. Alapértelmezett a  TextOnly .

**Visszatérési érték:**
int
### setExportType(int value) {#setExportType-int-}
```
public final void setExportType(int value)
```

Megadja a markdown specifikációt a prezentáció konvertálásához. Alapértelmezett a  TextOnly .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getBasePath() {#getBasePath--}
```
public final String getBasePath()
```

Megadja az alapútvonalat, ahol a forrásokkal együtt a dokumentum mentésre kerül. Alapértelmezett az alkalmazás aktuális könyvtára.

**Visszatérési érték:**
java.lang.String
### setBasePath(String value) {#setBasePath-java.lang.String-}
```
public final void setBasePath(String value)
```

Megadja az alapútvonalat, ahol a forrásokkal együtt a dokumentum mentésre kerül. Alapértelmezett az alkalmazás aktuális könyvtára.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getImagesSaveFolderName() {#getImagesSaveFolderName--}
```
public final String getImagesSaveFolderName()
```

Megadja a képek mentéséhez használandó mappa nevét. Alapértelmezett a  Images .

**Visszatérési érték:**
java.lang.String
### setImagesSaveFolderName(String value) {#setImagesSaveFolderName-java.lang.String-}
```
public final void setImagesSaveFolderName(String value)
```

Megadja a képek mentéséhez használandó mappa nevét. Alapértelmezett a  Images .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getNewLineType() {#getNewLineType--}
```
public final int getNewLineType()
```

Megadja, hogy a generált dokumentumban milyen sorvégeket kell használni: \\\\r (Macintosh), \\\\n (Unix) vagy \\\\r\\\\n (Windows). Alapértelmezett a  Unix .

**Visszatérési érték:**
int
### setNewLineType(int value) {#setNewLineType-int-}
```
public final void setNewLineType(int value)
```

Megadja, hogy a generált dokumentumban milyen sorvégeket kell használni: \\\\r (Macintosh), \\\\n (Unix) vagy \\\\r\\\\n (Windows). Alapértelmezett a  Unix .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final boolean getShowComments()
```

Megadja, hogy a generált dokumentumban megjelenjenek-e a megjegyzések vagy sem. Alapértelmezett false.

**Visszatérési érték:**
boolean
### setShowComments(boolean value) {#setShowComments-boolean-}
```
public final void setShowComments(boolean value)
```

Megadja, hogy a generált dokumentumban megjelenjenek-e a megjegyzések vagy sem. Alapértelmezett false.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Megadja, hogy a generált dokumentumban legyenek-e rejtett diák vagy sem. Alapértelmezett false.

**Visszatérési érték:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Megadja, hogy a generált dokumentumban legyenek-e rejtett diák vagy sem. Alapértelmezett false.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowSlideNumber() {#getShowSlideNumber--}
```
public final boolean getShowSlideNumber()
```

Megadja, hogy a generált dokumentumban megjelenjen-e minden dia száma vagy sem. Alapértelmezett false.

**Visszatérési érték:**
boolean
### setShowSlideNumber(boolean value) {#setShowSlideNumber-boolean-}
```
public final void setShowSlideNumber(boolean value)
```

Megadja, hogy a generált dokumentumban megjelenjen-e minden dia száma vagy sem. Alapértelmezett false.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getFlavor() {#getFlavor--}
```
public final int getFlavor()
```

Megadja a markdown specifikációt a prezentáció konvertálásához. Alapértelmezett a  Multi-markdown .

**Visszatérési érték:**
int
### setFlavor(int value) {#setFlavor-int-}
```
public final void setFlavor(int value)
```

Megadja a markdown specifikációt a prezentáció konvertálásához. Alapértelmezett a  Multi-markdown .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getSlideNumberFormat() {#getSlideNumberFormat--}
```
public final String getSlideNumberFormat()
```

Lekéri vagy beállítja a diá számfejlécének formátumkarakterláncát a Markdown kimenetben. A formátumnak tartalmaznia kell a “\{0\}” helykitöltőt, amelyet a dia indexével helyettesít a exportálás során. Példa: “\# Slide \{0\}” eredménye “\# Slide 1”, “\# Slide 2” stb.

**Visszatérési érték:**
java.lang.String
### setSlideNumberFormat(String value) {#setSlideNumberFormat-java.lang.String-}
```
public final void setSlideNumberFormat(String value)
```

Lekéri vagy beállítja a diá számfejlécének formátumkarakterláncát a Markdown kimenetben. A formátumnak tartalmaznia kell a “\{0\}” helykitöltőt, amelyet a dia indexével helyettesít a exportálás során. Példa: “\# Slide \{0\}” eredménye “\# Slide 1”, “\# Slide 2” stb.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getHandleRepeatedSpaces() {#getHandleRepeatedSpaces--}
```
public final int getHandleRepeatedSpaces()
```

Megadja, hogyan kell kezelni az ismétlődő szóköz karaktereket a Markdown exportálása során. Ez a tulajdonság meghatározza, hogy a egymást követő szóközök:
- megmaradjanak-ként szokásos szóköz karakterek,
- felváltva szokásos és nem törhető szóköz entitások (�) legyenek,
- vagy az első után teljesen nem törhető szóközzel helyettesüljenek a vizuális igazítás megőrzése érdekében a Markdown kimenetben. Az alapértelmezett érték [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Visszatérési érték:**
int
### setHandleRepeatedSpaces(int value) {#setHandleRepeatedSpaces-int-}
```
public final void setHandleRepeatedSpaces(int value)
```

Megadja, hogyan kell kezelni az ismétlődő szóköz karaktereket a Markdown exportálása során. Ez a tulajdonság meghatározza, hogy a egymást követő szóközök:
- megmaradjanak-ként szokásos szóköz karakterek,
- felváltva szokásos és nem törhető szóköz entitások (�) legyenek,
- vagy az első után teljesen nem törhető szóközzel helyettesüljenek a vizuális igazítás megőrzése érdekében a Markdown kimenetben. Az alapértelmezett érték [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getRemoveEmptyLines() {#getRemoveEmptyLines--}
```
public final boolean getRemoveEmptyLines()
```

Ha igazra van állítva, eltávolítja az üres vagy csak szóközt tartalmazó sorokat a végső Markdown kimenetből. Alapértelmezett false.

**Visszatérési érték:**
boolean
### setRemoveEmptyLines(boolean value) {#setRemoveEmptyLines-boolean-}
```
public final void setRemoveEmptyLines(boolean value)
```

Ha igazra van állítva, eltávolítja az üres vagy csak szóközt tartalmazó sorokat a végső Markdown kimenetből. Alapértelmezett false.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event) {#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-}
```
public final void setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)
```

Minden nem-SVG kép (bitmap vagy metafájl) esetén esemény keletkezik a Markdown exportálása során. Lehetővé teszi a kép mentésének és hivatkozásának testreszabását. Ha nincs kezelve, a kép lokálisan kerül mentésre relatív hivatkozással.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| event | [MarkdownImageSavingHandler](../../com.aspose.slides/markdownimagesavinghandler) | Markdown képmentési esemény. |

### setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event) {#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-}
```
public final void setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)
```

Minden SVG kép esetén esemény keletkezik a Markdown exportálása során. Lehetővé teszi az alapértelmezett mentés és linkgenerálás felülírását. Ha nincs kezelve, az SVG lokálisan kerül mentésre relatív hivatkozással.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| event | [MarkdownSvgImageSavingHandler](../../com.aspose.slides/markdownsvgimagesavinghandler) | Markdown SVG képmentési esemény. |
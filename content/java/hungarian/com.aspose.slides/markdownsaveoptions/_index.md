---
title: MarkdownSaveOptions
second_title: Aspose.Slides for Java API Referencia
description: Leírja azokat az opciókat, amelyek meghatározzák, hogyan kell a prezentációt markdown formátumba menteni.
type: docs
url: /hu/com.aspose.slides/markdownsaveoptions/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)
```
public class MarkdownSaveOptions extends SaveOptions
```

Azoknak a beállításoknak a leírása, amelyek meghatározzák, hogyan kell a prezentációt markdown formátumba menteni.

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
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getExportType()](#getExportType--) | Megadja a prezentáció átalakításához használandó markdown specifikációt. |
| [setExportType(int value)](#setExportType-int-) | Megadja a prezentáció átalakításához használandó markdown specifikációt. |
| [getBasePath()](#getBasePath--) | Megadja azt az alapútvonalat, ahová az erőforrásokat tartalmazó dokumentum mentésre kerül. |
| [setBasePath(String value)](#setBasePath-java.lang.String-) | Megadja azt az alapútvonalat, ahová az erőforrásokat tartalmazó dokumentum mentésre kerül. |
| [getImagesSaveFolderName()](#getImagesSaveFolderName--) | Megadja a képek mentéséhez használandó mappanév meghatározását. |
| [setImagesSaveFolderName(String value)](#setImagesSaveFolderName-java.lang.String-) | Megadja a képek mentéséhez használandó mappanév meghatározását. |
| [getNewLineType()](#getNewLineType--) | Megadja, hogy a létrehozott dokumentumban milyen sorvégeket kell használni: \\r (Macintosh), \\n (Unix) vagy \\r\\n (Windows). |
| [setNewLineType(int value)](#setNewLineType-int-) | Megadja, hogy a létrehozott dokumentumban milyen sorvégeket kell használni: \\r (Macintosh), \\n (Unix) vagy \\r\\n (Windows). |
| [getShowComments()](#getShowComments--) | Megadja, hogy a létrehozott dokumentumban megjelenjenek-e a megjegyzések. |
| [setShowComments(boolean value)](#setShowComments-boolean-) | Megadja, hogy a létrehozott dokumentumban megjelenjenek-e a megjegyzések. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Megadja, hogy a létrehozott dokumentumban legyenek-e rejtett diák. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Megadja, hogy a létrehozott dokumentumban legyenek-e rejtett diák. |
| [getShowSlideNumber()](#getShowSlideNumber--) | Megadja, hogy a létrehozott dokumentumban megjelenjen-e minden diára a szám. |
| [setShowSlideNumber(boolean value)](#setShowSlideNumber-boolean-) | Megadja, hogy a létrehozott dokumentumban megjelenjen-e minden diára a szám. |
| [getFlavor()](#getFlavor--) | Megadja a prezentáció átalakításához használandó markdown specifikációt. |
| [setFlavor(int value)](#setFlavor-int-) | Megadja a prezentáció átalakításához használandó markdown specifikációt. |
| [getSlideNumberFormat()](#getSlideNumberFormat--) | Lekéri vagy beállítja a markdown kimenetben a dia szám fejlécek formátumát. |
| [setSlideNumberFormat(String value)](#setSlideNumberFormat-java.lang.String-) | Lekéri vagy beállítja a markdown kimenetben a dia szám fejlécek formátumát. |
| [getHandleRepeatedSpaces()](#getHandleRepeatedSpaces--) | Megadja, hogyan kell kezelni a többszörös szóköz karaktereket a markdown exportálás során. |
| [setHandleRepeatedSpaces(int value)](#setHandleRepeatedSpaces-int-) | Megadja, hogyan kell kezelni a többszörös szóköz karaktereket a markdown exportálás során. |
| [getRemoveEmptyLines()](#getRemoveEmptyLines--) | Ha igazra van állítva, eltávolítja az üres vagy csak szóközt tartalmazó sorokat a végső markdown kimenetből. |
| [setRemoveEmptyLines(boolean value)](#setRemoveEmptyLines-boolean-) | Ha igazra van állítva, eltávolítja az üres vagy csak szóközt tartalmazó sorokat a végső markdown kimenetből. |
| [setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)](#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-) | Minden nem-SVG képnél (bitmap vagy metafájl) előfordul a markdown exportálás során. |
| [setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)](#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-) | Minden SVG képnél előfordul a markdown exportálás során. |
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```


Konstruktor.

### getExportType() {#getExportType--}
```
public final int getExportType()
```


Megadja a prezentáció átalakításához használandó markdown specifikációt. Alapértelmezett érték:  TextOnly .

**Visszatérési érték:**
int
### setExportType(int value) {#setExportType-int-}
```
public final void setExportType(int value)
```


Megadja a prezentáció átalakításához használandó markdown specifikációt. Alapértelmezett érték:  TextOnly .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getBasePath() {#getBasePath--}
```
public final String getBasePath()
```


Megadja azt az alapútvonalat, ahová az erőforrásokat tartalmazó dokumentum mentésre kerül. Alapértelmezett az alkalmazás aktuális könyvtára.

**Visszatérési érték:**
java.lang.String
### setBasePath(String value) {#setBasePath-java.lang.String-}
```
public final void setBasePath(String value)
```


Megadja azt az alapútvonalat, ahová az erőforrásokat tartalmazó dokumentum mentésre kerül. Alapértelmezett az alkalmazás aktuális könyvtára.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getImagesSaveFolderName() {#getImagesSaveFolderName--}
```
public final String getImagesSaveFolderName()
```


Megadja a képek mentéséhez használandó mappanév meghatározását. Alapértelmezett:  Images .

**Visszatérési érték:**
java.lang.String
### setImagesSaveFolderName(String value) {#setImagesSaveFolderName-java.lang.String-}
```
public final void setImagesSaveFolderName(String value)
```


Megadja a képek mentéséhez használandó mappanév meghatározását. Alapértelmezett:  Images .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getNewLineType() {#getNewLineType--}
```
public final int getNewLineType()
```


Megadja, hogy a létrehozott dokumentumban milyen sorvégeket kell használni: \\r (Macintosh), \\n (Unix) vagy \\r\\n (Windows). Alapértelmezett:  Unix .

**Visszatérési érték:**
int
### setNewLineType(int value) {#setNewLineType-int-}
```
public final void setNewLineType(int value)
```


Megadja, hogy a létrehozott dokumentumban milyen sorvégeket kell használni: \\r (Macintosh), \\n (Unix) vagy \\r\\n (Windows). Alapértelmezett:  Unix .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final boolean getShowComments()
```


Megadja, hogy a létrehozott dokumentumban megjelenjenek-e a megjegyzések. Alapértelmezett: false.

**Visszatérési érték:**
boolean
### setShowComments(boolean value) {#setShowComments-boolean-}
```
public final void setShowComments(boolean value)
```


Megadja, hogy a létrehozott dokumentumban megjelenjenek-e a megjegyzések. Alapértelmezett: false.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Megadja, hogy a létrehozott dokumentumban legyen-e rejtett diák. Alapértelmezett: false.

**Visszatérési érték:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Megadja, hogy a létrehozott dokumentumban legyen-e rejtett diák. Alapértelmezett: false.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowSlideNumber() {#getShowSlideNumber--}
```
public final boolean getShowSlideNumber()
```


Megadja, hogy a létrehozott dokumentumban megjelenjen-e minden diára a szám. Alapértelmezett: false.

**Visszatérési érték:**
boolean
### setShowSlideNumber(boolean value) {#setShowSlideNumber-boolean-}
```
public final void setShowSlideNumber(boolean value)
```


Megadja, hogy a létrehozott dokumentumban megjelenjen-e minden diára a szám. Alapértelmezett: false.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getFlavor() {#getFlavor--}
```
public final int getFlavor()
```


Megadja a prezentáció átalakításához használandó markdown specifikációt. Alapértelmezett:  Multi-markdown .

**Visszatérési érték:**
int
### setFlavor(int value) {#setFlavor-int-}
```
public final void setFlavor(int value)
```


Megadja a prezentáció átalakításához használandó markdown specifikációt. Alapértelmezett:  Multi-markdown .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getSlideNumberFormat() {#getSlideNumberFormat--}
```
public final String getSlideNumberFormat()
```


Lekéri vagy beállítja a markdown kimenetben a dia szám fejlécek formátumát. A formátumnak tartalmaznia kell a "\{0\}" helyőrzőt, amely a dia indexével lesz helyettesítve exportáláskor. Példa: "\# Slide \{0\}" eredményezi "\# Slide 1", "\# Slide 2", stb.

**Visszatérési érték:**
java.lang.String
### setSlideNumberFormat(String value) {#setSlideNumberFormat-java.lang.String-}
```
public final void setSlideNumberFormat(String value)
```


Lekéri vagy beállítja a markdown kimenetben a dia szám fejlécek formátumát. A formátumnak tartalmaznia kell a "\{0\}" helyőrzőt, amely a dia indexével lesz helyettesítve exportáláskor. Példa: "\# Slide \{0\}" eredményezi "\# Slide 1", "\# Slide 2", stb.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getHandleRepeatedSpaces() {#getHandleRepeatedSpaces--}
```
public final int getHandleRepeatedSpaces()
```


Megadja, hogyan kell kezelni a többszörös szóköz karaktereket a markdown exportálás során. Ez a tulajdonság meghatározza, hogy a egymást követő szóközök: - megtartása egyszerű szóköz karakterként, - váltakozása egyszerű szóköz és nem-törhető szóköz entitás (�) között, - vagy teljesen helyettesítése (az első után) nem-törhető szóközzel a vizuális igazítás megőrzése érdekében a markdown kimenetben. Alapértelmezett érték: [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Visszatérési érték:**
int
### setHandleRepeatedSpaces(int value) {#setHandleRepeatedSpaces-int-}
```
public final void setHandleRepeatedSpaces(int value)
```


Megadja, hogyan kell kezelni a többszörös szóköz karaktereket a markdown exportálás során. Ez a tulajdonság meghatározza, hogy a egymást követő szóközök: - megtartása egyszerű szóköz karakterként, - váltakozása egyszerű szóköz és nem-törhető szóköz entitás (�) között, - vagy teljesen helyettesítése (az első után) nem-törhető szóközzel a vizuális igazítás megőrzése érdekében a markdown kimenetben. Alapértelmezett érték: [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getRemoveEmptyLines() {#getRemoveEmptyLines--}
```
public final boolean getRemoveEmptyLines()
```


Ha igazra van állítva, eltávolítja az üres vagy csak szóközt tartalmazó sorokat a végső markdown kimenetből. Alapértelmezett: false.

**Visszatérési érték:**
boolean
### setRemoveEmptyLines(boolean value) {#setRemoveEmptyLines-boolean-}
```
public final void setRemoveEmptyLines(boolean value)
```


Ha igazra van állítva, eltávolítja az üres vagy csak szóközt tartalmazó sorokat a végső markdown kimenetből. Alapértelmezett: false.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event) {#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-}
```
public final void setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)
```


Minden nem-SVG képnél (bitmap vagy metafájl) előfordul a markdown exportálás során. Lehetővé teszi a kép mentésének és hivatkozásának testreszabását. Ha nincs kezelve, a kép helyi relatív hivatkozással kerül mentésre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| event | [MarkdownImageSavingHandler](../../com.aspose.slides/markdownimagesavinghandler) | Markdown képmentési esemény. |

### setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event) {#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-}
```
public final void setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)
```


Minden SVG képnél előfordul a markdown exportálás során. Lehetővé teszi az alapértelmezett mentés és hivatkozás generálás felülbírálását. Ha nincs kezelve, az SVG helyi relatív hivatkozással kerül mentésre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| event | [MarkdownSvgImageSavingHandler](../../com.aspose.slides/markdownsvgimagesavinghandler) | Markdown SVG képmentési esemény. |
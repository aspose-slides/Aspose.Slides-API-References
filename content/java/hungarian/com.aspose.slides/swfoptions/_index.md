---
title: SwfOptions
second_title: Aspose.Slides Java API referenciája
description: Lehetőséget biztosít a bemutató SWF formátumba mentésének vezérléséhez.
type: docs
url: /hu/com.aspose.slides/swfoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**All Implemented Interfaces:**
[com.aspose.slides.ISwfOptions](../../com.aspose.slides/iswfoptions)
```
public class SwfOptions extends SaveOptions implements ISwfOptions
```

Lehetőségeket biztosít a bemutató SWF formátumba mentésének vezérléséhez.

--------------------

> ```
> The following example shows how to convert PowerPoint to SWF Flash.
>  
>  // Példányosítsa a Presentation objektumot, amely egy bemutató fájlt képvisel
>  Presentation pres = new Presentation("HelloWorld.pptx");
>  try {
>      SwfOptions swfOptions = new SwfOptions();
>      swfOptions.setViewerIncluded(false);
>      INotesCommentsLayoutingOptions notesOptions = swfOptions.getNotesCommentsLayouting();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      // Bemutató és jegyzetoldalak mentése
>      pres.save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
>      swfOptions.setViewerIncluded(true);
>      pres.save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [SwfOptions()](#SwfOptions--) | Alapértelmezett konstruktor. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákot vagy sem. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákot vagy sem. |
| [getCompressed()](#getCompressed--) | Megadja, hogy a generált SWF dokumentum legyen-e tömörítve vagy sem. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Megadja, hogy a generált SWF dokumentum legyen-e tömörítve vagy sem. |
| [getViewerIncluded()](#getViewerIncluded--) | Megadja, hogy a generált SWF dokumentum tartalmazza-e az integrált dokumentumnézőt vagy sem. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | Megadja, hogy a generált SWF dokumentum tartalmazza-e az integrált dokumentumnézőt vagy sem. |
| [getShowPageBorder()](#getShowPageBorder--) | Megadja, hogy az oldalak körüli keret megjelenjen-e. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | Megadja, hogy az oldalak körüli keret megjelenjen-e. |
| [getShowFullScreen()](#getShowFullScreen--) | Teljes képernyős gomb megjelenítése/elrejtése. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | Teljes képernyős gomb megjelenítése/elrejtése. |
| [getShowPageStepper()](#getShowPageStepper--) | Oldal léptető megjelenítése/elrejtése. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | Oldal léptető megjelenítése/elrejtése. |
| [getShowSearch()](#getShowSearch--) | Keresési szakasz megjelenítése/elrejtése. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | Keresési szakasz megjelenítése/elrejtése. |
| [getShowTopPane()](#getShowTopPane--) | Teljes felső panel megjelenítése/elrejtése. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | Teljes felső panel megjelenítése/elrejtése. |
| [getShowBottomPane()](#getShowBottomPane--) | Alsó panel megjelenítése/elrejtése. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | Alsó panel megjelenítése/elrejtése. |
| [getShowLeftPane()](#getShowLeftPane--) | Bal panel megjelenítése/elrejtése. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | Bal panel megjelenítése/elrejtése. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | Bal panel megnyitott állapotban indítása. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | Bal panel megnyitott állapotban indítása. |
| [getEnableContextMenu()](#getEnableContextMenu--) | Helyi menü engedélyezése/letiltása. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | Helyi menü engedélyezése/letiltása. |
| [getLogoImageBytes()](#getLogoImageBytes--) | Kép, amely a néző jobb felső sarkában logóként jelenik meg. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | Kép, amely a néző jobb felső sarkában logóként jelenik meg. |
| [getLogoLink()](#getLogoLink--) | Lekéri vagy beállítja a logó teljes hiperlink címét. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | Lekéri vagy beállítja a logó teljes hiperlink címét. |
| [getJpegQuality()](#getJpegQuality--) | Megadja a JPEG képek minőségét. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Megadja a JPEG képek minőségét. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Lekéri vagy beállítja a módot, amelyben a diák az oldalon helyezkednek el egy bemutató exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Lekéri vagy beállítja a módot, amelyben a diák az oldalon helyezkednek el egy bemutató exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
### SwfOptions() {#SwfOptions--}
```
public SwfOptions()
```


Alapértelmezett konstruktor.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákot vagy sem. Alapértelmezett érték false.

**Visszatérési érték:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákot vagy sem. Alapértelmezett érték false.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getCompressed() {#getCompressed--}
```
public final boolean getCompressed()
```


Megadja, hogy a generált SWF dokumentum legyen-e tömörítve vagy sem. Alapértelmezett érték true.

**Visszatérési érték:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public final void setCompressed(boolean value)
```


Megadja, hogy a generált SWF dokumentum legyen-e tömörítve vagy sem. Alapértelmezett érték true.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public final boolean getViewerIncluded()
```


Megadja, hogy a generált SWF dokumentum tartalmazza-e az integrált dokumentumnézőt vagy sem. Alapértelmezett érték true.

**Visszatérési érték:**
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public final void setViewerIncluded(boolean value)
```


Megadja, hogy a generált SWF dokumentum tartalmazza-e az integrált dokumentumnézőt vagy sem. Alapértelmezett érték true.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public final boolean getShowPageBorder()
```


Megadja, hogy az oldalak körüli keret megjelenjen-e. Alapértelmezett érték true.

**Visszatérési érték:**
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public final void setShowPageBorder(boolean value)
```


Megadja, hogy az oldalak körüli keret megjelenjen-e. Alapértelmezett érték true.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public final boolean getShowFullScreen()
```


Teljes képernyős gomb megjelenítése/elrejtése. Felülbírálható a flashvars-ban. Alapértelmezett érték true.

**Visszatérési érték:**
boolean
### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public final void setShowFullScreen(boolean value)
```


Teljes képernyős gomb megjelenítése/elrejtése. Felülbírálható a flashvars-ban. Alapértelmezett érték true.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public final boolean getShowPageStepper()
```


Oldal léptető megjelenítése/elrejtése. Felülbírálható a flashvars-ban. Alapértelmezett érték true.

**Visszatérési érték:**
boolean
### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public final void setShowPageStepper(boolean value)
```


Oldal léptető megjelenítése/elrejtése. Felülbírálható a flashvars-ban. Alapértelmezett érték true.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public final boolean getShowSearch()
```


Keresési szakasz megjelenítése/elrejtése. Felülbírálható a flashvars-ban. Alapértelmezett érték true.

**Visszatérési érték:**
boolean
### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public final void setShowSearch(boolean value)
```


Keresési szakasz megjelenítése/elrejtése. Felülbírálható a flashvars-ban. Alapértelmezett érték true.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public final boolean getShowTopPane()
```


Teljes felső panel megjelenítése/elrejtése. Felülbírálható a flashvars-ban. Alapértelmezett érték true.

**Visszatérési érték:**
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public final void setShowTopPane(boolean value)
```


Teljes felső panel megjelenítése/elrejtése. Felülbírálható a flashvars-ban. Alapértelmezett érték true.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public final boolean getShowBottomPane()
```


Alsó panel megjelenítése/elrejtése. Felülbírálható a flashvars-ban. Alapértelmezett érték true.

**Visszatérési érték:**
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public final void setShowBottomPane(boolean value)
```


Alsó panel megjelenítése/elrejtése. Felülbírálható a flashvars-ban. Alapértelmezett érték true.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public final boolean getShowLeftPane()
```


Bal panel megjelenítése/elrejtése. Felülbírálható a flashvars-ban. Alapértelmezett érték true.

**Visszatérési érték:**
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public final void setShowLeftPane(boolean value)
```


Bal panel megjelenítése/elrejtése. Felülbírálható a flashvars-ban. Alapértelmezett érték true.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public final boolean getStartOpenLeftPane()
```


Bal panel megnyitott állapotban indítása. Felülbírálható a flashvars-ban. Alapértelmezett érték false.

**Visszatérési érték:**
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public final void setStartOpenLeftPane(boolean value)
```


Bal panel megnyitott állapotban indítása. Felülbírálható a flashvars-ban. Alapértelmezett érték false.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public final boolean getEnableContextMenu()
```


Helyi menü engedélyezése/letiltása. Alapértelmezett érték true.

**Visszatérési érték:**
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public final void setEnableContextMenu(boolean value)
```


Helyi menü engedélyezése/letiltása. Alapértelmezett érték true.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public final byte[] getLogoImageBytes()
```


Kép, amely a néző jobb felső sarkában logóként jelenik meg. A képnek 32x64 pixeles PNG-nek kell lennie, ellenkező esetben a logó helytelenül jelenhet meg.

**Visszatérési érték:**
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public final void setLogoImageBytes(byte[] value)
```


Kép, amely a néző jobb felső sarkában logóként jelenik meg. A képnek 32x64 pixeles PNG-nek kell lennie, ellenkező esetben a logó helytelenül jelenhet meg.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public final String getLogoLink()
```


Lekéri vagy beállítja a logó teljes hiperlink címét. Csak akkor van hatása, ha egy (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) van megadva.

**Visszatérési érték:**
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public final void setLogoLink(String value)
```


Lekéri vagy beállítja a logó teljes hiperlink címét. Csak akkor van hatása, ha egy (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) van megadva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```


Megadja a JPEG képek minőségét. Alapértelmezett érték 95.

**Visszatérési érték:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```


Megadja a JPEG képek minőségét. Alapértelmezett érték 95.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```


Lekéri vagy beállítja a módot, amelyben a diák az oldalon helyezkednek el egy bemutató exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Ez a tulajdonság nem támogatja [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) típusú objektumok hozzárendelését.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
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


Lekéri vagy beállítja a módot, amelyben a diák az oldalon helyezkednek el egy bemutató exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Ez a tulajdonság nem támogatja [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) típusú objektumok hozzárendelését.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |
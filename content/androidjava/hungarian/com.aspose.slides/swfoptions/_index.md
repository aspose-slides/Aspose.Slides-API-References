---
title: SwfOptions
second_title: Aspose.Slides Androidhoz a Java API hivatkozás alapján
description: Beállításokat biztosít, amelyek szabályozzák, hogyan mentődik el egy bemutató SWF formátumban.
type: docs
url: /hu/com.aspose.slides/swfoptions/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Minden megvalósított interfész:**
[com.aspose.slides.ISwfOptions](../../com.aspose.slides/iswfoptions)
```
public class SwfOptions extends SaveOptions implements ISwfOptions
```

Beállításokat biztosít, amelyek szabályozzák, hogyan mentődik el egy bemutató SWF formátumban.

--------------------

> ```
> The following example shows how to convert PowerPoint to SWF Flash.
>  
>  // Létrehoz egy Presentation objektumot, amely egy prezentációs fájlt képvisel
>  Presentation pres = new Presentation("HelloWorld.pptx");
>  try {
>      SwfOptions swfOptions = new SwfOptions();
>      swfOptions.setViewerIncluded(false);
>      INotesCommentsLayoutingOptions notesOptions = swfOptions.getNotesCommentsLayouting();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      // A prezentáció és a jegyzetoldalak mentése
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
| [getViewerIncluded()](#getViewerIncluded--) | Megadja, hogy a generált SWF dokumentum tartalmazza-e a beépített dokumentum megjelenítőt vagy sem. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | Megadja, hogy a generált SWF dokumentum tartalmazza-e a beépített dokumentum megjelenítőt vagy sem. |
| [getShowPageBorder()](#getShowPageBorder--) | Megadja, hogy az oldalak körüli keret megjelenjen-e. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | Megadja, hogy az oldalak körüli keret megjelenjen-e. |
| [getShowFullScreen()](#getShowFullScreen--) | Teljes képernyő gomb megjelenítése/elrejtése. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | Teljes képernyő gomb megjelenítése/elrejtése. |
| [getShowPageStepper()](#getShowPageStepper--) | Oldal léptető megjelenítése/elrejtése. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | Oldal léptető megjelenítése/elrejtése. |
| [getShowSearch()](#getShowSearch--) | Keresési szakasz megjelenítése/elrejtése. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | Keresési szakasz megjelenítése/elrejtése. |
| [getShowTopPane()](#getShowTopPane--) | Az egész felső ablaktábla megjelenítése/elrejtése. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | Az egész felső ablaktábla megjelenítése/elrejtése. |
| [getShowBottomPane()](#getShowBottomPane--) | Alsó ablaktábla megjelenítése/elrejtése. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | Alsó ablaktábla megjelenítése/elrejtése. |
| [getShowLeftPane()](#getShowLeftPane--) | Bal ablaktábla megjelenítése/elrejtése. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | Bal ablaktábla megjelenítése/elrejtése. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | Bal ablaktábla nyitott állapotban indul. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | Bal ablaktábla nyitott állapotban indul. |
| [getEnableContextMenu()](#getEnableContextMenu--) | Jobb kattintás menü engedélyezése/letiltása. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | Jobb kattintás menü engedélyezése/letiltása. |
| [getLogoImageBytes()](#getLogoImageBytes--) | Az a kép, amely a megjelenítő jobb felső sarkában logóként jelenik meg. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | Az a kép, amely a megjelenítő jobb felső sarkában logóként jelenik meg. |
| [getLogoLink()](#getLogoLink--) | Lekéri vagy beállítja a logó teljes hiperhivatkozás címét. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | Lekéri vagy beállítja a logó teljes hiperhivatkozás címét. |
| [getJpegQuality()](#getJpegQuality--) | Megadja a JPEG képek minőségét. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Megadja a JPEG képek minőségét. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Lekéri vagy beállítja azt a módot, amelyben a diák az oldalon elhelyezésre kerülnek a bemutató exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Lekéri vagy beállítja azt a módot, amelyben a diák az oldalon elhelyezésre kerülnek a bemutató exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |

### SwfOptions() {#SwfOptions--}
```
public SwfOptions()
```

Alapértelmezett konstruktor.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákot vagy sem. Alapértelmezett érték: false.

**Visszatérési érték:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákot vagy sem. Alapértelmezett érték: false.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getCompressed() {#getCompressed--}
```
public final boolean getCompressed()
```

Megadja, hogy a generált SWF dokumentum legyen-e tömörítve vagy sem. Alapértelmezett érték: true.

**Visszatérési érték:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public final void setCompressed(boolean value)
```

Megadja, hogy a generált SWF dokumentum legyen-e tömörítve vagy sem. Alapértelmezett érték: true.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public final boolean getViewerIncluded()
```

Megadja, hogy a generált SWF dokumentum tartalmazza-e a beépített dokumentum megjelenítőt vagy sem. Alapértelmezett érték: true.

**Visszatérési érték:**
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public final void setViewerIncluded(boolean value)
```

Megadja, hogy a generált SWF dokumentum tartalmazza-e a beépített dokumentum megjelenítőt vagy sem. Alapértelmezett érték: true.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public final boolean getShowPageBorder()
```

Megadja, hogy az oldalak körüli keret megjelenjen-e. Alapértelmezett érték: true.

**Visszatérési érték:**
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public final void setShowPageBorder(boolean value)
```

Megadja, hogy az oldalak körüli keret megjelenjen-e. Alapértelmezett érték: true.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public final boolean getShowFullScreen()
```

Teljes képernyő gomb megjelenítése/elrejtése. A flashvars-ban felülírható. Alapértelmezett érték: true.

**Visszatérési érték:**
boolean
### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public final void setShowFullScreen(boolean value)
```

Teljes képernyő gomb megjelenítése/elrejtése. A flashvars-ban felülírható. Alapértelmezett érték: true.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public final boolean getShowPageStepper()
```

Oldal léptető megjelenítése/elrejtése. A flashvars-ban felülírható. Alapértelmezett érték: true.

**Visszatérési érték:**
boolean
### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public final void setShowPageStepper(boolean value)
```

Oldal léptető megjelenítése/elrejtése. A flashvars-ban felülírható. Alapértelmezett érték: true.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public final boolean getShowSearch()
```

Keresési szakasz megjelenítése/elrejtése. A flashvars-ban felülírható. Alapértelmezett érték: true.

**Visszatérési érték:**
boolean
### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public final void setShowSearch(boolean value)
```

Keresési szakasz megjelenítése/elrejtése. A flashvars-ban felülírható. Alapértelmezett érték: true.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public final boolean getShowTopPane()
```

Az egész felső ablaktábla megjelenítése/elrejtése. A flashvars-ban felülírható. Alapértelmezett érték: true.

**Visszatérési érték:**
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public final void setShowTopPane(boolean value)
```

Az egész felső ablaktábla megjelenítése/elrejtése. A flashvars-ban felülírható. Alapértelmezett érték: true.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public final boolean getShowBottomPane()
```

Alsó ablaktábla megjelenítése/elrejtése. A flashvars-ban felülírható. Alapértelmezett érték: true.

**Visszatérési érték:**
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public final void setShowBottomPane(boolean value)
```

Alsó ablaktábla megjelenítése/elrejtése. A flashvars-ban felülírható. Alapértelmezett érték: true.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public final boolean getShowLeftPane()
```

Bal ablaktábla megjelenítése/elrejtése. A flashvars-ban felülírható. Alapértelmezett érték: true.

**Visszatérési érték:**
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public final void setShowLeftPane(boolean value)
```

Bal ablaktábla megjelenítése/elrejtése. A flashvars-ban felülírható. Alapértelmezett érték: true.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public final boolean getStartOpenLeftPane()
```

Bal ablaktábla nyitott állapotban indul. A flashvars-ban felülírható. Alapértelmezett érték: false.

**Visszatérési érték:**
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public final void setStartOpenLeftPane(boolean value)
```

Bal ablaktábla nyitott állapotban indul. A flashvars-ban felülírható. Alapértelmezett érték: false.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public final boolean getEnableContextMenu()
```

Jobb kattintás menü engedélyezése/letiltása. Alapértelmezett érték: true.

**Visszatérési érték:**
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public final void setEnableContextMenu(boolean value)
```

Jobb kattintás menü engedélyezése/letiltása. Alapértelmezett érték: true.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public final byte[] getLogoImageBytes()
```

Az a kép, amely a megjelenítő jobb felső sarkában logóként jelenik meg. A képnek 32x64 pixel méretű PNG-nek kell lennie, különben a logó helytelenül jelenhet meg.

**Visszatérési érték:**
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public final void setLogoImageBytes(byte[] value)
```

Az a kép, amely a megjelenítő jobb felső sarkában logóként jelenik meg. A képnek 32x64 pixel méretű PNG-nek kell lennie, különben a logó helytelenül jelenhet meg.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public final String getLogoLink()
```

Lekéri vagy beállítja a logó teljes hiperhivatkozás címét. Csak akkor van hatása, ha egy (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) van meghatározva.

**Visszatérési érték:**
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public final void setLogoLink(String value)
```

Lekéri vagy beállítja a logó teljes hiperhivatkozás címét. Csak akkor van hatása, ha egy (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) van meghatározva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

Megadja a JPEG képek minőségét. Alapértelmezett érték: 95.

**Visszatérési érték:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

Megadja a JPEG képek minőségét. Alapértelmezett érték: 95.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Lekéri vagy beállítja azt a módot, amelyben a diák az oldalon elhelyezésre kerülnek a bemutató exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Ez a tulajdonság nem támogatja a [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) típusú objektumok hozzárendelését.

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

Lekéri vagy beállítja azt a módot, amelyben a diák az oldalon elhelyezésre kerülnek a bemutató exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Ez a tulajdonság nem támogatja a [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) típusú objektumok hozzárendelését.

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
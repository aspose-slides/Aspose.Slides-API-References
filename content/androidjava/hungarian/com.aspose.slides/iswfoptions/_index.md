---
title: ISwfOptions
second_title: Aspose.Slides Android-hoz Java API Referencia
description: Lehetőségeket biztosít, amelyek szabályozzák, hogyan ment egy prezentációt SWF formátumban.
type: docs
url: /hu/com.aspose.slides/iswfoptions/
---
**Minden implementált interfész:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISwfOptions extends ISaveOptions
```

Lehetőségeket biztosít, amelyek szabályozzák, hogy a prezentáció hogyan kerül mentésre SWF formátumban.

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getCompressed()](#getCompressed--) | Megadja, hogy a generált SWF dokumentumot tömöríteni kell-e vagy sem. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Megadja, hogy a generált SWF dokumentumot tömöríteni kell-e vagy sem. |
| [getViewerIncluded()](#getViewerIncluded--) | Megadja, hogy a generált SWF dokumentumban szerepeljen-e az integrált dokumentum megjelenítő vagy sem. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | Megadja, hogy a generált SWF dokumentumban szerepeljen-e az integrált dokumentum megjelenítő vagy sem. |
| [getShowPageBorder()](#getShowPageBorder--) | Megadja, hogy a lapok körüli keret megjelenjen-e. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | Megadja, hogy a lapok körüli keret megjelenjen-e. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Megadja, hogy a generált dokumentumban legyenek-e rejtett diák vagy sem. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Megadja, hogy a generált dokumentumban legyenek-e rejtett diák vagy sem. |
| [getShowFullScreen()](#getShowFullScreen--) | Teljes képernyős gomb megjelenítése/elrejtése. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | Teljes képernyős gomb megjelenítése/elrejtése. |
| [getShowPageStepper()](#getShowPageStepper--) | Oldal léptető megjelenítése/elrejtése. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | Oldal léptető megjelenítése/elrejtése. |
| [getShowSearch()](#getShowSearch--) | Kereső szakasz megjelenítése/elrejtése. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | Kereső szakasz megjelenítése/elrejtése. |
| [getShowTopPane()](#getShowTopPane--) | Teljes felső panel megjelenítése/elrejtése. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | Teljes felső panel megjelenítése/elrejtése. |
| [getShowBottomPane()](#getShowBottomPane--) | Alsó panel megjelenítése/elrejtése. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | Alsó panel megjelenítése/elrejtése. |
| [getShowLeftPane()](#getShowLeftPane--) | Bal panel megjelenítése/elrejtése. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | Bal panel megjelenítése/elrejtése. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | Bal panel megnyitott állapotban indítása. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | Bal panel megnyitott állapotban indítása. |
| [getEnableContextMenu()](#getEnableContextMenu--) | A helyi menü engedélyezése/tiltása. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | A helyi menü engedélyezése/tiltása. |
| [getLogoImageBytes()](#getLogoImageBytes--) | Kép, amely a néző jobb felső sarkában logóként jelenik meg. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | Kép, amely a néző jobb felső sarkában logóként jelenik meg. |
| [getLogoLink()](#getLogoLink--) | Lekérdezi vagy beállítja a logó teljes hiperlink címét. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | Lekérdezi vagy beállítja a logó teljes hiperlink címét. |
| [getJpegQuality()](#getJpegQuality--) | Megadja a JPEG képek minőségét. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Megadja a JPEG képek minőségét. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Lekérdezi vagy beállítja azt a módot, ahogyan a diák az oldalon elhelyezésre kerülnek egy prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Lekérdezi vagy beállítja azt a módot, ahogyan a diák az oldalon elhelyezésre kerülnek egy prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |

### getCompressed() {#getCompressed--}
```
public abstract boolean getCompressed()
```

Megadja, hogy a generált SWF dokumentumot tömöríteni kell-e vagy sem. Alapértelmezett érték: true.

**Visszatérési érték:**  
boolean

### setCompressed(boolean value) {#setCompressed-boolean-}
```
public abstract void setCompressed(boolean value)
```

Megadja, hogy a generált SWF dokumentumot tömöríteni kell-e vagy sem. Alapértelmezett érték: true.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public abstract boolean getViewerIncluded()
```

Megadja, hogy a generált SWF dokumentumban szerepeljen-e az integrált dokumentum megjelenítő vagy sem. Alapértelmezett érték: true.

**Visszatérési érték:**  
boolean

### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public abstract void setViewerIncluded(boolean value)
```

Megadja, hogy a generált SWF dokumentumban szerepeljen-e az integrált dokumentum megjelenítő vagy sem. Alapértelmezett érték: true.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public abstract boolean getShowPageBorder()
```

Megadja, hogy a lapok körüli keret megjelenjen-e. Alapértelmezett érték: true.

**Visszatérési érték:**  
boolean

### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public abstract void setShowPageBorder(boolean value)
```

Megadja, hogy a lapok körüli keret megjelenjen-e. Alapértelmezett érték: true.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Megadja, hogy a generált dokumentumban legyenek-e rejtett diák vagy sem. Alapértelmezett érték: false.

**Visszatérési érték:**  
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Megadja, hogy a generált dokumentumban legyenek-e rejtett diák vagy sem. Alapértelmezett érték: false.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public abstract boolean getShowFullScreen()
```

Teljes képernyős gomb megjelenítése/elrejtése. Felülbírálható flashvars-ban. Alapértelmezett érték: true.

**Visszatérési érték:**  
boolean

### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public abstract void setShowFullScreen(boolean value)
```

Teljes képernyős gomb megjelenítése/elrejtése. Felülbírálható flashvars-ban. Alapértelmezett érték: true.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public abstract boolean getShowPageStepper()
```

Oldal léptető megjelenítése/elrejtése. Felülbírálható flashvars-ban. Alapértelmezett érték: true.

**Visszatérési érték:**  
boolean

### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public abstract void setShowPageStepper(boolean value)
```

Oldal léptető megjelenítése/elrejtése. Felülbírálható flashvars-ban. Alapértelmezett érték: true.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public abstract boolean getShowSearch()
```

Kereső szakasz megjelenítése/elrejtése. Felülbírálható flashvars-ban. Alapértelmezett érték: true.

**Visszatérési érték:**  
boolean

### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public abstract void setShowSearch(boolean value)
```

Kereső szakasz megjelenítése/elrejtése. Felülbírálható flashvars-ban. Alapértelmezett érték: true.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public abstract boolean getShowTopPane()
```

Teljes felső panel megjelenítése/elrejtése. Felülbírálható flashvars-ban. Alapértelmezett érték: true.

**Visszatérési érték:**  
boolean

### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public abstract void setShowTopPane(boolean value)
```

Teljes felső panel megjelenítése/elrejtése. Felülbírálható flashvars-ban. Alapértelmezett érték: true.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public abstract boolean getShowBottomPane()
```

Alsó panel megjelenítése/elrejtése. Felülbírálható flashvars-ban. Alapértelmezett érték: true.

**Visszatérési érték:**  
boolean

### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public abstract void setShowBottomPane(boolean value)
```

Alsó panel megjelenítése/elrejtése. Felülbírálható flashvars-ban. Alapértelmezett érték: true.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public abstract boolean getShowLeftPane()
```

Bal panel megjelenítése/elrejtése. Felülbírálható flashvars-ban. Alapértelmezett érték: true.

**Visszatérési érték:**  
boolean

### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public abstract void setShowLeftPane(boolean value)
```

Bal panel megjelenítése/elrejtése. Felülbírálható flashvars-ban. Alapértelmezett érték: true.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public abstract boolean getStartOpenLeftPane()
```

Bal panel megnyitott állapotban indítása. Felülbírálható flashvars-ban. Alapértelmezett érték: false.

**Visszatérési érték:**  
boolean

### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public abstract void setStartOpenLeftPane(boolean value)
```

Bal panel megnyitott állapotban indítása. Felülbírálható flashvars-ban. Alapértelmezett érték: false.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public abstract boolean getEnableContextMenu()
```

A helyi menü engedélyezése/tiltása. Alapértelmezett érték: true.

**Visszatérési érték:**  
boolean

### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public abstract void setEnableContextMenu(boolean value)
```

A helyi menü engedélyezése/tiltása. Alapértelmezett érték: true.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public abstract byte[] getLogoImageBytes()
```

Kép, amely a néző jobb felső sarkában logóként jelenik meg. A képnek 32x64 pixel méretű PNG-nek kell lennie, ellenkező esetben a logó helytelenül jelenhet meg.

**Visszatérési érték:**  
byte[]

### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public abstract void setLogoImageBytes(byte[] value)
```

Kép, amely a néző jobb felső sarkában logóként jelenik meg. A képnek 32x64 pixel méretű PNG-nek kell lennie, ellenkező esetben a logó helytelenül jelenhet meg.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public abstract String getLogoLink()
```

Lekérdezi vagy beállítja a logó teljes hiperlink címét. Hatása csak akkor van, ha egy (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) van megadva.

**Visszatérési érték:**  
java.lang.String

### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public abstract void setLogoLink(String value)
```

Lekérdezi vagy beállítja a logó teljes hiperlink címét. Hatása csak akkor van, ha egy (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) van megadva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

Megadja a JPEG képek minőségét. Alapértelmezett érték: 95.

**Visszatérési érték:**  
int

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

Megadja a JPEG képek minőségét. Alapértelmezett érték: 95.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Lekérdezi vagy beállítja azt a módot, ahogyan a diák az oldalon elhelyezésre kerülnek egy prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Ez a tulajdonság nem támogatja [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) típusú objektumok hozzárendelését.

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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Lekérdezi vagy beállítja azt a módot, ahogyan a diák az oldalon elhelyezésre kerülnek egy prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Ez a tulajdonság nem támogatja [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) típusú objektumok hozzárendelését.

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
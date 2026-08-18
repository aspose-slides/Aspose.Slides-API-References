---
title: ISwfOptions
second_title: Aspose.Slides Java API referenciája
description: Lehetőségeket biztosít, amelyek szabályozzák, hogyan mentődik el egy prezentáció SWF formátumban.
type: docs
url: /hu/com.aspose.slides/iswfoptions/
---
**Minden megvalósított interfész:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISwfOptions extends ISaveOptions
```

Az opciókat biztosítja, amelyek szabályozzák, hogyan mentődik el egy prezentáció SWF formátumban.
## Metódusok

| Módszer | Leírás |
| --- | --- |
| [getCompressed()](#getCompressed--) | Megadja, hogy a generált SWF dokumentum tömörítve legyen-e vagy sem. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Megadja, hogy a generált SWF dokumentum tömörítve legyen-e vagy sem. |
| [getViewerIncluded()](#getViewerIncluded--) | Megadja, hogy a generált SWF dokumentum tartalmazza-e a beépített dokumentumnézegetőt vagy sem. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | Megadja, hogy a generált SWF dokumentum tartalmazza-e a beépített dokumentumnézegetőt vagy sem. |
| [getShowPageBorder()](#getShowPageBorder--) | Megadja, hogy a lapok körüli keret megjelenjen-e. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | Megadja, hogy a lapok körüli keret megjelenjen-e. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Megadja, hogy a generált dokumentum tartalmazza-e a rejtett diákot vagy sem. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Megadja, hogy a generált dokumentum tartalmazza-e a rejtett diákot vagy sem. |
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
| [getShowLeftPane()](#getShowLeftPane--) | Bal oldali panel megjelenítése/elrejtése. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | Bal oldali panel megjelenítése/elrejtése. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | Bal oldali panel megnyitva indítása. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | Bal oldali panel megnyitva indítása. |
| [getEnableContextMenu()](#getEnableContextMenu--) | Helyi menü engedélyezése/letiltása. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | Helyi menü engedélyezése/letiltása. |
| [getLogoImageBytes()](#getLogoImageBytes--) | Kép, amely a megjelenítő jobb felső sarkában logóként jelenik meg. A képfájl 32x64 pixel méretű PNG legyen, különben a logó helytelenül jelenhet meg. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | Kép, amely a megjelenítő jobb felső sarkában logóként jelenik meg. A képfájl 32x64 pixel méretű PNG legyen, különben a logó helytelenül jelenhet meg. |
| [getLogoLink()](#getLogoLink--) | Lekéri vagy beállítja egy logó teljes hiperhivatkozási címét. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | Lekéri vagy beállítja egy logó teljes hiperhivatkozási címét. |
| [getJpegQuality()](#getJpegQuality--) | Megadja a JPEG képek minőségét. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Megadja a JPEG képek minőségét. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Lekéri vagy beállítja a módot, amelyben a diák az oldalon elhelyezésre kerülnek egy prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Lekéri vagy beállítja a módot, amelyben a diák az oldalon elhelyezésre kerülnek egy prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |

### getCompressed() {#getCompressed--}
```
public abstract boolean getCompressed()
```

Megadja, hogy a generált SWF dokumentum tömörítve legyen-e vagy sem. Alapértelmezett érték igaz.

**Visszatérési érték:**
boolean

### setCompressed(boolean value) {#setCompressed-boolean-}
```
public abstract void setCompressed(boolean value)
```

Megadja, hogy a generált SWF dokumentum tömörítve legyen-e vagy sem. Alapértelmezett érték igaz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public abstract boolean getViewerIncluded()
```

Megadja, hogy a generált SWF dokumentum tartalmazza-e a beépített dokumentumnézegetőt vagy sem. Alapértelmezett érték igaz.

**Visszatérési érték:**
boolean

### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public abstract void setViewerIncluded(boolean value)
```

Megadja, hogy a generált SWF dokumentum tartalmazza-e a beépített dokumentumnézegetőt vagy sem. Alapértelmezett érték igaz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public abstract boolean getShowPageBorder()
```

Megadja, hogy a lapok körüli keret megjelenjen-e. Alapértelmezett érték igaz.

**Visszatérési érték:**
boolean

### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public abstract void setShowPageBorder(boolean value)
```

Megadja, hogy a lapok körüli keret megjelenjen-e. Alapértelmezett érték igaz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Megadja, hogy a generált dokumentum tartalmazza-e a rejtett diákot vagy sem. Alapértelmezett érték hamis.

**Visszatérési érték:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Megadja, hogy a generált dokumentum tartalmazza-e a rejtett diákot vagy sem. Alapértelmezett érték hamis.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public abstract boolean getShowFullScreen()
```

Teljes képernyős gomb megjelenítése/elrejtése. A flashvars-ban felülírható. Alapértelmezett érték igaz.

**Visszatérési érték:**
boolean

### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public abstract void setShowFullScreen(boolean value)
```

Teljes képernyős gomb megjelenítése/elrejtése. A flashvars-ban felülírható. Alapértelmezett érték igaz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public abstract boolean getShowPageStepper()
```

Oldal léptető megjelenítése/elrejtése. A flashvars-ban felülírható. Alapértelmezett érték igaz.

**Visszatérési érték:**
boolean

### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public abstract void setShowPageStepper(boolean value)
```

Oldal léptető megjelenítése/elrejtése. A flashvars-ban felülírható. Alapértelmezett érték igaz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public abstract boolean getShowSearch()
```

Kereső szakasz megjelenítése/elrejtése. A flashvars-ban felülírható. Alapértelmezett érték igaz.

**Visszatérési érték:**
boolean

### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public abstract void setShowSearch(boolean value)
```

Kereső szakasz megjelenítése/elrejtése. A flashvars-ban felülírható. Alapértelmezett érték igaz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public abstract boolean getShowTopPane()
```

Teljes felső panel megjelenítése/elrejtése. A flashvars-ban felülírható. Alapértelmezett érték igaz.

**Visszatérési érték:**
boolean

### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public abstract void setShowTopPane(boolean value)
```

Teljes felső panel megjelenítése/elrejtése. A flashvars-ban felülírható. Alapértelmezett érték igaz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public abstract boolean getShowBottomPane()
```

Alsó panel megjelenítése/elrejtése. A flashvars-ban felülírható. Alapértelmezett érték igaz.

**Visszatérési érték:**
boolean

### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public abstract void setShowBottomPane(boolean value)
```

Alsó panel megjelenítése/elrejtése. A flashvars-ban felülírható. Alapértelmezett érték igaz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public abstract boolean getShowLeftPane()
```

Bal oldali panel megjelenítése/elrejtése. A flashvars-ban felülírható. Alapértelmezett érték igaz.

**Visszatérési érték:**
boolean

### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public abstract void setShowLeftPane(boolean value)
```

Bal oldali panel megjelenítése/elrejtése. A flashvars-ban felülírható. Alapértelmezett érték igaz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public abstract boolean getStartOpenLeftPane()
```

Bal oldali panel megnyitva indítása. A flashvars-ban felülírható. Alapértelmezett érték hamis.

**Visszatérési érték:**
boolean

### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public abstract void setStartOpenLeftPane(boolean value)
```

Bal oldali panel megnyitva indítása. A flashvars-ban felülírható. Alapértelmezett érték hamis.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public abstract boolean getEnableContextMenu()
```

Helyi menü engedélyezése/letiltása. Alapértelmezett érték igaz.

**Visszatérési érték:**
boolean

### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public abstract void setEnableContextMenu(boolean value)
```

Helyi menü engedélyezése/letiltása. Alapértelmezett érték igaz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public abstract byte[] getLogoImageBytes()
```

Kép, amely a megjelenítő jobb felső sarkában logóként jelenik meg. A képfájl 32x64 pixel méretű PNG legyen, különben a logó helytelenül jelenhet meg.

**Visszatérési érték:**
byte[]

### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public abstract void setLogoImageBytes(byte[] value)
```

Kép, amely a megjelenítő jobb felső sarkában logóként jelenik meg. A képfájl 32x64 pixel méretű PNG legyen, különben a logó helytelenül jelenhet meg.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public abstract String getLogoLink()
```

Lekéri vagy beállítja egy logó teljes hiperhivatkozási címét. Csak akkor hat, ha egy (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) van megadva.

**Visszatérési érték:**
java.lang.String

### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public abstract void setLogoLink(String value)
```

Lekéri vagy beállítja egy logó teljes hiperhivatkozási címét. Csak akkor hat, ha egy (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) van megadva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

Megadja a JPEG képek minőségét. Alapértelmezett érték 95.

**Visszatérési érték:**
int

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

Megadja a JPEG képek minőségét. Alapértelmezett érték 95.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Lekéri vagy beállítja a módot, amelyben a diák az oldalon elhelyezésre kerülnek egy prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Ez a tulajdonság nem támogatja a [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) típusú objektumok hozzárendelését.

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

Lekéri vagy beállítja a módot, amelyben a diák az oldalon elhelyezésre kerülnek egy prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Ez a tulajdonság nem támogatja a [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) típusú objektumok hozzárendelését.

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
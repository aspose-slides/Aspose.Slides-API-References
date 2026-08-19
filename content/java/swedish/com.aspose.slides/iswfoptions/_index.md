---
title: ISwfOptions
second_title: Aspose.Slides för Java API-referens
description: Tillhandahåller alternativ som styr hur en presentation sparas i SWF-format.
type: docs
url: /sv/com.aspose.slides/iswfoptions/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISwfOptions extends ISaveOptions
```

Tillhandahåller alternativ som styr hur en presentation sparas i SWF-format.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCompressed()](#getCompressed--) | Anger om det genererade SWF-dokumentet ska komprimeras eller inte. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Anger om det genererade SWF-dokumentet ska komprimeras eller inte. |
| [getViewerIncluded()](#getViewerIncluded--) | Anger om det genererade SWF-dokumentet ska inkludera den integrerade dokumentvisaren eller inte. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | Anger om det genererade SWF-dokumentet ska inkludera den integrerade dokumentvisaren eller inte. |
| [getShowPageBorder()](#getShowPageBorder--) | Anger om kantlinjen runt sidor ska visas. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | Anger om kantlinjen runt sidor ska visas. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. |
| [getShowFullScreen()](#getShowFullScreen--) | Visa/dölj helskärmsknapp. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | Visa/dölj helskärmsknapp. |
| [getShowPageStepper()](#getShowPageStepper--) | Visa/dölj sidstegare. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | Visa/dölj sidstegare. |
| [getShowSearch()](#getShowSearch--) | Visa/dölj söksektion. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | Visa/dölj söksektion. |
| [getShowTopPane()](#getShowTopPane--) | Visa/dölj hela översta panelen. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | Visa/dölj hela översta panelen. |
| [getShowBottomPane()](#getShowBottomPane--) | Visa/dölj nedre panelen. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | Visa/dölj nedre panelen. |
| [getShowLeftPane()](#getShowLeftPane--) | Visa/dölj vänstra panelen. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | Visa/dölj vänstra panelen. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | Starta med öppnad vänsterpanel. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | Starta med öppnad vänsterpanel. |
| [getEnableContextMenu()](#getEnableContextMenu--) | Aktivera/inaktivera kontextmeny. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | Aktivera/inaktivera kontextmeny. |
| [getLogoImageBytes()](#getLogoImageBytes--) | Bild som kommer att visas som logotyp i övre högra hörnet av visaren. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | Bild som kommer att visas som logotyp i övre högra hörnet av visaren. |
| [getLogoLink()](#getLogoLink--) | Hämtar eller anger den fullständiga hyperlänkadressen för en logotyp. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | Hämtar eller anger den fullständiga hyperlänkadressen för en logotyp. |
| [getJpegQuality()](#getJpegQuality--) | Anger kvaliteten på JPEG-bilder. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Anger kvaliteten på JPEG-bilder. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Hämtar eller anger läget i vilket bilder placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Hämtar eller anger läget i vilket bilder placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |

### getCompressed() {#getCompressed--}
```
public abstract boolean getCompressed()
```

Anger om det genererade SWF-dokumentet ska komprimeras eller inte. Standardvärdet är true.

**Returnerar:**
boolean

### setCompressed(boolean value) {#setCompressed-boolean-}
```
public abstract void setCompressed(boolean value)
```

Anger om det genererade SWF-dokumentet ska komprimeras eller inte. Standardvärdet är true.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public abstract boolean getViewerIncluded()
```

Anger om det genererade SWF-dokumentet ska inkludera den integrerade dokumentvisaren eller inte. Standardvärdet är true.

**Returnerar:**
boolean

### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public abstract void setViewerIncluded(boolean value)
```

Anger om det genererade SWF-dokumentet ska inkludera den integrerade dokumentvisaren eller inte. Standardvärdet är true.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public abstract boolean getShowPageBorder()
```

Anger om kantlinjen runt sidor ska visas. Standardvärdet är true.

**Returnerar:**
boolean

### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public abstract void setShowPageBorder(boolean value)
```

Anger om kantlinjen runt sidor ska visas. Standardvärdet är true.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. Standardvärdet är false.

**Returnerar:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. Standardvärdet är false.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public abstract boolean getShowFullScreen()
```

Visa/dölj helskärmsknapp. Kan åsidosättas i flashvars. Standardvärdet är true.

**Returnerar:**
boolean

### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public abstract void setShowFullScreen(boolean value)
```

Visa/dölj helskärmsknapp. Kan åsidosättas i flashvars. Standardvärdet är true.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public abstract boolean getShowPageStepper()
```

Visa/dölj sidstegare. Kan åsidosättas i flashvars. Standardvärdet är true.

**Returnerar:**
boolean

### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public abstract void setShowPageStepper(boolean value)
```

Visa/dölj sidstegare. Kan åsidosättas i flashvars. Standardvärdet är true.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public abstract boolean getShowSearch()
```

Visa/dölj söksektion. Kan åsidosättas i flashvars. Standardvärdet är true.

**Returnerar:**
boolean

### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public abstract void setShowSearch(boolean value)
```

Visa/dölj söksektion. Kan åsidosättas i flashvars. Standardvärdet är true.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public abstract boolean getShowTopPane()
```

Visa/dölj hela översta panelen. Kan åsidosättas i flashvars. Standardvärdet är true.

**Returnerar:**
boolean

### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public abstract void setShowTopPane(boolean value)
```

Visa/dölj hela översta panelen. Kan åsidosättas i flashvars. Standardvärdet är true.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public abstract boolean getShowBottomPane()
```

Visa/dölj nedre panelen. Kan åsidosättas i flashvars. Standardvärdet är true.

**Returnerar:**
boolean

### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public abstract void setShowBottomPane(boolean value)
```

Visa/dölj nedre panelen. Kan åsidosättas i flashvars. Standardvärdet är true.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public abstract boolean getShowLeftPane()
```

Visa/dölj vänstra panelen. Kan åsidosättas i flashvars. Standardvärdet är true.

**Returnerar:**
boolean

### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public abstract void setShowLeftPane(boolean value)
```

Visa/dölj vänstra panelen. Kan åsidosättas i flashvars. Standardvärdet är true.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public abstract boolean getStartOpenLeftPane()
```

Starta med öppnad vänsterpanel. Kan åsidosättas i flashvars. Standardvärdet är false.

**Returnerar:**
boolean

### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public abstract void setStartOpenLeftPane(boolean value)
```

Starta med öppnad vänsterpanel. Kan åsidosättas i flashvars. Standardvärdet är false.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public abstract boolean getEnableContextMenu()
```

Aktivera/inaktivera kontextmeny. Standardvärdet är true.

**Returnerar:**
boolean

### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public abstract void setEnableContextMenu(boolean value)
```

Aktivera/inaktivera kontextmeny. Standardvärdet är true.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public abstract byte[] getLogoImageBytes()
```

Bild som kommer att visas som logotyp i övre högra hörnet av visaren. Bilden bör vara en 32x64 pixlar PNG, annars kan logotypen visas felaktigt.

**Returnerar:**
byte[]

### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public abstract void setLogoImageBytes(byte[] value)
```

Bild som kommer att visas som logotyp i övre högra hörnet av visaren. Bilden bör vara en 32x64 pixlar PNG, annars kan logotypen visas felaktigt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public abstract String getLogoLink()
```

Hämtar eller anger den fullständiga hyperlänkadressen för en logotyp. Har endast effekt om ett (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) är specificerat.

**Returnerar:**
java.lang.String

### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public abstract void setLogoLink(String value)
```

Hämtar eller anger den fullständiga hyperlänkadressen för en logotyp. Har endast effekt om ett (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) är specificerat.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

Anger kvaliteten på JPEG-bilder. Standardvärdet är 95.

**Returnerar:**
int

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

Anger kvaliteten på JPEG-bilder. Standardvärdet är 95.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Hämtar eller anger läget i vilket bilder placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Denna egendom stöder inte tilldelning av objekt av typen [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

--------------------

> ```
> Exempel:
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


**Returnerar:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Hämtar eller anger läget i vilket bilder placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Denna egendom stöder inte tilldelning av objekt av typen [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

--------------------

> ```
> Exempel:
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


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |
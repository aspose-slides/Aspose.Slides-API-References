---
title: SwfOptions
second_title: Aspose.Slides för Android via Java API-referens
description: Tillhandahåller alternativ som styr hur en presentation sparas i Swf-format.
type: docs
url: /sv/com.aspose.slides/swfoptions/
---
**Arv:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Alla implementerade gränssnitt:**
[com.aspose.slides.ISwfOptions](../../com.aspose.slides/iswfoptions)
```
public class SwfOptions extends SaveOptions implements ISwfOptions
```

Tillhandahåller alternativ som styr hur en presentation sparas i Swf-format.

--------------------

> ```
> The following example shows how to convert PowerPoint to SWF Flash.
>  
>  // Instansiera ett Presentation-objekt som representerar en presentationsfil
>  Presentation pres = new Presentation("HelloWorld.pptx");
>  try {
>      SwfOptions swfOptions = new SwfOptions();
>      SwfOptions.setViewerIncluded(false);
>      INotesCommentsLayoutingOptions notesOptions = swfOptions.getNotesCommentsLayouting();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      // Sparar presentation och anteckningssidor
>      pres.save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
>      swfOptions.setViewerIncluded(true);
>      pres.save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [SwfOptions()](#SwfOptions--) | Standardkonstruktor. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. |
| [getCompressed()](#getCompressed--) | Anger om det genererade SWF-dokumentet ska komprimeras eller inte. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Anger om det genererade SWF-dokumentet ska komprimeras eller inte. |
| [getViewerIncluded()](#getViewerIncluded--) | Anger om det genererade SWF-dokumentet ska inkludera den integrerade dokumentvisaren eller inte. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | Anger om det genererade SWF-dokumentet ska inkludera den integrerade dokumentvisaren eller inte. |
| [getShowPageBorder()](#getShowPageBorder--) | Anger om kantlinjen runt sidor ska visas. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | Anger om kantlinjen runt sidor ska visas. |
| [getShowFullScreen()](#getShowFullScreen--) | Visa/dölj helskärmsknapp. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | Visa/dölj helskärmsknapp. |
| [getShowPageStepper()](#getShowPageStepper--) | Visa/dölj sidstegare. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | Visa/dölj sidstegare. |
| [getShowSearch()](#getShowSearch--) | Visa/dölj söksektion. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | Visa/dölj söksektion. |
| [getShowTopPane()](#getShowTopPane--) | Visa/dölj hela övre panelen. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | Visa/dölj hela övre panelen. |
| [getShowBottomPane()](#getShowBottomPane--) | Visa/dölj nedre panelen. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | Visa/dölj nedre panelen. |
| [getShowLeftPane()](#getShowLeftPane--) | Visa/dölj vänsterpanel. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | Visa/dölj vänsterpanel. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | Starta med öppnad vänsterpanel. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | Starta med öppnad vänsterpanel. |
| [getEnableContextMenu()](#getEnableContextMenu--) | Aktivera/inaktivera snabbmenyn. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | Aktivera/inaktivera snabbmenyn. |
| [getLogoImageBytes()](#getLogoImageBytes--) | Bild som visas som logotyp i det övre högra hörnet av visaren. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | Bild som visas som logotyp i det övre högra hörnet av visaren. |
| [getLogoLink()](#getLogoLink--) | Hämtar eller anger den fullständiga hyperlänkadressen för en logotyp. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | Hämtar eller anger den fullständiga hyperlänkadressen för en logotyp. |
| [getJpegQuality()](#getJpegQuality--) | Anger kvaliteten på JPEG-bilder. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Anger kvaliteten på JPEG-bilder. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Hämtar eller anger läget i vilket bilder placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Hämtar eller anger läget i vilket bilder placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
### SwfOptions() {#SwfOptions--}
```
public SwfOptions()
```

Standardkonstruktor.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. Standard är false.

**Returnerar:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. Standard är false.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getCompressed() {#getCompressed--}
```
public final boolean getCompressed()
```

Anger om det genererade SWF-dokumentet ska komprimeras eller inte. Standard är true.

**Returnerar:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public final void setCompressed(boolean value)
```

Anger om det genererade SWF-dokumentet ska komprimeras eller inte. Standard är true.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public final boolean getViewerIncluded()
```

Anger om det genererade SWF-dokumentet ska inkludera den integrerade dokumentvisaren eller inte. Standard är true.

**Returnerar:**
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public final void setViewerIncluded(boolean value)
```

Anger om det genererade SWF-dokumentet ska inkludera den integrerade dokumentvisaren eller inte. Standard är true.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public final boolean getShowPageBorder()
```

Anger om kantlinjen runt sidor ska visas. Standard är true.

**Returnerar:**
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public final void setShowPageBorder(boolean value)
```

Anger om kantlinjen runt sidor ska visas. Standard är true.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public final boolean getShowFullScreen()
```

Visa/dölj helskärmsknapp. Kan åsidosättas i flashvars. Standard är true.

**Returnerar:**
boolean
### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public final void setShowFullScreen(boolean value)
```

Visa/dölj helskärmsknapp. Kan åsidosättas i flashvars. Standard är true.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public final boolean getShowPageStepper()
```

Visa/dölj sidstegare. Kan åsidosättas i flashvars. Standard är true.

**Returnerar:**
boolean
### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public final void setShowPageStepper(boolean value)
```

Visa/dölj sidstegare. Kan åsidosättas i flashvars. Standard är true.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public final boolean getShowSearch()
```

Visa/dölj söksektion. Kan åsidosättas i flashvars. Standard är true.

**Returnerar:**
boolean
### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public final void setShowSearch(boolean value)
```

Visa/dölj söksektion. Kan åsidosättas i flashvars. Standard är true.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public final boolean getShowTopPane()
```

Visa/dölj hela övre panelen. Kan åsidosättas i flashvars. Standard är true.

**Returnerar:**
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public final void setShowTopPane(boolean value)
```

Visa/dölj hela övre panelen. Kan åsidosättas i flashvars. Standard är true.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public final boolean getShowBottomPane()
```

Visa/dölj nedre panelen. Kan åsidosättas i flashvars. Standard är true.

**Returnerar:**
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public final void setShowBottomPane(boolean value)
```

Visa/dölj nedre panelen. Kan åsidosättas i flashvars. Standard är true.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public final boolean getShowLeftPane()
```

Visa/dölj vänsterpanel. Kan åsidosättas i flashvars. Standard är true.

**Returnerar:**
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public final void setShowLeftPane(boolean value)
```

Visa/dölj vänsterpanel. Kan åsidosättas i flashvars. Standard är true.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public final boolean getStartOpenLeftPane()
```

Starta med öppnad vänsterpanel. Kan åsidosättas i flashvars. Standard är false.

**Returnerar:**
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public final void setStartOpenLeftPane(boolean value)
```

Starta med öppnad vänsterpanel. Kan åsidosättas i flashvars. Standard är false.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public final boolean getEnableContextMenu()
```

Aktivera/inaktivera snabbmenyn. Standard är true.

**Returnerar:**
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public final void setEnableContextMenu(boolean value)
```

Aktivera/inaktivera snabbmenyn. Standard är true.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public final byte[] getLogoImageBytes()
```

Bild som visas som logotyp i det övre högra hörnet av visaren. Bilden bör vara 32x64 pixlar PNG, annars kan logotypen visas felaktigt.

**Returnerar:**
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public final void setLogoImageBytes(byte[] value)
```

Bild som visas som logotyp i det övre högra hörnet av visaren. Bilden bör vara 32x64 pixlar PNG, annars kan logotypen visas felaktigt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public final String getLogoLink()
```

Hämtar eller anger den fullständiga hyperlänkadressen för en logotyp. Har en effekt endast om en (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) anges.

**Returnerar:**
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public final void setLogoLink(String value)
```

Hämtar eller anger den fullständiga hyperlänkadressen för en logotyp. Har en effekt endast om en (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) anges.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

Anger kvaliteten på JPEG-bilder. Standard är 95.

**Returnerar:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

Anger kvaliteten på JPEG-bilder. Standard är 95.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Hämtar eller anger läget i vilket bilder placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Denna egenskap stöder inte tilldelning av objekt av typen [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

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

**Returnerar:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Hämtar eller anger läget i vilket bilder placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Denna egenskap stöder inte tilldelning av objekt av typen [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions).

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |
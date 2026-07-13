---
title: ISwfOptions
second_title: Aspose.Slides för Android via Java API-referens
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
| [getCompressed()](#getCompressed--) | Specifies whether the generated SWF document should be compressed or not. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Specifies whether the generated SWF document should be compressed or not. |
| [getViewerIncluded()](#getViewerIncluded--) | Specifies whether the generated SWF document should include the integrated document viewer or not. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | Specifies whether the generated SWF document should include the integrated document viewer or not. |
| [getShowPageBorder()](#getShowPageBorder--) | Specifies whether border around pages should be shown. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | Specifies whether border around pages should be shown. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specifies whether the generated document should include hidden slides or not. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specifies whether the generated document should include hidden slides or not. |
| [getShowFullScreen()](#getShowFullScreen--) | Show/hide fullscreen button. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | Show/hide fullscreen button. |
| [getShowPageStepper()](#getShowPageStepper--) | Show/hide page stepper. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | Show/hide page stepper. |
| [getShowSearch()](#getShowSearch--) | Show/hide search section. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | Show/hide search section. |
| [getShowTopPane()](#getShowTopPane--) | Show/hide whole top pane. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | Show/hide whole top pane. |
| [getShowBottomPane()](#getShowBottomPane--) | Show/hide bottom pane. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | Show/hide bottom pane. |
| [getShowLeftPane()](#getShowLeftPane--) | Show/hide left pane. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | Show/hide left pane. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | Start with opened left pane. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | Start with opened left pane. |
| [getEnableContextMenu()](#getEnableContextMenu--) | Enable/disable context menu. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | Enable/disable context menu. |
| [getLogoImageBytes()](#getLogoImageBytes--) | Image that will be displayed as logo in the top right corner of the viewer. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | Image that will be displayed as logo in the top right corner of the viewer. |
| [getLogoLink()](#getLogoLink--) | Gets or sets the full hyperlink address for a logo. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | Gets or sets the full hyperlink address for a logo. |
| [getJpegQuality()](#getJpegQuality--) | Specifies the quality of JPEG images. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Specifies the quality of JPEG images. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Gets or sets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Gets or sets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
### getCompressed() {#getCompressed--}
```
public abstract boolean getCompressed()
```

Anger om det genererade SWF-dokumentet ska komprimeras eller inte. Standard är true.

**Returnerar:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public abstract void setCompressed(boolean value)
```

Anger om det genererade SWF-dokumentet ska komprimeras eller inte. Standard är true.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getViewerIncluded() {#getViewerIncluded--}
```
public abstract boolean getViewerIncluded()
```

Anger om det genererade SWF-dokumentet ska inkludera den integrerade dokumentvisaren eller inte. Standard är true.

**Returnerar:**
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public abstract void setViewerIncluded(boolean value)
```

Anger om det genererade SWF-dokumentet ska inkludera den integrerade dokumentvisaren eller inte. Standard är true.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getShowPageBorder() {#getShowPageBorder--}
```
public abstract boolean getShowPageBorder()
```

Anger om kantlinjen runt sidor ska visas. Standard är true.

**Returnerar:**
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public abstract void setShowPageBorder(boolean value)
```

Anger om kantlinjen runt sidor ska visas. Standard är true.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. Standard är false.

**Returnerar:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. Standard är false.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getShowFullScreen() {#getShowFullScreen--}
```
public abstract boolean getShowFullScreen()
```

Visa/dölj helskärmsknapp. Kan åsidosättas i flashvars. Standard är true.

**Returnerar:**
boolean
### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public abstract void setShowFullScreen(boolean value)
```

Visa/dölj helskärmsknapp. Kan åsidosättas i flashvars. Standard är true.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getShowPageStepper() {#getShowPageStepper--}
```
public abstract boolean getShowPageStepper()
```

Visa/dölj sidstegare. Kan åsidosättas i flashvars. Standard är true.

**Returnerar:**
boolean
### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public abstract void setShowPageStepper(boolean value)
```

Visa/dölj sidstegare. Kan åsidosättas i flashvars. Standard är true.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getShowSearch() {#getShowSearch--}
```
public abstract boolean getShowSearch()
```

Visa/dölj söksektion. Kan åsidosättas i flashvars. Standard är true.

**Returnerar:**
boolean
### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public abstract void setShowSearch(boolean value)
```

Visa/dölj söksektion. Kan åsidosättas i flashvars. Standard är true.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getShowTopPane() {#getShowTopPane--}
```
public abstract boolean getShowTopPane()
```

Visa/dölj hela övre panelen. Kan åsidosättas i flashvars. Standard är true.

**Returnerar:**
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public abstract void setShowTopPane(boolean value)
```

Visa/dölj hela övre panelen. Kan åsidosättas i flashvars. Standard är true.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getShowBottomPane() {#getShowBottomPane--}
```
public abstract boolean getShowBottomPane()
```

Visa/dölj nedre panelen. Kan åsidosättas i flashvars. Standard är true.

**Returnerar:**
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public abstract void setShowBottomPane(boolean value)
```

Visa/dölj nedre panelen. Kan åsidosättas i flashvars. Standard är true.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getShowLeftPane() {#getShowLeftPane--}
```
public abstract boolean getShowLeftPane()
```

Visa/dölj vänstra panelen. Kan åsidosättas i flashvars. Standard är true.

**Returnerar:**
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public abstract void setShowLeftPane(boolean value)
```

Visa/dölj vänstra panelen. Kan åsidosättas i flashvars. Standard är true.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public abstract boolean getStartOpenLeftPane()
```

Starta med vänstra panelen öppen. Kan åsidosättas i flashvars. Standard är false.

**Returnerar:**
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public abstract void setStartOpenLeftPane(boolean value)
```

Starta med vänstra panelen öppen. Kan åsidosättas i flashvars. Standard är false.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getEnableContextMenu() {#getEnableContextMenu--}
```
public abstract boolean getEnableContextMenu()
```

Aktivera/inaktivera snabbmenyn. Standard är true.

**Returnerar:**
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public abstract void setEnableContextMenu(boolean value)
```

Aktivera/inaktivera snabbmenyn. Standard är true.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getLogoImageBytes() {#getLogoImageBytes--}
```
public abstract byte[] getLogoImageBytes()
```

Bild som visas som logotyp i det övre högra hörnet av visaren. Bilden ska vara en 32x64 pixlar PNG, annars kan logotypen visas felaktigt.

**Returnerar:**
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public abstract void setLogoImageBytes(byte[] value)
```

Bild som visas som logotyp i det övre högra hörnet av visaren. Bilden ska vara en 32x64 pixlar PNG, annars kan logotypen visas felaktigt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte[] |  |
### getLogoLink() {#getLogoLink--}
```
public abstract String getLogoLink()
```

Hämtar eller anger den fullständiga hyperlänkadressen för en logotyp. Har bara effekt om en (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) har angetts.

**Returnerar:**
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public abstract void setLogoLink(String value)
```

Hämtar eller anger den fullständiga hyperlänkadressen för en logotyp. Har bara effekt om en (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) har angetts.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

Anger kvaliteten på JPEG-bilder. Standard är 95.

**Returnerar:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

Anger kvaliteten på JPEG-bilder. Standard är 95.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Hämtar eller anger läget som bilder placeras på sidan i när en presentation exporteras [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Denna egenskap stödjer inte att tilldela objekt av typen [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Hämtar eller anger läget som bilder placeras på sidan i när en presentation exporteras [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Denna egenskap stödjer inte att tilldela objekt av typen [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

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
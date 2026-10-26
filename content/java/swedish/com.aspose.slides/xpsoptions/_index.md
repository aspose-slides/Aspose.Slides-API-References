---
title: XpsOptions
second_title: Aspose.Slides för Java API-referens
description: Tillhandahåller alternativ som styr hur en presentation sparas i XPS-format.
type: docs
url: /sv/com.aspose.slides/xpsoptions/
---
**Arv:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IXpsOptions](../../com.aspose.slides/ixpsoptions)
```
public class XpsOptions extends SaveOptions implements IXpsOptions
```

Tillhandahåller alternativ som styr hur en presentation sparas i XPS-format.

--------------------

> ```
> The following example shows how to converting presentations to XPS using default settings.
>  
>  // Instansiera ett Presentation-objekt som representerar en presentationsfil
>  Presentation pres = new Presentation("Convert_XPS.pptx");
>  try {
>      // Sparar presentationen till XPS-dokument
>      pres.save("XPS_Output_Without_XPSOption_out.xps", SaveFormat.Xps);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to converting presentations to XPS using custom settings.
>  
>  // Instansiera ett Presentation-objekt som representerar en presentationsfil
>  Presentation pres = new Presentation("Convert_XPS_Options.pptx");
>  try {
>      // Instansiera TiffOptions-klassen
>      XpsOptions options = new XpsOptions();
>      // Spara metafiler som PNG
>      options.setSaveMetafilesAsPng(true);
>      // Spara presentationen till XPS-dokument
>      pres.save("XPS_With_Options_out.xps", SaveFormat.Xps, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [XpsOptions()](#XpsOptions--) | Standardkonstruktor. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Sant för att konvertera alla metafiler som används i en presentation till PNG-bilder. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Sant för att konvertera alla metafiler som används i en presentation till PNG-bilder. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Sant för att rita en svart ram runt varje bild. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Sant för att rita en svart ram runt varje bild. |
### XpsOptions() {#XpsOptions--}
```
public XpsOptions()
```


Standardkonstruktor.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. Standard är **false**.

**Returnerar:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. Standard är **false**.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```


Sant för att konvertera alla metafiler som används i en presentation till PNG-bilder. Läsa/skriva boolean.

--------------------

Standard är **true**.

**Returnerar:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```


Sant för att konvertera alla metafiler som används i en presentation till PNG-bilder. Läsa/skriva boolean.

--------------------

Standard är **true**.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```


Sant för att rita en svart ram runt varje bild. Läsa/skriva boolean.

--------------------

Standard är **false**.

**Returnerar:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```


Sant för att rita en svart ram runt varje bild. Läsa/skriva boolean.

--------------------

Standard är **false**.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
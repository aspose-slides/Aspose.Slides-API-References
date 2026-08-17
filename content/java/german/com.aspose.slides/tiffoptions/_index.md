---
title: TiffOptions
second_title: Aspose.Slides für Java API-Referenz
description: Bietet Optionen, die steuern, wie eine Präsentation im TIFF-Format gespeichert wird.
type: docs
url: /de/com.aspose.slides/tiffoptions/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ITiffOptions](../../com.aspose.slides/itiffoptions)
```
public class TiffOptions extends SaveOptions implements ITiffOptions
```

Bietet Optionen, die steuern, wie eine Präsentation im TIFF-Format gespeichert wird.

--------------------

> ```
> The following example shows how to convert PowerPoint to TIFF with default size.
>  
>  // Instanziiert ein Presentation-Objekt, das eine Präsentationsdatei darstellt
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      // Speichert die Präsentation als TIFF-Dokument
>      pres.save("Tiffoutput_out.tiff", SaveFormat.Tiff);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom size.
>  
>  // Instanziiert ein Presentation-Objekt, das eine Präsentationsdatei darstellt
>  Presentation pres = new Presentation("Convert_Tiff_Custom.pptx");
>  try {
>      // Instanziiert die TiffOptions-Klasse
>      TiffOptions opts = new TiffOptions();
>      // Legt den Kompressionstyp fest
>      opts.setCompressionType(TiffCompressionTypes.Default);
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      opts.setSlidesLayoutOptions(notesOptions);
>      // Kompressionstypen
>      // Default - Gibt das Standardschema für die Kompression (LZW) an.
>      // None - Gibt an, dass keine Kompression verwendet wird.
>      // CCITT3
>      // CCITT4
>      // LZW
>      // RLE
>      // Die Tiefe hängt vom Kompressionstyp ab und kann nicht manuell eingestellt werden.
>      // Die Auflösungseinheit ist immer gleich 2 (Punkte pro Zoll)
>      // Legt die Bild-DPI fest
>      opts.setDpiX(200);
>      opts.setDpiY(100);
>      // Bildgröße festlegen
>      opts.setImageSize(new Dimension(1728, 1078));
>      // Speichert die Präsentation als TIFF mit angegebener Bildgröße
>      pres.save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom image pixel format.
>  
>  // Instanziiert ein Presentation-Objekt, das eine Präsentationsdatei darstellt
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      options.setPixelFormat(ImagePixelFormat.Format8bppIndexed);
> 
>      //ImagePixelFormat enthält die folgenden Werte (wie aus der Dokumentation ersichtlich):
>      //Format1bppIndexed; // 1 Bit pro Pixel, indiziert.
>      //Format4bppIndexed; // 4 Bits pro Pixel, indiziert.
>      //Format8bppIndexed; // 8 Bits pro Pixel, indiziert.
>      //Format24bppRgb; // 24 Bits pro Pixel, RGB.
>      //Format32bppArgb; // 32 Bits pro Pixel, ARGB.
> 
>      // Speichert die Präsentation als TIFF mit angegebener Bildgröße
>      pres.save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TiffOptions()](#TiffOptions--) | Standardkonstruktor. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Bietet Optionen, die das Aussehen von Ink-Objekten im exportierten Dokument steuern. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Gibt an, ob das erzeugte Dokument verborgene Folien enthalten soll oder nicht. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Gibt an, ob das erzeugte Dokument verborgene Folien enthalten soll oder nicht. |
| [getImageSize()](#getImageSize--) | Gibt die Größe eines erzeugten TIFF-Bildes an. |
| [setImageSize(Dimension value)](#setImageSize-java.awt.Dimension-) | Gibt die Größe eines erzeugten TIFF-Bildes an. |
| [getDpiX()](#getDpiX--) | Gibt die horizontale Auflösung in Punkten pro Zoll an. |
| [setDpiX(long value)](#setDpiX-long-) | Gibt die horizontale Auflösung in Punkten pro Zoll an. |
| [getDpiY()](#getDpiY--) | Gibt die vertikale Auflösung in Punkten pro Zoll an. |
| [setDpiY(long value)](#setDpiY-long-) | Gibt die vertikale Auflösung in Punkten pro Zoll an. |
| [getCompressionType()](#getCompressionType--) | Gibt den Kompressionstyp an. |
| [setCompressionType(int value)](#setCompressionType-int-) | Gibt den Kompressionstyp an. |
| [getPixelFormat()](#getPixelFormat--) | Gibt das Pixel-Format für die erzeugten Bilder an. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Gibt das Pixel-Format für die erzeugten Bilder an. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Ruft den Modus ab oder legt ihn fest, in dem Folien beim Export einer Präsentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Ruft den Modus ab oder legt ihn fest, in dem Folien beim Export einer Präsentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Gibt den Algorithmus an, der ein Farbbild in ein Schwarz-weiß-Bild umwandelt. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Gibt den Algorithmus an, der ein Farbbild in ein Schwarz-weiß-Bild umwandelt. |
### TiffOptions() {#TiffOptions--}
```
public TiffOptions()
```

Standardkonstruktor.

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Bietet Optionen, die das Aussehen von Ink-Objekten im exportierten Dokument steuern. Nur lesbar [IInkOptions](../../com.aspose.slides/iinkoptions)

**Rückgabewert:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Gibt an, ob das erzeugte Dokument verborgene Folien enthalten soll oder nicht. Standardwert ist false.

**Rückgabewert:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Gibt an, ob das erzeugte Dokument verborgene Folien enthalten soll oder nicht. Standardwert ist false.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getImageSize() {#getImageSize--}
```
public final Dimension getImageSize()
```

Gibt die Größe eines erzeugten TIFF-Bildes an. Der Standardwert ist 0x0, was bedeutet, dass die Bildgröße anhand der Foliengröße der Präsentation berechnet wird. Lese/Schreib java.awt.Dimension.

**Rückgabewert:**
java.awt.Dimension
### setImageSize(Dimension value) {#setImageSize-java.awt.Dimension-}
```
public final void setImageSize(Dimension value)
```

Gibt die Größe eines erzeugten TIFF-Bildes an. Der Standardwert ist 0x0, was bedeutet, dass die Bildgröße anhand der Foliengröße der Präsentation berechnet wird. Lese/Schreib java.awt.Dimension.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getDpiX() {#getDpiX--}
```
public final long getDpiX()
```

Gibt die horizontale Auflösung in Punkten pro Zoll an. Lese/Schreib long.

**Rückgabewert:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public final void setDpiX(long value)
```

Gibt die horizontale Auflösung in Punkten pro Zoll an. Lese/Schreib long.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public final long getDpiY()
```

Gibt die vertikale Auflösung in Punkten pro Zoll an. Lese/Schreib long.

**Rückgabewert:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public final void setDpiY(long value)
```

Gibt die vertikale Auflösung in Punkten pro Zoll an. Lese/Schreib long.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | long |  |

### getCompressionType() {#getCompressionType--}
```
public final int getCompressionType()
```

Gibt den Kompressionstyp an. Lese/Schreib [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Rückgabewert:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public final void setCompressionType(int value)
```

Gibt den Kompressionstyp an. Lese/Schreib [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public final int getPixelFormat()
```

Gibt das Pixel-Format für die erzeugten Bilder an. Lese/Schreib [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Rückgabewert:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public final void setPixelFormat(int value)
```

Gibt das Pixel-Format für die erzeugten Bilder an. Lese/Schreib [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Ruft den Modus ab oder legt ihn fest, in dem Folien beim Export einer Präsentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Rückgabewert:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Ruft den Modus ab oder legt ihn fest, in dem Folien beim Export einer Präsentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getBwConversionMode() {#getBwConversionMode--}
```
public final int getBwConversionMode()
```

Gibt den Algorithmus an, der ein Farbbild in ein Schwarz-weiß-Bild umwandelt. Diese Option wird nur angewendet, wenn der Kompressionstyp (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) auf [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) oder [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) gesetzt ist. Lese/Schreib [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Standardwert ist [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

--------------------

> ```
> TiffOptions tiffOptions = new TiffOptions();
>  tiffOptions.setCompressionType(TiffCompressionTypes.CCITT4);
>  tiffOptions.setBwConversionMode(BlackWhiteConversionMode.Dithering);
>  Presentation presentation = new Presentation();
>  try {
>      presentation.save(tiffFilePath, SaveFormat.Tiff, tiffOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Rückgabewert:**
int
### setBwConversionMode(int value) {#setBwConversionMode-int-}
```
public final void setBwConversionMode(int value)
```

Gibt den Algorithmus an, der ein Farbbild in ein Schwarz-weiß-Bild umwandelt. Diese Option wird nur angewendet, wenn der Kompressionstyp (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) auf [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) oder [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) gesetzt ist. Lese/Schreib [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Standardwert ist [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

--------------------

> ```
> TiffOptions tiffOptions = new TiffOptions();
>  tiffOptions.setCompressionType(TiffCompressionTypes.CCITT4);
>  tiffOptions.setBwConversionMode(BlackWhiteConversionMode.Dithering);
>  Presentation presentation = new Presentation();
>  try {
>      presentation.save(tiffFilePath, SaveFormat.Tiff, tiffOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
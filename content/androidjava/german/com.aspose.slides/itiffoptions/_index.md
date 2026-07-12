---
title: ITiffOptions
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Bietet Optionen, die steuern, wie eine Präsentation im TIFF-Format gespeichert wird.
type: docs
url: /de/com.aspose.slides/itiffoptions/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ITiffOptions extends ISaveOptions
```

Bietet Optionen, die steuern, wie eine Präsentation im TIFF-Format gespeichert wird.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getImageSize()](#getImageSize--) | Legt die Größe eines erzeugten TIFF-Bildes fest. |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | Legt die Größe eines erzeugten TIFF-Bildes fest. |
| [getDpiX()](#getDpiX--) | Legt die horizontale Auflösung in Punkten pro Zoll fest. |
| [setDpiX(long value)](#setDpiX-long-) | Legt die horizontale Auflösung in Punkten pro Zoll fest. |
| [getDpiY()](#getDpiY--) | Legt die vertikale Auflösung in Punkten pro Zoll fest. |
| [setDpiY(long value)](#setDpiY-long-) | Legt die vertikale Auflösung in Punkten pro Zoll fest. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Legt fest, ob das erzeugte Dokument versteckte Folien enthalten soll oder nicht. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Legt fest, ob das erzeugte Dokument versteckte Folien enthalten soll oder nicht. |
| [getCompressionType()](#getCompressionType--) | Legt den Kompressionstyp fest. |
| [setCompressionType(int value)](#setCompressionType-int-) | Legt den Kompressionstyp fest. |
| [getPixelFormat()](#getPixelFormat--) | Legt das Pixel-Format für die erzeugten Bilder fest. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Legt das Pixel-Format für die erzeugten Bilder fest. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Erhält oder setzt den Modus, in dem Folien auf der Seite beim Export einer Präsentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) angeordnet werden. |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Erhält oder setzt den Modus, in dem Folien auf der Seite beim Export einer Präsentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) angeordnet werden. |
| [getBwConversionMode()](#getBwConversionMode--) | Legt den Algorithmus für die Umwandlung eines Farbbildes in ein Schwarz-Weiß-Bild fest. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Legt den Algorithmus für die Umwandlung eines Farbbildes in ein Schwarz-Weiß-Bild fest. |
| [getInkOptions()](#getInkOptions--) | Bietet Optionen, die das Aussehen von Ink-Objekten im exportierten Dokument steuern. |

### getImageSize() {#getImageSize--}
```
public abstract Size getImageSize()
```

Legt die Größe eines erzeugten TIFF-Bildes fest. Der Standardwert ist 0x0, was bedeutet, dass die erzeugten Bildgrößen basierend auf dem Foliengrößenwert der Präsentation berechnet werden. Lesen/Schreiben [Size](../../com.aspose.slides.android/size).

**Rückgabewert:**
[Size](../../com.aspose.slides.android/size)

### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public abstract void setImageSize(Size value)
```

Legt die Größe eines erzeugten TIFF-Bildes fest. Der Standardwert ist 0x0, was bedeutet, dass die erzeugten Bildgrößen basierend auf dem Foliengrößenwert der Präsentation berechnet werden. Lesen/Schreiben [Size](../../com.aspose.slides.android/size).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getDpiX() {#getDpiX--}
```
public abstract long getDpiX()
```

Legt die horizontale Auflösung in Punkten pro Zoll fest. Lesen/Schreiben long.

**Rückgabewert:**
long

### setDpiX(long value) {#setDpiX-long-}
```
public abstract void setDpiX(long value)
```

Legt die horizontale Auflösung in Punkten pro Zoll fest. Lesen/Schreiben long.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public abstract long getDpiY()
```

Legt die vertikale Auflösung in Punkten pro Zoll fest. Lesen/Schreiben long.

**Rückgabewert:**
long

### setDpiY(long value) {#setDpiY-long-}
```
public abstract void setDpiY(long value)
```

Legt die vertikale Auflösung in Punkten pro Zoll fest. Lesen/Schreiben long.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | long |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Legt fest, ob das erzeugte Dokument versteckte Folien enthalten soll oder nicht. Standard ist false.

**Rückgabewert:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Legt fest, ob das erzeugte Dokument versteckte Folien enthalten soll oder nicht. Standard ist false.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getCompressionType() {#getCompressionType--}
```
public abstract int getCompressionType()
```

Legt den Kompressionstyp fest. Lesen/Schreiben [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Rückgabewert:**
int

### setCompressionType(int value) {#setCompressionType-int-}
```
public abstract void setCompressionType(int value)
```

Legt den Kompressionstyp fest. Lesen/Schreiben [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public abstract int getPixelFormat()
```

Legt das Pixel-Format für die erzeugten Bilder fest. Lesen/Schreiben [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Rückgabewert:**
int

### setPixelFormat(int value) {#setPixelFormat-int-}
```
public abstract void setPixelFormat(int value)
```

Legt das Pixel-Format für die erzeugten Bilder fest. Lesen/Schreiben [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Erhält oder setzt den Modus, in dem Folien auf der Seite beim Export einer Präsentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) angeordnet werden.

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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Erhält oder setzt den Modus, in dem Folien auf der Seite beim Export einer Präsentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) angeordnet werden.

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
public abstract int getBwConversionMode()
```

Legt den Algorithmus für die Umwandlung eines Farbbildes in ein Schwarz-Weiß-Bild fest. Diese Option wird nur angewendet, wenn CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) auf [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) oder [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) gesetzt ist. Lesen/Schreiben [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Standard ist [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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
public abstract void setBwConversionMode(int value)
```

Legt den Algorithmus für die Umwandlung eines Farbbildes in ein Schwarz-Weiß-Bild fest. Diese Option wird nur angewendet, wenn CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) auf [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) oder [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) gesetzt ist. Lesen/Schreiben [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Standard ist [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Bietet Optionen, die das Aussehen von Ink-Objekten im exportierten Dokument steuern. Nur lesbar [IInkOptions](../../com.aspose.slides/iinkoptions)

**Rückgabewert:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
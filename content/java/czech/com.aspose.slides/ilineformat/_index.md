---
title: ILineFormat
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje formát čáry.
type: docs
url: /cs/com.aspose.slides/ilineformat/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormat extends ILineParamSource
```

Reprezentuje formát čáry.
## Metody

| Method | Description |
| --- | --- |
| [isFormatNotDefined()](#isFormatNotDefined--) | Vrací true, pokud není formát čáry definován (právě vytvořený, výchozí). |
| [getFillFormat()](#getFillFormat--) | Vrací výplňový formát čáry. |
| [getSketchFormat()](#getSketchFormat--) | Vrací skicový formát čáry. |
| [getWidth()](#getWidth--) | Vrací nebo nastavuje šířku čáry. |
| [setWidth(double value)](#setWidth-double-) | Vrací nebo nastavuje šířku čáry. |
| [getDashStyle()](#getDashStyle--) | Vrací nebo nastavuje styl čárkování čáry. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | Vrací nebo nastavuje styl čárkování čáry. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Vrací nebo nastavuje vlastní vzor čárek. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | Vrací nebo nastavuje vlastní vzor čárek. |
| [getCapStyle()](#getCapStyle--) | Vrací nebo nastavuje styl zakončení čáry. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | Vrací nebo nastavuje styl zakončení čáry. |
| [getStyle()](#getStyle--) | Vrací nebo nastavuje styl čáry. |
| [setStyle(byte value)](#setStyle-byte-) | Vrací nebo nastavuje styl čáry. |
| [getAlignment()](#getAlignment--) | Vrací nebo nastavuje zarovnání čáry. |
| [setAlignment(byte value)](#setAlignment-byte-) | Vrací nebo nastavuje zarovnání čáry. |
| [getJoinStyle()](#getJoinStyle--) | Vrací nebo nastavuje styl spojení úseků čáry. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | Vrací nebo nastavuje styl spojení úseků čáry. |
| [getMiterLimit()](#getMiterLimit--) | Vrací nebo nastavuje limit štíhlého spoje čáry. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Vrací nebo nastavuje limit štíhlého spoje čáry. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Vrací nebo nastavuje styl šipky na začátku čáry. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | Vrací nebo nastavuje styl šipky na začátku čáry. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Vrací nebo nastavuje styl šipky na konci čáry. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | Vrací nebo nastavuje styl šipky na konci čáry. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Vrací nebo nastavuje šířku šipky na začátku čáry. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | Vrací nebo nastavuje šířku šipky na začátku čáry. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Vrací nebo nastavuje šířku šipky na konci čáry. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | Vrací nebo nastavuje šířku šipky na konci čáry. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Vrací nebo nastavuje délku šipky na začátku čáry. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | Vrací nebo nastavuje délku šipky na začátku čáry. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Vrací nebo nastavuje délku šipky na konci čáry. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | Vrací nebo nastavuje délku šipky na konci čáry. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | Určuje, zda jsou dvě instance LineFormat rovny. |
| [getEffective()](#getEffective--) | Získá efektivní data formátování čáry s použitím dědičnosti. |

### isFormatNotDefined() {#isFormatNotDefined--}
```
public abstract boolean isFormatNotDefined()
```

Vrací true, pokud není formát čáry definován (právě vytvořený, výchozí). Pouze pro čtení boolean.

**Vrací:**
boolean

### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormat getFillFormat()
```

Vrací výplňový formát čáry. Pouze pro čtení [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Vrací:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)

### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormat getSketchFormat()
```

Vrací skicový formát čáry. Pouze pro čtení [ISketchFormat](../../com.aspose.slides/isketchformat).

**Vrací:**
[ISketchFormat](../../com.aspose.slides/isketchformat)

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Vrací nebo nastavuje šířku čáry. Čtení/zápis double.

**Vrací:**
double

### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

Vrací nebo nastavuje šířku čáry. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

Vrací nebo nastavuje styl čárkování čáry. Čtení/zápis [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Vrací:**
byte

### setDashStyle(byte value) {#setDashStyle-byte-}
```
public abstract void setDashStyle(byte value)
```

Vrací nebo nastavuje styl čárkování čáry. Čtení/zápis [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

Vrací nebo nastavuje vlastní vzor čárek. Čtení/zápis float[].

**Vrací:**
float[]

### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public abstract void setCustomDashPattern(float[] value)
```

Vrací nebo nastavuje vlastní vzor čárek. Čtení/zápis float[].

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

Vrací nebo nastavuje styl zakončení čáry. Čtení/zápis [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Vrací:**
byte

### setCapStyle(byte value) {#setCapStyle-byte-}
```
public abstract void setCapStyle(byte value)
```

Vrací nebo nastavuje styl zakončení čáry. Čtení/zápis [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

Vrací nebo nastavuje styl čáry. Čtení/zápis [LineStyle](../../com.aspose.slides/linestyle).

**Vrací:**
byte

### setStyle(byte value) {#setStyle-byte-}
```
public abstract void setStyle(byte value)
```

Vrací nebo nastavuje styl čáry. Čtení/zápis [LineStyle](../../com.aspose.slides/linestyle).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

Vrací nebo nastavuje zarovnání čáry. Čtení/zápis [LineAlignment](../../com.aspose.slides/linealignment).

**Vrací:**
byte

### setAlignment(byte value) {#setAlignment-byte-}
```
public abstract void setAlignment(byte value)
```

Vrací nebo nastavuje zarovnání čáry. Čtení/zápis [LineAlignment](../../com.aspose.slides/linealignment).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

Vrací nebo nastavuje styl spojení úseků čáry. Čtení/zápis [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Vrací:**
byte

### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public abstract void setJoinStyle(byte value)
```

Vrací nebo nastavuje styl spojení úseků čáry. Čtení/zápis [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

Vrací nebo nastavuje limit štíhlého spoje čáry. Čtení/zápis float.

**Vrací:**
float

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public abstract void setMiterLimit(float value)
```

Vrací nebo nastavuje limit štíhlého spoje čáry. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

Vrací nebo nastavuje styl šipky na začátku čáry. Čtení/zápis [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Vrací:**
byte

### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public abstract void setBeginArrowheadStyle(byte value)
```

Vrací nebo nastavuje styl šipky na začátku čáry. Čtení/zápis [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

Vrací nebo nastavuje styl šipky na konci čáry. Čtení/zápis [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Vrací:**
byte

### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public abstract void setEndArrowheadStyle(byte value)
```

Vrací nebo nastavuje styl šipky na konci čáry. Čtení/zápis [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

Vrací nebo nastavuje šířku šipky na začátku čáry. Čtení/zápis [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Vrací:**
byte

### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public abstract void setBeginArrowheadWidth(byte value)
```

Vrací nebo nastavuje šířku šipky na začátku čáry. Čtení/zápis [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

Vrací nebo nastavuje šířku šipky na konci čáry. Čtení/zápis [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Vrací:**
byte

### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public abstract void setEndArrowheadWidth(byte value)
```

Vrací nebo nastavuje šířku šipky na konci čáry. Čtení/zápis [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

Vrací nebo nastavuje délku šipky na začátku čáry. Čtení/zápis [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Vrací:**
byte

### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public abstract void setBeginArrowheadLength(byte value)
```

Vrací nebo nastavuje délku šipky na začátku čáry. Čtení/zápis [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

Vrací nebo nastavuje délku šipky na konci čáry. Čtení/zápis [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Vrací:**
byte

### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public abstract void setEndArrowheadLength(byte value)
```

Vrací nebo nastavuje délku šipky na konci čáry. Čtení/zápis [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public abstract boolean equals(ILineFormat lineFormat)
```

Určuje, zda jsou dvě instance LineFormat rovny.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | LineFormat, se kterým se porovnává aktuální LineFormat. |

**Vrací:**
boolean - **true**, pokud je zadaný LineFormat roven aktuálnímu LineFormat; jinak **false**.

### getEffective() {#getEffective--}
```
public abstract ILineFormatEffectiveData getEffective()
```

Získá efektivní data formátování čáry s použitím dědičnosti.

**Vrací:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - A [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).
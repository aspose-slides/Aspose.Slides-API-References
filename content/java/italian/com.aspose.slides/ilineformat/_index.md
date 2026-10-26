---
title: ILineFormat
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta il formato di una linea.
type: docs
url: /it/com.aspose.slides/ilineformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormat extends ILineParamSource
```

Rappresenta il formato di una linea.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isFormatNotDefined()](#isFormatNotDefined--) | Restituisce true se il formato della linea non è definito (come appena creato, predefinito). |
| [getFillFormat()](#getFillFormat--) | Restituisce il formato di riempimento di una linea. |
| [getSketchFormat()](#getSketchFormat--) | Restituisce il formato di schizzi di una linea. |
| [getWidth()](#getWidth--) | Restituisce o imposta la larghezza di una linea. |
| [setWidth(double value)](#setWidth-double-) | Restituisce o imposta la larghezza di una linea. |
| [getDashStyle()](#getDashStyle--) | Restituisce o imposta lo stile di tratteggio della linea. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | Restituisce o imposta lo stile di tratteggio della linea. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Restituisce o imposta lo schema di tratteggio personalizzato. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | Restituisce o imposta lo schema di tratteggio personalizzato. |
| [getCapStyle()](#getCapStyle--) | Restituisce o imposta lo stile di estremità della linea. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | Restituisce o imposta lo stile di estremità della linea. |
| [getStyle()](#getStyle--) | Restituisce o imposta lo stile della linea. |
| [setStyle(byte value)](#setStyle-byte-) | Restituisce o imposta lo stile della linea. |
| [getAlignment()](#getAlignment--) | Restituisce o imposta l’allineamento della linea. |
| [setAlignment(byte value)](#setAlignment-byte-) | Restituisce o imposta l’allineamento della linea. |
| [getJoinStyle()](#getJoinStyle--) | Restituisce o imposta lo stile di giunzione delle linee. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | Restituisce o imposta lo stile di giunzione delle linee. |
| [getMiterLimit()](#getMiterLimit--) | Restituisce o imposta il limite di smusso di una linea. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Restituisce o imposta il limite di smusso di una linea. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Restituisce o imposta lo stile della punta della freccia all’inizio di una linea. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | Restituisce o imposta lo stile della punta della freccia all’inizio di una linea. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Restituisce o imposta lo stile della punta della freccia alla fine di una linea. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | Restituisce o imposta lo stile della punta della freccia alla fine di una linea. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Restituisce o imposta la larghezza della punta della freccia all’inizio di una linea. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | Restituisce o imposta la larghezza della punta della freccia all’inizio di una linea. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Restituisce o imposta la larghezza della punta della freccia alla fine di una linea. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | Restituisce o imposta la larghezza della punta della freccia alla fine di una linea. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Restituisce o imposta la lunghezza della punta della freccia all’inizio di una linea. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | Restituisce o imposta la lunghezza della punta della freccia all’inizio di una linea. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Restituisce o imposta la lunghezza della punta della freccia alla fine di una linea. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | Restituisce o imposta la lunghezza della punta della freccia alla fine di una linea. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | Determina se le due istanze di LineFormat sono uguali. |
| [getEffective()](#getEffective--) | Ottiene i dati di formattazione della linea efficaci con l’eredità applicata. |

### isFormatNotDefined() {#isFormatNotDefined--}
```
public abstract boolean isFormatNotDefined()
```

Restituisce true se il formato della linea non è definito (come appena creato, predefinito). Solo lettura boolean.

**Restituisce:**
boolean

### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormat getFillFormat()
```

Restituisce il formato di riempimento di una linea. Solo lettura [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Restituisce:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)

### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormat getSketchFormat()
```

Restituisce il formato di schizzi di una linea. Solo lettura [ISketchFormat](../../com.aspose.slides/isketchformat).

**Restituisce:**
[ISketchFormat](../../com.aspose.slides/isketchformat)

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Restituisce o imposta la larghezza di una linea. Lettura/scrittura double.

**Restituisce:**
double

### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

Restituisce o imposta la larghezza di una linea. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

Restituisce o imposta lo stile di tratteggio della linea. Lettura/scrittura [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Restituisce:**
byte

### setDashStyle(byte value) {#setDashStyle-byte-}
```
public abstract void setDashStyle(byte value)
```

Restituisce o imposta lo stile di tratteggio della linea. Lettura/scrittura [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

Restituisce o imposta lo schema di tratteggio personalizzato. Lettura/scrittura float[].

**Restituisce:**
float[]

### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public abstract void setCustomDashPattern(float[] value)
```

Restituisce o imposta lo schema di tratteggio personalizzato. Lettura/scrittura float[].

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

Restituisce o imposta lo stile di estremità della linea. Lettura/scrittura [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Restituisce:**
byte

### setCapStyle(byte value) {#setCapStyle-byte-}
```
public abstract void setCapStyle(byte value)
```

Restituisce o imposta lo stile di estremità della linea. Lettura/scrittura [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

Restituisce o imposta lo stile della linea. Lettura/scrittura [LineStyle](../../com.aspose.slides/linestyle).

**Restituisce:**
byte

### setStyle(byte value) {#setStyle-byte-}
```
public abstract void setStyle(byte value)
```

Restituisce o imposta lo stile della linea. Lettura/scrittura [LineStyle](../../com.aspose.slides/linestyle).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

Restituisce o imposta l’allineamento della linea. Lettura/scrittura [LineAlignment](../../com.aspose.slides/linealignment).

**Restituisce:**
byte

### setAlignment(byte value) {#setAlignment-byte-}
```
public abstract void setAlignment(byte value)
```

Restituisce o imposta l’allineamento della linea. Lettura/scrittura [LineAlignment](../../com.aspose.slides/linealignment).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

Restituisce o imposta lo stile di giunzione delle linee. Lettura/scrittura [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Restituisce:**
byte

### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public abstract void setJoinStyle(byte value)
```

Restituisce o imposta lo stile di giunzione delle linee. Lettura/scrittura [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

Restituisce o imposta il limite di smusso di una linea. Lettura/scrittura float.

**Restituisce:**
float

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public abstract void setMiterLimit(float value)
```

Restituisce o imposta il limite di smusso di una linea. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

Restituisce o imposta lo stile della punta della freccia all’inizio di una linea. Lettura/scrittura [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Restituisce:**
byte

### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public abstract void setBeginArrowheadStyle(byte value)
```

Restituisce o imposta lo stile della punta della freccia all’inizio di una linea. Lettura/scrittura [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

Restituisce o imposta lo stile della punta della freccia alla fine di una linea. Lettura/scrittura [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Restituisce:**
byte

### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public abstract void setEndArrowheadStyle(byte value)
```

Restituisce o imposta lo stile della punta della freccia alla fine di una linea. Lettura/scrittura [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

Restituisce o imposta la larghezza della punta della freccia all’inizio di una linea. Lettura/scrittura [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Restituisce:**
byte

### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public abstract void setBeginArrowheadWidth(byte value)
```

Restituisce o imposta la larghezza della punta della freccia all’inizio di una linea. Lettura/scrittura [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

Restituisce o imposta la larghezza della punta della freccia alla fine di una linea. Lettura/scrittura [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Restituisce:**
byte

### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public abstract void setEndArrowheadWidth(byte value)
```

Restituisce o imposta la larghezza della punta della freccia alla fine di una linea. Lettura/scrittura [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

Restituisce o imposta la lunghezza della punta della freccia all’inizio di una linea. Lettura/scrittura [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Restituisce:**
byte

### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public abstract void setBeginArrowheadLength(byte value)
```

Restituisce o imposta la lunghezza della punta della freccia all’inizio di una linea. Lettura/scrittura [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

Restituisce o imposta la lunghezza della punta della freccia alla fine di una linea. Lettura/scrittura [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Restituisce:**
byte

### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public abstract void setEndArrowheadLength(byte value)
```

Restituisce o imposta la lunghezza della punta della freccia alla fine di una linea. Lettura/scrittura [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public abstract boolean equals(ILineFormat lineFormat)
```

Determina se le due istanze di LineFormat sono uguali.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | Il LineFormat da confrontare con l’attuale LineFormat. |

**Restituisce:**
boolean - **true** se il LineFormat specificato è uguale al LineFormat corrente; altrimenti, **false**.

### getEffective() {#getEffective--}
```
public abstract ILineFormatEffectiveData getEffective()
```

Ottiene i dati di formattazione della linea efficaci con l’eredità applicata.

**Restituisce:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - Un [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).
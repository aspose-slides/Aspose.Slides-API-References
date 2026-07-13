---
title: ILineFormat
second_title: Aspose.Slides per Android via Riferimento API Java
description: Rappresenta il formato di una linea.
type: docs
url: /it/com.aspose.slides/ilineformat/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormat extends ILineParamSource
```

Rappresenta il formato di una linea.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isFormatNotDefined()](#isFormatNotDefined--) | Restituisce true se il formato della linea non è definito (come appena creata, predefinito). |
| [getFillFormat()](#getFillFormat--) | Restituisce il formato di riempimento di una linea. |
| [getSketchFormat()](#getSketchFormat--) | Restituisce il formato di schizzi di una linea. |
| [getWidth()](#getWidth--) | Restituisce o imposta la larghezza di una linea. |
| [setWidth(double value)](#setWidth-double-) | Restituisce o imposta la larghezza di una linea. |
| [getDashStyle()](#getDashStyle--) | Restituisce o imposta lo stile di tratteggio della linea. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | Restituisce o imposta lo stile di tratteggio della linea. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Restituisce o imposta il modello di tratteggio personalizzato. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | Restituisce o imposta il modello di tratteggio personalizzato. |
| [getCapStyle()](#getCapStyle--) | Restituisce o imposta lo stile di cap della linea. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | Restituisce o imposta lo stile di cap della linea. |
| [getStyle()](#getStyle--) | Restituisce o imposta lo stile della linea. |
| [setStyle(byte value)](#setStyle-byte-) | Restituisce o imposta lo stile della linea. |
| [getAlignment()](#getAlignment--) | Restituisce o imposta l'allineamento della linea. |
| [setAlignment(byte value)](#setAlignment-byte-) | Restituisce o imposta l'allineamento della linea. |
| [getJoinStyle()](#getJoinStyle--) | Restituisce o imposta lo stile di unione delle linee. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | Restituisce o imposta lo stile di unione delle linee. |
| [getMiterLimit()](#getMiterLimit--) | Restituisce o imposta il limite di punta di una linea. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Restituisce o imposta il limite di punta di una linea. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Restituisce o imposta lo stile della freccia all'inizio di una linea. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | Restituisce o imposta lo stile della freccia all'inizio di una linea. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Restituisce o imposta lo stile della freccia alla fine di una linea. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | Restituisce o imposta lo stile della freccia alla fine di una linea. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Restituisce o imposta la larghezza della freccia all'inizio di una linea. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | Restituisce o imposta la larghezza della freccia all'inizio di una linea. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Restituisce o imposta la larghezza della freccia alla fine di una linea. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | Restituisce o imposta la larghezza della freccia alla fine di una linea. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Restituisce o imposta la lunghezza della freccia all'inizio di una linea. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | Restituisce o imposta la lunghezza della freccia all'inizio di una linea. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Restituisce o imposta la lunghezza della freccia alla fine di una linea. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | Restituisce o imposta la lunghezza della freccia alla fine di una linea. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | Determina se le due istanze di LineFormat sono uguali. |
| [getEffective()](#getEffective--) | Ottiene i dati di formattazione della linea effettivi con l'ereditarietà applicata. |

### isFormatNotDefined() {#isFormatNotDefined--}
```
public abstract boolean isFormatNotDefined()
```

Restituisce true se il formato della linea non è definito (come appena creata, predefinito). Booleano di sola lettura.

**Restituisce:**
boolean

### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormat getFillFormat()
```

Restituisce il formato di riempimento di una linea. [ILineFillFormat](../../com.aspose.slides/ilinefillformat) di sola lettura.

**Restituisce:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)

### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormat getSketchFormat()
```

Restituisce il formato di schizzi di una linea. [ISketchFormat](../../com.aspose.slides/isketchformat) di sola lettura.

**Restituisce:**
[ISketchFormat](../../com.aspose.slides/isketchformat)

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Restituisce o imposta la larghezza di una linea. double di lettura/scrittura.

**Restituisce:**
double

### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

Restituisce o imposta la larghezza di una linea. double di lettura/scrittura.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

Restituisce o imposta lo stile di tratteggio della linea. [LineDashStyle](../../com.aspose.slides/linedashstyle) di lettura/scrittura.

**Restituisce:**
byte

### setDashStyle(byte value) {#setDashStyle-byte-}
```
public abstract void setDashStyle(byte value)
```

Restituisce o imposta lo stile di tratteggio della linea. [LineDashStyle](../../com.aspose.slides/linedashstyle) di lettura/scrittura.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

Restituisce o imposta il modello di tratteggio personalizzato. float[] di lettura/scrittura.

**Restituisce:**
float[]

### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public abstract void setCustomDashPattern(float[] value)
```

Restituisce o imposta il modello di tratteggio personalizzato. float[] di lettura/scrittura.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

Restituisce o imposta lo stile di cap della linea. [LineCapStyle](../../com.aspose.slides/linecapstyle) di lettura/scrittura.

**Restituisce:**
byte

### setCapStyle(byte value) {#setCapStyle-byte-}
```
public abstract void setCapStyle(byte value)
```

Restituisce o imposta lo stile di cap della linea. [LineCapStyle](../../com.aspose.slides/linecapstyle) di lettura/scrittura.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

Restituisce o imposta lo stile della linea. [LineStyle](../../com.aspose.slides/linestyle) di lettura/scrittura.

**Restituisce:**
byte

### setStyle(byte value) {#setStyle-byte-}
```
public abstract void setStyle(byte value)
```

Restituisce o imposta lo stile della linea. [LineStyle](../../com.aspose.slides/linestyle) di lettura/scrittura.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

Restituisce o imposta l'allineamento della linea. [LineAlignment](../../com.aspose.slides/linealignment) di lettura/scrittura.

**Restituisce:**
byte

### setAlignment(byte value) {#setAlignment-byte-}
```
public abstract void setAlignment(byte value)
```

Restituisce o imposta l'allineamento della linea. [LineAlignment](../../com.aspose.slides/linealignment) di lettura/scrittura.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

Restituisce o imposta lo stile di unione delle linee. [LineJoinStyle](../../com.aspose.slides/linejoinstyle) di lettura/scrittura.

**Restituisce:**
byte

### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public abstract void setJoinStyle(byte value)
```

Restituisce o imposta lo stile di unione delle linee. [LineJoinStyle](../../com.aspose.slides/linejoinstyle) di lettura/scrittura.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

Restituisce o imposta il limite di punta di una linea. float di lettura/scrittura.

**Restituisce:**
float

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public abstract void setMiterLimit(float value)
```

Restituisce o imposta il limite di punta di una linea. float di lettura/scrittura.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

Restituisce o imposta lo stile della freccia all'inizio di una linea. [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle) di lettura/scrittura.

**Restituisce:**
byte

### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public abstract void setBeginArrowheadStyle(byte value)
```

Restituisce o imposta lo stile della freccia all'inizio di una linea. [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle) di lettura/scrittura.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

Restituisce o imposta lo stile della freccia alla fine di una linea. [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle) di lettura/scrittura.

**Restituisce:**
byte

### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public abstract void setEndArrowheadStyle(byte value)
```

Restituisce o imposta lo stile della freccia alla fine di una linea. [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle) di lettura/scrittura.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

Restituisce o imposta la larghezza della freccia all'inizio di una linea. [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth) di lettura/scrittura.

**Restituisce:**
byte

### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public abstract void setBeginArrowheadWidth(byte value)
```

Restituisce o imposta la larghezza della freccia all'inizio di una linea. [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth) di lettura/scrittura.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

Restituisce o imposta la larghezza della freccia alla fine di una linea. [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth) di lettura/scrittura.

**Restituisce:**
byte

### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public abstract void setEndArrowheadWidth(byte value)
```

Restituisce o imposta la larghezza della freccia alla fine di una linea. [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth) di lettura/scrittura.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

Restituisce o imposta la lunghezza della freccia all'inizio di una linea. [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength) di lettura/scrittura.

**Restituisce:**
byte

### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public abstract void setBeginArrowheadLength(byte value)
```

Restituisce o imposta la lunghezza della freccia all'inizio di una linea. [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength) di lettura/scrittura.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

Restituisce o imposta la lunghezza della freccia alla fine di una linea. [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength) di lettura/scrittura.

**Restituisce:**
byte

### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public abstract void setEndArrowheadLength(byte value)
```

Restituisce o imposta la lunghezza della freccia alla fine di una linea. [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength) di lettura/scrittura.

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
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | Il LineFormat da confrontare con l'attuale LineFormat. |

**Restituisce:**
boolean - **true** se il LineFormat specificato è uguale al LineFormat corrente; altrimenti, **false**.

### getEffective() {#getEffective--}
```
public abstract ILineFormatEffectiveData getEffective()
```

Ottiene i dati di formattazione della linea effettivi con l'ereditarietà applicata.

**Restituisce:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - Un [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).
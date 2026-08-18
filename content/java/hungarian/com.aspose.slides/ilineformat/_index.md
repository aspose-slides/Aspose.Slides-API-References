---
title: ILineFormat
second_title: Aspose.Slides Java API Referencia
description: A vonal formátumát képviseli.
type: docs
url: /hu/com.aspose.slides/ilineformat/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormat extends ILineParamSource
```

A vonal formátumát képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [isFormatNotDefined()](#isFormatNotDefined--) | Igaz értéket ad vissza, ha a vonal formátuma nincs definiálva (újonnan létrehozott, alapértelmezett). |
| [getFillFormat()](#getFillFormat--) | Visszaadja a vonal kitöltésének formátumát. |
| [getSketchFormat()](#getSketchFormat--) | Visszaadja a vonal vázlat formátumát. |
| [getWidth()](#getWidth--) | Visszaadja vagy beállítja a vonal szélességét. |
| [setWidth(double value)](#setWidth-double-) | Visszaadja vagy beállítja a vonal szélességét. |
| [getDashStyle()](#getDashStyle--) | Visszaadja vagy beállítja a vonal szaggatott stílusát. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | Visszaadja vagy beállítja a vonal szaggatott stílusát. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Visszaadja vagy beállítja az egyéni szaggatott mintát. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | Visszaadja vagy beállítja az egyéni szaggatott mintát. |
| [getCapStyle()](#getCapStyle--) | Visszaadja vagy beállítja a vonal végpont stílusát. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | Visszaadja vagy beállítja a vonal végpont stílusát. |
| [getStyle()](#getStyle--) | Visszaadja vagy beállítja a vonal stílusát. |
| [setStyle(byte value)](#setStyle-byte-) | Visszaadja vagy beállítja a vonal stílusát. |
| [getAlignment()](#getAlignment--) | Visszaadja vagy beállítja a vonal igazítását. |
| [setAlignment(byte value)](#setAlignment-byte-) | Visszaadja vagy beállítja a vonal igazítását. |
| [getJoinStyle()](#getJoinStyle--) | Visszaadja vagy beállítja a vonalak összekapcsolási stílusát. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | Visszaadja vagy beállítja a vonalak összekapcsolási stílusát. |
| [getMiterLimit()](#getMiterLimit--) | Visszaadja vagy beállítja a vonal miter limitjét. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Visszaadja vagy beállítja a vonal miter limitjét. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Visszaadja vagy beállítja a vonal elején lévő nyílfej stílusát. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | Visszaadja vagy beállítja a vonal elején lévő nyílfej stílusát. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Visszaadja vagy beállítja a vonal végén lévő nyílfej stílusát. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | Visszaadja vagy beállítja a vonal végén lévő nyílfej stílusát. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Visszaadja vagy beállítja a vonal elején lévő nyílfej szélességét. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | Visszaadja vagy beállítja a vonal elején lévő nyílfej szélességét. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Visszaadja vagy beállítja a vonal végén lévő nyílfej szélességét. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | Visszaadja vagy beállítja a vonal végén lévő nyílfej szélességét. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Visszaadja vagy beállítja a vonal elején lévő nyílfej hosszát. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | Visszaadja vagy beállítja a vonal elején lévő nyílfej hosszát. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Visszaadja vagy beállítja a vonal végén lévő nyílfej hosszát. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | Visszaadja vagy beállítja a vonal végén lévő nyílfej hosszát. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | Megállapítja, hogy a két LineFormat példány egyenlő-e. |
| [getEffective()](#getEffective--) | Lekéri a hatékony vonalformázási adatokat a öröklődés alkalmazásával. |

### isFormatNotDefined() {#isFormatNotDefined--}
```
public abstract boolean isFormatNotDefined()
```

Igaz értéket ad vissza, ha a vonal formátuma nincs definiálva (újonnan létrehozott, alapértelmezett). Csak olvasható boolean.

**Visszatér:**  
boolean

### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormat getFillFormat()
```

Visszaadja a vonal kitöltésének formátumát. Csak olvasható [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Visszatér:**  
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)

### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormat getSketchFormat()
```

Visszaadja a vonal vázlat formátumát. Csak olvasható [ISketchFormat](../../com.aspose.slides/isketchformat).

**Visszatér:**  
[ISketchFormat](../../com.aspose.slides/isketchformat)

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Visszaadja vagy beállítja a vonal szélességét. Olvasható/írható double.

**Visszatér:**  
double

### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

Visszaadja vagy beállítja a vonal szélességét. Olvasható/írható double.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

Visszaadja vagy beállítja a vonal szaggatott stílusát. Olvasható/írható [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Visszatér:**  
byte

### setDashStyle(byte value) {#setDashStyle-byte-}
```
public abstract void setDashStyle(byte value)
```

Visszaadja vagy beállítja a vonal szaggatott stílusát. Olvasható/írható [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

Visszaadja vagy beállítja az egyéni szaggatott mintát. Olvasható/írható float[].

**Visszatér:**  
float[]

### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public abstract void setCustomDashPattern(float[] value)
```

Visszaadja vagy beállítja az egyéni szaggatott mintát. Olvasható/írható float[].

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

Visszaadja vagy beállítja a vonal végpont stílusát. Olvasható/írható [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Visszatér:**  
byte

### setCapStyle(byte value) {#setCapStyle-byte-}
```
public abstract void setCapStyle(byte value)
```

Visszaadja vagy beállítja a vonal végpont stílusát. Olvasható/írható [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

Visszaadja vagy beállítja a vonal stílusát. Olvasható/írható [LineStyle](../../com.aspose.slides/linestyle).

**Visszatér:**  
byte

### setStyle(byte value) {#setStyle-byte-}
```
public abstract void setStyle(byte value)
```

Visszaadja vagy beállítja a vonal stílusát. Olvasható/írható [LineStyle](../../com.aspose.slides/linestyle).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

Visszaadja vagy beállítja a vonal igazítását. Olvasható/írható [LineAlignment](../../com.aspose.slides/linealignment).

**Visszatér:**  
byte

### setAlignment(byte value) {#setAlignment-byte-}
```
public abstract void setAlignment(byte value)
```

Visszaadja vagy beállítja a vonal igazítását. Olvasható/írható [LineAlignment](../../com.aspose.slides/linealignment).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

Visszaadja vagy beállítja a vonalak összekapcsolási stílusát. Olvasható/írható [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Visszatér:**  
byte

### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public abstract void setJoinStyle(byte value)
```

Visszaadja vagy beállítja a vonalak összekapcsolási stílusát. Olvasható/írható [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

Visszaadja vagy beállítja a vonal miter limitjét. Olvasható/írható float.

**Visszatér:**  
float

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public abstract void setMiterLimit(float value)
```

Visszaadja vagy beállítja a vonal miter limitjét. Olvasható/írható float.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

Visszaadja vagy beállítja a vonal elején lévő nyílfej stílusát. Olvasható/írható [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Visszatér:**  
byte

### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public abstract void setBeginArrowheadStyle(byte value)
```

Visszaadja vagy beállítja a vonal elején lévő nyílfej stílusát. Olvasható/írható [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

Visszaadja vagy beállítja a vonal végén lévő nyílfej stílusát. Olvasható/írható [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Visszatér:**  
byte

### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public abstract void setEndArrowheadStyle(byte value)
```

Visszaadja vagy beállítja a vonal végén lévő nyílfej stílusát. Olvasható/írható [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

Visszaadja vagy beállítja a vonal elején lévő nyílfej szélességét. Olvasható/írható [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Visszatér:**  
byte

### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public abstract void setBeginArrowheadWidth(byte value)
```

Visszaadja vagy beállítja a vonal elején lévő nyílfej szélességét. Olvasható/írható [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

Visszaadja vagy beállítja a vonal végén lévő nyílfej szélességét. Olvasható/írható [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Visszatér:**  
byte

### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public abstract void setEndArrowheadWidth(byte value)
```

Visszaadja vagy beállítja a vonal végén lévő nyílfej szélességét. Olvasható/írható [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

Visszaadja vagy beállítja a vonal elején lévő nyílfej hosszát. Olvasható/írható [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Visszatér:**  
byte

### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public abstract void setBeginArrowheadLength(byte value)
```

Visszaadja vagy beállítja a vonal elején lévő nyílfej hosszát. Olvasható/írható [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

Visszaadja vagy beállítja a vonal végén lévő nyílfej hosszát. Olvasható/írható [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Visszatér:**  
byte

### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public abstract void setEndArrowheadLength(byte value)
```

Visszaadja vagy beállítja a vonal végén lévő nyílfej hosszát. Olvasható/írható [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public abstract boolean equals(ILineFormat lineFormat)
```

Megállapítja, hogy a két LineFormat példány egyenlő-e.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | A LineFormat, amivel a jelenlegi LineFormat-ot összehasonlítja. |

**Visszatér:**  
boolean - **true** ha a megadott LineFormat egyenlő a jelenlegi LineFormat-tel; különben, **false**.

### getEffective() {#getEffective--}
```
public abstract ILineFormatEffectiveData getEffective()
```

Lekéri a hatékony vonalformázási adatokat a öröklődés alkalmazásával.

**Visszatér:**  
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - A [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).
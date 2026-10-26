---
title: LineFormat
second_title: Aspose.Slides Androidhoz a Java API hivatkozásán keresztül
description: A vonal formátumát képviseli.
type: docs
url: /hu/com.aspose.slides/lineformat/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Minden megvalósított interfész:**
[com.aspose.slides.ILineFormat](../../com.aspose.slides/ilineformat)
```
public final class LineFormat extends PVIObject implements ILineFormat
```

A vonal formátumát képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [isFormatNotDefined()](#isFormatNotDefined--) | Igaz értéket ad vissza, ha a vonal formátuma nincs definiálva (újonnan létrehozott, alapértelmezett). |
| [getFillFormat()](#getFillFormat--) | Visszaadja a vonal kitöltés formátumát. |
| [getSketchFormat()](#getSketchFormat--) | Visszaadja a vonal vázlat formátumát. |
| [getWidth()](#getWidth--) | Visszaadja vagy beállítja a vonal szélességét. |
| [setWidth(double value)](#setWidth-double-) | Visszaadja vagy beállítja a vonal szélességét. |
| [getDashStyle()](#getDashStyle--) | Visszaadja vagy beállítja a vonal vonalstílusát. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | Visszaadja vagy beállítja a vonal vonalstílusát. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Visszaadja vagy beállítja az egyéni szaggatott mintát. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | Visszaadja vagy beállítja az egyéni szaggatott mintát. |
| [getCapStyle()](#getCapStyle--) | Visszaadja vagy beállítja a vonal végpont stílusát. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | Visszaadja vagy beállítja a vonal végpont stílusát. |
| [getStyle()](#getStyle--) | Visszaadja vagy beállítja a vonal stílusát. |
| [setStyle(byte value)](#setStyle-byte-) | Visszaadja vagy beállítja a vonal stílusát. |
| [getAlignment()](#getAlignment--) | Visszaadja vagy beállítja a vonal igazítását. |
| [setAlignment(byte value)](#setAlignment-byte-) | Visszaadja vagy beállítja a vonal igazítását. |
| [getJoinStyle()](#getJoinStyle--) | Visszaadja vagy beállítja a vonalak csatlakozási stílusát. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | Visszaadja vagy beállítja a vonalak csatlakozási stílusát. |
| [getMiterLimit()](#getMiterLimit--) | Visszaadja vagy beállítja a vonal ferdülési korlátját. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Visszaadja vagy beállítja a vonal ferdülési korlátját. |
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
| [getEffective()](#getEffective--) | Megkapja a vonal formázási adatokat a öröklődés alkalmazásával. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Verzió. Csak olvasható long.

**Visszatér:**
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Összehasonlítja a megadott objektummal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Visszatér:**
boolean

### isFormatNotDefined() {#isFormatNotDefined--}
```
public final boolean isFormatNotDefined()
```

Igaz értéket ad vissza, ha a vonal formátuma nincs definiálva (újonnan létrehozott, alapértelmezett). Csak olvasható boolean.

**Visszatér:**
boolean

### getFillFormat() {#getFillFormat--}
```
public final ILineFillFormat getFillFormat()
```

Visszaadja a vonal kitöltés formátumát. Csak olvasható [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Visszatér:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)

### getSketchFormat() {#getSketchFormat--}
```
public final ISketchFormat getSketchFormat()
```

Visszaadja a vonal vázlat formátumát. Csak olvasható [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Visszatér:**
[ISketchFormat](../../com.aspose.slides/isketchformat)

### getWidth() {#getWidth--}
```
public final double getWidth()
```

Visszaadja vagy beállítja a vonal szélességét. Olvasás/írás double.

**Visszatér:**
double

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

Visszaadja vagy beállítja a vonal szélességét. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public final byte getDashStyle()
```

Visszaadja vagy beállítja a vonal vonalstílusát. Olvasás/írás [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Visszatér:**
byte

### setDashStyle(byte value) {#setDashStyle-byte-}
```
public final void setDashStyle(byte value)
```

Visszaadja vagy beállítja a vonal vonalstílusát. Olvasás/írás [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public final float[] getCustomDashPattern()
```

Visszaadja vagy beállítja az egyéni szaggatott mintát. Olvasás/írás float[].

**Visszatér:**
float[]

### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public final void setCustomDashPattern(float[] value)
```

Visszaadja vagy beállítja az egyéni szaggatott mintát. Olvasás/írás float[].

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public final byte getCapStyle()
```

Visszaadja vagy beállítja a vonal végpont stílusát. Olvasás/írás [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Visszatér:**
byte

### setCapStyle(byte value) {#setCapStyle-byte-}
```
public final void setCapStyle(byte value)
```

Visszaadja vagy beállítja a vonal végpont stílusát. Olvasás/írás [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public final byte getStyle()
```

Visszaadja vagy beállítja a vonal stílusát. Olvasás/írás [LineStyle](../../com.aspose.slides/linestyle).

**Visszatér:**
byte

### setStyle(byte value) {#setStyle-byte-}
```
public final void setStyle(byte value)
```

Visszaadja vagy beállítja a vonal stílusát. Olvasás/írás [LineStyle](../../com.aspose.slides/linestyle).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public final byte getAlignment()
```

Visszaadja vagy beállítja a vonal igazítását. Olvasás/írás [LineAlignment](../../com.aspose.slides/linealignment).

**Visszatér:**
byte

### setAlignment(byte value) {#setAlignment-byte-}
```
public final void setAlignment(byte value)
```

Visszaadja vagy beállítja a vonal igazítását. Olvasás/írás [LineAlignment](../../com.aspose.slides/linealignment).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public final byte getJoinStyle()
```

Visszaadja vagy beállítja a vonalak csatlakozási stílusát. Olvasás/írás [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Visszatér:**
byte

### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public final void setJoinStyle(byte value)
```

Visszaadja vagy beállítja a vonalak csatlakozási stílusát. Olvasás/írás [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```

Visszaadja vagy beállítja a vonal ferdülési korlátját. Olvasás/írás float.

**Visszatér:**
float

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```

Visszaadja vagy beállítja a vonal ferdülési korlátját. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public final byte getBeginArrowheadStyle()
```

Visszaadja vagy beállítja a vonal elején lévő nyílfej stílusát. Olvasás/írás [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Visszatér:**
byte

### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public final void setBeginArrowheadStyle(byte value)
```

Visszaadja vagy beállítja a vonal elején lévő nyílfej stílusát. Olvasás/írás [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public final byte getEndArrowheadStyle()
```

Visszaadja vagy beállítja a vonal végén lévő nyílfej stílusát. Olvasás/írás [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Visszatér:**
byte

### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public final void setEndArrowheadStyle(byte value)
```

Visszaadja vagy beállítja a vonal végén lévő nyílfej stílusát. Olvasás/írás [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public final byte getBeginArrowheadWidth()
```

Visszaadja vagy beállítja a vonal elején lévő nyílfej szélességét. Olvasás/írás [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Visszatér:**
byte

### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public final void setBeginArrowheadWidth(byte value)
```

Visszaadja vagy beállítja a vonal elején lévő nyílfej szélességét. Olvasás/írás [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public final byte getEndArrowheadWidth()
```

Visszaadja vagy beállítja a vonal végén lévő nyílfej szélességét. Olvasás/írás [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Visszatér:**
byte

### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public final void setEndArrowheadWidth(byte value)
```

Visszaadja vagy beállítja a vonal végén lévő nyílfej szélességét. Olvasás/írás [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public final byte getBeginArrowheadLength()
```

Visszaadja vagy beállítja a vonal elején lévő nyílfej hosszát. Olvasás/írás [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Visszatér:**
byte

### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public final void setBeginArrowheadLength(byte value)
```

Visszaadja vagy beállítja a vonal elején lévő nyílfej hosszát. Olvasás/írás [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public final byte getEndArrowheadLength()
```

Visszaadja vagy beállítja a vonal végén lévő nyílfej hosszát. Olvasás/írás [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Visszatér:**
byte

### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public final void setEndArrowheadLength(byte value)
```

Visszaadja vagy beállítja a vonal végén lévő nyílfej hosszát. Olvasás/írás [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public final boolean equals(ILineFormat lineFormat)
```

Megállapítja, hogy a két LineFormat példány egyenlő-e.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | A LineFormat, amelyet a jelenlegi LineFormat-val összehasonlít. |

**Visszatér:**
boolean – **true** ha a megadott LineFormat egyenlő a jelenlegi LineFormat-tal; egyébként **false**.

### getEffective() {#getEffective--}
```
public final ILineFormatEffectiveData getEffective()
```

Megkapja a vonal formázási adatokat a öröklődés alkalmazásával.

--------------------

> ```
> This example demonstrates getting shape's effective line format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	ILineFormatEffectiveData effectiveLineFormat = pres.getSlides().get_Item(0).getShapes().get_Item(0).getLineFormat().getEffective();
>  	System.out.println("Style: " + effectiveLineFormat.getStyle());
>  	System.out.println("Width: " + effectiveLineFormat.getWidth());
>  	System.out.println("Fill type: " + effectiveLineFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**Visszatér:** [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - A [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).
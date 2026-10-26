---
title: LineFormat
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta il formato di una linea.
type: docs
url: /it/com.aspose.slides/lineformat/
---
**Eredità:** [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tutte le interfacce implementate:**
[com.aspose.slides.ILineFormat](../../com.aspose.slides/ilineformat)
```
public final class LineFormat extends PVIObject implements ILineFormat
```

Rappresenta il formato di una linea.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [isFormatNotDefined()](#isFormatNotDefined--) | Restituisce true se il formato della linea non è definito (come appena creato, default). |
| [getFillFormat()](#getFillFormat--) | Restituisce il formato di riempimento di una linea. |
| [getSketchFormat()](#getSketchFormat--) | Restituisce il formato di schizzo di una linea. |
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
| [getMiterLimit()](#getMiterLimit--) | Restituisce o imposta il limite di spigolo di una linea. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Restituisce o imposta il limite di spigolo di una linea. |
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
| [getEffective()](#getEffective--) | Ottiene i dati di formattazione della linea effettiva con l'ereditarietà applicata. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versione. Di sola lettura long.

**Restituisce:**
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Confronta con l'oggetto specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Restituisce:**
boolean

### isFormatNotDefined() {#isFormatNotDefined--}
```
public final boolean isFormatNotDefined()
```

Restituisce true se il formato della linea non è definito (come appena creato, default). Di sola lettura boolean .

**Restituisce:**
boolean

### getFillFormat() {#getFillFormat--}
```
public final ILineFillFormat getFillFormat()
```

Restituisce il formato di riempimento di una linea. Di sola lettura [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Restituisce:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)

### getSketchFormat() {#getSketchFormat--}
```
public final ISketchFormat getSketchFormat()
```

Restituisce il formato di schizzo di una linea. Di sola lettura [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Restituisce:**
[ISketchFormat](../../com.aspose.slides/isketchformat)

### getWidth() {#getWidth--}
```
public final double getWidth()
```

Restituisce o imposta la larghezza di una linea. Lettura/scrittura double .

**Restituisce:**
double

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

Restituisce o imposta la larghezza di una linea. Lettura/scrittura double .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public final byte getDashStyle()
```

Restituisce o imposta lo stile di tratteggio della linea. Lettura/scrittura [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Restituisce:**
byte

### setDashStyle(byte value) {#setDashStyle-byte-}
```
public final void setDashStyle(byte value)
```

Restituisce o imposta lo stile di tratteggio della linea. Lettura/scrittura [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public final float[] getCustomDashPattern()
```

Restituisce o imposta il modello di tratteggio personalizzato. Lettura/scrittura float[] .

**Restituisce:**
float[]

### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public final void setCustomDashPattern(float[] value)
```

Restituisce o imposta il modello di tratteggio personalizzato. Lettura/scrittura float[] .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public final byte getCapStyle()
```

Restituisce o imposta lo stile di cap della linea. Lettura/scrittura [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Restituisce:**
byte

### setCapStyle(byte value) {#setCapStyle-byte-}
```
public final void setCapStyle(byte value)
```

Restituisce o imposta lo stile di cap della linea. Lettura/scrittura [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public final byte getStyle()
```

Restituisce o imposta lo stile della linea. Lettura/scrittura [LineStyle](../../com.aspose.slides/linestyle).

**Restituisce:**
byte

### setStyle(byte value) {#setStyle-byte-}
```
public final void setStyle(byte value)
```

Restituisce o imposta lo stile della linea. Lettura/scrittura [LineStyle](../../com.aspose.slides/linestyle).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public final byte getAlignment()
```

Restituisce o imposta l'allineamento della linea. Lettura/scrittura [LineAlignment](../../com.aspose.slides/linealignment).

**Restituisce:**
byte

### setAlignment(byte value) {#setAlignment-byte-}
```
public final void setAlignment(byte value)
```

Restituisce o imposta l'allineamento della linea. Lettura/scrittura [LineAlignment](../../com.aspose.slides/linealignment).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public final byte getJoinStyle()
```

Restituisce o imposta lo stile di unione delle linee. Lettura/scrittura [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Restituisce:**
byte

### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public final void setJoinStyle(byte value)
```

Restituisce o imposta lo stile di unione delle linee. Lettura/scrittura [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```

Restituisce o imposta il limite di spigolo di una linea. Lettura/scrittura float .

**Restituisce:**
float

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```

Restituisce o imposta il limite di spigolo di una linea. Lettura/scrittura float .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public final byte getBeginArrowheadStyle()
```

Restituisce o imposta lo stile della freccia all'inizio di una linea. Lettura/scrittura [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Restituisce:**
byte

### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public final void setBeginArrowheadStyle(byte value)
```

Restituisce o imposta lo stile della freccia all'inizio di una linea. Lettura/scrittura [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public final byte getEndArrowheadStyle()
```

Restituisce o imposta lo stile della freccia alla fine di una linea. Lettura/scrittura [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Restituisce:**
byte

### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public final void setEndArrowheadStyle(byte value)
```

Restituisce o imposta lo stile della freccia alla fine di una linea. Lettura/scrittura [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public final byte getBeginArrowheadWidth()
```

Restituisce o imposta la larghezza della freccia all'inizio di una linea. Lettura/scrittura [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Restituisce:**
byte

### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public final void setBeginArrowheadWidth(byte value)
```

Restituisce o imposta la larghezza della freccia all'inizio di una linea. Lettura/scrittura [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public final byte getEndArrowheadWidth()
```

Restituisce o imposta la larghezza della freccia alla fine di una linea. Lettura/scrittura [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Restituisce:**
byte

### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public final void setEndArrowheadWidth(byte value)
```

Restituisce o imposta la larghezza della freccia alla fine di una linea. Lettura/scrittura [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public final byte getBeginArrowheadLength()
```

Restituisce o imposta la lunghezza della freccia all'inizio di una linea. Lettura/scrittura [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Restituisce:**
byte

### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public final void setBeginArrowheadLength(byte value)
```

Restituisce o imposta la lunghezza della freccia all'inizio di una linea. Lettura/scrittura [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public final byte getEndArrowheadLength()
```

Restituisce o imposta la lunghezza della freccia alla fine di una linea. Lettura/scrittura [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Restituisce:**
byte

### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public final void setEndArrowheadLength(byte value)
```

Restituisce o imposta la lunghezza della freccia alla fine di una linea. Lettura/scrittura [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public final boolean equals(ILineFormat lineFormat)
```

Determina se le due istanze di LineFormat sono uguali.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | Il LineFormat da confrontare con l'attuale LineFormat. |

**Restituisce:**
boolean - **true** se il LineFormat specificato è uguale all'attuale LineFormat; altrimenti, **false**.

### getEffective() {#getEffective--}
```
public final ILineFormatEffectiveData getEffective()
```

Ottiene i dati di formattazione della linea effettiva con l'ereditarietà applicata.

--------------------

> ```
> Questo esempio dimostra come ottenere le proprietà del formato di linea effettivo della forma.
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

**Restituisce:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - A [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).
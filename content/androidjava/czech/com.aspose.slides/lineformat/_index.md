---
title: LineFormat
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Reprezentuje formát řádku.
type: docs
url: /cs/com.aspose.slides/lineformat/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Všechny implementované rozhraní:**
[com.aspose.slides.ILineFormat](../../com.aspose.slides/ilineformat)
```
public final class LineFormat extends PVIObject implements ILineFormat
```

Reprezentuje formát řádku.
## Metody

| Metoda | Popis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [isFormatNotDefined()](#isFormatNotDefined--) | Vrací true, pokud není formát řádku definován (právě vytvořený, výchozí). |
| [getFillFormat()](#getFillFormat--) | Vrací formát výplně řádku. |
| [getSketchFormat()](#getSketchFormat--) | Vrací formát skicu řádku. |
| [getWidth()](#getWidth--) | Vrací nebo nastavuje šířku řádku. |
| [setWidth(double value)](#setWidth-double-) | Vrací nebo nastavuje šířku řádku. |
| [getDashStyle()](#getDashStyle--) | Vrací nebo nastavuje styl čárkování řádku. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | Vrací nebo nastavuje styl čárkování řádku. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Vrací nebo nastavuje vlastní vzor čárkování. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | Vrací nebo nastavuje vlastní vzor čárkování. |
| [getCapStyle()](#getCapStyle--) | Vrací nebo nastavuje styl čárkování řádku. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | Vrací nebo nastavuje styl čárkování řádku. |
| [getStyle()](#getStyle--) | Vrací nebo nastavuje styl řádku. |
| [setStyle(byte value)](#setStyle-byte-) | Vrací nebo nastavuje styl řádku. |
| [getAlignment()](#getAlignment--) | Vrací nebo nastavuje zarovnání řádku. |
| [setAlignment(byte value)](#setAlignment-byte-) | Vrací nebo nastavuje zarovnání řádku. |
| [getJoinStyle()](#getJoinStyle--) | Vrací nebo nastavuje styl spojení čar. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | Vrací nebo nastavuje styl spojení čar. |
| [getMiterLimit()](#getMiterLimit--) | Vrací nebo nastavuje limit zkosení řádku. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Vrací nebo nastavuje limit zkosení řádku. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Vrací nebo nastavuje styl šipky na začátku řádku. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | Vrací nebo nastavuje styl šipky na začátku řádku. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Vrací nebo nastavuje styl šipky na konci řádku. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | Vrací nebo nastavuje styl šipky na konci řádku. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Vrací nebo nastavuje šířku šipky na začátku řádku. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | Vrací nebo nastavuje šířku šipky na začátku řádku. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Vrací nebo nastavuje šířku šipky na konci řádku. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | Vrací nebo nastavuje šířku šipky na konci řádku. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Vrací nebo nastavuje délku šipky na začátku řádku. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | Vrací nebo nastavuje délku šipky na začátku řádku. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Vrací nebo nastavuje délku šipky na konci řádku. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | Vrací nebo nastavuje délku šipky na konci řádku. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | Určuje, zda jsou dvě instance LineFormat rovny. |
| [getEffective()](#getEffective--) | Získává data efektivního formátování řádku s aplikovaným děděním. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Verze. Pouze pro čtení long.

**Vrací:**
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Porovnává se zadaným objektem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Vrací:**
boolean

### isFormatNotDefined() {#isFormatNotDefined--}
```
public final boolean isFormatNotDefined()
```

Vrací true, pokud není formát řádku definován (právě vytvořený, výchozí). Pouze pro čtení  boolean .

**Vrací:**
boolean

### getFillFormat() {#getFillFormat--}
```
public final ILineFillFormat getFillFormat()
```

Vrací formát výplně řádku. Pouze pro čtení [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Vrací:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)

### getSketchFormat() {#getSketchFormat--}
```
public final ISketchFormat getSketchFormat()
```

Vrací formát skicu řádku. Pouze pro čtení [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Vrací:**
[ISketchFormat](../../com.aspose.slides/isketchformat)

### getWidth() {#getWidth--}
```
public final double getWidth()
```

Vrací nebo nastavuje šířku řádku. Čtení/zápis  double .

**Vrací:**
double

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

Vrací nebo nastavuje šířku řádku. Čtení/zápis  double .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public final byte getDashStyle()
```

Vrací nebo nastavuje styl čárkování řádku. Čtení/zápis [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Vrací:**
byte

### setDashStyle(byte value) {#setDashStyle-byte-}
```
public final void setDashStyle(byte value)
```

Vrací nebo nastavuje styl čárkování řádku. Čtení/zápis [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public final float[] getCustomDashPattern()
```

Vrací nebo nastavuje vlastní vzor čárkování. Čtení/zápis  float[] .

**Vrací:**
float[]

### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public final void setCustomDashPattern(float[] value)
```

Vrací nebo nastavuje vlastní vzor čárkování. Čtení/zápis  float[] .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public final byte getCapStyle()
```

Vrací nebo nastavuje styl zakončení řádku. Čtení/zápis [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Vrací:**
byte

### setCapStyle(byte value) {#setCapStyle-byte-}
```
public final void setCapStyle(byte value)
```

Vrací nebo nastavuje styl zakončení řádku. Čtení/zápis [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public final byte getStyle()
```

Vrací nebo nastavuje styl řádku. Čtení/zápis [LineStyle](../../com.aspose.slides/linestyle).

**Vrací:**
byte

### setStyle(byte value) {#setStyle-byte-}
```
public final void setStyle(byte value)
```

Vrací nebo nastavuje styl řádku. Čtení/zápis [LineStyle](../../com.aspose.slides/linestyle).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public final byte getAlignment()
```

Vrací nebo nastavuje zarovnání řádku. Čtení/zápis [LineAlignment](../../com.aspose.slides/linealignment).

**Vrací:**
byte

### setAlignment(byte value) {#setAlignment-byte-}
```
public final void setAlignment(byte value)
```

Vrací nebo nastavuje zarovnání řádku. Čtení/zápis [LineAlignment](../../com.aspose.slides/linealignment).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public final byte getJoinStyle()
```

Vrací nebo nastavuje styl spojení čar. Čtení/zápis [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Vrací:**
byte

### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public final void setJoinStyle(byte value)
```

Vrací nebo nastavuje styl spojení čar. Čtení/zápis [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```

Vrací nebo nastavuje limit zkosení řádku. Čtení/zápis  float .

**Vrací:**
float

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```

Vrací nebo nastavuje limit zkosení řádku. Čtení/zápis  float .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public final byte getBeginArrowheadStyle()
```

Vrací nebo nastavuje styl šipky na začátku řádku. Čtení/zápis [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Vrací:**
byte

### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public final void setBeginArrowheadStyle(byte value)
```

Vrací nebo nastavuje styl šipky na začátku řádku. Čtení/zápis [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public final byte getEndArrowheadStyle()
```

Vrací nebo nastavuje styl šipky na konci řádku. Čtení/zápis [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Vrací:**
byte

### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public final void setEndArrowheadStyle(byte value)
```

Vrací nebo nastavuje styl šipky na konci řádku. Čtení/zápis [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public final byte getBeginArrowheadWidth()
```

Vrací nebo nastavuje šířku šipky na začátku řádku. Čtení/zápis [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Vrací:**
byte

### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public final void setBeginArrowheadWidth(byte value)
```

Vrací nebo nastavuje šířku šipky na začátku řádku. Čtení/zápis [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public final byte getEndArrowheadWidth()
```

Vrací nebo nastavuje šířku šipky na konci řádku. Čtení/zápis [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Vrací:**
byte

### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public final void setEndArrowheadWidth(byte value)
```

Vrací nebo nastavuje šířku šipky na konci řádku. Čtení/zápis [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public final byte getBeginArrowheadLength()
```

Vrací nebo nastavuje délku šipky na začátku řádku. Čtení/zápis [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Vrací:**
byte

### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public final void setBeginArrowheadLength(byte value)
```

Vrací nebo nastavuje délku šipky na začátku řádku. Čtení/zápis [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public final byte getEndArrowheadLength()
```

Vrací nebo nastavuje délku šipky na konci řádku. Čtení/zápis [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Vrací:**
byte

### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public final void setEndArrowheadLength(byte value)
```

Vrací nebo nastavuje délku šipky na konci řádku. Čtení/zápis [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public final boolean equals(ILineFormat lineFormat)
```

Určuje, zda jsou dvě instance LineFormat rovnocenné.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | LineFormat k porovnání s aktuálním LineFormat. |

**Vrací:**
boolean - **true** pokud je zadaný LineFormat roven aktuálnímu LineFormat; jinak **false**.

### getEffective() {#getEffective--}
```
public final ILineFormatEffectiveData getEffective()
```

Získává data efektivního formátování řádku s aplikovaným děděním.

--------------------

> ```
> Tento příklad ukazuje, jak získat efektivní vlastnosti formátu čáry objektu shape.
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


**Vrací:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - A [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).
---
title: LineFormat
second_title: Aspose.Slides pro Java - referenční příručka API
description: Reprezentuje formát čáry.
type: docs
url: /cs/com.aspose.slides/lineformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.ILineFormat](../../com.aspose.slides/ilineformat)
```
public final class LineFormat extends PVIObject implements ILineFormat
```

Representuje formát řádku.
## Metody

| Metoda | Popis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [isFormatNotDefined()](#isFormatNotDefined--) | Vrací true, pokud není formát čáry definován (právě po vytvoření, výchozí). |
| [getFillFormat()](#getFillFormat--) | Vrací formát výplně čáry. |
| [getSketchFormat()](#getSketchFormat--) | Vrací formát skicu čáry. |
| [getWidth()](#getWidth--) | Vrací nebo nastavuje šířku čáry. |
| [setWidth(double value)](#setWidth-double-) | Vrací nebo nastavuje šířku čáry. |
| [getDashStyle()](#getDashStyle--) | Vrací nebo nastavuje styl přerušení čáry. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | Vrací nebo nastavuje styl přerušení čáry. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Vrací nebo nastavuje vlastní vzor přerušení. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | Vrací nebo nastavuje vlastní vzor přerušení. |
| [getCapStyle()](#getCapStyle--) | Vrací nebo nastavuje styl zakončení (cap) čáry. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | Vrací nebo nastavuje styl zakončení (cap) čáry. |
| [getStyle()](#getStyle--) | Vrací nebo nastavuje styl čáry. |
| [setStyle(byte value)](#setStyle-byte-) | Vrací nebo nastavuje styl čáry. |
| [getAlignment()](#getAlignment--) | Vrací nebo nastavuje zarovnání čáry. |
| [setAlignment(byte value)](#setAlignment-byte-) | Vrací nebo nastavuje zarovnání čáry. |
| [getJoinStyle()](#getJoinStyle--) | Vrací nebo nastavuje styl spojení čar. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | Vrací nebo nastavuje styl spojení čar. |
| [getMiterLimit()](#getMiterLimit--) | Vrací nebo nastavuje limit úhlu spojení čáry. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Vrací nebo nastavuje limit úhlu spojení čáry. |
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
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | Určuje, zda jsou dvě instance LineFormat stejné. |
| [getEffective()](#getEffective--) | Získává efektivní data formátování čáry s použitím dědičnosti. |
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

Vrací true, pokud formát čáry není definován (právě po vytvoření, výchozí). Pouze pro čtení boolean.

**Vrací:**
boolean
### getFillFormat() {#getFillFormat--}
```
public final ILineFillFormat getFillFormat()
```

Vrací formát výplně čáry. Pouze pro čtení [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Vrací:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)
### getSketchFormat() {#getSketchFormat--}
```
public final ISketchFormat getSketchFormat()
```

Vrací formát skicu čáry. Pouze pro čtení [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Vrací:**
[ISketchFormat](../../com.aspose.slides/isketchformat)
### getWidth() {#getWidth--}
```
public final double getWidth()
```

Vrací nebo nastavuje šířku čáry. Čtení/Zápis double.

**Vrací:**
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

Vrací nebo nastavuje šířku čáry. Čtení/Zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getDashStyle() {#getDashStyle--}
```
public final byte getDashStyle()
```

Vrací nebo nastavuje styl přerušení čáry. Čtení/Zápis [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Vrací:**
byte
### setDashStyle(byte value) {#setDashStyle-byte-}
```
public final void setDashStyle(byte value)
```

Vrací nebo nastavuje styl přerušení čáry. Čtení/Zápis [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getCustomDashPattern() {#getCustomDashPattern--}
```
public final float[] getCustomDashPattern()
```

Vrací nebo nastavuje vlastní vzor přerušení. Čtení/Zápis float[].

**Vrací:**
float[]
### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public final void setCustomDashPattern(float[] value)
```

Vrací nebo nastavuje vlastní vzor přerušení. Čtení/Zápis float[].

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float[] |  |
### getCapStyle() {#getCapStyle--}
```
public final byte getCapStyle()
```

Vrací nebo nastavuje styl zakončení (cap) čáry. Čtení/Zápis [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Vrací:**
byte
### setCapStyle(byte value) {#setCapStyle-byte-}
```
public final void setCapStyle(byte value)
```

Vrací nebo nastavuje styl zakončení (cap) čáry. Čtení/Zápis [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getStyle() {#getStyle--}
```
public final byte getStyle()
```

Vrací nebo nastavuje styl čáry. Čtení/Zápis [LineStyle](../../com.aspose.slides/linestyle).

**Vrací:**
byte
### setStyle(byte value) {#setStyle-byte-}
```
public final void setStyle(byte value)
```

Vrací nebo nastavuje styl čáry. Čtení/Zápis [LineStyle](../../com.aspose.slides/linestyle).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getAlignment() {#getAlignment--}
```
public final byte getAlignment()
```

Vrací nebo nastavuje zarovnání čáry. Čtení/Zápis [LineAlignment](../../com.aspose.slides/linealignment).

**Vrací:**
byte
### setAlignment(byte value) {#setAlignment-byte-}
```
public final void setAlignment(byte value)
```

Vrací nebo nastavuje zarovnání čáry. Čtení/Zápis [LineAlignment](../../com.aspose.slides/linealignment).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getJoinStyle() {#getJoinStyle--}
```
public final byte getJoinStyle()
```

Vrací nebo nastavuje styl spojení čar. Čtení/Zápis [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Vrací:**
byte
### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public final void setJoinStyle(byte value)
```

Vrací nebo nastavuje styl spojení čar. Čtení/Zápis [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```

Vrací nebo nastavuje limit úhlu spojení čáry. Čtení/Zápis float.

**Vrací:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```

Vrací nebo nastavuje limit úhlu spojení čáry. Čtení/Zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public final byte getBeginArrowheadStyle()
```

Vrací nebo nastavuje styl šipky na začátku čáry. Čtení/Zápis [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Vrací:**
byte
### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public final void setBeginArrowheadStyle(byte value)
```

Vrací nebo nastavuje styl šipky na začátku čáry. Čtení/Zápis [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public final byte getEndArrowheadStyle()
```

Vrací nebo nastavuje styl šipky na konci čáry. Čtení/Zápis [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Vrací:**
byte
### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public final void setEndArrowheadStyle(byte value)
```

Vrací nebo nastavuje styl šipky na konci čáry. Čtení/Zápis [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public final byte getBeginArrowheadWidth()
```

Vrací nebo nastavuje šířku šipky na začátku čáry. Čtení/Zápis [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Vrací:**
byte
### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public final void setBeginArrowheadWidth(byte value)
```

Vrací nebo nastavuje šířku šipky na začátku čáry. Čtení/Zápis [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public final byte getEndArrowheadWidth()
```

Vrací nebo nastavuje šířku šipky na konci čáry. Čtení/Zápis [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Vrací:**
byte
### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public final void setEndArrowheadWidth(byte value)
```

Vrací nebo nastavuje šířku šipky na konci čáry. Čtení/Zápis [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public final byte getBeginArrowheadLength()
```

Vrací nebo nastavuje délku šipky na začátku čáry. Čtení/Zápis [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Vrací:**
byte
### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public final void setBeginArrowheadLength(byte value)
```

Vrací nebo nastavuje délku šipky na začátku čáry. Čtení/Zápis [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public final byte getEndArrowheadLength()
```

Vrací nebo nastavuje délku šipky na konci čáry. Čtení/Zápis [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Vrací:**
byte
### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public final void setEndArrowheadLength(byte value)
```

Vrací nebo nastavuje délku šipky na konci čáry. Čtení/Zápis [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public final boolean equals(ILineFormat lineFormat)
```

Určuje, zda jsou dvě instance LineFormat stejné.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | LineFormat, se kterými se porovnává aktuální LineFormat. |

**Vrací:**
boolean - **true** pokud je zadaný LineFormat roven aktuálnímu LineFormat; jinak **false**.
### getEffective() {#getEffective--}
```
public final ILineFormatEffectiveData getEffective()
```

Získává efektivní data formátování čáry s použitím dědičnosti.

--------------------

> ```
> Tento příklad ukazuje získání vlastností efektivního formátu čáry tvaru.
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
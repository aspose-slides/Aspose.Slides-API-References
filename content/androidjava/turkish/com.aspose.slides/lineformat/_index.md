---
title: LineFormat
second_title: Aspose.Slides for Android via Java API Referansı
description: Bir satırın biçimini temsil eder.
type: docs
url: /tr/com.aspose.slides/lineformat/
---
**Miras:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.ILineFormat](../../com.aspose.slides/ilineformat)
```
public final class LineFormat extends PVIObject implements ILineFormat
```

Bir satırın biçimini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [isFormatNotDefined()](#isFormatNotDefined--) | Satır formatı tanımlı değilse (yeni oluşturulduğu gibi, varsayılan) true döner. |
| [getFillFormat()](#getFillFormat--) | Bir satırın dolgu biçimini döndürür. |
| [getSketchFormat()](#getSketchFormat--) | Bir satırın taslak biçimini döndürür. |
| [getWidth()](#getWidth--) | Bir satırın genişliğini döndürür veya ayarlar. |
| [setWidth(double value)](#setWidth-double-) | Bir satırın genişliğini döndürür veya ayarlar. |
| [getDashStyle()](#getDashStyle--) | Bir satırın kesikli çizgi stilini döndürür veya ayarlar. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | Bir satırın kesikli çizgi stilini döndürür veya ayarlar. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Özel kesikli desenini döndürür veya ayarlar. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | Özel kesikli deseni döndürür veya ayarlar. |
| [getCapStyle()](#getCapStyle--) | Bir satırın uç stilini döndürür veya ayarlar. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | Bir satırın uç stilini döndürür veya ayarlar. |
| [getStyle()](#getStyle--) | Bir satır stilini döndürür veya ayarlar. |
| [setStyle(byte value)](#setStyle-byte-) | Bir satır stilini döndürür veya ayarlar. |
| [getAlignment()](#getAlignment--) | Bir satır hizalamasını döndürür veya ayarlar. |
| [setAlignment(byte value)](#setAlignment-byte-) | Bir satır hizalamasını döndürür veya ayarlar. |
| [getJoinStyle()](#getJoinStyle--) | Satırların birleşim stilini döndürür veya ayarlar. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | Satırların birleşim stilini döndürür veya ayarlar. |
| [getMiterLimit()](#getMiterLimit--) | Bir satırın açı limiti değerini döndürür veya ayarlar. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Bir satırın açı limiti değerini döndürür veya ayarlar. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Bir satırın başlangıcındaki ok başı stilini döndürür veya ayarlar. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | Bir satırın başlangıcındaki ok başı stilini döndürür veya ayarlar. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Bir satırın sonundaki ok başı stilini döndürür veya ayarlar. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | Bir satırın sonundaki ok başı stilini döndürür veya ayarlar. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Bir satırın başlangıcındaki ok başı genişliğini döndürür veya ayarlar. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | Bir satırın başlangıcındaki ok başı genişliğini döndürür veya ayarlar. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Bir satırın sonundaki ok başı genişliğini döndürür veya ayarlar. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | Bir satırın sonundaki ok başı genişliğini döndürür veya ayarlar. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Bir satırın başlangıcındaki ok başı uzunluğunu döndürür veya ayarlar. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | Bir satırın başlangıcındaki ok başı uzunluğunu döndürür veya ayarlar. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Bir satırın sonundaki ok başı uzunluğunu döndürür veya ayarlar. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | Bir satırın sonundaki ok başı uzunluğunu döndürür veya ayarlar. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | İki LineFormat örneğinin eşit olup olmadığını belirler. |
| [getEffective()](#getEffective--) | Kalıtım uygulanmış etkili satır biçimlendirme verilerini alır. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Sürüm. Salt-okunur long.

**Döndürür:**
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Belirtilen nesneyle karşılaştırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Döndürür:**
boolean

### isFormatNotDefined() {#isFormatNotDefined--}
```
public final boolean isFormatNotDefined()
```

Satır formatı tanımlı değilse (yeni oluşturulduğu gibi, varsayılan) true döner. Salt-okunur boolean.

**Döndürür:**
boolean

### getFillFormat() {#getFillFormat--}
```
public final ILineFillFormat getFillFormat()
```

Bir satırın dolgu biçimini döndürür. Salt-okunur [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Döndürür:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)

### getSketchFormat() {#getSketchFormat--}
```
public final ISketchFormat getSketchFormat()
```

Bir satırın taslak biçimini döndürür. Salt-okunur [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Döndürür:**
[ISketchFormat](../../com.aspose.slides/isketchformat)

### getWidth() {#getWidth--}
```
public final double getWidth()
```

Bir satırın genişliğini döndürür veya ayarlar. Okunur/Yazılabilir double.

**Döndürür:**
double

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

Bir satırın genişliğini döndürür veya ayarlar. Okunur/Yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public final byte getDashStyle()
```

Bir satırın kesikli çizgi stilini döndürür veya ayarlar. Okunur/Yazılabilir [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Döndürür:**
byte

### setDashStyle(byte value) {#setDashStyle-byte-}
```
public final void setDashStyle(byte value)
```

Bir satırın kesikli çizgi stilini döndürür veya ayarlar. Okunur/Yazılabilir [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public final float[] getCustomDashPattern()
```

Özel kesikli deseni döndürür veya ayarlar. Okunur/Yazılabilir float[].

**Döndürür:**
float[]

### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public final void setCustomDashPattern(float[] value)
```

Özel kesikli deseni döndürür veya ayarlar. Okunur/Yazılabilir float[].

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public final byte getCapStyle()
```

Bir satırın uç stilini döndürür veya ayarlar. Okunur/Yazılabilir [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Döndürür:**
byte

### setCapStyle(byte value) {#setCapStyle-byte-}
```
public final void setCapStyle(byte value)
```

Bir satırın uç stilini döndürür veya ayarlar. Okunur/Yazılabilir [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public final byte getStyle()
```

Bir satırın stilini döndürür veya ayarlar. Okunur/Yazılabilir [LineStyle](../../com.aspose.slides/linestyle).

**Döndürür:**
byte

### setStyle(byte value) {#setStyle-byte-}
```
public final void setStyle(byte value)
```

Bir satırın stilini döndürür veya ayarlar. Okunur/Yazılabilir [LineStyle](../../com.aspose.slides/linestyle).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public final byte getAlignment()
```

Bir satırın hizalamasını döndürür veya ayarlar. Okunur/Yazılabilir [LineAlignment](../../com.aspose.slides/linealignment).

**Döndürür:**
byte

### setAlignment(byte value) {#setAlignment-byte-}
```
public final void setAlignment(byte value)
```

Bir satırın hizalamasını döndürür veya ayarlar. Okunur/Yazılabilir [LineAlignment](../../com.aspose.slides/linealignment).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public final byte getJoinStyle()
```

Satırların birleşim stilini döndürür veya ayarlar. Okunur/Yazılabilir [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Döndürür:**
byte

### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public final void setJoinStyle(byte value)
```

Satırların birleşim stilini döndürür veya ayarlar. Okunur/Yazılabilir [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```

Bir satırın açı limiti değerini döndürür veya ayarlar. Okunur/Yazılabilir float.

**Döndürür:**
float

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```

Bir satırın açı limiti değerini döndürür veya ayarlar. Okunur/Yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public final byte getBeginArrowheadStyle()
```

Bir satırın başlangıcındaki ok başı stilini döndürür veya ayarlar. Okunur/Yazılabilir [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Döndürür:**
byte

### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public final void setBeginArrowheadStyle(byte value)
```

Bir satırın başlangıcındaki ok başı stilini döndürür veya ayarlar. Okunur/Yazılabilir [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public final byte getEndArrowheadStyle()
```

Bir satırın sonundaki ok başı stilini döndürür veya ayarlar. Okunur/Yazılabilir [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Döndürür:**
byte

### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public final void setEndArrowheadStyle(byte value)
```

Bir satırın sonundaki ok başı stilini döndürür veya ayarlar. Okunur/Yazılabilir [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public final byte getBeginArrowheadWidth()
```

Bir satırın başlangıcındaki ok başı genişliğini döndürür veya ayarlar. Okunur/Yazılabilir [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Döndürür:**
byte

### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public final void setBeginArrowheadWidth(byte value)
```

Bir satırın başlangıcındaki ok başı genişliğini döndürür veya ayarlar. Okunur/Yazılabilir [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public final byte getEndArrowheadWidth()
```

Bir satırın sonundaki ok başı genişliğini döndürür veya ayarlar. Okunur/Yazılabilir [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Döndürür:**
byte

### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public final void setEndArrowheadWidth(byte value)
```

Bir satırın sonundaki ok başı genişliğini döndürür veya ayarlar. Okunur/Yazılabilir [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public final byte getBeginArrowheadLength()
```

Bir satırın başlangıcındaki ok başı uzunluğunu döndürür veya ayarlar. Okunur/Yazılabilir [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Döndürür:**
byte

### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public final void setBeginArrowheadLength(byte value)
```

Bir satırın başlangıcındaki ok başı uzunluğunu döndürür veya ayarlar. Okunur/Yazılabilir [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public final byte getEndArrowheadLength()
```

Bir satırın sonundaki ok başı uzunluğunu döndürür veya ayarlar. Okunur/Yazılabilir [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Döndürür:**
byte

### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public final void setEndArrowheadLength(byte value)
```

Bir satırın sonundaki ok başı uzunluğunu döndürür veya ayarlar. Okunur/Yazılabilir [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public final boolean equals(ILineFormat lineFormat)
```

İki LineFormat örneğinin eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | Karşılaştırılacak LineFormat. |

**Döndürür:**
boolean - **true** eğer belirtilen LineFormat mevcut LineFormat ile eşitse; aksi takdirde **false**.

### getEffective() {#getEffective--}
```
public final ILineFormatEffectiveData getEffective()
```

Kalıtım uygulanmış etkili satır biçimlendirme verilerini alır.

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


**Döndürür:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - Bir [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).
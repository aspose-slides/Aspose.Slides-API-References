---
title: LineFormat
second_title: Aspose.Slides for Java API Referansı
description: Bir satırın formatını temsil eder.
type: docs
url: /tr/com.aspose.slides/lineformat/
---
**Kalıtım:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Uygulanan Tüm Arayüzler:**  
[com.aspose.slides.ILineFormat](../../com.aspose.slides/ilineformat)  
```
public final class LineFormat extends PVIObject implements ILineFormat
```

Bir satırın formatını temsil eder.
## Yöntemler

| Method | Açıklama |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [isFormatNotDefined()](#isFormatNotDefined--) | Satır formatı tanımlı değilse (yeni oluşturulmuş, varsayılan) true döndürür. |
| [getFillFormat()](#getFillFormat--) | Bir satırın doldurma formatını döndürür. |
| [getSketchFormat()](#getSketchFormat--) | Bir satırın taslak formatını döndürür. |
| [getWidth()](#getWidth--) | Bir satırın genişliğini döndürür veya ayarlar. |
| [setWidth(double value)](#setWidth-double-) | Bir satırın genişliğini döndürür veya ayarlar. |
| [getDashStyle()](#getDashStyle--) | Satır kesikli stilini döndürür veya ayarlar. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | Satır kesikli stilini döndürür veya ayarlar. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Özel kesikli deseni döndürür veya ayarlar. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | Özel kesikli deseni döndürür veya ayarlar. |
| [getCapStyle()](#getCapStyle--) | Satır uç stilini döndürür veya ayarlar. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | Satır uç stilini döndürür veya ayarlar. |
| [getStyle()](#getStyle--) | Satır stilini döndürür veya ayarlar. |
| [setStyle(byte value)](#setStyle-byte-) | Satır stilini döndürür veya ayarlar. |
| [getAlignment()](#getAlignment--) | Satır hizalamasını döndürür veya ayarlar. |
| [setAlignment(byte value)](#setAlignment-byte-) | Satır hizalamasını döndürür veya ayarlar. |
| [getJoinStyle()](#getJoinStyle--) | Satır birleşim stilini döndürür veya ayarlar. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | Satır birleşim stilini döndürür veya ayarlar. |
| [getMiterLimit()](#getMiterLimit--) | Bir satırın sınırlama (miter) değerini döndürür veya ayarlar. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Bir satırın sınırlama (miter) değerini döndürür veya ayarlar. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Satırın başlangıcındaki ok başı stilini döndürür veya ayarlar. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | Satırın başlangıcındaki ok başı stilini döndürür veya ayarlar. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Satırın sonundaki ok başı stilini döndürür veya ayarlar. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | Satırın sonundaki ok başı stilini döndürür veya ayarlar. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Satırın başlangıcındaki ok başı genişliğini döndürür veya ayarlar. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | Satırın başlangıcındaki ok başı genişliğini döndürür veya ayarlar. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Satırın sonundaki ok başı genişliğini döndürür veya ayarlar. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | Satırın sonundaki ok başı genişliğini döndürür veya ayarlar. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Satırın başlangıcındaki ok başı uzunluğunu döndürür veya ayarlar. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | Satırın başlangıcındaki ok başı uzunluğunu döndürür veya ayarlar. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Satırın sonundaki ok başı uzunluğunu döndürür veya ayarlar. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | Satırın sonundaki ok başı uzunluğunu döndürür veya ayarlar. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | İki LineFormat örneğinin eşit olup olmadığını belirler. |
| [getEffective()](#getEffective--) | Uygulanan kalıtımla etkili satır biçimlendirme verilerini alır. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Sürüm. Salt okunur long.

**Döndürür:**
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Belirtilen nesne ile karşılaştırır.

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

Satır formatı tanımlı değilse (yeni oluşturulmuş, varsayılan) true döndürür. Salt okunur boolean.

**Döndürür:**
boolean

### getFillFormat() {#getFillFormat--}
```
public final ILineFillFormat getFillFormat()
```

Bir satırın doldurma formatını döndürür. Salt okunur [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Döndürür:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)

### getSketchFormat() {#getSketchFormat--}
```
public final ISketchFormat getSketchFormat()
```

Bir satırın taslak formatını döndürür. Salt okunur [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Döndürür:**
[ISketchFormat](../../com.aspose.slides/isketchformat)

### getWidth() {#getWidth--}
```
public final double getWidth()
```

Bir satırın genişliğini döndürür veya ayarlar. Okunur/yazılabilir double.

**Döndürür:**
double

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

Bir satırın genişliğini döndürür veya ayarlar. Okunur/yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public final byte getDashStyle()
```

Satır kesikli stilini döndürür veya ayarlar. Okunur/yazılabilir [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Döndürür:**
byte

### setDashStyle(byte value) {#setDashStyle-byte-}
```
public final void setDashStyle(byte value)
```

Satır kesikli stilini döndürür veya ayarlar. Okunur/yazılabilir [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public final float[] getCustomDashPattern()
```

Özel kesikli deseni döndürür veya ayarlar. Okunur/yazılabilir float[].

**Döndürür:**
float[]

### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public final void setCustomDashPattern(float[] value)
```

Özel kesikli deseni döndürür veya ayarlar. Okunur/yazılabilir float[].

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public final byte getCapStyle()
```

Satır uç stilini döndürür veya ayarlar. Okunur/yazılabilir [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Döndürür:**
byte

### setCapStyle(byte value) {#setCapStyle-byte-}
```
public final void setCapStyle(byte value)
```

Satır uç stilini döndürür veya ayarlar. Okunur/yazılabilir [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public final byte getStyle()
```

Satır stilini döndürür veya ayarlar. Okunur/yazılabilir [LineStyle](../../com.aspose.slides/linestyle).

**Döndürür:**
byte

### setStyle(byte value) {#setStyle-byte-}
```
public final void setStyle(byte value)
```

Satır stilini döndürür veya ayarlar. Okunur/yazılabilir [LineStyle](../../com.aspose.slides/linestyle).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public final byte getAlignment()
```

Satır hizalamasını döndürür veya ayarlar. Okunur/yazılabilir [LineAlignment](../../com.aspose.slides/linealignment).

**Döndürür:**
byte

### setAlignment(byte value) {#setAlignment-byte-}
```
public final void setAlignment(byte value)
```

Satır hizalamasını döndürür veya ayarlar. Okunur/yazılabilir [LineAlignment](../../com.aspose.slides/linealignment).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public final byte getJoinStyle()
```

Satır birleşim stilini döndürür veya ayarlar. Okunur/yazılabilir [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Döndürür:**
byte

### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public final void setJoinStyle(byte value)
```

Satır birleşim stilini döndürür veya ayarlar. Okunur/yazılabilir [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```

Bir satırın sınırlama (miter) değerini döndürür veya ayarlar. Okunur/yazılabilir float.

**Döndürür:**
float

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```

Bir satırın sınırlama (miter) değerini döndürür veya ayarlar. Okunur/yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public final byte getBeginArrowheadStyle()
```

Satırın başlangıcındaki ok başı stilini döndürür veya ayarlar. Okunur/yazılabilir [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Döndürür:**
byte

### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public final void setBeginArrowheadStyle(byte value)
```

Satırın başlangıcındaki ok başı stilini döndürür veya ayarlar. Okunur/yazılabilir [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public final byte getEndArrowheadStyle()
```

Satırın sonundaki ok başı stilini döndürür veya ayarlar. Okunur/yazılabilir [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Döndürür:**
byte

### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public final void setEndArrowheadStyle(byte value)
```

Satırın sonundaki ok başı stilini döndürür veya ayarlar. Okunur/yazılabilir [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public final byte getBeginArrowheadWidth()
```

Satırın başlangıcındaki ok başı genişliğini döndürür veya ayarlar. Okunur/yazılabilir [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Döndürür:**
byte

### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public final void setBeginArrowheadWidth(byte value)
```

Satırın başlangıcındaki ok başı genişliğini döndürür veya ayarlar. Okunur/yazılabilir [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public final byte getEndArrowheadWidth()
```

Satırın sonundaki ok başı genişliğini döndürür veya ayarlar. Okunur/yazılabilir [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Döndürür:**
byte

### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public final void setEndArrowheadWidth(byte value)
```

Satırın sonundaki ok başı genişliğini döndürür veya ayarlar. Okunur/yazılabilir [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public final byte getBeginArrowheadLength()
```

Satırın başlangıcındaki ok başı uzunluğunu döndürür veya ayarlar. Okunur/yazılabilir [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Döndürür:**
byte

### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public final void setBeginArrowheadLength(byte value)
```

Satırın başlangıcındaki ok başı uzunluğunu döndürür veya ayarlar. Okunur/yazılabilir [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public final byte getEndArrowheadLength()
```

Satırın sonundaki ok başı uzunluğunu döndürür veya ayarlar. Okunur/yazılabilir [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Döndürür:**
byte

### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public final void setEndArrowheadLength(byte value)
```

Satırın sonundaki ok başı uzunluğunu döndürür veya ayarlar. Okunur/yazılabilir [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

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
boolean - **true** if the specified LineFormat is equal to the current LineFormat; otherwise, **false**.

### getEffective() {#getEffective--}
```
public final ILineFormatEffectiveData getEffective()
```

Uygulanan kalıtımla etkili satır biçimlendirme verilerini alır.

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
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - A [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).
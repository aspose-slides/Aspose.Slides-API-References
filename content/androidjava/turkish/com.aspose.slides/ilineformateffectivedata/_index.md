---
title: ILineFormatEffectiveData
second_title: Aspose.Slides for Android için Java API Referansı
description: Etkili çizgi biçimlendirme özelliklerini içeren değiştirilemez nesne.
type: docs
url: /tr/com.aspose.slides/ilineformateffectivedata/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormatEffectiveData extends ILineParamSource
```

Etkili çizgi biçimlendirme özelliklerini içeren değiştirilemez nesne.

--------------------

Bu arayüz, [ILineFormat](../../com.aspose.slides/ilineformat) arayüzü ile birlikte, kalıtım uygulanan etkili biçimlendirme değerlerini döndürmek için kullanılır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Bir çizginin doldurma biçimini döndürür. |
| [getSketchFormat()](#getSketchFormat--) | Bir çizginin taslak biçimini döndürür. |
| [getWidth()](#getWidth--) | Bir çizginin genişliğini döndürür. |
| [getDashStyle()](#getDashStyle--) | Çizgi kesik stilini döndürür. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Özel noktalama desenini döndürür. |
| [getCapStyle()](#getCapStyle--) | Çizgi uç stilini döndürür. |
| [getStyle()](#getStyle--) | Çizgi stilini döndürür. |
| [getAlignment()](#getAlignment--) | Çizgi hizalamasını döndürür. |
| [getJoinStyle()](#getJoinStyle--) | Çizgilerin birleşim stilini döndürür. |
| [getMiterLimit()](#getMiterLimit--) | Bir çizginin mitre limitini döndürür. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Bir çizginin başındaki ok ucu stilini döndürür. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Bir çizginin sonundaki ok ucu stilini döndürür. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Bir çizginin başındaki ok ucu genişliğini döndürür. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Bir çizginin sonundaki ok ucu genişliğini döndürür. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Bir çizginin başındaki ok ucu uzunluğunu döndürür. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Bir çizginin sonundaki ok ucu uzunluğunu döndürür. |
| [equals(ILineFormatEffectiveData lf)](#equals-com.aspose.slides.ILineFormatEffectiveData-) | İki ILineFormatEffectiveData örneğinin eşit olup olmadığını belirler. |

### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormatEffectiveData getFillFormat()
```

Bir çizginin doldurma biçimini döndürür. Sadece-okunur [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).

**Döndürür:**
[ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata)
### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormatEffectiveData getSketchFormat()
```

Bir çizginin taslak biçimini döndürür. Sadece-okunur [ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata).

**Döndürür:**
[ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata)
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Bir çizginin genişliğini döndürür. Sadece-okunur double.

**Döndürür:**
double
### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

Çizgi noktalı stilini döndürür. Sadece-okunur [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Döndürür:**
byte
### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

Özel noktalama desenini döndürür. Sadece-okunur float[].

**Döndürür:**
float[]
### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

Çizgi uç stilini döndürür. Sadece-okunur [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Döndürür:**
byte
### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

Çizgi stilini döndürür. Sadece-okunur [LineStyle](../../com.aspose.slides/linestyle).

**Döndürür:**
byte
### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

Çizgi hizalamasını döndürür. Sadece-okunur [LineAlignment](../../com.aspose.slides/linealignment).

**Döndürür:**
byte
### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

Çizgilerin birleşim stilini döndürür. Sadece-okunur [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Döndürür:**
byte
### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

Bir çizginin mitre limitini döndürür. Sadece-okunur float.

**Döndürür:**
float
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

Bir çizginin başındaki ok ucu stilini döndürür. Sadece-okunur [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Döndürür:**
byte
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

Bir çizginin sonundaki ok ucu stilini döndürür. Sadece-okunur [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Döndürür:**
byte
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

Bir çizginin başındaki ok ucu genişliğini döndürür. Sadece-okunur [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Döndürür:**
byte
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

Bir çizginin sonundaki ok ucu genişliğini döndürür. Sadece-okunur [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Döndürür:**
byte
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

Bir çizginin başındaki ok ucu uzunluğunu döndürür. Sadece-okunur [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Döndürür:**
byte
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

Bir çizginin sonundaki ok ucu uzunluğunu döndürür. Sadece-okunur [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Döndürür:**
byte
### equals(ILineFormatEffectiveData lf) {#equals-com.aspose.slides.ILineFormatEffectiveData-}
```
public abstract boolean equals(ILineFormatEffectiveData lf)
```

İki ILineFormatEffectiveData örneğinin eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lf | [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) | Mevcut ILineFormatEffectiveData ile karşılaştırılacak ILineFormatEffectiveData. |

**Döndürür:**
boolean - **true** eğer belirtilen ILineFormatEffectiveData mevcut ILineFormatEffectiveData ile eşitse; aksi takdirde **false**.
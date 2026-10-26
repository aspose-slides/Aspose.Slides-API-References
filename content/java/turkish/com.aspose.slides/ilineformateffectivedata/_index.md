---
title: ILineFormatEffectiveData
second_title: Aspose.Slides için Java API Referansı
description: Etkili satır biçimlendirme özelliklerini içeren değiştirilemez nesne.
type: docs
url: /tr/com.aspose.slides/ilineformateffectivedata/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormatEffectiveData extends ILineParamSource
```

Etkili satır biçimlendirme özelliklerini içeren değiştirilemez nesne.

--------------------

Bu arayüz, [ILineFormat](../../com.aspose.slides/ilineformat) arayüzüyle birlikte, kalıtım uygulanmış etkili biçimlendirme değerlerini döndürmek için kullanılır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Bir satırın doldurma formatını döndürür. |
| [getSketchFormat()](#getSketchFormat--) | Bir satırın taslak formatını döndürür. |
| [getWidth()](#getWidth--) | Bir satırın genişliğini döndürür. |
| [getDashStyle()](#getDashStyle--) | Satırın kesikli stilini döndürür. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Özel kesikli deseni döndürür. |
| [getCapStyle()](#getCapStyle--) | Satırın uç stilini döndürür. |
| [getStyle()](#getStyle--) | Satır stilini döndürür. |
| [getAlignment()](#getAlignment--) | Satır hizalamasını döndürür. |
| [getJoinStyle()](#getJoinStyle--) | Satırların birleştirme stilini döndürür. |
| [getMiterLimit()](#getMiterLimit--) | Bir satırın miter limitini döndürür. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Bir satırın başındaki ok ucu stilini döndürür. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Bir satırın sonundaki ok ucu stilini döndürür. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Bir satırın başındaki ok ucu genişliğini döndürür. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Bir satırın sonundaki ok ucu genişliğini döndürür. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Bir satırın başındaki ok ucu uzunluğunu döndürür. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Bir satırın sonundaki ok ucu uzunluğunu döndürür. |
| [equals(ILineFormatEffectiveData lf)](#equals-com.aspose.slides.ILineFormatEffectiveData-) | İki ILineFormatEffectiveData örneğinin eşit olup olmadığını belirler. |
### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormatEffectiveData getFillFormat()
```


Bir satırın doldurma formatını döndürür. Salt okunur [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).

**Döndürür:**
[ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata)
### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormatEffectiveData getSketchFormat()
```


Bir satırın taslak formatını döndürür. Salt okunur [ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata).

**Döndürür:**
[ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata)
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Bir satırın genişliğini döndürür. Salt okunur double.

**Döndürür:**
double
### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```


Satırın kesikli stilini döndürür. Salt okunur [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Döndürür:**
byte
### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```


Özel kesikli deseni döndürür. Salt okunur float[].

**Döndürür:**
float[]
### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```


Satırın uç stilini döndürür. Salt okunur [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Döndürür:**
byte
### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```


Satır stilini döndürür. Salt okunur [LineStyle](../../com.aspose.slides/linestyle).

**Döndürür:**
byte
### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```


Satır hizalamasını döndürür. Salt okunur [LineAlignment](../../com.aspose.slides/linealignment).

**Döndürür:**
byte
### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```


Satırların birleştirme stilini döndürür. Salt okunur [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Döndürür:**
byte
### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```


Bir satırın miter limitini döndürür. Salt okunur float.

**Döndürür:**
float
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```


Bir satırın başındaki ok ucu stilini döndürür. Salt okunur [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Döndürür:**
byte
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```


Bir satırın sonundaki ok ucu stilini döndürür. Salt okunur [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Döndürür:**
byte
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```


Bir satırın başındaki ok ucu genişliğini döndürür. Salt okunur [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Döndürür:**
byte
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```


Bir satırın sonundaki ok ucu genişliğini döndürür. Salt okunur [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Döndürür:**
byte
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```


Bir satırın başındaki ok ucu uzunluğunu döndürür. Salt okunur [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Döndürür:**
byte
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```


Bir satırın sonundaki ok ucu uzunluğunu döndürür. Salt okunur [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

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
| lf | [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) | Karşılaştırılacak ILineFormatEffectiveData. |

**Döndürür:**
boolean - **true** eğer belirtilen ILineFormatEffectiveData mevcut ILineFormatEffectiveData ile eşitse; aksi takdirde, **false**.
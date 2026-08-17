---
title: ILineFormat
second_title: Aspose.Slides Java API Referansı
description: Bir çizginin biçimini temsil eder.
type: docs
url: /tr/com.aspose.slides/ilineformat/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormat extends ILineParamSource
```

Bir çizginin biçimini temsil eder.
## Yöntemler

| Method | Description |
| --- | --- |
| [isFormatNotDefined()](#isFormatNotDefined--) | Satır biçimi tanımlanmamışsa (yeni oluşturulmuş, varsayılan) true döndürür. |
| [getFillFormat()](#getFillFormat--) | Bir çizginin doldurma biçimini döndürür. |
| [getSketchFormat()](#getSketchFormat--) | Bir çizginin eskiz biçimini döndürür. |
| [getWidth()](#getWidth--) | Bir çizginin genişliğini döndürür veya ayarlar. |
| [setWidth(double value)](#setWidth-double-) | Bir çizginin genişliğini döndürür veya ayarlar. |
| [getDashStyle()](#getDashStyle--) | Çizgi tire stilini döndürür veya ayarlar. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | Çizgi tire stilini döndürür veya ayarlar. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Özel tire desenini döndürür veya ayarlar. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | Özel tire desenini döndürür veya ayarlar. |
| [getCapStyle()](#getCapStyle--) | Çizgi kapama stilini döndürür veya ayarlar. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | Çizgi kapama stilini döndürür veya ayarlar. |
| [getStyle()](#getStyle--) | Çizgi stilini döndürür veya ayarlar. |
| [setStyle(byte value)](#setStyle-byte-) | Çizgi stilini döndürür veya ayarlar. |
| [getAlignment()](#getAlignment--) | Çizgi hizalamasını döndürür veya ayarlar. |
| [setAlignment(byte value)](#setAlignment-byte-) | Çizgi hizalamasını döndürür veya ayarlar. |
| [getJoinStyle()](#getJoinStyle--) | Çizgi birleşim stilini döndürür veya ayarlar. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | Çizgi birleşim stilini döndürür veya ayarlar. |
| [getMiterLimit()](#getMiterLimit--) | Bir çizginin kiriş limitini döndürür veya ayarlar. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Bir çizginin kiriş limitini döndürür veya ayarlar. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Bir çizginin başlangıcındaki ok ucu stilini döndürür veya ayarlar. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | Bir çizginin başlangıcındaki ok ucu stilini döndürür veya ayarlar. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Bir çizginin sonundaki ok ucu stilini döndürür veya ayarlar. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | Bir çizginin sonundaki ok ucu stilini döndürür veya ayarlar. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Bir çizginin başlangıcındaki ok ucu genişliğini döndürür veya ayarlar. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | Bir çizginin başlangıcındaki ok ucu genişliğini döndürür veya ayarlar. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Bir çizginin sonundaki ok ucu genişliğini döndürür veya ayarlar. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | Bir çizginin sonundaki ok ucu genişliğini döndürür veya ayarlar. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Bir çizginin başlangıcındaki ok ucu uzunluğunu döndürür veya ayarlar. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | Bir çizginin başlangıcındaki ok ucu uzunluğunu döndürür veya ayarlar. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Bir çizginin sonundaki ok ucu uzunluğunu döndürür veya ayarlar. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | Bir çizginin sonundaki ok ucu uzunluğunu döndürür veya ayarlar. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | İki LineFormat örneğinin eşit olup olmadığını belirler. |
| [getEffective()](#getEffective--) | Miras uygulanmış etkili çizgi biçimlendirme verilerini alır. |
### isFormatNotDefined() {#isFormatNotDefined--}
```
public abstract boolean isFormatNotDefined()
```

Satır biçimi tanımlanmamışsa (yeni oluşturulmuş, varsayılan) true döndürür. Salt okunur boolean.

**Döndürür:**
boolean
### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormat getFillFormat()
```

Bir çizginin doldurma biçimini döndürür. Salt okunur [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Döndürür:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)
### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormat getSketchFormat()
```

Bir çizginin eskiz biçimini döndürür. Salt okunur [ISketchFormat](../../com.aspose.slides/isketchformat).

**Döndürür:**
[ISketchFormat](../../com.aspose.slides/isketchformat)
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Bir çizginin genişliğini döndürür veya ayarlar. Okuma/yazma double.

**Döndürür:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

Bir çizginin genişliğini döndürür veya ayarlar. Okuma/yazma double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |
### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

Çizgi tire stilini döndürür veya ayarlar. Okuma/yazma [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Döndürür:**
byte
### setDashStyle(byte value) {#setDashStyle-byte-}
```
public abstract void setDashStyle(byte value)
```

Çizgi tire stilini döndürür veya ayarlar. Okuma/yazma [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

Özel tire desenini döndürür veya ayarlar. Okuma/yazma float[].

**Döndürür:**
float[]
### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public abstract void setCustomDashPattern(float[] value)
```

Özel tire desenini döndürür veya ayarlar. Okuma/yazma float[].

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float[] |  |
### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

Çizgi kapama stilini döndürür veya ayarlar. Okuma/yazma [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Döndürür:**
byte
### setCapStyle(byte value) {#setCapStyle-byte-}
```
public abstract void setCapStyle(byte value)
```

Çizgi kapama stilini döndürür veya ayarlar. Okuma/yazma [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

Çizgi stilini döndürür veya ayarlar. Okuma/yazma [LineStyle](../../com.aspose.slides/linestyle).

**Döndürür:**
byte
### setStyle(byte value) {#setStyle-byte-}
```
public abstract void setStyle(byte value)
```

Çizgi stilini döndürür veya ayarlar. Okuma/yazma [LineStyle](../../com.aspose.slides/linestyle).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

Çizgi hizalamasını döndürür veya ayarlar. Okuma/yazma [LineAlignment](../../com.aspose.slides/linealignment).

**Döndürür:**
byte
### setAlignment(byte value) {#setAlignment-byte-}
```
public abstract void setAlignment(byte value)
```

Çizgi hizalamasını döndürür veya ayarlar. Okuma/yazma [LineAlignment](../../com.aspose.slides/linealignment).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

Çizgi birleşim stilini döndürür veya ayarlar. Okuma/yazma [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Döndürür:**
byte
### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public abstract void setJoinShape(byte value)
```

Çizgi birleşim stilini döndürür veya ayarlar. Okuma/yazma [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

Bir çizginin kiriş limitini döndürür veya ayarlar. Okuma/yazma float.

**Döndürür:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public abstract void setMiterLimit(float value)
```

Bir çizginin kiriş limitini döndürür veya ayarlar. Okuma/yazma float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

Bir çizginin başlangıcındaki ok ucu stilini döndürür veya ayarlar. Okuma/yazma [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Döndürür:**
byte
### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public abstract void setBeginArrowheadStyle(byte value)
```

Bir çizginin başlangıcındaki ok ucu stilini döndürür veya ayarlar. Okuma/yazma [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

Bir çizginin sonundaki ok ucu stilini döndürür veya ayarlar. Okuma/yazma [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Döndürür:**
byte
### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public abstract void setEndArrowheadStyle(byte value)
```

Bir çizginin sonundaki ok ucu stilini döndürür veya ayarlar. Okuma/yazma [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

Bir çizginin başlangıcındaki ok ucu genişliğini döndürür veya ayarlar. Okuma/yazma [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Döndürür:**
byte
### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public abstract void setBeginArrowheadWidth(byte value)
```

Bir çizginin başlangıcındaki ok ucu genişliğini döndürür veya ayarlar. Okuma/yazma [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

Bir çizginin sonundaki ok ucu genişliğini döndürür veya ayarlar. Okuma/yazma [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Döndürür:**
byte
### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public abstract void setEndArrowheadWidth(byte value)
```

Bir çizginin sonundaki ok ucu genişliğini döndürür veya ayarlar. Okuma/yazma [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

Bir çizginin başlangıcındaki ok ucu uzunluğunu döndürür veya ayarlar. Okuma/yazma [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Döndürür:**
byte
### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public abstract void setBeginArrowheadLength(byte value)
```

Bir çizginin başlangıcındaki ok ucu uzunluğunu döndürür veya ayarlar. Okuma/yazma [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

Bir çizginin sonundaki ok ucu uzunluğunu döndürür veya ayarlar. Okuma/yazma [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Döndürür:**
byte
### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public abstract void setEndArrowheadLength(byte value)
```

Bir çizginin sonundaki ok ucu uzunluğunu döndürür veya ayarlar. Okuma/yazma [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public abstract boolean equals(ILineFormat lineFormat)
```

İki LineFormat örneğinin eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | Mevcut LineFormat ile karşılaştırılacak LineFormat. |

**Döndürür:**
boolean - belirtilen LineFormat mevcut LineFormat ile eşitse **true**, aksi takdirde **false**.
### getEffective() {#getEffective--}
```
public abstract ILineFormatEffectiveData getEffective()
```

Miras uygulanmış etkili çizgi biçimlendirme verilerini alır.

**Döndürür:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - A [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).
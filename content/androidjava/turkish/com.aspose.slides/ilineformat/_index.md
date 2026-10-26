---
title: ILineFormat
second_title: Aspose.Slides için Android üzerinden Java API Referansı
description: Bir satırın biçimini temsil eder.
type: docs
url: /tr/com.aspose.slides/ilineformat/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormat extends ILineParamSource
```

Bir satırın biçimini temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [isFormatNotDefined()](#isFormatNotDefined--) | Satır biçimi tanımlanmamışsa (yeni oluşturulmuş, varsayılan) doğru döndürür. |
| [getFillFormat()](#getFillFormat--) | Satırın doldurma biçimini döndürür. |
| [getSketchFormat()](#getSketchFormat--) | Satırın taslak biçimini döndürür. |
| [getWidth()](#getWidth--) | Satırın genişliğini döndürür veya ayarlar. |
| [setWidth(double value)](#setWidth-double-) | Satırın genişliğini döndürür veya ayarlar. |
| [getDashStyle()](#getDashStyle--) | Satır uç stilini döndürür veya ayarlar. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | Satır uç stilini döndürür veya ayarlar. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Özel kesikli deseni döndürür veya ayarlar. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | Özel kesikli deseni döndürür veya ayarlar. |
| [getCapStyle()](#getCapStyle--) | Satır uç stilini döndürür veya ayarlar. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | Satır uç stilini döndürür veya ayarlar. |
| [getStyle()](#getStyle--) | Satır stilini döndürür veya ayarlar. |
| [setStyle(byte value)](#setStyle-byte-) | Satır stilini döndürür veya ayarlar. |
| [getAlignment()](#getAlignment--) | Satır hizalamasını döndürür veya ayarlar. |
| [setAlignment(byte value)](#setAlignment-byte-) | Satır hizalamasını döndürür veya ayarlar. |
| [getJoinStyle()](#getJoinStyle--) | Satırların birleşim stilini döndürür veya ayarlar. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | Satırların birleşim stilini döndürür veya ayarlar. |
| [getMiterLimit()](#getMiterLimit--) | Satırın kiriş sınırını döndürür veya ayarlar. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Satırın kiriş sınırını döndürür veya ayarlar. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Satırın başlangıcındaki ok ucu stilini döndürür veya ayarlar. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | Satırın başlangıcındaki ok ucu stilini döndürür veya ayarlar. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Satırın sonundaki ok ucu stilini döndürür veya ayarlar. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | Satırın sonundaki ok ucu stilini döndürür veya ayarlar. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Satırın başlangıcındaki ok ucu genişliğini döndürür veya ayarlar. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | Satırın başlangıcındaki ok ucu genişliğini döndürür veya ayarlar. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Satırın sonundaki ok ucu genişliğini döndürür veya ayarlar. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | Satırın sonundaki ok ucu genişliğini döndürür veya ayarlar. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Satırın başlangıcındaki ok ucu uzunluğunu döndürür veya ayarlar. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | Satırın başlangıcındaki ok ucu uzunluğunu döndürür veya ayarlar. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Satırın sonundaki ok ucu uzunluğunu döndürür veya ayarlar. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | Satırın sonundaki ok ucu uzunluğunu döndürür veya ayarlar. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | İki LineFormat örneğinin eşit olup olmadığını belirler. |
| [getEffective()](#getEffective--) | Miras uygulanmış etkili satır biçimlendirme verisini alır. |
### isFormatNotDefined() {#isFormatNotDefined--}
```
public abstract boolean isFormatNotDefined()
```

Satır biçimi tanımlanmamışsa (yeni oluşturulmuş, varsayılan) doğru döndürür. Yalnızca okuma boolean.

**Döndürür:**
boolean
### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormat getFillFormat()
```

Satırın doldurma biçimini döndürür. Yalnızca okuma [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Döndürür:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)
### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormat getSketchFormat()
```

Satırın taslak biçimini döndürür. Yalnızca okuma [ISketchFormat](../../com.aspose.slides/isketchformat).

**Döndürür:**
[ISketchFormat](../../com.aspose.slides/isketchformat)
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Satırın genişliğini döndürür veya ayarlar. Okuma/Yazma double.

**Döndürür:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

Satırın genişliğini döndürür veya ayarlar. Okuma/Yazma double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |
### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

Satırın kesikli stilini döndürür veya ayarlar. Okuma/Yazma [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Döndürür:**
byte
### setDashStyle(byte value) {#setDashStyle-byte-}
```
public abstract void setDashStyle(byte value)
```

Satırın kesikli stilini döndürür veya ayarlar. Okuma/Yazma [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

Özel kesikli deseni döndürür veya ayarlar. Okuma/Yazma float[].

**Döndürür:**
float[]
### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public abstract void setCustomDashPattern(float[] value)
```

Özel kesikli deseni döndürür veya ayarlar. Okuma/Yazma float[].

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float[] |  |
### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

Satır uç stilini döndürür veya ayarlar. Okuma/Yazma [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Döndürür:**
byte
### setCapStyle(byte value) {#setCapStyle-byte-}
```
public abstract void setCapStyle(byte value)
```

Satır uç stilini döndürür veya ayarlar. Okuma/Yazma [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

Satır stilini döndürür veya ayarlar. Okuma/Yazma [LineStyle](../../com.aspose.slides/linestyle).

**Döndürür:**
byte
### setStyle(byte value) {#setStyle-byte-}
```
public abstract void setStyle(byte value)
```

Satır stilini döndürür veya ayarlar. Okuma/Yazma [LineStyle](../../com.aspose.slides/linestyle).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

Satır hizalamasını döndürür veya ayarlar. Okuma/Yazma [LineAlignment](../../com.aspose.slides/linealignment).

**Döndürür:**
byte
### setAlignment(byte value) {#setAlignment-byte-}
```
public abstract void setAlignment(byte value)
```

Satır hizalamasını döndürür veya ayarlar. Okuma/Yazma [LineAlignment](../../com.aspose.slides/linealignment).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

Satırların birleşim stilini döndürür veya ayarlar. Okuma/Yazma [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Döndürür:**
byte
### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public abstract void setJoinStyle(byte value)
```

Satırların birleşim stilini döndürür veya ayarlar. Okuma/Yazma [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

Satırın kiriş sınırını döndürür veya ayarlar. Okuma/Yazma float.

**Döndürür:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public abstract void setMiterLimit(float value)
```

Satırın kiriş sınırını döndürür veya ayarlar. Okuma/Yazma float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

Satırın başlangıcındaki ok ucu stilini döndürür veya ayarlar. Okuma/Yazma [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Döndürür:**
byte
### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public abstract void setBeginArrowheadStyle(byte value)
```

Satırın başlangıcındaki ok ucu stilini döndürür veya ayarlar. Okuma/Yazma [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

Satırın sonundaki ok ucu stilini döndürür veya ayarlar. Okuma/Yazma [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Döndürür:**
byte
### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public abstract void setEndArrowheadStyle(byte value)
```

Satırın sonundaki ok ucu stilini döndürür veya ayarlar. Okuma/Yazma [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

Satırın başlangıcındaki ok ucu genişliğini döndürür veya ayarlar. Okuma/Yazma [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Döndürür:**
byte
### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public abstract void setBeginArrowheadWidth(byte value)
```

Satırın başlangıcındaki ok ucu genişliğini döndürür veya ayarlar. Okuma/Yazma [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

Satırın sonundaki ok ucu genişliğini döndürür veya ayarlar. Okuma/Yazma [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Döndürür:**
byte
### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public abstract void setEndArrowheadWidth(byte value)
```

Satırın sonundaki ok ucu genişliğini döndürür veya ayarlar. Okuma/Yazma [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

Satırın başlangıcındaki ok ucu uzunluğunu döndürür veya ayarlar. Okuma/Yazma [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Döndürür:**
byte
### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public abstract void setBeginArrowheadLength(byte value)
```

Satırın başlangıcındaki ok ucu uzunluğunu döndürür veya ayarlar. Okuma/Yazma [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

Satırın sonundaki ok ucu uzunluğunu döndürür veya ayarlar. Okuma/Yazma [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Döndürür:**
byte
### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public abstract void setEndArrowheadLength(byte value)
```

Satırın sonundaki ok ucu uzunluğunu döndürür veya ayarlar. Okuma/Yazma [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

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
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | Karşılaştırılacak LineFormat. |

**Döndürür:**
boolean - **true** if the specified LineFormat is equal to the current LineFormat; otherwise, **false**.
### getEffective() {#getEffective--}
```
public abstract ILineFormatEffectiveData getEffective()
```

Miras uygulanmış etkili satır biçimlendirme verisini alır.

**Döndürür:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - A [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).
---
title: Row
second_title: Aspose.Slides for Java API Referansı
description: Bir tablo satırını temsil eder.
type: docs
url: /tr/com.aspose.slides/row/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IRow](../../com.aspose.slides/irow)
```
public final class Row extends CellCollection implements IRow
```

Bir tablo satırını temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getHeight()](#getHeight--) | Bir satırın yüksekliğini döndürür. |
| [getMinimalHeight()](#getMinimalHeight--) | Bir satırın mümkün olan minimum yüksekliğini döndürür veya ayarlar. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Bir satırın mümkün olan minimum yüksekliğini döndürür veya ayarlar. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Tüm satır hücrelerinin bölümlerine tanımlı bölüm biçim özelliklerini ayarlar. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Tüm satır hücrelerinin paragraflarına tanımlı paragraf biçim özelliklerini ayarlar. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Tüm satır hücrelerinin metin çerçevelerine tanımlı metin çerçevesi biçim özelliklerini ayarlar. |
| [getRowFormat()](#getRowFormat--) | Bu satır için biçimlendirme özelliklerini içeren RowFormat nesnesini döndürür. |
### getHeight() {#getHeight--}
```
public final double getHeight()
```

Bir satırın yüksekliğini döndürür. Salt okunur double.

**Döndürür:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

Bir satırın mümkün olan minimum yüksekliğini döndürür veya ayarlar. Okunur/yazılabilir double.

**Döndürür:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public final void setMinimalHeight(double value)
```

Bir satırın mümkün olan minimum yüksekliğini döndürür veya ayarlar. Okunur/yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |
### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Tüm satır hücrelerinin bölümlerine tanımlı bölüm biçim özelliklerini ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | Gerekli özellikleri ayarlanmış IPortionFormat nesnesi. |
### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Tüm satır hücrelerinin paragraflarına tanımlı paragraf biçim özelliklerini ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | Gerekli özellikleri ayarlanmış IParagraphFormat nesnesi. |
### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

Tüm satır hücrelerinin metin çerçevelerine tanımlı metin çerçevesi biçim özelliklerini ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | Gerekli özellikleri ayarlanmış ITextFrameFormat nesnesi. |
### getRowFormat() {#getRowFormat--}
```
public final IRowFormat getRowFormat()
```

Bu satır için biçimlendirme özelliklerini içeren RowFormat nesnesini döndürür. Salt okunur [IRowFormat](../../com.aspose.slides/irowformat).

**Döndürür:**
[IRowFormat](../../com.aspose.slides/irowformat)
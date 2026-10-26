---
title: Column
second_title: Aspose.Slides for Java API Referansı
description: Bir tabloda bir sütunu temsil eder.
type: docs
url: /tr/com.aspose.slides/column/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IColumn](../../com.aspose.slides/icolumn)
```
public final class Column extends CellCollection implements IColumn
```

Bir tablo içindeki sütunu temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getWidth()](#getWidth--) | Bir sütunun genişliğini döndürür veya ayarlar. |
| [setWidth(double value)](#setWidth-double-) | Bir sütunun genişliğini döndürür veya ayarlar. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Tanımlı bölüm biçim özelliklerini tüm sütun hücrelerinin bölümlerine ayarlar. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Tanımlı paragraf biçim özelliklerini tüm sütun hücrelerinin paragraflarına ayarlar. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Tanımlı metin çerçevesi biçim özelliklerini tüm sütun hücrelerinin metin çerçevelerine ayarlar. |
| [getColumnFormat()](#getColumnFormat--) | Bu sütun için biçimlendirme özelliklerini içeren ColumnFormat nesnesini döndürür. |
### getWidth() {#getWidth--}
```
public final double getWidth()
```

Bir sütunun genişliğini döndürür veya ayarlar. Okunur/yazılır double.

**Döndürür:**
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

Bir sütunun genişliğini döndürür veya ayarlar. Okunur/yazılır double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |
### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Tanımlı bölüm biçim özelliklerini tüm sütun hücrelerinin bölümlerine ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | Gerekli özellikleri ayarlanmış IPortionFormat nesnesi. |
### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Tanımlı paragraf biçim özelliklerini tüm sütun hücrelerinin paragraflarına ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | Gerekli özellikleri ayarlanmış IParagraphFormat nesnesi. |
### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFrameFormat(ITextFrameFormat source)
```

Tanımlı metin çerçevesi biçim özelliklerini tüm sütun hücrelerinin metin çerçevelerine ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | Gerekli özellikleri ayarlanmış ITextFrameFormat nesnesi. |
### getColumnFormat() {#getColumnFormat--}
```
public final IColumnFormat getColumnFormat()
```

Bu sütun için biçimlendirme özelliklerini içeren ColumnFormat nesnesini döndürür. Yalnızca okunur [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Döndürür:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)
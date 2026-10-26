---
title: Column
second_title: Aspose.Slides for Android üzerinden Java API Referansı
description: Bir tablodaki sütunu temsil eder.
type: docs
url: /tr/com.aspose.slides/column/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**All Implemented Interfaces:**
[com.aspose.slides.IColumn](../../com.aspose.slides/icolumn)
```
public final class Column extends CellCollection implements IColumn
```

Bir tabloda bir sütunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getWidth()](#getWidth--) | Bir sütunun genişliğini alır veya ayarlar. |
| [setWidth(double value)](#setWidth-double-) | Bir sütunun genişliğini alır veya ayarlar. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Tüm sütun hücrelerinin bölümlerine tanımlı bölüm biçim özelliklerini ayarlar. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Tüm sütun hücrelerinin paragraflarına tanımlı paragraf biçim özelliklerini ayarlar. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Tüm sütun hücrelerinin metin çerçevelerine tanımlı metin çerçevesi biçim özelliklerini ayarlar. |
| [getColumnFormat()](#getColumnFormat--) | Bu sütun için biçim özelliklerini içeren ColumnFormat nesnesini döndürür. |
### getWidth() {#getWidth--}
```
public final double getWidth()
```


Bir sütunun genişliğini alır veya ayarlar. Okuma/Yazma double.

**Returns:**
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Bir sütunun genişliğini alır veya ayarlar. Okuma/Yazma double.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```


Tüm sütun hücrelerinin bölümlerine tanımlı bölüm biçim özelliklerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | IPortionFormat object with necessary properties set. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```


Tüm sütun hücrelerinin paragraflarına tanımlı paragraf biçim özelliklerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | IParagraphFormat object with necessary properties set. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```


Tüm sütun hücrelerinin metin çerçevelerine tanımlı metin çerçevesi biçim özelliklerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat object with necessary properties set. |

### getColumnFormat() {#getColumnFormat--}
```
public final IColumnFormat getColumnFormat()
```


Bu sütun için biçim özelliklerini içeren ColumnFormat nesnesini döndürür. Salt-okunur [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Returns:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)
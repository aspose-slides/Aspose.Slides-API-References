---
title: IColumn
second_title: Aspose.Slides Android için Java API Referansı
description: Bir tabloda sütunu temsil eder.
type: docs
url: /tr/com.aspose.slides/icolumn/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IColumn extends ICellCollection, IBulkTextFormattable
```

Bir tabloda sütunu temsil eder.
## Metotlar

| Yöntem | Açıklama |
| --- | --- |
| [getWidth()](#getWidth--) | Bir sütunun genişliğini döndürür veya ayarlar. |
| [setWidth(double value)](#setWidth-double-) | Bir sütunun genişliğini döndürür veya ayarlar. |
| [getColumnFormat()](#getColumnFormat--) | Bu sütun için biçimlendirme özelliklerini içeren ColumnFormat nesnesini döndürür. |
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Bir sütunun genişliğini döndürür veya ayarlar. Okuma/yazma double.

**Döndürür:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```


Bir sütunun genişliğini döndürür veya ayarlar. Okuma/yazma double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getColumnFormat() {#getColumnFormat--}
```
public abstract IColumnFormat getColumnFormat()
```


Bu sütun için biçimlendirme özelliklerini içeren ColumnFormat nesnesini döndürür. Salt-okunur [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Döndürür:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)
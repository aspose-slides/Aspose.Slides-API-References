---
title: IColumn
second_title: Aspose.Slides for Java API Referansı
description: Bir tabloda sütunu temsil eder.
type: docs
url: /tr/com.aspose.slides/icolumn/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IColumn extends ICellCollection, IBulkTextFormattable
```

Bir tabloda sütunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getWidth()](#getWidth--) | Bir sütunun genişliğini alır veya ayarlar. |
| [setWidth(double value)](#setWidth-double-) | Bir sütunun genişliğini alır veya ayarlar. |
| [getColumnFormat()](#getColumnFormat--) | Bu sütun için biçimlendirme özelliklerini içeren ColumnFormat nesnesini alır. |
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Bir sütunun genişliğini alır veya ayarlar. Okuma/Yazma double.

**Döndürür:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```


Bir sütunun genişliğini alır veya ayarlar. Okuma/Yazma double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getColumnFormat() {#getColumnFormat--}
```
public abstract IColumnFormat getColumnFormat()
```


Bu sütun için biçimlendirme özelliklerini içeren ColumnFormat nesnesini alır. Salt-okunur [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Döndürür:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)
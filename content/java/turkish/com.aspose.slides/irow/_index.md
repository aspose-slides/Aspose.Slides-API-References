---
title: IRow
second_title: Aspose.Slides için Java API Referansı
description: Bir tabloda bir satırı temsil eder.
type: docs
url: /tr/com.aspose.slides/irow/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IRow extends ICellCollection, IBulkTextFormattable
```

Bir tabloda bir satırı temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getHeight()](#getHeight--) | Bir satırın yüksekliğini döndürür. |
| [getMinimalHeight()](#getMinimalHeight--) | Bir satırın mümkün olan minimum yüksekliğini alır veya ayarlar. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Bir satırın mümkün olan minimum yüksekliğini alır veya ayarlar. |
| [getRowFormat()](#getRowFormat--) | Bu satır için biçimlendirme özelliklerini içeren RowFormat nesnesini döndürür. |
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


Bir satırın yüksekliğini döndürür. Salt okunur double.

**Dönüş:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```


Bir satırın mümkün olan minimum yüksekliğini alır veya ayarlar. Okunabilir/yazılabilir double.

**Dönüş:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public abstract void setMinimalHeight(double value)
```


Bir satırın mümkün olan minimum yüksekliğini alır veya ayarlar. Okunabilir/yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getRowFormat() {#getRowFormat--}
```
public abstract IRowFormat getRowFormat()
```


Bu satır için biçimlendirme özelliklerini içeren RowFormat nesnesini döndürür. Salt okunur [IRowFormat](../../com.aspose.slides/irowformat).

**Dönüş:**
[IRowFormat](../../com.aspose.slides/irowformat)
---
title: ITable
second_title: Aspose.Slides for Android via Java API Referansı
description: Bir slayttaki tabloyu temsil eder.
type: docs
url: /tr/com.aspose.slides/itable/
---
**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface ITable extends IGraphicalObject, IBulkTextFormattable
```

Bir slayttaki tabloyu temsil eder.
## Yöntemler

| Method | Description |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Belirtilen sütun ve satır indekslerindeki hücreyi döndürür. |
| [getRows()](#getRows--) | Satırların koleksiyonunu döndürür. |
| [getColumns()](#getColumns--) | Sütunların koleksiyonunu döndürür. |
| [getTableFormat()](#getTableFormat--) | Bu tablo için biçimlendirme özelliklerini içeren TableFormat nesnesini döndürür. |
| [getStylePreset()](#getStylePreset--) | Yerleşik tablo stilini alır veya ayarlar. |
| [setStylePreset(int value)](#setStylePreset-int-) | Yerleşik tablo stilini alır veya ayarlar. |
| [getRightToLeft()](#getRightToLeft--) | Tablonun sağdan sola okuma düzenine sahip olup olmadığını belirler. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Tablonun sağdan sola okuma düzenine sahip olup olmadığını belirler. |
| [getFirstRow()](#getFirstRow--) | Bir tablonun ilk satırının özel bir biçimlendirme ile çizilip çizilmemesi gerektiğini belirler. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | Bir tablonun ilk satırının özel bir biçimlendirme ile çizilip çizilmemesi gerektiğini belirler. |
| [getFirstCol()](#getFirstCol--) | Bir tablonun ilk sütununun özel bir biçimlendirme ile çizilip çizilmemesi gerektiğini belirler. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | Bir tablonun ilk sütununun özel bir biçimlendirme ile çizilip çizilmemesi gerektiğini belirler. |
| [getLastRow()](#getLastRow--) | Bir tablonun son satırının özel bir biçimlendirme ile çizilip çizilmemesi gerektiğini belirler. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | Bir tablonun son satırının özel bir biçimlendirme ile çizilip çizilmemesi gerektiğini belirler. |
| [getLastCol()](#getLastCol--) | Bir tablonun son sütununun özel bir biçimlendirme ile çizilip çizilmemesi gerektiğini belirler. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | Bir tablonun son sütununun özel bir biçimlendirme ile çizilip çizilmemesi gerektiğini belirler. |
| [getHorizontalBanding()](#getHorizontalBanding--) | Çift satırların farklı bir biçimlendirme ile çizilip çizilmemesi gerektiğini belirler. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | Çift satırların farklı bir biçimlendirme ile çizilip çizilmemesi gerektiğini belirler. |
| [getVerticalBanding()](#getVerticalBanding--) | Çift sütunların farklı bir biçimlendirme ile çizilip çizilmemesi gerektiğini belirler. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | Çift sütunların farklı bir biçimlendirme ile çizilip çizilmemesi gerektiğini belirler. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Komşu hücreleri birleştirir. |

### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public abstract ICell get_Item(int columnIndex, int rowIndex)
```

Belirtilen sütun ve satır indekslerindeki hücreyi döndürür. Salt okunur [ICell](../../com.aspose.slides/icell).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Dönüş:**
[ICell](../../com.aspose.slides/icell)

### getRows() {#getRows--}
```
public abstract IRowCollection getRows()
```

Satırların koleksiyonunu döndürür. Salt okunur [IRowCollection](../../com.aspose.slides/irowcollection).

**Dönüş:**
[IRowCollection](../../com.aspose.slides/irowcollection)

### getColumns() {#getColumns--}
```
public abstract IColumnCollection getColumns()
```

Sütunların koleksiyonunu döndürür. Salt okunur [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Dönüş:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)

### getTableFormat() {#getTableFormat--}
```
public abstract ITableFormat getTableFormat()
```

Bu tablo için biçimlendirme özelliklerini içeren TableFormat nesnesini döndürür. Salt okunur [ITableFormat](../../com.aspose.slides/itableformat).

**Dönüş:**
[ITableFormat](../../com.aspose.slides/itableformat)

### getStylePreset() {#getStylePreset--}
```
public abstract int getStylePreset()
```

Yerleşik tablo stilini alır veya ayarlar. Okunur/yazılabilir [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Dönüş:**
int

### setStylePreset(int value) {#setStylePreset-int-}
```
public abstract void setStylePreset(int value)
```

Yerleşik tablo stilini alır veya ayarlar. Okunur/yazılabilir [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

Tablonun sağdan sola okuma düzenine sahip olup olmadığını belirler. Okunur-yazılabilir boolean.

**Dönüş:**
boolean

### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public abstract void setRightToLeft(boolean value)
```

Tablonun sağdan sola okuma düzenine sahip olup olmadığını belirler. Okunur-yazılabilir boolean.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public abstract boolean getFirstRow()
```

Bir tablonun ilk satırının özel bir biçimlendirme ile çizilip çizilmemesi gerektiğini belirler. Okunur-yazılabilir boolean.

**Dönüş:**
boolean

### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public abstract void setFirstRow(boolean value)
```

Bir tablonun ilk satırının özel bir biçimlendirme ile çizilip çizilmemesi gerektiğini belirler. Okunur-yazılabilir boolean.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public abstract boolean getFirstCol()
```

Bir tablonun ilk sütununun özel bir biçimlendirme ile çizilip çizilmemesi gerektiğini belirler. Okunur-yazılabilir boolean.

**Dönüş:**
boolean

### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public abstract void setFirstCol(boolean value)
```

Bir tablonun ilk sütununun özel bir biçimlendirme ile çizilip çizilmemesi gerektiğini belirler. Okunur-yazılabilir boolean.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public abstract boolean getLastRow()
```

Bir tablonun son satırının özel bir biçimlendirme ile çizilip çizilmemesi gerektiğini belirler. Okunur-yazılabilir boolean.

**Dönüş:**
boolean

### setLastRow(boolean value) {#setLastRow-boolean-}
```
public abstract void setLastRow(boolean value)
```

Bir tablonun son satırının özel bir biçimlendirme ile çizilip çizilmemesi gerektiğini belirler. Okunur-yazılabilir boolean.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public abstract boolean getLastCol()
```

Bir tablonun son sütununun özel bir biçimlendirme ile çizilip çizilmemesi gerektiğini belirler. Okunur-yazılabilir boolean.

**Dönüş:**
boolean

### setLastCol(boolean value) {#setLastCol-boolean-}
```
public abstract void setLastCol(boolean value)
```

Bir tablonun son sütununun özel bir biçimlendirme ile çizilip çizilmemesi gerektiğini belirler. Okunur-yazılabilir boolean.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public abstract boolean getHorizontalBanding()
```

Çift satırların farklı bir biçimlendirme ile çizilip çizilmemesi gerektiğini belirler. Okunur-yazılabilir boolean.

**Dönüş:**
boolean

### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public abstract void setHorizontalBanding(boolean value)
```

Çift satırların farklı bir biçimlendirme ile çizilip çizilmemesi gerektiğini belirler. Okunur-yazılabilir boolean.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public abstract boolean getVerticalBanding()
```

Çift sütunların farklı bir biçimlendirme ile çizilip çizilmemesi gerektiğini belirler. Okunur-yazılabilir boolean.

**Dönüş:**
boolean

### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public abstract void setVerticalBanding(boolean value)
```

Çift sütunların farklı bir biçimlendirme ile çizilip çizilmemesi gerektiğini belirler. Okunur-yazılabilir boolean.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public abstract ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

Komşu hücreleri birleştirir.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Birleştirilecek hücre. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Birleştirilecek hücre. |
| allowSplitting | boolean | Hücrelerin bölünmesine izin vermek için true. |

**Dönüş:**
[ICell](../../com.aspose.slides/icell) - Birleştirilmiş hücre.
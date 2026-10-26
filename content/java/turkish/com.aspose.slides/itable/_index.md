---
title: ITable
second_title: Aspose.Slides Java API Referansı
description: Bir slayttaki tabloyu temsil eder.
type: docs
url: /tr/com.aspose.slides/itable/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface ITable extends IGraphicalObject, IBulkTextFormattable
```

Bir slaytta tabloyu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Belirtilen sütun ve satır indekslerindeki cell'i döndürür. |
| [getRows()](#getRows--) | Rows'in koleksiyonunu döndürür. |
| [getColumns()](#getColumns--) | Columns'in koleksiyonunu döndürür. |
| [getTableFormat()](#getTableFormat--) | Bu tablo için biçimlendirme özelliklerini içeren TableFormat nesnesini döndürür. |
| [getStylePreset()](#getStylePreset--) | Yerleşik tablo stilini alır veya ayarlar. |
| [setStylePreset(int value)](#setStylePreset-int-) | Yerleşik tablo stilini alır veya ayarlar. |
| [getRightToLeft()](#getRightToLeft--) | Tablonun sağdan sola okuma düzenine sahip olup olmadığını belirler. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Tablonun sağdan sola okuma düzenine sahip olup olmadığını belirler. |
| [getFirstRow()](#getFirstRow--) | Tablonun ilk satırının özel bir biçimlendirme ile çizilip çizilmediğini belirler. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | Tablonun ilk satırının özel bir biçimlendirme ile çizilip çizilmediğini belirler. |
| [getFirstCol()](#getFirstCol--) | Tablonun ilk sütununun özel bir biçimlendirme ile çizilip çizilmediğini belirler. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | Tablonun ilk sütununun özel bir biçimlendirme ile çizilip çizilmediğini belirler. |
| [getLastRow()](#getLastRow--) | Tablonun son satırının özel bir biçimlendirme ile çizilip çizilmediğini belirler. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | Tablonun son satırının özel bir biçimlendirme ile çizilip çizilmediğini belirler. |
| [getLastCol()](#getLastCol--) | Tablonun son sütununun özel bir biçimlendirme ile çizilip çizilmediğini belirler. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | Tablonun son sütununun özel bir biçimlendirme ile çizilip çizilmediğini belirler. |
| [getHorizontalBanding()](#getHorizontalBanding--) | Çift satırların farklı bir biçimlendirme ile çizilip çizilmediğini belirler. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | Çift satırların farklı bir biçimlendirme ile çizilip çizilmediğini belirler. |
| [getVerticalBanding()](#getVerticalBanding--) | Çift sütunların farklı bir biçimlendirme ile çizilip çizilmediğini belirler. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | Çift sütunların farklı bir biçimlendirme ile çizilip çizilmediğini belirler. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Komşu cells'i birleştirir. |

### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public abstract ICell get_Item(int columnIndex, int rowIndex)
```

Belirtilen sütun ve satır indekslerindeki cell'i döndürür. Salt-okunur [ICell](../../com.aspose.slides/icell).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Döndürür:**
[ICell](../../com.aspose.slides/icell)

### getRows() {#getRows--}
```
public abstract IRowCollection getRows()
```

Rows'in koleksiyonunu döndürür. Salt-okunur [IRowCollection](../../com.aspose.slides/irowcollection).

**Döndürür:**
[IRowCollection](../../com.aspose.slides/irowcollection)

### getColumns() {#getColumns--}
```
public abstract IColumnCollection getColumns()
```

Columns'in koleksiyonunu döndürür. Salt-okunur [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Döndürür:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)

### getTableFormat() {#getTableFormat--}
```
public abstract ITableFormat getTableFormat()
```

Bu tablo için biçimlendirme özelliklerini içeren TableFormat nesnesini döndürür. Salt-okunur [ITableFormat](../../com.aspose.slides/itableformat).

**Döndürür:**
[ITableFormat](../../com.aspose.slides/itableformat)

### getStylePreset() {#getStylePreset--}
```
public abstract int getStylePreset()
```

Yerleşik tablo stilini alır veya ayarlar. Okuma/yazma [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Döndürür:**
int

### setStylePreset(int value) {#setStylePreset-int-}
```
public abstract void setStylePreset(int value)
```

Yerleşik tablo stilini alır veya ayarlar. Okuma/yazma [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

Tablonun sağdan sola okuma düzenine sahip olup olmadığını belirler. Okuma/yazma boolean.

**Döndürür:**
boolean

### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public abstract void setRightToLeft(boolean value)
```

Tablonun sağdan sola okuma düzenine sahip olup olmadığını belirler. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public abstract boolean getFirstRow()
```

Tablonun ilk satırının özel bir biçimlendirme ile çizilip çizilmediğini belirler. Okuma/yazma boolean.

**Döndürür:**
boolean

### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public abstract void setFirstRow(boolean value)
```

Tablonun ilk satırının özel bir biçimlendirme ile çizilip çizilmediğini belirler. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public abstract boolean getFirstCol()
```

Tablonun ilk sütununun özel bir biçimlendirme ile çizilip çizilmediğini belirler. Okuma/yazma boolean.

**Döndürür:**
boolean

### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public abstract void setFirstCol(boolean value)
```

Tablonun ilk sütununun özel bir biçimlendirme ile çizilip çizilmediğini belirler. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public abstract boolean getLastRow()
```

Tablonun son satırının özel bir biçimlendirme ile çizilip çizilmediğini belirler. Okuma/yazma boolean.

**Döndürür:**
boolean

### setLastRow(boolean value) {#setLastRow-boolean-}
```
public abstract void setLastRow(boolean value)
```

Tablonun son satırının özel bir biçimlendirme ile çizilip çizilmediğini belirler. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public abstract boolean getLastCol()
```

Tablonun son sütununun özel bir biçimlendirme ile çizilip çizilmediğini belirler. Okuma/yazma boolean.

**Döndürür:**
boolean

### setLastCol(boolean value) {#setLastCol-boolean-}
```
public abstract void setLastCol(boolean value)
```

Tablonun son sütununun özel bir biçimlendirme ile çizilip çizilmediğini belirler. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public abstract boolean getHorizontalBanding()
```

Çift satırların farklı bir biçimlendirme ile çizilip çizilmediğini belirler. Okuma/yazma boolean.

**Döndürür:**
boolean

### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public abstract void setHorizontalBanding(boolean value)
```

Çift satırların farklı bir biçimlendirme ile çizilip çizilmediğini belirler. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public abstract boolean getVerticalBanding()
```

Çift sütunların farklı bir biçimlendirme ile çizilip çizilmediğini belirler. Okuma/yazma boolean.

**Döndürür:**
boolean

### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public abstract void setVerticalBanding(boolean value)
```

Çift sütunların farklı bir biçimlendirme ile çizilip çizilmediğini belirler. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public abstract ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

Komşu cells'i birleştirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Cell to merge. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Cell to merge. |
| allowSplitting | boolean | True to allow cells splitting. |

**Döndürür:**
[ICell](../../com.aspose.slides/icell) - Birleştirilmiş cell.
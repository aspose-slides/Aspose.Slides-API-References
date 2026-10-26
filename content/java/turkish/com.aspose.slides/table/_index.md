---
title: Table
second_title: Aspose.Slides Java için API Referansı
description: Bir slayttaki tabloyu temsil eder.
type: docs
url: /tr/com.aspose.slides/table/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ITable](../../com.aspose.slides/itable)
```
public final class Table extends GraphicalObject implements ITable
```

Bir slayttaki tabloyu temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Belirtilen sütun ve satır indekslerindeki hücreyi döndürür. |
| [getRows()](#getRows--) | Satırların koleksiyonunu döndürür. |
| [getColumns()](#getColumns--) | Sütunların koleksiyonunu döndürür. |
| [getTableFormat()](#getTableFormat--) | Bu tablo için biçimlendirme özelliklerini içeren TableFormat nesnesini döndürür. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Komşu hücreleri birleştirir. |
| [getStylePreset()](#getStylePreset--) | Yerleşik tablo stilini alır veya ayarlar. |
| [setStylePreset(int value)](#setStylePreset-int-) | Yerleşik tablo stilini alır veya ayarlar. |
| [getRightToLeft()](#getRightToLeft--) | Tablonun sağdan sola okuma sırasına sahip olup olmadığını belirler. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Tablonun sağdan sola okuma sırasına sahip olup olmadığını belirler. |
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
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Tüm tablo hücrelerinin bölümlerine tanımlı bölüm biçim özelliklerini ayarlar. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Tüm tablo hücrelerinin paragraflarına tanımlı paragraf biçim özelliklerini ayarlar. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Tüm tablo hücrelerinin metin çerçevelerine tanımlı metin çerçeve biçim özelliklerini ayarlar. |
| [getFillFormat()](#getFillFormat--) | Tablo için doldurma biçimlendirmesini içeren bir TableFormat.FillFormat nesnesini döndürür. |

### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public final ICell get_Item(int columnIndex, int rowIndex)
```

Belirtilen sütun ve satır indekslerindeki hücreyi döndürür. Salt okunur [Cell](../../com.aspose.slides/cell).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Döndürür:**
[ICell](../../com.aspose.slides/icell)

### getRows() {#getRows--}
```
public final IRowCollection getRows()
```

Satırların koleksiyonunu döndürür. Salt okunur [IRowCollection](../../com.aspose.slides/irowcollection).

**Döndürür:**
[IRowCollection](../../com.aspose.slides/irowcollection)

### getColumns() {#getColumns--}
```
public final IColumnCollection getColumns()
```

Sütunların koleksiyonunu döndürür. Salt okunur [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Döndürür:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)

### getTableFormat() {#getTableFormat--}
```
public final ITableFormat getTableFormat()
```

Bu tablo için biçimlendirme özelliklerini içeren TableFormat nesnesini döndürür. Salt okunur [ITableFormat](../../com.aspose.slides/itableformat).

**Döndürür:**
[ITableFormat](../../com.aspose.slides/itableformat)

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public final ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

Komşu hücreleri birleştirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Birleştirilecek hücre. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Birleştirilecek hücre. |
| allowSplitting | boolean | Hücrelerin bölünmesine izin vermek için true. |

**Döndürür:**
[ICell](../../com.aspose.slides/icell) - Birleştirilmiş hücre.

### getStylePreset() {#getStylePreset--}
```
public final int getStylePreset()
```

Yerleşik tablo stilini alır veya ayarlar. Okunur/yazılır [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Döndürür:**
int

### setStylePreset(int value) {#setStylePreset-int-}
```
public final void setStylePreset(int value)
```

Yerleşik tablo stilini alır veya ayarlar. Okunur/yazılır [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public final boolean getRightToLeft()
```

Tablonun sağdan sola okuma sırasına sahip olup olmadığını belirler. Okunur-yazılır  boolean .

**Döndürür:**
boolean

### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public final void setRightToLeft(boolean value)
```

Tablonun sağdan sola okuma sırasına sahip olup olmadığını belirler. Okunur-yazılır  boolean .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final boolean getFirstRow()
```

Tablonun ilk satırının özel bir biçimlendirme ile çizilip çizilmediğini belirler. Okunur/yazılır  boolean .

**Döndürür:**
boolean

### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public final void setFirstRow(boolean value)
```

Tablonun ilk satırının özel bir biçimlendirme ile çizilip çizilmediğini belirler. Okunur/yazılır  boolean .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public final boolean getFirstCol()
```

Tablonun ilk sütununun özel bir biçimlendirme ile çizilip çizilmediğini belirler. Okunur/yazılır  boolean .

**Döndürür:**
boolean

### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public final void setFirstCol(boolean value)
```

Tablonun ilk sütununun özel bir biçimlendirme ile çizilip çizilmediğini belirler. Okunur/yazılır  boolean .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public final boolean getLastRow()
```

Tablonun son satırının özel bir biçimlendirme ile çizilip çizilmediğini belirler. Okunur/yazılır  boolean .

**Döndürür:**
boolean

### setLastRow(boolean value) {#setLastRow-boolean-}
```
public final void setLastRow(boolean value)
```

Tablonun son satırının özel bir biçimlendirme ile çizilip çizilmediğini belirler. Okunur/yazılır  boolean .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public final boolean getLastCol()
```

Tablonun son sütununun özel bir biçimlendirme ile çizilip çizilmediğini belirler. Okunur/yazılır  boolean .

**Döndürür:**
boolean

### setLastCol(boolean value) {#setLastCol-boolean-}
```
public final void setLastCol(boolean value)
```

Tablonun son sütununun özel bir biçimlendirme ile çizilip çizilmediğini belirler. Okunur/yazılır  boolean .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public final boolean getHorizontalBanding()
```

Çift satırların farklı bir biçimlendirme ile çizilip çizilmediğini belirler. Okunur/yazılır  boolean .

**Döndürür:**
boolean

### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public final void setHorizontalBanding(boolean value)
```

Çift satırların farklı bir biçimlendirme ile çizilip çizilmediğini belirler. Okunur/yazılır  boolean .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public final boolean getVerticalBanding()
```

Çift sütunların farklı bir biçimlendirme ile çizilip çizilmediğini belirler. Okunur/yazılır  boolean .

**Döndürür:**
boolean

### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public final void setVerticalBanding(boolean value)
```

Çift sütunların farklı bir biçimlendirme ile çizilip çizilmediğini belirler. Okunur/yazılır  boolean .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Tüm tablo hücrelerinin bölümlerine tanımlı bölüm biçim özelliklerini ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | Gerekli özellikleri ayarlanmış IPortionFormat nesnesi. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Tüm tablo hücrelerinin paragraflarına tanımlı paragraf biçim özelliklerini ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | Gerekli özellikleri ayarlanmış IParagraphFormat nesnesi. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

Tüm tablo hücrelerinin metin çerçevelerine tanımlı metin çerçeve biçim özelliklerini ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | Gerekli özellikleri ayarlanmış ITextFrameFormat nesnesi. |

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

Tablo için doldurma biçimlendirmesini içeren bir TableFormat.FillFormat nesnesini döndürür. Salt okunur [IFillFormat](../../com.aspose.slides/ifillformat).

**Döndürür:**
[IFillFormat](../../com.aspose.slides/ifillformat)
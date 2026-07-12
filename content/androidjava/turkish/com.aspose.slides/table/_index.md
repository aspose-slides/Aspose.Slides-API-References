---
title: Table
second_title: Aspose.Slides Android için Java API Referansı
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
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Belirtilen sütun ve satır indekslerinde hücreyi döndürür. |
| [getRows()](#getRows--) | Satırların koleksiyonunu döndürür. |
| [getColumns()](#getColumns--) | Sütunların koleksiyonunu döndürür. |
| [getTableFormat()](#getTableFormat--) | Bu tablo için biçimlendirme özelliklerini içeren TableFormat nesnesini döndürür. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Komşu hücreleri birleştirir. |
| [getStylePreset()](#getStylePreset--) | Yerleşik tablo stilini alır veya ayarlar. |
| [setStylePreset(int value)](#setStylePreset-int-) | Yerleşik tablo stilini alır veya ayarlar. |
| [getRightToLeft()](#getRightToLeft--) | Tablonun sağdan sola okuma düzenine sahip olup olmadığını belirler. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Tablonun sağdan sola okuma düzenine sahip olup olmadığını belirler. |
| [getFirstRow()](#getFirstRow--) | Bir tablonun ilk satırının özel bir biçimlendirme ile çizilip çizilmediğini belirler. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | Bir tablonun ilk satırının özel bir biçimlendirme ile çizilip çizilmediğini belirler. |
| [getFirstCol()](#getFirstCol--) | Bir tablonun ilk sütununun özel bir biçimlendirme ile çizilip çizilmediğini belirler. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | Bir tablonun ilk sütununun özel bir biçimlendirme ile çizilip çizilmediğini belirler. |
| [getLastRow()](#getLastRow--) | Bir tablonun son satırının özel bir biçimlendirme ile çizilip çizilmediğini belirler. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | Bir tablonun son satırının özel bir biçimlendirme ile çizilip çizilmediğini belirler. |
| [getLastCol()](#getLastCol--) | Bir tablonun son sütununun özel bir biçimlendirme ile çizilip çizilmediğini belirler. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | Bir tablonun son sütununun özel bir biçimlendirme ile çizilip çizilmediğini belirler. |
| [getHorizontalBanding()](#getHorizontalBanding--) | Çift satırların farklı bir biçimlendirme ile çizilip çizilmediğini belirler. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | Çift satırların farklı bir biçimlendirme ile çizilip çizilmediğini belirler. |
| [getVerticalBanding()](#getVerticalBanding--) | Çift sütunların farklı bir biçimlendirme ile çizilip çizilmediğini belirler. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | Çift sütunların farklı bir biçimlendirme ile çizilip çizilmediğini belirler. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Tanımlı bölüm formatı özelliklerini tüm tablo hücrelerinin bölümlerine uygular. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Tanımlı paragraf formatı özelliklerini tüm tablo hücrelerinin paragraflarına uygular. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Tanımlı metin çerçevesi formatı özelliklerini tüm tablo hücrelerinin metin çerçevelerine uygular. |
| [getFillFormat()](#getFillFormat--) | Tablo için dolgu formatını içeren bir TableFormat.FillFormat nesnesi döndürür. |
### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public final ICell get_Item(int columnIndex, int rowIndex)
```

Belirtilen sütun ve satır indekslerinde hücreyi döndürür. Yalnızca okuma [Cell](../../com.aspose.slides/cell).

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

Satırların koleksiyonunu döndürür. Yalnızca okuma [IRowCollection](../../com.aspose.slides/irowcollection).

**Döndürür:**
[IRowCollection](../../com.aspose.slides/irowcollection)
### getColumns() {#getColumns--}
```
public final IColumnCollection getColumns()
```

Sütunların koleksiyonunu döndürür. Yalnızca okuma [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Döndürür:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)
### getTableFormat() {#getTableFormat--}
```
public final ITableFormat getTableFormat()
```

Bu tablo için biçimlendirme özelliklerini içeren TableFormat nesnesini döndürür. Yalnızca okuma [ITableFormat](../../com.aspose.slides/itableformat).

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
| allowSplitting | boolean | Hücrelerin bölünmesine izin vermek için doğru. |

**Döndürür:**
[ICell](../../com.aspose.slides/icell) - Birleştirilen hücre.
### getStylePreset() {#getStylePreset--}
```
public final int getStylePreset()
```

Yerleşik tablo stilini alır veya ayarlar. Okuma/yazma [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Döndürür:**
int
### setStylePreset(int value) {#setStylePreset-int-}
```
public final void setStylePreset(int value)
```

Yerleşik tablo stilini alır veya ayarlar. Okuma/yazma [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getRightToLeft() {#getRightToLeft--}
```
public final boolean getRightToLeft()
```

Tablonun sağdan sola okuma düzenine sahip olup olmadığını belirler. Okuma/yazma boolean .

**Döndürür:**
boolean
### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public final void setRightToLeft(boolean value)
```

Tablonun sağdan sola okuma düzenine sahip olup olmadığını belirler. Okuma/yazma boolean .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getFirstRow() {#getFirstRow--}
```
public final boolean getFirstRow()
```

Bir tablonun ilk satırının özel bir biçimlendirme ile çizilip çizilmediğini belirler. Okuma/yazma boolean .

**Döndürür:**
boolean
### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public final void setFirstRow(boolean value)
```

Bir tablonun ilk satırının özel bir biçimlendirme ile çizilip çizilmediğini belirler. Okuma/yazma boolean .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getFirstCol() {#getFirstCol--}
```
public final boolean getFirstCol()
```

Bir tablonun ilk sütununun özel bir biçimlendirme ile çizilip çizilmediğini belirler. Okuma/yazma boolean .

**Döndürür:**
boolean
### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public final void setFirstCol(boolean value)
```

Bir tablonun ilk sütununun özel bir biçimlendirme ile çizilip çizilmediğini belirler. Okuma/yazma boolean .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getLastRow() {#getLastRow--}
```
public final boolean getLastRow()
```

Bir tablonun son satırının özel bir biçimlendirme ile çizilip çizilmediğini belirler. Okuma/yazma boolean .

**Döndürür:**
boolean
### setLastRow(boolean value) {#setLastRow-boolean-}
```
public final void setLastRow(boolean value)
```

Bir tablonun son satırının özel bir biçimlendirme ile çizilip çizilmediğini belirler. Okuma/yazma boolean .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getLastCol() {#getLastCol--}
```
public final boolean getLastCol()
```

Bir tablonun son sütununun özel bir biçimlendirme ile çizilip çizilmediğini belirler. Okuma/yazma boolean .

**Döndürür:**
boolean
### setLastCol(boolean value) {#setLastCol-boolean-}
```
public final void setLastCol(boolean value)
```

Bir tablonun son sütununun özel bir biçimlendirme ile çizilip çizilmediğini belirler. Okuma/yazma boolean .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getHorizontalBanding() {#getHorizontalBanding--}
```
public final boolean getHorizontalBanding()
```

Çift satırların farklı bir biçimlendirme ile çizilip çizilmediğini belirler. Okuma/yazma boolean .

**Döndürür:**
boolean
### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public final void setHorizontalBanding(boolean value)
```

Çift satırların farklı bir biçimlendirme ile çizilip çizilmediğini belirler. Okuma/yazma boolean .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBanding() {#getVerticalBanding--}
```
public final boolean getVerticalBanding()
```

Çift sütunların farklı bir biçimlendirme ile çizilip çizilmediğini belirler. Okuma/yazma boolean .

**Döndürür:**
boolean
### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public final void setVerticalBanding(boolean value)
```

Çift sütunların farklı bir biçimlendirme ile çizilip çizilmediğini belirler. Okuma/yazma boolean .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Tanımlı bölüm formatı özelliklerini tüm tablo hücrelerinin bölümlerine uygular.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | Gerekli özellikler ayarlanmış IPortionFormat nesnesi. |
### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Tanımlı paragraf formatı özelliklerini tüm tablo hücrelerinin paragraflarına uygular.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | Gerekli özellikler ayarlanmış IParagraphFormat nesnesi. |
### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

Tanımlı metin çerçevesi formatı özelliklerini tüm tablo hücrelerinin metin çerçevelerine uygular.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | Gerekli özellikler ayarlanmış ITextFrameFormat nesnesi. |
### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

Tablo için dolgu formatını içeren bir TableFormat.FillFormat nesnesi döndürür. Yalnızca okuma [IFillFormat](../../com.aspose.slides/ifillformat).

**Döndürür:**
[IFillFormat](../../com.aspose.slides/ifillformat)
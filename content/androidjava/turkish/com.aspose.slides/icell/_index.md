---
title: ICell
second_title: Java API Referansı aracılığıyla Aspose.Slides for Android
description: Bir tabloda hücreyi temsil eder.
type: docs
url: /tr/com.aspose.slides/icell/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ICell extends ISlideComponent
```

Bir tabloda hücreyi temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | Tablonun sol kenarından hücrenin sol kenarına olan mesafeyi döndürür. |
| [getOffsetY()](#getOffsetY--) | Tablonun üst kenarından hücrenin üst kenarına olan mesafeyi döndürür. |
| [getFirstRowIndex()](#getFirstRowIndex--) | Hücre tarafından kapsanan ilk satırın indeksini döndürür. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | Hücre tarafından kapsanan ilk sütunun indeksini döndürür. |
| [getWidth()](#getWidth--) | Hücrenin genişliğini döndürür. |
| [getHeight()](#getHeight--) | Hücrenin yüksekliğini döndürür. |
| [getMinimalHeight()](#getMinimalHeight--) | Hücrenin minimum yüksekliğini döndürür. |
| [getMarginLeft()](#getMarginLeft--) | Bir TextFrame içinde sol kenar boşluğunu döndürür veya ayarlar. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Bir TextFrame içinde sol kenar boşluğunu döndürür veya ayarlar. |
| [getMarginRight()](#getMarginRight--) | Bir TextFrame içinde sağ kenar boşluğunu döndürür veya ayarlar. |
| [setMarginRight(double value)](#setMarginRight-double-) | Bir TextFrame içinde sağ kenar boşluğunu döndürür veya ayarlar. |
| [getMarginTop()](#getMarginTop--) | Bir TextFrame içinde üst kenar boşluğunu döndürür veya ayarlar. |
| [setMarginTop(double value)](#setMarginTop-double-) | Bir TextFrame içinde üst kenar boşluğunu döndürür veya ayarlar. |
| [getMarginBottom()](#getMarginBottom--) | Bir TextFrame içinde alt kenar boşluğunu döndürür veya ayarlar. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Bir TextFrame içinde alt kenar boşluğunu döndürür veya ayarlar. |
| [getTextVerticalType()](#getTextVerticalType--) | Dikey metin tipini döndürür veya ayarlar. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Dikey metin tipini döndürür veya ayarlar. |
| [getTextAnchorType()](#getTextAnchorType--) | Metin tutma (anchor) tipini döndürür veya ayarlar. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | Metin tutma (anchor) tipini döndürür veya ayarlar. |
| [getAnchorCenter()](#getAnchorCenter--) | Metin kutusunun hücre içinde ortalanıp ortalanmadığını belirler. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | Metin kutusunun hücre içinde ortalanıp ortalanmadığını belirler. |
| [getFirstColumn()](#getFirstColumn--) | Hücrenin ilk sütununu alır. |
| [getFirstRow()](#getFirstRow--) | Hücrenin ilk satırını alır. |
| [getColSpan()](#getColSpan--) | Mevcut hücre tarafından kapsanacak, üst tablonun tablo ızgarasındaki ızgara sütun sayısını döndürür. |
| [getRowSpan()](#getRowSpan--) | Bir birleştirilmiş hücrenin kapsadığı satır sayısını döndürür. |
| [getTextFrame()](#getTextFrame--) | Bir hücrenin metin çerçevesini döndürür. |
| [getTable()](#getTable--) | Bir hücrenin üst Tablo nesnesini döndürür. |
| [isMergedCell()](#isMergedCell--) | Hücrenin herhangi bir ayarlanmış hücreyle birleştirilmiş olup olmadığını true döndürür; aksi takdirde false. |
| [getCellFormat()](#getCellFormat--) | Bu hücre için biçimlendirme özelliklerini içeren CellFormat nesnesini döndürür. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | Hücreyi sütun indeksine göre iki hücreye ayırır. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | Hücreyi satır indeksine göre iki hücreye ayırır. |
| [splitByHeight(double height)](#splitByHeight-double-) | Hücreyi yüksekliğe göre ayırır. |
| [splitByWidth(double width)](#splitByWidth-double-) | Hücreyi genişliğe göre ayırır. |

### getOffsetX() {#getOffsetX--}
```
public abstract double getOffsetX()
```

Tablonun sol kenarından hücrenin sol kenarına olan mesafeyi döndürür. Salt okunur double.

**Döndürür:**
double

### getOffsetY() {#getOffsetY--}
```
public abstract double getOffsetY()
```

Tablonun üst kenarından hücrenin üst kenarına olan mesafeyi döndürür. Salt okunur double.

**Döndürür:**
double

### getFirstRowIndex() {#getFirstRowIndex--}
```
public abstract int getFirstRowIndex()
```

Hücre tarafından kapsanan ilk satırın indeksini döndürür. Salt okunur int.

**Döndürür:**
int

### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public abstract int getFirstColumnIndex()
```

Hücre tarafından kapsanan ilk sütunun indeksini döndürür. Salt okunur int.

**Döndürür:**
int

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Hücrenin genişliğini döndürür. Salt okunur double.

**Döndürür:**
double

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```

Hücrenin yüksekliğini döndürür. Salt okunur double.

**Döndürür:**
double

### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```

Bir hücrenin minimum yüksekliğini döndürür. Bu, hücre tarafından kapsanan tüm satırların minimum yüksekliklerinin toplamıdır. Salt okunur double.

**Döndürür:**
double

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Bir TextFrame içinde sol kenar boşluğunu döndürür veya ayarlar. Okunur/yazılır double.

**Döndürür:**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Bir TextFrame içinde sol kenar boşluğunu döndürür veya ayarlar. Okunur/yazılır double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Bir TextFrame içinde sağ kenar boşluğunu döndürür veya ayarlar. Okunur/yazılır double.

**Döndürür:**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Bir TextFrame içinde sağ kenar boşluğunu döndürür veya ayarlar. Okunur/yazılır double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Bir TextFrame içinde üst kenar boşluğunu döndürür veya ayarlar. Okunur/yazılır double.

**Döndürür:**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Bir TextFrame içinde üst kenar boşluğunu döndürür veya ayarlar. Okunur/yazılır double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Bir TextFrame içinde alt kenar boşluğunu döndürür veya ayarlar. Okunur/yazılır double.

**Döndürür:**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Bir TextFrame içinde alt kenar boşluğunu döndürür veya ayarlar. Okunur/yazılır double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Dikey metin tipini döndürür veya ayarlar. Okunur/yazılır [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Döndürür:**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Dikey metin tipini döndürür veya ayarlar. Okunur/yazılır [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getTextAnchorType() {#getTextAnchorType--}
```
public abstract byte getTextAnchorType()
```

Metin tutma (anchor) tipini döndürür veya ayarlar. Okunur/yazılır [TextAnchorType](../../com.aspose.slides/textanchortype).

**Döndürür:**
byte

### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public abstract void setTextAnchorType(byte value)
```

Metin tutma (anchor) tipini döndürür veya ayarlar. Okunur/yazılır [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getAnchorCenter() {#getAnchorCenter--}
```
public abstract boolean getAnchorCenter()
```

Metin kutusunun hücre içinde ortalanıp ortalanmadığını belirler. Okunur/yazılır boolean.

**Döndürür:**
boolean

### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public abstract void setAnchorCenter(boolean value)
```

Metin kutusunun hücre içinde ortalanıp ortalanmadığını belirler. Okunur/yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getFirstColumn() {#getFirstColumn--}
```
public abstract IColumn getFirstColumn()
```

Hücrenin ilk sütununu alır. Salt okunur [IColumn](../../com.aspose.slides/icolumn).

**Döndürür:**
[IColumn](../../com.aspose.slides/icolumn)

### getFirstRow() {#getFirstRow--}
```
public abstract IRow getFirstRow()
```

Hücrenin ilk satırını alır. Salt okunur [IRow](../../com.aspose.slides/irow).

**Döndürür:**
[IRow](../../com.aspose.slides/irow)

### getColSpan() {#getColSpan--}
```
public abstract int getColSpan()
```

Mevcut hücre tarafından kapsanacak, üst tablonun tablo ızgarasındaki ızgara sütun sayısını döndürür. Bu özellik, hücrelerin tabloda diğer hücrelerin dikey sınırlarını kapsayarak birleştirilmiş görünmesini sağlar. Salt okunur int.

**Döndürür:**
int

### getRowSpan() {#getRowSpan--}
```
public abstract int getRowSpan()
```

Bir birleştirilmiş hücrenin kapsadığı satır sayısını döndürür. Bu, yatay birleştirme başlangıç hücresini belirtmek için diğer hücrelerdeki vMerge özelliğiyle birlikte kullanılır. Salt okunur int.

**Döndürür:**
int

### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

Bir hücrenin metin çerçevesini döndürür. Salt okunur [ITextFrame](../../com.aspose.slides/itextframe).

**Döndürür:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTable() {#getTable--}
```
public abstract ITable getTable()
```

Bir hücrenin üst Tablo nesnesini döndürür. Salt okunur [ITable](../../com.aspose.slides/itable).

**Döndürür:**
[ITable](../../com.aspose.slides/itable)

### isMergedCell() {#isMergedCell--}
```
public abstract boolean isMergedCell()
```

Hücrenin herhangi bir ayarlanmış hücreyle birleştirilmiş olup olmadığını true döndürür; aksi takdirde false. Salt okunur boolean.

**Döndürür:**
boolean

### getCellFormat() {#getCellFormat--}
```
public abstract ICellFormat getCellFormat()
```

Bu hücre için biçimlendirme özelliklerini içeren CellFormat nesnesini döndürür. Salt okunur [ICellFormat](../../com.aspose.slides/icellformat).

**Döndürür:**
[ICellFormat](../../com.aspose.slides/icellformat)

### splitByColSpan(int index) {#splitByColSpan-int-}
```
public abstract void splitByColSpan(int index)
```

Hücreyi sütun indeksine göre iki hücreye ayırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Sütun indeksi. |

### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public abstract void splitByRowSpan(int index)
```

Hücreyi satır indeksine göre iki hücreye ayırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Satır indeksi. |

### splitByHeight(double height) {#splitByHeight-double-}
```
public abstract void splitByHeight(double height)
```

Hücreyi yüksekliğe göre ayırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| height | double | Bir satırın yüksekliği. |

### splitByWidth(double width) {#splitByWidth-double-}
```
public abstract void splitByWidth(double width)
```

Hücreyi genişliğe göre ayırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| width | double | Bir sütunun genişliği. |
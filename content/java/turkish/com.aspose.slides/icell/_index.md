---
title: ICell
second_title: Aspose.Slides için Java API Referansı
description: Bir tablo içindeki bir hücreyi temsil eder.
type: docs
url: /tr/com.aspose.slides/icell/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ICell extends ISlideComponent
```

Bir tablo içindeki bir hücreyi temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | Bir tablonun sol tarafı ile bir hücrenin sol tarafı arasındaki mesafeyi döndürür. |
| [getOffsetY()](#getOffsetY--) | Bir tablonun üst tarafı ile bir hücrenin üst tarafı arasındaki mesafeyi döndürür. |
| [getFirstRowIndex()](#getFirstRowIndex--) | Hücre tarafından kapsanan ilk satırın indeksini döndürür. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | Hücre tarafından kapsanan ilk sütunun indeksini döndürür. |
| [getWidth()](#getWidth--) | Hücrenin genişliğini döndürür. |
| [getHeight()](#getHeight--) | Hücrenin yüksekliğini döndürür. |
| [getMinimalHeight()](#getMinimalHeight--) | Bir hücrenin minimum yüksekliğini döndürür. |
| [getMarginLeft()](#getMarginLeft--) | Sol kenar boşluğunu bir TextFrame içinde alır veya ayarlar. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Sol kenar boşluğunu bir TextFrame içinde alır veya ayarlar. |
| [getMarginRight()](#getMarginRight--) | Sağ kenar boşluğunu bir TextFrame içinde alır veya ayarlar. |
| [setMarginRight(double value)](#setMarginRight-double-) | Sağ kenar boşluğunu bir TextFrame içinde alır veya ayarlar. |
| [getMarginTop()](#getMarginTop--) | Üst kenar boşluğunu bir TextFrame içinde alır veya ayarlar. |
| [setMarginTop(double value)](#setMarginTop-double-) | Üst kenar boşluğunu bir TextFrame içinde alır veya ayarlar. |
| [getMarginBottom()](#getMarginBottom--) | Alt kenar boşluğunu bir TextFrame içinde alır veya ayarlar. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Alt kenar boşluğunu bir TextFrame içinde alır veya ayarlar. |
| [getTextVerticalType()](#getTextVerticalType--) | Dikey metin tipini alır veya ayarlar. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Dikey metin tipini alır veya ayarlar. |
| [getTextAnchorType()](#getTextAnchorType--) | Metin çapa tipini alır veya ayarlar. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | Metin çapa tipini alır veya ayarlar. |
| [getAnchorCenter()](#getAnchorCenter--) | Metin kutusunun hücre içinde ortalanıp ortalanmadığını belirler. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | Metin kutusunun hücre içinde ortalanıp ortalanmadığını belirler. |
| [getFirstColumn()](#getFirstColumn--) | Hücrenin ilk sütununu alır. |
| [getFirstRow()](#getFirstRow--) | Hücrenin ilk satırını alır. |
| [getColSpan()](#getColSpan--) | Geçerli hücre tarafından kapsanacak olan üst tablonun tablo ızgarasındaki ızgara sütunlarının sayısını döndürür. |
| [getRowSpan()](#getRowSpan--) | Birleştirilmiş bir hücrenin kapsadığı satır sayısını döndürür. |
| [getTextFrame()](#getTextFrame--) | Bir hücrenin metin çerçevesini döndürür. |
| [getTable()](#getTable--) | Bir hücrenin üst Table nesnesini döndürür. |
| [isMergedCell()](#isMergedCell--) | Birleştirilmiş hücre ise true, aksi takdirde false döndürür. |
| [getCellFormat()](#getCellFormat--) | Bu hücre için biçimlendirme özelliklerini içeren CellFormat nesnesini döndürür. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | Hücreyi sütun indeksine göre iki hücreye böler. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | Hücreyi satır indeksine göre iki hücreye böler. |
| [splitByHeight(double height)](#splitByHeight-double-) | Hücreyi yüksekliğe göre böler. |
| [splitByWidth(double width)](#splitByWidth-double-) | Hücreyi genişliğe göre böler. |
### getOffsetX() {#getOffsetX--}
```
public abstract double getOffsetX()
```

Bir tablonun sol tarafı ile bir hücrenin sol tarafı arasındaki mesafeyi döndürür. Salt okunur double.

**Döndürür:**
double
### getOffsetY() {#getOffsetY--}
```
public abstract double getOffsetY()
```

Bir tablonun üst tarafı ile bir hücrenin üst tarafı arasındaki mesafeyi döndürür. Salt okunur double.

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

Sol kenar boşluğunu bir TextFrame içinde alır veya ayarlar. Okunur/Yazılabilir double.

**Döndürür:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Sol kenar boşluğunu bir TextFrame içinde alır veya ayarlar. Okunur/Yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Sağ kenar boşluğunu bir TextFrame içinde alır veya ayarlar. Okunur/Yazılabilir double.

**Döndürür:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Sağ kenar boşluğunu bir TextFrame içinde alır veya ayarlar. Okunur/Yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Üst kenar boşluğunu bir TextFrame içinde alır veya ayarlar. Okunur/Yazılabilir double.

**Döndürür:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Üst kenar boşluğunu bir TextFrame içinde alır veya ayarlar. Okunur/Yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Alt kenar boşluğunu bir TextFrame içinde alır veya ayarlar. Okunur/Yazılabilir double.

**Döndürür:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Alt kenar boşluğunu bir TextFrame içinde alır veya ayarlar. Okunur/Yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Dikey metin tipini alır veya ayarlar. Okunur/Yazılabilir [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Döndürür:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Dikey metin tipini alır veya ayarlar. Okunur/Yazılabilir [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getTextAnchorType() {#getTextAnchorType--}
```
public abstract byte getTextAnchorType()
```

Metin çapa tipini alır veya ayarlar. Okunur/Yazılabilir [TextAnchorType](../../com.aspose.slides/textanchortype).

**Döndürür:**
byte
### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public abstract void setTextAnchorType(byte value)
```

Metin çapa tipini alır veya ayarlar. Okunur/Yazılabilir [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getAnchorCenter() {#getAnchorCenter--}
```
public abstract boolean getAnchorCenter()
```

Metin kutusunun hücre içinde ortalanıp ortalanmadığını belirler. Okunur/Yazılabilir boolean.

**Döndürür:**
boolean
### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public abstract void setAnchorCenter(boolean value)
```

Metin kutusunun hücre içinde ortalanıp ortalanmadığını belirler. Okunur/Yazılabilir boolean.

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

Geçerli hücre tarafından kapsanacak olan üst tablonun tablo ızgarasındaki ızgara sütunlarının sayısını döndürür. Bu özellik hücrelerin tablodaki diğer hücrelerin dikey sınırlarını kapsayarak birleştirilmiş gibi görünmesini sağlar. Salt okunur int.

**Döndürür:**
int
### getRowSpan() {#getRowSpan--}
```
public abstract int getRowSpan()
```

Birleştirilmiş bir hücrenin kapsadığı satır sayısını döndürür. Bu, diğer hücrelerdeki vMerge özniteliğiyle birlikte, yatay birleştirmenin başlangıç hücresini belirtmek için kullanılır. Salt okunur int.

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

Bir hücrenin üst Table nesnesini döndürür. Salt okunur [ITable](../../com.aspose.slides/itable).

**Döndürür:**
[ITable](../../com.aspose.slides/itable)
### isMergedCell() {#isMergedCell--}
```
public abstract boolean isMergedCell()
```

Hücre herhangi bir ayarlanmış hücreyle birleştirilmişse true, aksi takdirde false döndürür. Salt okunur boolean.

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

Hücreyi sütun indeksine göre iki hücreye böler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Sütun indeksi. |
### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public abstract void splitByRowSpan(int index)
```

Hücreyi satır indeksine göre iki hücreye böler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Satır indeksi. |
### splitByHeight(double height) {#splitByHeight-double-}
```
public abstract void splitByHeight(double height)
```

Hücreyi yüksekliğe göre böler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| height | double | Bir satırın yüksekliği. |
### splitByWidth(double width) {#splitByWidth-double-}
```
public abstract void splitByWidth(double width)
```

Hücreyi genişliğe göre böler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| width | double | Bir sütunun genişliği. |
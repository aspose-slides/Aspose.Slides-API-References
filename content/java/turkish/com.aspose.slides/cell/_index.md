---
title: Cell
second_title: Aspose.Slides for Java API Referansı
description: Bir tablonun hücresini temsil eder.
type: docs
url: /tr/com.aspose.slides/cell/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arayüzler:**
com.aspose.slides.IDOMObject, [com.aspose.slides.ICell](../../com.aspose.slides/icell)
```
public class Cell implements IDOMObject, ICell
```

Bir tablonun hücresini temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | Bir tablonun sol tarafından hücrenin sol tarafına olan mesafeyi döndürür. |
| [getOffsetY()](#getOffsetY--) | Bir tablonun üst tarafından hücrenin üst tarafına olan mesafeyi döndürür. |
| [getFirstRowIndex()](#getFirstRowIndex--) | Hücre tarafından kapsanan ilk satırın dizinini döndürür. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | Hücre tarafından kapsanan ilk sütunun dizinini döndürür. |
| [getWidth()](#getWidth--) | Hücrenin genişliğini döndürür. |
| [getHeight()](#getHeight--) | Hücrenin yüksekliğini döndürür. |
| [getMinimalHeight()](#getMinimalHeight--) | Bir hücrenin minimum yüksekliğini döndürür. |
| [getMarginLeft()](#getMarginLeft--) | Bir TextFrame içindeki sol kenar boşluğunu döndürür veya ayarlar. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Bir TextFrame içindeki sol kenar boşluğunu döndürür veya ayarlar. |
| [getMarginRight()](#getMarginRight--) | Bir TextFrame içindeki sağ kenar boşluğunu döndürür veya ayarlar. |
| [setMarginRight(double value)](#setMarginRight-double-) | Bir TextFrame içindeki sağ kenar boşluğunu döndürür veya ayarlar. |
| [getMarginTop()](#getMarginTop--) | Bir TextFrame içindeki üst kenar boşluğunu döndürür veya ayarlar. |
| [setMarginTop(double value)](#setMarginTop-double-) | Bir TextFrame içindeki üst kenar boşluğunu döndürür veya ayarlar. |
| [getMarginBottom()](#getMarginBottom--) | Bir TextFrame içindeki alt kenar boşluğunu döndürür veya ayarlar. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Bir TextFrame içindeki alt kenar boşluğunu döndürür veya ayarlar. |
| [getTextVerticalType()](#getTextVerticalType--) | Dikey metin tipini döndürür veya ayarlar. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Dikey metin tipini döndürür veya ayarlar. |
| [getTextAnchorType()](#getTextAnchorType--) | Metin çapa tipini döndürür veya ayarlar. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | Metin çapa tipini döndürür veya ayarlar. |
| [getAnchorCenter()](#getAnchorCenter--) | Metin kutusunun hücre içinde ortalanıp ortalanmadığını belirler. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | Metin kutusunun hücre içinde ortalanıp ortalanmadığını belirler. |
| [getFirstRow()](#getFirstRow--) | Hücrenin ilk satırını alır. |
| [getFirstColumn()](#getFirstColumn--) | Hücrenin ilk sütununu alır. |
| [getColSpan()](#getColSpan--) | Mevcut hücrenin kapsayacağı, ebeveyn tablonun tablo ızgarasındaki ızgara sütun sayısını döndürür. |
| [getRowSpan()](#getRowSpan--) | Birleştirilmiş hücrenin kapsadığı satır sayısını döndürür. |
| [getTextFrame()](#getTextFrame--) | Bir hücrenin metin çerçevesini döndürür. |
| [getTable()](#getTable--) | Bir hücrenin ebeveyn Table nesnesini döndürür. |
| [isMergedCell()](#isMergedCell--) | Hücre herhangi bir ayarlanmış hücreyle birleştirilmişse true, aksi takdirde false döndürür. |
| [getCellFormat()](#getCellFormat--) | Bu hücre için biçimlendirme özelliklerini içeren CellFormat nesnesini döndürür. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | Hücreyi sütun dizinine göre iki hücreye böler. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | Hücreyi satır dizinine göre iki hücreye böler. |
| [splitByHeight(double height)](#splitByHeight-double-) | Hücreyi yüksekliğe göre böler. |
| [splitByWidth(double width)](#splitByWidth-double-) | Hücreyi genişliğe göre böler. |
| [getSlide()](#getSlide--) | Bir hücrenin ebeveyn slaytını döndürür. |
| [getPresentation()](#getPresentation--) | Bir hücrenin ebeveyn sunumunu döndürür. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getOffsetX() {#getOffsetX--}
```
public final double getOffsetX()
```

Bir tablonun sol tarafından hücrenin sol tarafına olan mesafeyi döndürür. Salt-okunur double.

**Döndürür:**
double
### getOffsetY() {#getOffsetY--}
```
public final double getOffsetY()
```

Bir tablonun üst tarafından hücrenin üst tarafına olan mesafeyi döndürür. Salt-okunur double.

**Döndürür:**
double
### getFirstRowIndex() {#getFirstRowIndex--}
```
public final int getFirstRowIndex()
```

Hücre tarafından kapsanan ilk satırın dizinini döndürür. Salt-okunur int.

**Döndürür:**
int
### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public final int getFirstColumnIndex()
```

Hücre tarafından kapsanan ilk sütunun dizinini döndürür. Salt-okunur int.

**Döndürür:**
int
### getWidth() {#getWidth--}
```
public final double getWidth()
```

Hücrenin genişliğini döndürür. Salt-okunur double.

**Döndürür:**
double
### getHeight() {#getHeight--}
```
public final double getHeight()
```

Hücrenin yüksekliğini döndürür. Salt-okunur double.

**Döndürür:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

Bir hücrenin minimum yüksekliğini döndürür. Bu, hücre tarafından kapsanan tüm satırların minimal yüksekliklerinin toplamıdır. Salt-okunur double.

**Döndürür:**
double
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

Bir TextFrame içindeki sol kenar boşluğunu döndürür veya ayarlar. Okunur/yazılır double.

**Döndürür:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

Bir TextFrame içindeki sol kenar boşluğunu döndürür veya ayarlar. Okunur/yazılır double.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

Bir TextFrame içindeki sağ kenar boşluğunu döndürür veya ayarlar. Okunur/yazılır double.

**Döndürür:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

Bir TextFrame içindeki sağ kenar boşluğunu döndürür veya ayarlar. Okunur/yazılır double.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

Bir TextFrame içindeki üst kenar boşluğunu döndürür veya ayarlar. Okunur/yazılır double.

**Döndürür:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

Bir TextFrame içindeki üst kenar boşluğunu döndürür veya ayarlar. Okunur/yazılır double.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

Bir TextFrame içindeki alt kenar boşluğunu döndürür veya ayarlar. Okunur/yazılır double.

**Döndürür:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

Bir TextFrame içindeki alt kenar boşluğunu döndürür veya ayarlar. Okunur/yazılır double.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

Dikey metin tipini döndürür veya ayarlar. Okunur/yazılır [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Döndürür:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

Dikey metin tipini döndürür veya ayarlar. Okunur/yazılır [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getTextAnchorType() {#getTextAnchorType--}
```
public final byte getTextAnchorType()
```

Metin çapa tipini döndürür veya ayarlar. Okunur/yazılır [TextAnchorType](../../com.aspose.slides/textanchortype).

**Döndürür:**
byte
### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public final void setTextAnchorType(byte value)
```

Metin çapa tipini döndürür veya ayarlar. Okunur/yazılır [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getAnchorCenter() {#getAnchorCenter--}
```
public final boolean getAnchorCenter()
```

Metin kutusunun hücre içinde ortalanıp ortalanmadığını belirler. Okunur/yazılır boolean.

**Döndürür:**
boolean
### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public final void setAnchorCenter(boolean value)
```

Metin kutusunun hücre içinde ortalanıp ortalanmadığını belirler. Okunur/yazılır boolean.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getFirstRow() {#getFirstRow--}
```
public final IRow getFirstRow()
```

Hücrenin ilk satırını alır. Salt-okunur [IRow](../../com.aspose.slides/irow).

**Döndürür:**
[IRow](../../com.aspose.slides/irow)
### getFirstColumn() {#getFirstColumn--}
```
public final IColumn getFirstColumn()
```

Hücrenin ilk sütununu alır. Salt-okunur [IColumn](../../com.aspose.slides/icolumn).

**Döndürür:**
[IColumn](../../com.aspose.slides/icolumn)
### getColSpan() {#getColSpan--}
```
public final int getColSpan()
```

Mevcut hücrenin kapsayacağı, ebeveyn tablonun tablo ızgarasındaki ızgara sütun sayısını döndürür. Bu özellik, hücrelerin tablo içinde diğer hücrelerin dikey sınırlarını kapsamasıyla birleştirilmiş görünüm elde etmesini sağlar. Salt-okunur int.

**Döndürür:**
int
### getRowSpan() {#getRowSpan--}
```
public final int getRowSpan()
```

Birleştirilmiş hücrenin kapsadığı satır sayısını döndürür. Bu, diğer hücrelerdeki vMerge özelliğiyle birlikte, yatay birleştirmenin başlangıç hücresini belirtmek için kullanılır. Salt-okunur int.

**Döndürür:**
int
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Bir hücrenin metin çerçevesini döndürür. Salt-okunur [ITextFrame](../../com.aspose.slides/itextframe).

**Döndürür:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTable() {#getTable--}
```
public final ITable getTable()
```

Bir hücrenin ebeyn Table nesnesini döndürür. Salt-okunur [ITable](../../com.aspose.slides/itable).

**Döndürür:**
[ITable](../../com.aspose.slides/itable)
### isMergedCell() {#isMergedCell--}
```
public final boolean isMergedCell()
```

Hücre herhangi bir ayarlanmış hücreyle birleştirilmişse true, aksi takdirde false döndürür. Salt-okunur boolean.

**Döndürür:**
boolean
### getCellFormat() {#getCellFormat--}
```
public final ICellFormat getCellFormat()
```

Bu hücre için biçimlendirme özelliklerini içeren CellFormat nesnesini döndürür. Salt-okunur [ICellFormat](../../com.aspose.slides/icellformat).

**Döndürür:**
[ICellFormat](../../com.aspose.slides/icellformat)
### splitByColSpan(int index) {#splitByColSpan-int-}
```
public final void splitByColSpan(int index)
```

Hücreyi sütun dizinine göre iki hücreye böler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Sütun dizini. |
### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public final void splitByRowSpan(int index)
```

Hücreyi satır dizinine göre iki hücreye böler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Satır dizini. |
### splitByHeight(double height) {#splitByHeight-double-}
```
public final void splitByHeight(double height)
```

Hücreyi yüksekliğe göre böler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| height | double | Bir satırın yüksekliği. |
### splitByWidth(double width) {#splitByWidth-double-}
```
public final void splitByWidth(double width)
```

Hücreyi genişliğe göre böler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | double | Bir sütunun genişliği. |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Bir hücrenin ebeyn slaytını döndürür. Salt-okunur [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Döndürür:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Bir hücrenin ebeyn sunumunu döndürür. Salt-okunur [IPresentation](../../com.aspose.slides/ipresentation).

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Salt-okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject
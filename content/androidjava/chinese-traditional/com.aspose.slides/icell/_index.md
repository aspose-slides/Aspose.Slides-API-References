---
title: ICell
second_title: Aspose.Slides for Android 的 Java API 參考
description: 表示表格中的儲存格。
type: docs
url: /zh-hant/com.aspose.slides/icell/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ICell extends ISlideComponent
```

表示表格中的儲存格。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | 傳回表格左側到儲存格左側的距離。 |
| [getOffsetY()](#getOffsetY--) | 傳回表格上側到儲存格上側的距離。 |
| [getFirstRowIndex()](#getFirstRowIndex--) | 傳回儲存格所覆蓋的第一列索引。 |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | 傳回儲存格所覆蓋的第一欄索引。 |
| [getWidth()](#getWidth--) | 傳回儲存格的寬度。 |
| [getHeight()](#getHeight--) | 傳回儲存格的高度。 |
| [getMinimalHeight()](#getMinimalHeight--) | 傳回儲存格的最小高度。 |
| [getMarginLeft()](#getMarginLeft--) | 傳回或設定 TextFrame 中的左邊距。 |
| [setMarginLeft(double value)](#setMarginLeft-double-) | 傳回或設定 TextFrame 中的左邊距。 |
| [getMarginRight()](#getMarginRight--) | 傳回或設定 TextFrame 中的右邊距。 |
| [setMarginRight(double value)](#setMarginRight-double-) | 傳回或設定 TextFrame 中的右邊距。 |
| [getMarginTop()](#getMarginTop--) | 傳回或設定 TextFrame 中的上邊距。 |
| [setMarginTop(double value)](#setMarginTop-double-) | 傳回或設定 TextFrame 中的上邊距。 |
| [getMarginBottom()](#getMarginBottom--) | 傳回或設定 TextFrame 中的下邊距。 |
| [setMarginBottom(double value)](#setMarginBottom-double-) | 傳回或設定 TextFrame 中的下邊距。 |
| [getTextVerticalType()](#getTextVerticalType--) | 傳回或設定垂直文字的類型。 |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | 傳回或設定垂直文字的類型。 |
| [getTextAnchorType()](#getTextAnchorType--) | 傳回或設定文字錨點類型。 |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | 傳回或設定文字錨點類型。 |
| [getAnchorCenter()](#getAnchorCenter--) | 判斷文字方塊是否在儲存格內置中。 |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | 判斷文字方塊是否在儲存格內置中。 |
| [getFirstColumn()](#getFirstColumn--) | 取得儲存格的第一欄。 |
| [getFirstRow()](#getFirstRow--) | 取得儲存格的第一列。 |
| [getColSpan()](#getColSpan--) | 傳回父表格之表格網格中，此儲存格所跨越的網格欄數。 |
| [getRowSpan()](#getRowSpan--) | 傳回合併儲存格跨越的列數。 |
| [getTextFrame()](#getTextFrame--) | 傳回儲存格的文字框。 |
| [getTable()](#getTable--) | 傳回儲存格的父 Table 物件。 |
| [isMergedCell()](#isMergedCell--) | 如果儲存格與任何相鄰儲存格合併則傳回 true，否則傳回 false。 |
| [getCellFormat()](#getCellFormat--) | 傳回包含此儲存格格式屬性的 CellFormat 物件。 |
| [splitByColSpan(int index)](#splitByColSpan-int-) | 依欄索引將儲存格分割為兩個儲存格。 |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | 依列索引將儲存格分割為兩個儲存格。 |
| [splitByHeight(double height)](#splitByHeight-double-) | 依高度分割儲存格。 |
| [splitByWidth(double width)](#splitByWidth-double-) | 依寬度分割儲存格。 |
### getOffsetX() {#getOffsetX--}
```
public abstract double getOffsetX()
```


傳回表格左側到儲存格左側的距離。唯讀 double.

**返回:**
double
### getOffsetY() {#getOffsetY--}
```
public abstract double getOffsetY()
```


傳回表格上側到儲存格上側的距離。唯讀 double.

**返回:**
double
### getFirstRowIndex() {#getFirstRowIndex--}
```
public abstract int getFirstRowIndex()
```


傳回儲存格所覆蓋的第一列索引。唯讀 int.

**返回:**
int
### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public abstract int getFirstColumnIndex()
```


傳回儲存格所覆蓋的第一欄索引。唯讀 int.

**返回:**
int
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


傳回儲存格的寬度。唯讀 double.

**返回:**
double
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


傳回儲存格的高度。唯讀 double.

**返回:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```


傳回儲存格的最小高度。這是所有被儲存格覆蓋之列的最小高度之和。唯讀 double.

**返回:**
double
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```


傳回或設定 TextFrame 中的左邊距。可讀寫 double.

**返回:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```


傳回或設定 TextFrame 中的左邊距。可讀寫 double.

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```


傳回或設定 TextFrame 中的右邊距。可讀寫 double.

**返回:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```


傳回或設定 TextFrame 中的右邊距。可讀寫 double.

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```


傳回或設定 TextFrame 中的上邊距。可讀寫 double.

**返回:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```


傳回或設定 TextFrame 中的上邊距。可讀寫 double.

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```


傳回或設定 TextFrame 中的下邊距。可讀寫 double.

**返回:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```


傳回或設定 TextFrame 中的下邊距。可讀寫 double.

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```


傳回或設定垂直文字的類型。可讀寫 [TextVerticalType](../../com.aspose.slides/textverticaltype).

**返回:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```


傳回或設定垂直文字的類型。可讀寫 [TextVerticalType](../../com.aspose.slides/textverticaltype).

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### getTextAnchorType() {#getTextAnchorType--}
```
public abstract byte getTextAnchorType()
```


傳回或設定文字錨點類型。可讀寫 [TextAnchorType](../../com.aspose.slides/textanchortype).

**返回:**
byte
### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public abstract void setTextAnchorType(byte value)
```


傳回或設定文字錨點類型。可讀寫 [TextAnchorType](../../com.aspose.slides/textanchortype).

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### getAnchorCenter() {#getAnchorCenter--}
```
public abstract boolean getAnchorCenter()
```


判斷文字方塊是否在儲存格內置中。可讀寫 boolean.

**返回:**
boolean
### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public abstract void setAnchorCenter(boolean value)
```


判斷文字方塊是否在儲存格內置中。可讀寫 boolean.

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getFirstColumn() {#getFirstColumn--}
```
public abstract IColumn getFirstColumn()
```


取得儲存格的第一欄。唯讀 [IColumn](../../com.aspose.slides/icolumn).

**返回:**
[IColumn](../../com.aspose.slides/icolumn)
### getFirstRow() {#getFirstRow--}
```
public abstract IRow getFirstRow()
```


取得儲存格的第一列。唯讀 [IRow](../../com.aspose.slides/irow).

**返回:**
[IRow](../../com.aspose.slides/irow)
### getColSpan() {#getColSpan--}
```
public abstract int getColSpan()
```


傳回父表格之表格網格中，此儲存格所跨越的網格欄數。此屬性允許儲存格看起來被合併，因為它跨越表格中其他儲存格的垂直邊界。唯讀 int.

**返回:**
int
### getRowSpan() {#getRowSpan--}
```
public abstract int getRowSpan()
```


傳回合併儲存格跨越的列數。此屬性與其他儲存格上的 vMerge 屬性結合使用，以指定水平合併的起始儲存格。唯讀 int.

**返回:**
int
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


傳回儲存格的文字框。唯讀 [ITextFrame](../../com.aspose.slides/itextframe).

**返回:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTable() {#getTable--}
```
public abstract ITable getTable()
```


傳回儲存格的父 Table 物件。唯讀 [ITable](../../com.aspose.slides/itable).

**返回:**
[ITable](../../com.aspose.slides/itable)
### isMergedCell() {#isMergedCell--}
```
public abstract boolean isMergedCell()
```


如果儲存格與任何相鄰儲存格合併則傳回 true，否則傳回 false。唯讀 boolean.

**返回:**
boolean
### getCellFormat() {#getCellFormat--}
```
public abstract ICellFormat getCellFormat()
```


傳回包含此儲存格格式屬性的 CellFormat 物件。唯讀 [ICellFormat](../../com.aspose.slides/icellformat).

**返回:**
[ICellFormat](../../com.aspose.slides/icellformat)
### splitByColSpan(int index) {#splitByColSpan-int-}
```
public abstract void splitByColSpan(int index)
```


依欄索引將儲存格分割為兩個儲存格。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 欄的索引。 |
### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public abstract void splitByRowSpan(int index)
```


依列索引將儲存格分割為兩個儲存格。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 列的索引。 |
### splitByHeight(double height) {#splitByHeight-double-}
```
public abstract void splitByHeight(double height)
```


依高度分割儲存格。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| height | double | 列的高度。 |
### splitByWidth(double width) {#splitByWidth-double-}
```
public abstract void splitByWidth(double width)
```


依寬度分割儲存格。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| width | double | 欄的寬度。 |
---
title: ICell
second_title: Aspose.Slides for Android 용 Java API 참조
description: 테이블의 셀을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/icell/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ICell extends ISlideComponent
```

테이블의 셀을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | 테이블의 왼쪽 측면에서 셀의 왼쪽 측면까지의 거리를 반환합니다. |
| [getOffsetY()](#getOffsetY--) | 테이블의 위쪽 측면에서 셀의 위쪽 측면까지의 거리를 반환합니다. |
| [getFirstRowIndex()](#getFirstRowIndex--) | 셀에 포함된 첫 번째 행의 인덱스를 반환합니다. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | 셀에 포함된 첫 번째 열의 인덱스를 반환합니다. |
| [getWidth()](#getWidth--) | 셀의 너비를 반환합니다. |
| [getHeight()](#getHeight--) | 셀의 높이를 반환합니다. |
| [getMinimalHeight()](#getMinimalHeight--) | 셀의 최소 높이를 반환합니다. |
| [getMarginLeft()](#getMarginLeft--) | TextFrame의 왼쪽 여백을 반환하거나 설정합니다. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | TextFrame의 왼쪽 여백을 반환하거나 설정합니다. |
| [getMarginRight()](#getMarginRight--) | TextFrame의 오른쪽 여백을 반환하거나 설정합니다. |
| [setMarginRight(double value)](#setMarginRight-double-) | TextFrame의 오른쪽 여백을 반환하거나 설정합니다. |
| [getMarginTop()](#getMarginTop--) | TextFrame의 위쪽 여백을 반환하거나 설정합니다. |
| [setMarginTop(double value)](#setMarginTop-double-) | TextFrame의 위쪽 여백을 반환하거나 설정합니다. |
| [getMarginBottom()](#getMarginBottom--) | TextFrame의 아래쪽 여백을 반환하거나 설정합니다. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | TextFrame의 아래쪽 여백을 반환하거나 설정합니다. |
| [getTextVerticalType()](#getTextVerticalType--) | 수직 텍스트의 유형을 반환하거나 설정합니다. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | 수직 텍스트의 유형을 반환하거나 설정합니다. |
| [getTextAnchorType()](#getTextAnchorType--) | 텍스트 앵커 유형을 반환하거나 설정합니다. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | 텍스트 앵커 유형을 반환하거나 설정합니다. |
| [getAnchorCenter()](#getAnchorCenter--) | 텍스트 상자가 셀 안에서 중앙에 배치되는지 여부를 확인합니다. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | 텍스트 상자가 셀 안에서 중앙에 배치되는지 여부를 확인합니다. |
| [getFirstColumn()](#getFirstColumn--) | 셀의 첫 번째 열을 가져옵니다. |
| [getFirstRow()](#getFirstRow--) | 셀의 첫 번째 행을 가져옵니다. |
| [getColSpan()](#getColSpan--) | 현재 셀이 차지해야 하는 부모 테이블 그리드의 열 수를 반환합니다. |
| [getRowSpan()](#getRowSpan--) | 병합된 셀이 차지하는 행 수를 반환합니다. |
| [getTextFrame()](#getTextFrame--) | 셀의 텍스트 프레임을 반환합니다. |
| [getTable()](#getTable--) | 셀에 대한 부모 Table 객체를 반환합니다. |
| [isMergedCell()](#isMergedCell--) | 셀이 조정된 셀과 병합되어 있으면 true, 그렇지 않으면 false를 반환합니다. |
| [getCellFormat()](#getCellFormat--) | 이 셀에 대한 서식 속성을 포함하는 CellFormat 객체를 반환합니다. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | 열 인덱스로 셀을 두 개의 셀로 분할합니다. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | 행 인덱스로 셀을 두 개의 셀로 분할합니다. |
| [splitByHeight(double height)](#splitByHeight-double-) | 높이로 셀을 분할합니다. |
| [splitByWidth(double width)](#splitByWidth-double-) | 너비로 셀을 분할합니다. |
### getOffsetX() {#getOffsetX--}
```
public abstract double getOffsetX()
```

테이블의 왼쪽 측면에서 셀의 왼쪽 측면까지의 거리를 반환합니다. 읽기 전용 double.

**반환값:**
double
### getOffsetY() {#getOffsetY--}
```
public abstract double getOffsetY()
```

테이블의 위쪽 측면에서 셀의 위쪽 측면까지의 거리를 반환합니다. 읽기 전용 double.

**반환값:**
double
### getFirstRowIndex() {#getFirstRowIndex--}
```
public abstract int getFirstRowIndex()
```

셀에 포함된 첫 번째 행의 인덱스를 반환합니다. 읽기 전용 int.

**반환값:**
int
### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public abstract int getFirstColumnIndex()
```

셀에 포함된 첫 번째 열의 인덱스를 반환합니다. 읽기 전용 int.

**반환값:**
int
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

셀의 너비를 반환합니다. 읽기 전용 double.

**반환값:**
double
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```

셀의 높이를 반환합니다. 읽기 전용 double.

**반환값:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```

셀의 최소 높이를 반환합니다. 이는 셀이 차지하는 모든 행의 최소 높이의 합계입니다. 읽기 전용 double.

**반환값:**
double
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

TextFrame의 왼쪽 여백을 반환하거나 설정합니다. 읽기/쓰기 double.

**반환값:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

TextFrame의 왼쪽 여백을 반환하거나 설정합니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

TextFrame의 오른쪽 여백을 반환하거나 설정합니다. 읽기/쓰기 double.

**반환값:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

TextFrame의 오른쪽 여백을 반환하거나 설정합니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

TextFrame의 위쪽 여백을 반환하거나 설정합니다. 읽기/쓰기 double.

**반환값:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

TextFrame의 위쪽 여백을 반환하거나 설정합니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

TextFrame의 아래쪽 여백을 반환하거나 설정합니다. 읽기/쓰기 double.

**반환값:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

TextFrame의 아래쪽 여백을 반환하거나 설정합니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

수직 텍스트의 유형을 반환하거나 설정합니다. 읽기/쓰기 [TextVerticalType](../../com.aspose.slides/textverticaltype).

**반환값:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

수직 텍스트의 유형을 반환하거나 설정합니다. 읽기/쓰기 [TextVerticalType](../../com.aspose.slides/textverticaltype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getTextAnchorType() {#getTextAnchorType--}
```
public abstract byte getTextAnchorType()
```

텍스트 앵커 유형을 반환하거나 설정합니다. 읽기/쓰기 [TextAnchorType](../../com.aspose.slides/textanchortype).

**반환값:**
byte
### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public abstract void setTextAnchorType(byte value)
```

텍스트 앵커 유형을 반환하거나 설정합니다. 읽기/쓰기 [TextAnchorType](../../com.aspose.slides/textanchortype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getAnchorCenter() {#getAnchorCenter--}
```
public abstract boolean getAnchorCenter()
```

텍스트 상자가 셀 안에서 중앙에 배치되는지 여부를 확인합니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public abstract void setAnchorCenter(boolean value)
```

텍스트 상자가 셀 안에서 중앙에 배치되는지 여부를 확인합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getFirstColumn() {#getFirstColumn--}
```
public abstract IColumn getFirstColumn()
```

셀의 첫 번째 열을 가져옵니다. 읽기 전용 [IColumn](../../com.aspose.slides/icolumn).

**반환값:**
[IColumn](../../com.aspose.slides/icolumn)
### getFirstRow() {#getFirstRow--}
```
public abstract IRow getFirstRow()
```

셀의 첫 번째 행을 가져옵니다. 읽기 전용 [IRow](../../com.aspose.slides/irow).

**반환값:**
[IRow](../../com.aspose.slides/irow)
### getColSpan() {#getColSpan--}
```
public abstract int getColSpan()
```

현재 셀이 차지해야 하는 부모 테이블 그리드의 열 수를 반환합니다. 이 속성은 셀이 테이블 내 다른 셀의 수직 경계를 가로지르면서 병합된 것처럼 보이게 합니다. 읽기 전용 int.

**반환값:**
int
### getRowSpan() {#getRowSpan--}
```
public abstract int getRowSpan()
```

병합된 셀이 차지하는 행 수를 반환합니다. 이는 다른 셀의 vMerge 속성과 함께 사용되어 수평 병합의 시작 셀을 지정합니다. 읽기 전용 int.

**반환값:**
int
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

셀의 텍스트 프레임을 반환합니다. 읽기 전용 [ITextFrame](../../com.aspose.slides/itextframe).

**반환값:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTable() {#getTable--}
```
public abstract ITable getTable()
```

셀에 대한 부모 Table 객체를 반환합니다. 읽기 전용 [ITable](../../com.aspose.slides/itable).

**반환값:**
[ITable](../../com.aspose.slides/itable)
### isMergedCell() {#isMergedCell--}
```
public abstract boolean isMergedCell()
```

셀이 조정된 셀과 병합되어 있으면 true, 그렇지 않으면 false를 반환합니다. 읽기 전용 boolean.

**반환값:**
boolean
### getCellFormat() {#getCellFormat--}
```
public abstract ICellFormat getCellFormat()
```

이 셀에 대한 서식 속성을 포함하는 CellFormat 객체를 반환합니다. 읽기 전용 [ICellFormat](../../com.aspose.slides/icellformat).

**반환값:**
[ICellFormat](../../com.aspose.slides/icellformat)
### splitByColSpan(int index) {#splitByColSpan-int-}
```
public abstract void splitByColSpan(int index)
```

열 인덱스로 셀을 두 개의 셀로 분할합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 열의 인덱스. |
### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public abstract void splitByRowSpan(int index)
```

행 인덱스로 셀을 두 개의 셀로 분할합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 행의 인덱스. |
### splitByHeight(double height) {#splitByHeight-double-}
```
public abstract void splitByHeight(double height)
```

높이로 셀을 분할합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| height | double | 행의 높이. |
### splitByWidth(double width) {#splitByWidth-double-}
```
public abstract void splitByWidth(double width)
```

너비로 셀을 분할합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| width | double | 열의 너비. |
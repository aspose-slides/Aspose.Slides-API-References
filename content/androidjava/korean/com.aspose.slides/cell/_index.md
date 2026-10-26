---
title: Cell
second_title: Java API를 이용한 Android용 Aspose.Slides 레퍼런스
description: 표의 셀을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/cell/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
com.aspose.slides.IDOMObject, [com.aspose.slides.ICell](../../com.aspose.slides/icell)
```
public class Cell implements IDOMObject, ICell
```

표의 셀을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | 표의 왼쪽 측면에서 셀의 왼쪽 측면까지의 거리를 반환합니다. |
| [getOffsetY()](#getOffsetY--) | 표의 위쪽 측면에서 셀의 위쪽 측면까지의 거리를 반환합니다. |
| [getFirstRowIndex()](#getFirstRowIndex--) | 셀에 의해 차지되는 첫 번째 행의 인덱스를 반환합니다. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | 셀에 의해 차지되는 첫 번째 열의 인덱스를 반환합니다. |
| [getWidth()](#getWidth--) | 셀의 너비를 반환합니다. |
| [getHeight()](#getHeight--) | 셀의 높이를 반환합니다. |
| [getMinimalHeight()](#getMinimalHeight--) | 셀의 최소 높이를 반환합니다. |
| [getMarginLeft()](#getMarginLeft--) | 텍스트 프레임의 왼쪽 여백을 반환하거나 설정합니다. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | 텍스트 프레임의 왼쪽 여백을 반환하거나 설정합니다. |
| [getMarginRight()](#getMarginRight--) | 텍스트 프레임의 오른쪽 여백을 반환하거나 설정합니다. |
| [setMarginRight(double value)](#setMarginRight-double-) | 텍스트 프레임의 오른쪽 여백을 반환하거나 설정합니다. |
| [getMarginTop()](#getMarginTop--) | 텍스트 프레임의 위쪽 여백을 반환하거나 설정합니다. |
| [setMarginTop(double value)](#setMarginTop-double-) | 텍스트 프레임의 위쪽 여백을 반환하거나 설정합니다. |
| [getMarginBottom()](#getMarginBottom--) | 텍스트 프레임의 아래쪽 여백을 반환하거나 설정합니다. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | 텍스트 프레임의 아래쪽 여백을 반환하거나 설정합니다. |
| [getTextVerticalType()](#getTextVerticalType--) | 수직 텍스트 유형을 반환하거나 설정합니다. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | 수직 텍스트 유형을 반환하거나 설정합니다. |
| [getTextAnchorType()](#getTextAnchorType--) | 텍스트 앵커 유형을 반환하거나 설정합니다. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | 텍스트 앵커 유형을 반환하거나 설정합니다. |
| [getAnchorCenter()](#getAnchorCenter--) | 텍스트 상자가 셀 안에 가운데 정렬되어 있는지 여부를 판단합니다. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | 텍스트 상자가 셀 안에 가운데 정렬되어 있는지 여부를 판단합니다. |
| [getFirstRow()](#getFirstRow--) | 셀의 첫 번째 행을 가져옵니다. |
| [getFirstColumn()](#getFirstColumn--) | 셀의 첫 번째 열을 가져옵니다. |
| [getColSpan()](#getColSpan--) | 현재 셀이 차지하는 상위 테이블의 테이블 그리드에서 그리드 열 수를 반환합니다. |
| [getRowSpan()](#getRowSpan--) | 병합된 셀이 차지하는 행 수를 반환합니다. |
| [getTextFrame()](#getTextFrame--) | 셀의 텍스트 프레임을 반환합니다. |
| [getTable()](#getTable--) | 셀의 상위 Table 객체를 반환합니다. |
| [isMergedCell()](#isMergedCell--) | 셀을 다른 셀과 병합한 경우 true, 그렇지 않으면 false를 반환합니다. |
| [getCellFormat()](#getCellFormat--) | 이 셀의 서식 속성을 포함하는 CellFormat 객체를 반환합니다. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | 열 인덱스를 기준으로 셀을 두 개의 셀로 분할합니다. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | 행 인덱스를 기준으로 셀을 두 개의 셀로 분할합니다. |
| [splitByHeight(double height)](#splitByHeight-double-) | 높이를 기준으로 셀을 분할합니다. |
| [splitByWidth(double width)](#splitByWidth-double-) | 너비를 기준으로 셀을 분할합니다. |
| [getSlide()](#getSlide--) | 셀의 상위 슬라이드를 반환합니다. |
| [getPresentation()](#getPresentation--) | 셀의 상위 프레젠테이션을 반환합니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getOffsetX() {#getOffsetX--}
```
public final double getOffsetX()
```

표의 왼쪽 측면에서 셀의 왼쪽 측면까지의 거리를 반환합니다. 읽기 전용 double.

**반환:**  
double

### getOffsetY() {#getOffsetY--}
```
public final double getOffsetY()
```

표의 위쪽 측면에서 셀의 위쪽 측면까지의 거리를 반환합니다. 읽기 전용 double.

**반환:**  
double

### getFirstRowIndex() {#getFirstRowIndex--}
```
public final int getFirstRowIndex()
```

셀에 의해 차지되는 첫 번째 행의 인덱스를 반환합니다. 읽기 전용 int.

**반환:**  
int

### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public final int getFirstColumnIndex()
```

셀에 의해 차지되는 첫 번째 열의 인덱스를 반환합니다. 읽기 전용 int.

**반환:**  
int

### getWidth() {#getWidth--}
```
public final double getWidth()
```

셀의 너비를 반환합니다. 읽기 전용 double.

**반환:**  
double

### getHeight() {#getHeight--}
```
public final double getHeight()
```

셀의 높이를 반환합니다. 읽기 전용 double.

**반환:**  
double

### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

셀의 최소 높이를 반환합니다. 이는 셀에 의해 차지되는 모든 행의 최소 높이의 합계입니다. 읽기 전용 double.

**반환:**  
double

### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

텍스트 프레임의 왼쪽 여백을 반환하거나 설정합니다. 읽기/쓰기 double.

**반환:**  
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

텍스트 프레임의 왼쪽 여백을 반환하거나 설정합니다. 읽기/쓰기 double.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

텍스트 프레임의 오른쪽 여백을 반환하거나 설정합니다. 읽기/쓰기 double.

**반환:**  
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

텍스트 프레임의 오른쪽 여백을 반환하거나 설정합니다. 읽기/쓰기 double.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

텍스트 프레임의 위쪽 여백을 반환하거나 설정합니다. 읽기/쓰기 double.

**반환:**  
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

텍스트 프레임의 위쪽 여백을 반환하거나 설정합니다. 읽기/쓰기 double.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

텍스트 프레임의 아래쪽 여백을 반환하거나 설정합니다. 읽기/쓰기 double.

**반환:**  
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

텍스트 프레임의 아래쪽 여백을 반환하거나 설정합니다. 읽기/쓰기 double.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

수직 텍스트 유형을 반환하거나 설정합니다. 읽기/쓰기 [TextVerticalType](../../com.aspose.slides/textverticaltype).

**반환:**  
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

수직 텍스트 유형을 반환하거나 설정합니다. 읽기/쓰기 [TextVerticalType](../../com.aspose.slides/textverticaltype).

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getTextAnchorType() {#getTextAnchorType--}
```
public final byte getTextAnchorType()
```

텍스트 앵커 유형을 반환하거나 설정합니다. 읽기/쓰기 [TextAnchorType](../../com.aspose.slides/textanchortype).

**반환:**  
byte

### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public final void setTextAnchorType(byte value)
```

텍스트 앵커 유형을 반환하거나 설정합니다. 읽기/쓰기 [TextAnchorType](../../com.aspose.slides/textanchortype).

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getAnchorCenter() {#getAnchorCenter--}
```
public final boolean getAnchorCenter()
```

텍스트 상자가 셀 안에 가운데 정렬되어 있는지 여부를 판단합니다. 읽기/쓰기 boolean.

**반환:**  
boolean

### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public final void setAnchorCenter(boolean value)
```

텍스트 상자가 셀 안에 가운데 정렬되어 있는지 여부를 판단합니다. 읽기/쓰기 boolean.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final IRow getFirstRow()
```

셀의 첫 번째 행을 가져옵니다. 읽기 전용 [IRow](../../com.aspose.slides/irow).

**반환:**  
[IRow](../../com.aspose.slides/irow)

### getFirstColumn() {#getFirstColumn--}
```
public final IColumn getFirstColumn()
```

셀의 첫 번째 열을 가져옵니다. 읽기 전용 [IColumn](../../com.aspose.slides/icolumn).

**반환:**  
[IColumn](../../com.aspose.slides/icolumn)

### getColSpan() {#getColSpan--}
```
public final int getColSpan()
```

현재 셀이 차지하는 상위 테이블의 테이블 그리드에서 그리드 열 수를 반환합니다. 읽기 전용 int.

**반환:**  
int

### getRowSpan() {#getRowSpan--}
```
public final int getRowSpan()
```

병합된 셀이 차지하는 행 수를 반환합니다. 이는 다른 셀의 vMerge 속성과 조합하여 수평 병합의 시작 셀을 지정하는 데 사용됩니다. 읽기 전용 int.

**반환:**  
int

### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

셀의 텍스트 프레임을 반환합니다. 읽기 전용 [ITextFrame](../../com.aspose.slides/itextframe).

**반환:**  
[ITextFrame](../../com.aspose.slides/itextframe)

### getTable() {#getTable--}
```
public final ITable getTable()
```

셀의 상위 Table 객체를 반환합니다. 읽기 전용 [ITable](../../com.aspose.slides/itable).

**반환:**  
[ITable](../../com.aspose.slides/itable)

### isMergedCell() {#isMergedCell--}
```
public final boolean isMergedCell()
```

셀을 다른 셀과 병합한 경우 true, 그렇지 않으면 false를 반환합니다. 읽기 전용 boolean.

**반환:**  
boolean

### getCellFormat() {#getCellFormat--}
```
public final ICellFormat getCellFormat()
```

이 셀의 서식 속성을 포함하는 CellFormat 객체를 반환합니다. 읽기 전용 [ICellFormat](../../com.aspose.slides/icellformat).

**반환:**  
[ICellFormat](../../com.aspose.slides/icellformat)

### splitByColSpan(int index) {#splitByColSpan-int-}
```
public final void splitByColSpan(int index)
```

열 인덱스를 기준으로 셀을 두 개의 셀로 분할합니다.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 열 인덱스. |

### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public final void splitByRowSpan(int index)
```

행 인덱스를 기준으로 셀을 두 개의 셀로 분할합니다.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 행 인덱스. |

### splitByHeight(double height) {#splitByHeight-double-}
```
public final void splitByHeight(double height)
```

높이를 기준으로 셀을 분할합니다.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| height | double | 행의 높이. |

### splitByWidth(double width) {#splitByWidth-double-}
```
public final void splitByWidth(double width)
```

너비를 기준으로 셀을 분할합니다.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| width | double | 열의 너비. |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

셀의 상위 슬라이드를 반환합니다. 읽기 전용 [IBaseSlide](../../com.aspose.slides/ibaseslide).

**반환:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

셀의 상위 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../../com.aspose.slides/ipresentation).

**반환:**  
[IPresentation](../../com.aspose.slides/ipresentation)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환:**  
com.aspose.slides.IDOMObject
---
title: Table
second_title: Aspose.Slides Android용 Java API 참조
description: 슬라이드에 있는 표를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/table/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**All Implemented Interfaces:**  
[com.aspose.slides.ITable](../../com.aspose.slides/itable)  
```
public final class Table extends GraphicalObject implements ITable
```

표 슬라이드에 있는 테이블을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | 지정된 열 및 행 인덱스에 있는 셀을 반환합니다. |
| [getRows()](#getRows--) | 행 컬렉션을 반환합니다. |
| [getColumns()](#getColumns--) | 열 컬렉션을 반환합니다. |
| [getTableFormat()](#getTableFormat--) | 이 표의 서식 속성을 포함하는 TableFormat 객체를 반환합니다. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | 인접 셀을 병합합니다. |
| [getStylePreset()](#getStylePreset--) | 내장 테이블 스타일을 가져오거나 설정합니다. |
| [setStylePreset(int value)](#setStylePreset-int-) | 내장 테이블 스타일을 가져오거나 설정합니다. |
| [getRightToLeft()](#getRightToLeft--) | 표가 오른쪽에서 왼쪽으로 읽는 순서인지 여부를 판단합니다. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | 표가 오른쪽에서 왼쪽으로 읽는 순서인지 여부를 판단합니다. |
| [getFirstRow()](#getFirstRow--) | 표의 첫 번째 행을 특수 서식으로 그릴지 여부를 판단합니다. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | 표의 첫 번째 행을 특수 서식으로 그릴지 여부를 판단합니다. |
| [getFirstCol()](#getFirstCol--) | 표의 첫 번째 열을 특수 서식으로 그릴지 여부를 판단합니다. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | 표의 첫 번째 열을 특수 서식으로 그릴지 여부를 판단합니다. |
| [getLastRow()](#getLastRow--) | 표의 마지막 행을 특수 서식으로 그릴지 여부를 판단합니다. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | 표의 마지막 행을 특수 서식으로 그릴지 여부를 판단합니다. |
| [getLastCol()](#getLastCol--) | 표의 마지막 열을 특수 서식으로 그릴지 여부를 판단합니다. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | 표의 마지막 열을 특수 서식으로 그릴지 여부를 판단합니다. |
| [getHorizontalBanding()](#getHorizontalBanding--) | 짝수 행을 다른 서식으로 그릴지 여부를 판단합니다. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | 짝수 행을 다른 서식으로 그릴지 여부를 판단합니다. |
| [getVerticalBanding()](#getVerticalBanding--) | 짝수 열을 다른 서식으로 그릴지 여부를 판단합니다. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | 짝수 열을 다른 서식으로 그릴지 여부를 판단합니다. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | 정의된 부분 서식 속성을 모든 표 셀의 부분에 설정합니다. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | 정의된 단락 서식 속성을 모든 표 셀의 단락에 설정합니다. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | 정의된 텍스트 프레임 서식 속성을 모든 표 셀의 텍스트 프레임에 설정합니다. |
| [getFillFormat()](#getFillFormat--) | 표의 채우기 서식을 포함하는 TableFormat.FillFormat 객체를 반환합니다. |
### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public final ICell get_Item(int columnIndex, int rowIndex)
```

지정된 열 및 행 인덱스에 있는 셀을 반환합니다. 읽기 전용 [Cell](../../com.aspose.slides/cell).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**반환값:**
[ICell](../../com.aspose.slides/icell)
### getRows() {#getRows--}
```
public final IRowCollection getRows()
```

행 컬렉션을 반환합니다. 읽기 전용 [IRowCollection](../../com.aspose.slides/irowcollection).

**반환값:**
[IRowCollection](../../com.aspose.slides/irowcollection)
### getColumns() {#getColumns--}
```
public final IColumnCollection getColumns()
```

열 컬렉션을 반환합니다. 읽기 전용 [IColumnCollection](../../com.aspose.slides/icolumncollection).

**반환값:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)
### getTableFormat() {#getTableFormat--}
```
public final ITableFormat getTableFormat()
```

이 표의 서식 속성을 포함하는 TableFormat 객체를 반환합니다. 읽기 전용 [ITableFormat](../../com.aspose.slides/itableformat).

**반환값:**
[ITableFormat](../../com.aspose.slides/itableformat)
### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public final ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

인접 셀을 병합합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | 병합할 셀. |
| cell2 | [ICell](../../com.aspose.slides/icell) | 병합할 셀. |
| allowSplitting | boolean | 셀 분할을 허용하려면 true. |

**반환값:**
[ICell](../../com.aspose.slides/icell) - 병합된 셀.
### getStylePreset() {#getStylePreset--}
```
public final int getStylePreset()
```

내장 테이블 스타일을 가져오거나 설정합니다. 읽기/쓰기 [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**반환값:**
int
### setStylePreset(int value) {#setStylePreset-int-}
```
public final void setStylePreset(int value)
```

내장 테이블 스타일을 가져오거나 설정합니다. 읽기/쓰기 [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |
### getRightToLeft() {#getRightToLeft--}
```
public final boolean getRightToLeft()
```

표가 오른쪽에서 왼쪽으로 읽는 순서인지 여부를 판단합니다. 읽기/쓰기 boolean .

**반환값:**
boolean
### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public final void setRightToLeft(boolean value)
```

표가 오른쪽에서 왼쪽으로 읽는 순서인지 여부를 판단합니다. 읽기/쓰기 boolean .

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getFirstRow() {#getFirstRow--}
```
public final boolean getFirstRow()
```

표의 첫 번째 행을 특수 서식으로 그릴지 여부를 판단합니다. 읽기/쓰기 boolean .

**반환값:**
boolean
### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public final void setFirstRow(boolean value)
```

표의 첫 번째 행을 특수 서식으로 그릴지 여부를 판단합니다. 읽기/쓰기 boolean .

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getFirstCol() {#getFirstCol--}
```
public final boolean getFirstCol()
```

표의 첫 번째 열을 특수 서식으로 그릴지 여부를 판단합니다. 읽기/쓰기 boolean .

**반환값:**
boolean
### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public final void setFirstCol(boolean value)
```

표의 첫 번째 열을 특수 서식으로 그릴지 여부를 판단합니다. 읽기/쓰기 boolean .

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getLastRow() {#getLastRow--}
```
public final boolean getLastRow()
```

표의 마지막 행을 특수 서식으로 그릴지 여부를 판단합니다. 읽기/쓰기 boolean .

**반환값:**
boolean
### setLastRow(boolean value) {#setLastRow-boolean-}
```
public final void setLastRow(boolean value)
```

표의 마지막 행을 특수 서식으로 그릴지 여부를 판단합니다. 읽기/쓰기 boolean .

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getLastCol() {#getLastCol--}
```
public final boolean getLastCol()
```

표의 마지막 열을 특수 서식으로 그릴지 여부를 판단합니다. 읽기/쓰기 boolean .

**반환값:**
boolean
### setLastCol(boolean value) {#setLastCol-boolean-}
```
public final void setLastCol(boolean value)
```

표의 마지막 열을 특수 서식으로 그릴지 여부를 판단합니다. 읽기/쓰기 boolean .

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getHorizontalBanding() {#getHorizontalBanding--}
```
public final boolean getHorizontalBanding()
```

짝수 행을 다른 서식으로 그릴지 여부를 판단합니다. 읽기/쓰기 boolean .

**반환값:**
boolean
### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public final void setHorizontalBanding(boolean value)
```

짝수 행을 다른 서식으로 그릴지 여부를 판단합니다. 읽기/쓰기 boolean .

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBanding() {#getVerticalBanding--}
```
public final boolean getVerticalBanding()
```

짝수 열을 다른 서식으로 그릴지 여부를 판단합니다. 읽기/쓰기 boolean .

**반환값:**
boolean
### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public final void setVerticalBanding(boolean value)
```

짝수 열을 다른 서식으로 그릴지 여부를 판단합니다. 읽기/쓰기 boolean .

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

정의된 부분 서식 속성을 모든 표 셀의 부분에 설정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | 필요한 속성이 설정된 IPortionFormat 객체. |
### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

정의된 단락 서식 속성을 모든 표 셀의 단락에 설정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | 필요한 속성이 설정된 IParagraphFormat 객체. |
### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

정의된 텍스트 프레임 서식 속성을 모든 표 셀의 텍스트 프레임에 설정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | 필요한 속성이 설정된 ITextFrameFormat 객체. |
### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

표의 채우기 서식을 포함하는 TableFormat.FillFormat 객체를 반환합니다. 읽기 전용 [IFillFormat](../../com.aspose.slides/ifillformat).

**반환값:**
[IFillFormat](../../com.aspose.slides/ifillformat)
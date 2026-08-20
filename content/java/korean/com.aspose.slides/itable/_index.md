---
title: ITable
second_title: Aspose.Slides for Java API 레퍼런스
description: 슬라이드에 있는 표를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/itable/
---
**All Implemented Interfaces:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface ITable extends IGraphicalObject, IBulkTextFormattable
```

Represents a table on a slide.
## 메서드

| Method | Description |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | 지정된 열 및 행 인덱스에 있는 셀을 반환합니다. |
| [getRows()](#getRows--) | 행 컬렉션을 반환합니다. |
| [getColumns()](#getColumns--) | 열 컬렉션을 반환합니다. |
| [getTableFormat()](#getTableFormat--) | 이 표에 대한 서식 속성을 포함하는 TableFormat 개체를 반환합니다. |
| [getStylePreset()](#getStylePreset--) | 내장 테이블 스타일을 가져오거나 설정합니다. |
| [setStylePreset(int value)](#setStylePreset-int-) | 내장 테이블 스타일을 가져오거나 설정합니다. |
| [getRightToLeft()](#getRightToLeft--) | 표가 오른쪽에서 왼쪽으로 읽는 순서를 갖는지 여부를 결정합니다. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | 표가 오른쪽에서 왼쪽으로 읽는 순서를 갖는지 여부를 결정합니다. |
| [getFirstRow()](#getFirstRow--) | 표의 첫 번째 행을 특수 서식으로 그려야 하는지 여부를 결정합니다. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | 표의 첫 번째 행을 특수 서식으로 그려야 하는지 여부를 결정합니다. |
| [getFirstCol()](#getFirstCol--) | 표의 첫 번째 열을 특수 서식으로 그려야 하는지 여부를 결정합니다. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | 표의 첫 번째 열을 특수 서식으로 그려야 하는지 여부를 결정합니다. |
| [getLastRow()](#getLastRow--) | 표의 마지막 행을 특수 서식으로 그려야 하는지 여부를 결정합니다. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | 표의 마지막 행을 특수 서식으로 그려야 하는지 여부를 결정합니다. |
| [getLastCol()](#getLastCol--) | 표의 마지막 열을 특수 서식으로 그려야 하는지 여부를 결정합니다. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | 표의 마지막 열을 특수 서식으로 그려야 하는지 여부를 결정합니다. |
| [getHorizontalBanding()](#getHorizontalBanding--) | 짝수 행을 다른 서식으로 그려야 하는지 여부를 결정합니다. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | 짝수 행을 다른 서식으로 그려야 하는지 여부를 결정합니다. |
| [getVerticalBanding()](#getVerticalBanding--) | 짝수 열을 다른 서식으로 그려야 하는지 여부를 결정합니다. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | 짝수 열을 다른 서식으로 그려야 하는지 여부를 결정합니다. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | 인접 셀을 병합합니다. |
### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public abstract ICell get_Item(int columnIndex, int rowIndex)
```


지정된 열 및 행 인덱스에 있는 셀을 반환합니다. 읽기 전용 [ICell](../../com.aspose.slides/icell).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**반환값:**
[ICell](../../com.aspose.slides/icell)
### getRows() {#getRows--}
```
public abstract IRowCollection getRows()
```


행 컬렉션을 반환합니다. 읽기 전용 [IRowCollection](../../com.aspose.slides/irowcollection).

**반환값:**
[IRowCollection](../../com.aspose.slides/irowcollection)
### getColumns() {#getColumns--}
```
public abstract IColumnCollection getColumns()
```


열 컬렉션을 반환합니다. 읽기 전용 [IColumnCollection](../../com.aspose.slides/icolumncollection).

**반환값:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)
### getTableFormat() {#getTableFormat--}
```
public abstract ITableFormat getTableFormat()
```


이 표에 대한 서식 속성을 포함하는 TableFormat 개체를 반환합니다. 읽기 전용 [ITableFormat](../../com.aspose.slides/itableformat).

**반환값:**
[ITableFormat](../../com.aspose.slides/itableformat)
### getStylePreset() {#getStylePreset--}
```
public abstract int getStylePreset()
```


내장 테이블 스타일을 가져오거나 설정합니다. 읽기/쓰기 [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**반환값:**
int
### setStylePreset(int value) {#setStylePreset-int-}
```
public abstract void setStylePreset(int value)
```


내장 테이블 스타일을 가져오거나 설정합니다. 읽기/쓰기 [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```


표가 오른쪽에서 왼쪽으로 읽는 순서를 갖는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public abstract void setRightToLeft(boolean value)
```


표가 오른쪽에서 왼쪽으로 읽는 순서를 갖는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public abstract boolean getFirstRow()
```


표의 첫 번째 행을 특수 서식으로 그려야 하는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public abstract void setFirstRow(boolean value)
```


표의 첫 번째 행을 특수 서식으로 그려야 하는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public abstract boolean getFirstCol()
```


표의 첫 번째 열을 특수 서식으로 그려야 하는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public abstract void setFirstCol(boolean value)
```


표의 첫 번째 열을 특수 서식으로 그려야 하는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public abstract boolean getLastRow()
```


표의 마지막 행을 특수 서식으로 그려야 하는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setLastRow(boolean value) {#setLastRow-boolean-}
```
public abstract void setLastRow(boolean value)
```


표의 마지막 행을 특수 서식으로 그려야 하는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public abstract boolean getLastCol()
```


표의 마지막 열을 특수 서식으로 그려야 하는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setLastCol(boolean value) {#setLastCol-boolean-}
```
public abstract void setLastCol(boolean value)
```


표의 마지막 열을 특수 서식으로 그려야 하는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public abstract boolean getHorizontalBanding()
```


짝수 행을 다른 서식으로 그려야 하는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public abstract void setHorizontalBanding(boolean value)
```


짝수 행을 다른 서식으로 그려야 하는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public abstract boolean getVerticalBanding()
```


짝수 열을 다른 서식으로 그려야 하는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public abstract void setVerticalBanding(boolean value)
```


짝수 열을 다른 서식으로 그려야 하는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public abstract ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```


인접 셀을 병합합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Cell을 병합합니다. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Cell을 병합합니다. |
| allowSplitting | boolean | 셀 분할을 허용하려면 True. |

**반환값:**
[ICell](../../com.aspose.slides/icell) - Merged cell.
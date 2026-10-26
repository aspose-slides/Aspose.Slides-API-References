---
title: MathMatrix
second_title: Java API 참조를 통해 Android용 Aspose.Slides
description: 행과 열 하나 이상에 배치된 자식 요소로 구성된 Matrix 객체를 지정합니다.
type: docs
url: /ko/com.aspose.slides/mathmatrix/
---
**상속:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**모든 구현된 인터페이스:**  
[com.aspose.slides.IMathMatrix](../../com.aspose.slides/imathmatrix), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathMatrix extends MathElementBase implements IMathMatrix, IHasControlCharacterProperties
```

행과 열 하나 이상에 배치된 자식 요소로 구성된 Matrix 객체를 지정합니다. 행렬은 내장 구분 기호가 없다는 점에 유의해야 합니다. 행렬을 대괄호 안에 배치하려면 구분 기호 객체(IMathDelimiter)를 사용해야 합니다. Null 인수를 사용하여 행렬에 빈 공간을 만들 수 있습니다.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MathMatrix(int rowCount, int columnCount)](#MathMatrix-int-int-) | MathMatrix 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getRowCount()](#getRowCount--) | 행렬의 행 수 |
| [getColumnCount()](#getColumnCount--) | 행렬의 열 수 |
| [getHidePlaceholders()](#getHidePlaceholders--) | 빈 행렬 요소에 대한 자리 표시자를 숨깁니다. 기본값: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | 빈 행렬 요소에 대한 자리 표시자를 숨깁니다. 기본값: false |
| [getBaseJustification()](#getBaseJustification--) | 주변 텍스트에 대한 수직 정렬을 지정합니다. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | 주변 텍스트에 대한 수직 정렬을 지정합니다. |
| [getMinColumnWidth()](#getMinColumnWidth--) | twips(포인트의 1/20) 단위의 최소 열 너비이며, 갭 간격(\\u201cColumn Gap\\u201d 또는 \\u201cGap Width\\u201d라고도 함)은 MinColumnWidth에 추가되어 전체 행렬 열 간격(다른 열의 동일한 가장자리 사이 거리)을 결정합니다. |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | twips(포인트의 1/20) 단위의 최소 열 너비이며, 갭 간격(\\u201cColumn Gap\\u201d 또는 \\u201cGap Width\\u201d라고도 함)은 MinColumnWidth에 추가되어 전체 행렬 열 간격(다른 열의 동일한 가장자리 사이 거리)을 결정합니다. |
| [getColumnGapRule()](#getColumnGapRule--) | 행렬 열 사이의 수평 간격 유형이며, 수평 간격 단위는 em 또는 포인트(twips로 저장)일 수 있습니다. |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | 행렬 열 사이의 수평 간격 유형이며, 수평 간격 단위는 em 또는 포인트(twips로 저장)일 수 있습니다. |
| [getColumnGap()](#getColumnGap--) | 행렬 열 사이의 수평 간격 값이며, ColumnGapRule이 3("Exactly")으로 설정된 경우 단위는 twips(포인트의 1/20)로 해석됩니다. ColumnGapRule이 4("Multiple")으로 설정된 경우 단위는 0.5 em 증가 수로 해석됩니다. |
| [setColumnGap(long value)](#setColumnGap-long-) | 행렬 열 사이의 수평 간격 값이며, ColumnGapRule이 3("Exactly")으로 설정된 경우 단위는 twips(포인트의 1/20)로 해석됩니다. ColumnGapRule이 4("Multiple")으로 설정된 경우 단위는 0.5 em 증가 수로 해석됩니다. |
| [getRowGapRule()](#getRowGapRule--) | 행렬 행 사이의 수직 간격 유형이며, 수직 간격 단위는 라인 또는 포인트(twips로 저장)일 수 있습니다. |
| [setRowGapRule(int value)](#setRowGapRule-int-) | 행렬 행 사이의 수직 간격 유형이며, 수직 간격 단위는 라인 또는 포인트(twips로 저장)일 수 있습니다. |
| [getRowGap()](#getRowGap--) | 행렬 행 사이의 수직 간격 값이며, RowGapRule이 3("Exactly")으로 설정된 경우 단위는 twips(포인트의 1/20)로 해석됩니다. RowGapRule이 4("Multiple")으로 설정된 경우 단위는 반 라인(half-lines)으로 해석됩니다. |
| [setRowGap(long value)](#setRowGap-long-) | 행렬 행 사이의 수직 간격 값이며, RowGapRule이 3("Exactly")으로 설정된 경우 단위는 twips(포인트의 1/20)로 해석됩니다. RowGapRule이 4("Multiple")으로 설정된 경우 단위는 반 라인(half-lines)으로 해석됩니다. |
| [get_Item(int row, int column)](#get-Item-int-int-) | 행렬 요소 |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | 행렬 요소 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 제어 문자 속성 |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | 지정된 열의 수평 정렬을 가져옵니다. |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | 지정된 열의 수평 정렬을 설정합니다. |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | 지정된 열들의 수평 정렬을 설정합니다. |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | 지정된 행 앞에 새 행을 삽입합니다. 새 행의 모든 요소는 처음에 null입니다. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | 지정된 행 뒤에 새 행을 삽입합니다. 새 행의 모든 요소는 처음에 null입니다. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | 지정된 행을 삭제합니다. |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | 지정된 열 앞에 새 열을 삽입합니다. 새 열의 모든 요소는 처음에 null입니다. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | 지정된 열 뒤에 새 열을 삽입합니다. 새 열의 모든 요소는 처음에 null입니다. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | 지정된 열을 삭제합니다. |
| [getChildren()](#getChildren--) | 자식 요소를 가져옵니다. |
### MathMatrix(int rowCount, int columnCount) {#MathMatrix-int-int-}
```
public MathMatrix(int rowCount, int columnCount)
```

MathMatrix 클래스의 새 인스턴스를 초기화합니다.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rowCount | int | 행 수 |
| columnCount | int | 열 수 |

### getRowCount() {#getRowCount--}
```
public final int getRowCount()
```

행렬의 행 수

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int rowCount = matrix.getRowCount();
> ```

**반환값:**
int
### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```

행렬의 열 수

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int columnCount = matrix.getColumnCount();
> ```

**반환값:**
int
### getHidePlaceholders() {#getHidePlaceholders--}
```
public final boolean getHidePlaceholders()
```

빈 행렬 요소에 대한 자리 표시자를 숨깁니다. 기본값: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**반환값:**
boolean
### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public final void setHidePlaceholders(boolean value)
```

빈 행렬 요소에 대한 자리 표시자를 숨깁니다. 기본값: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```

주변 텍스트에 대한 수직 정렬을 지정합니다. 가능한 값은 top, bottom, center이며 기본값은 Center입니다.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**반환값:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```

주변 텍스트에 대한 수직 정렬을 지정합니다. 가능한 값은 top, bottom, center이며 기본값은 Center입니다.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getMinColumnWidth() {#getMinColumnWidth--}
```
public final long getMinColumnWidth()
```

twips(포인트의 1/20) 단위의 최소 열 너비이며, 갭 간격(\\u201cColumn Gap\\u201d 또는 \\u201cGap Width\\u201d라고도 함)은 MinColumnWidth에 추가되어 전체 행렬 열 간격(다른 열의 동일한 가장자리 사이 거리)을 결정합니다. 기본값: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**반환값:**
long
### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public final void setMinColumnWidth(long value)
```

twips(포인트의 1/20) 단위의 최소 열 너비이며, 갭 간격(\\u201cColumn Gap\\u201d 또는 \\u201cGap Width\\u201d라고도 함)은 MinColumnWidth에 추가되어 전체 행렬 열 간격(다른 열의 동일한 가장자리 사이 거리)을 결정합니다. 기본값: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | long |  |

### getColumnGapRule() {#getColumnGapRule--}
```
public final int getColumnGapRule()
```

행렬 열 사이의 수평 간격 유형이며, 수평 간격 단위는 em 또는 포인트(twips로 저장)일 수 있습니다. 기본값: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**반환값:**
int
### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public final void setColumnGapRule(int value)
```

행렬 열 사이의 수평 간격 유형이며, 수평 간격 단위는 em 또는 포인트(twips로 저장)일 수 있습니다. 기본값: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getColumnGap() {#getColumnGap--}
```
public final long getColumnGap()
```

행렬 열 사이의 수평 간격 값이며, ColumnGapRule이 3("Exactly")으로 설정된 경우 단위는 twips(포인트의 1/20)로 해석됩니다. ColumnGapRule이 4("Multiple")으로 설정된 경우 단위는 0.5 em 증가 수로 해석됩니다. 기타 경우는 무시됩니다. 기본값: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**반환값:**
long
### setColumnGap(long value) {#setColumnGap-long-}
```
public final void setColumnGap(long value)
```

행렬 열 사이의 수평 간격 값이며, ColumnGapRule이 3("Exactly")으로 설정된 경우 단위는 twips(포인트의 1/20)로 해석됩니다. ColumnGapRule이 4("Multiple")으로 설정된 경우 단위는 0.5 em 증가 수로 해석됩니다. 기타 경우는 무시됩니다. 기본값: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | long |  |

### getRowGapRule() {#getRowGapRule--}
```
public final int getRowGapRule()
```

행렬 행 사이의 수직 간격 유형이며, 수직 간격 단위는 라인 또는 포인트(twips로 저장)일 수 있습니다. 기본값: SingleSpacingGap (0)

--------------------

> ```
> 예시:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```


**반환값:**
int
### setRowGapRule(int value) {#setRowGapRule-int-}
```
public final void setRowGapRule(int value)
```

행렬 행 사이의 수직 간격 유형이며, 수직 간격 단위는 라인 또는 포인트(twips로 저장)일 수 있습니다. 기본값: SingleSpacingGap (0)

--------------------

> ```
> 예시:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getRowGap() {#getRowGap--}
```
public final long getRowGap()
```

행렬 행 사이의 수직 간격 값이며, RowGapRule이 3("Exactly")으로 설정된 경우 단위는 twips(포인트의 1/20)로 해석됩니다. RowGapRule이 4("Multiple")으로 설정된 경우 단위는 반 라인(half-lines)으로 해석됩니다. 기본값: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**반환값:**
long
### setRowGap(long value) {#setRowGap-long-}
```
public final void setRowGap(long value)
```

행렬 행 사이의 수직 간격 값이며, RowGapRule이 3("Exactly")으로 설정된 경우 단위는 twips(포인트의 1/20)로 해석됩니다. RowGapRule이 4("Multiple")으로 설정된 경우 단위는 반 라인(half-lines)으로 해석됩니다. 기본값: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | long |  |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public final IMathElement get_Item(int row, int column)
```

행렬 요소

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| row | int | 가져올 항목의 0 기반 행 인덱스 |
| column | int | 가져올 항목의 0 기반 열 인덱스 |

**반환값:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int row, int column, IMathElement value)
```

행렬 요소

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| row | int | 가져올 항목의 0 기반 행 인덱스 |
| column | int | 가져올 항목의 0 기반 열 인덱스 |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

제어 문자 속성

**반환값:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public final int getColumnAlignment(int columnIndex)
```

지정된 열의 수평 정렬을 가져옵니다.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| columnIndex | int | 0 기반 열 인덱스 |

**반환값:**
int - 지정된 열의 수평 정렬
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public final void setColumnAlignment(int columnIndex, int val)
```

지정된 열의 수평 정렬을 설정합니다.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| columnIndex | int | 0 기반 열 인덱스 |
| val | int | 지정된 열의 새로운 수평 정렬 값 |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public final void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

지정된 열들의 수평 정렬을 설정합니다.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| columnIndex | int | 첫 번째 열의 0 기반 인덱스 |
| columnsCount | long | 정렬을 지정할 열 수 |
| val | int | 지정된 열의 새로운 수평 정렬 값 |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public final void insertRowBefore(int rowIndex)
```

지정된 행 앞에 새 행을 삽입합니다. 새 행의 모든 요소는 처음에 null입니다.

--------------------

> ```
> 예시:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rowIndex | int | 새 행을 삽입할 위치의 행 인덱스 |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public final void insertRowAfter(int rowIndex)
```

지정된 행 뒤에 새 행을 삽입합니다. 새 행의 모든 요소는 처음에 null입니다.

--------------------

> ```
> 예시:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rowIndex | int | 새 행을 삽입할 위치의 행 인덱스 |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public final void deleteRow(int rowIndex)
```

지정된 행을 삭제합니다.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rowIndex | int | 삭제할 행의 0 기반 인덱스 |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public final void insertColumnBefore(int columnIndex)
```

지정된 열 앞에 새 열을 삽입합니다. 새 열의 모든 요소는 처음에 null입니다.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| columnIndex | int | 삽입할 위치의 열 인덱스 |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public final void insertColumnAfter(int columnIndex)
```

지정된 열 뒤에 새 열을 삽입합니다. 새 열의 모든 요소는 처음에 null입니다.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| columnIndex | int | 삽입할 위치의 열 인덱스 |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public final void deleteColumn(int columnIndex)
```

지정된 열을 삭제합니다.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| columnIndex | int | 삭제할 열의 0 기반 인덱스 |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

자식 요소를 가져옵니다.

**반환값:**
com.aspose.slides.IMathElement[]
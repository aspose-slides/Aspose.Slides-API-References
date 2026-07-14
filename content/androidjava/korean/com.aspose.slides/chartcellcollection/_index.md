---
title: ChartCellCollection
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 데이터가 있는 셀의 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/chartcellcollection/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IChartCellCollection](../../com.aspose.slides/ichartcellcollection), com.aspose.slides.IDOMObject
```
public class ChartCellCollection implements IChartCellCollection, IDOMObject
```

데이터가 있는 셀의 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | 워크북에 있는 셀 집합의 주소를 반환합니다. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | 모든 셀 문자열 값을 연결한 문자열을 반환합니다. |
| [get_Item(int index)](#get-Item-int-) | 인덱스로 셀(IChartDataCell)을 반환합니다. |
| [add(IChartDataCell cell)](#add-com.aspose.slides.IChartDataCell-) | 새 셀을 컬렉션에 추가합니다. |
| [add(Object value)](#add-java.lang.Object-) | 지정된 값으로 [ChartDataCell](../../com.aspose.slides/chartdatacell)을 생성하고 컬렉션에 추가합니다. |
| [removeAt(int index)](#removeAt-int-) | 인덱스로 컬렉션에서 셀을 제거합니다. |
| [getCount()](#getCount--) | 컬렉션에 있는 셀 수를 가져옵니다. |
| [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 Java 이터레이터를 반환합니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getCellsAddress() {#getCellsAddress--}
```
public final String getCellsAddress()
```

워크북에 있는 셀 집합의 주소를 반환합니다.

**반환:**
java.lang.String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public final String getConcatenatedValuesFromCells()
```

모든 셀 문자열 값을 연결한 문자열을 반환합니다.

**반환:**
java.lang.String
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataCell get_Item(int index)
```

인덱스로 셀(IChartDataCell)을 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 셀의 인덱스. |

**반환:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - 데이터가 있는 셀.
### add(IChartDataCell cell) {#add-com.aspose.slides.IChartDataCell-}
```
public final void add(IChartDataCell cell)
```

새 셀을 컬렉션에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 추가할 새 셀. |

### add(Object value) {#add-java.lang.Object-}
```
public final void add(Object value)
```

지정된 값으로 [ChartDataCell](../../com.aspose.slides/chartdatacell)을 생성하고 컬렉션에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.Object | 값.

--------------------

이 메서드는 AUTO_DATA라는 이름의 워크시트를 추가하고 모든 값을 그곳에 삽입합니다. [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook)를 사용하여 셀 값을 추가하거나 편집하는 경우, 이 워크시트를 사용하지 않도록 하십시오. 이 메서드를 사용하여 추가되는 값의 최대 수는 16,711,680을 초과해서는 안 됩니다. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

인덱스로 컬렉션에서 셀을 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 제거할 셀의 인덱스. |

### getCount() {#getCount--}
```
public final int getCount()
```

컬렉션에 있는 셀 수를 가져옵니다. 읽기 전용 int.

**반환:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iterator()
```

컬렉션을 순회하는 열거자를 반환합니다.

**반환:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - 컬렉션을 순회하는 데 사용할 수 있는 IGenericEnumerator
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iteratorJava()
```

전체 컬렉션에 대한 Java 이터레이터를 반환합니다.

**반환:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - 전체 컬렉션에 대한 java.util.Iterator
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환:**
com.aspose.slides.IDOMObject
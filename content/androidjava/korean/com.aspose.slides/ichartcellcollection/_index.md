---
title: IChartCellCollection
second_title: Java API를 통한 Android용 Aspose.Slides 레퍼런스
description: 데이터가 포함된 셀들의 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ichartcellcollection/
---
**구현된 모든 인터페이스:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IChartCellCollection extends System.Collections.Generic.IGenericEnumerable<IChartDataCell>
```

데이터가 있는 셀들의 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | 워크북에 있는 셀 집합의 주소를 반환합니다. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | 모든 셀 문자열 값들을 연결한 문자열을 반환합니다. |
| [get_Item(int index)](#get-Item-int-) | 인덱스로 셀(IChartDataCell)을 반환합니다. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | 새로운 셀을 컬렉션에 추가합니다. |
| [add(Object value)](#add-java.lang.Object-) | 지정된 값으로 [IChartDataCell](../../com.aspose.slides/ichartdatacell)을 생성하고 컬렉션에 추가합니다. |
| [removeAt(int index)](#removeAt-int-) | 인덱스로 컬렉션에서 셀을 제거합니다. |
| [getCount()](#getCount--) | 컬렉션에 있는 셀의 수를 가져옵니다. |
### getCellsAddress() {#getCellsAddress--}
```
public abstract String getCellsAddress()
```

워크북에 있는 셀 집합의 주소를 반환합니다.

**반환값:**
java.lang.String - 워크북에 있는 셀 집합의 주소 String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public abstract String getConcatenatedValuesFromCells()
```

모든 셀 문자열 값들을 연결한 문자열.

**반환값:**
java.lang.String - 결과 문자열 String
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int index)
```

인덱스로 셀(IChartDataCell)을 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 셀의 인덱스. |

**반환값:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - 데이터가 있는 셀.
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract void add(IChartDataCell chartDataCell)
```

새로운 셀을 컬렉션에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 추가할 새 셀. |

### add(Object value) {#add-java.lang.Object-}
```
public abstract void add(Object value)
```

[IChartDataCell](../../com.aspose.slides/ichartdatacell)을 지정된 값으로 생성하고 컬렉션에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.Object | 값.

--------------------

이 메서드는 이름이 AUTO_DATA인 워크시트를 추가하고 모든 값을 그곳에 넣습니다. [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)를 사용하여 셀 값을 추가하거나 편집하는 경우, 해당 워크시트를 사용하지 않도록 주의하십시오. 이 메서드를 사용하여 추가된 값의 최대 개수는 16711680을 초과할 수 없습니다.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

인덱스로 컬렉션에서 셀을 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 제거할 셀의 인덱스. |

### getCount() {#getCount--}
```
public abstract int getCount()
```

컬렉션에 있는 셀의 수를 가져옵니다. 읽기 전용 int.

**반환값:**
int
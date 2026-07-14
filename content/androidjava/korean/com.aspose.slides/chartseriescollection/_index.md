---
title: ChartSeriesCollection
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 컬렉션을 나타냅니다
type: docs
url: /ko/com.aspose.slides/chartseriescollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
```
public class ChartSeriesCollection extends DomObject<ChartData> implements IChartSeriesCollection
```

컬렉션을 나타냅니다 [ChartSeries](../../com.aspose.slides/chartseries)
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스의 요소를 가져옵니다. |
| [size()](#size--) | 컬렉션에 있는 객체 수를 반환합니다. |
| [add(int type)](#add-int-) | 새 차트 시리즈를 생성하고 컬렉션에 추가합니다. |
| [insert(int index, int type)](#insert-int-int-) | 새 차트 시리즈를 생성하고 컬렉션에 삽입합니다. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | [ChartDataCell](../../com.aspose.slides/chartdatacell)에서 새로운 차트 시리즈를 생성하고 컬렉션에 추가합니다. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | [ChartCellCollection](../../com.aspose.slides/chartcellcollection)에서 새로운 차트 시리즈를 생성하고 컬렉션에 추가합니다. |
| [add(String name, int type)](#add-java.lang.String-int-) | 값에서 새로운 차트 시리즈를 생성하고 컬렉션에 추가합니다. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | 지정된 [ChartSeries](../../com.aspose.slides/chartseries)을 검색하고 전체 컬렉션에서 첫 번째 발생 위치의 0 기반 인덱스를 반환합니다. |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | 지정된 값을 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 컬렉션에서 지정된 위치에 저장된 ActiveX 컨트롤을 제거합니다. |
| [clear()](#clear--) | 컬렉션의 모든 컨트롤을 제거합니다. |
| [iterator()](#iterator--) | 컬렉션을 반복하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java 반복자를 반환합니다. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 전체 컬렉션을 지정된 배열에 복사합니다. |
| [isSynchronized()](#isSynchronized--) | 컬렉션에 대한 접근이 동기화(스레드 안전)되어 있는지 여부를 나타내는 값을 반환합니다. |
| [getSyncRoot()](#getSyncRoot--) | 동기화 루트를 반환합니다. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```


지정된 인덱스의 요소를 가져옵니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[IChartSeries](../../com.aspose.slides/ichartseries) - 지정된 인덱스의 요소.
### size() {#size--}
```
public final int size()
```


컬렉션에 있는 객체 수를 반환합니다. 읽기 전용 int.

**반환값:**
int
### add(int type) {#add-int-}
```
public final IChartSeries add(int type)
```


새 차트 시리즈를 생성하고 컬렉션에 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| type | int | 시리즈 유형 |

**반환값:**
[IChartSeries](../../com.aspose.slides/ichartseries) - 새 차트 시리즈.
### insert(int index, int type) {#insert-int-int-}
```
public final IChartSeries insert(int index, int type)
```


새 차트 시리즈를 생성하고 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| index | int |  |
| type | int |  |

**반환값:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public final IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```


[ChartDataCell](../../com.aspose.slides/chartdatacell)에서 새로운 차트 시리즈를 생성하고 컬렉션에 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 시리즈 이름을 포함하는 셀 |
| type | int | 시리즈 유형을 설정하는 타입

--------------------

컬렉션에 이미 동일한 셀에서 만든 차트 시리즈가 있는 경우 메서드는 아무 것도 추가하지 않으며 해당 인덱스를 반환합니다. |

**반환값:**
[IChartSeries](../../com.aspose.slides/ichartseries) - 추가된 차트 시리즈 또는 이미 컬렉션에 존재하는 시리즈.
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public final IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```


[ChartCellCollection](../../com.aspose.slides/chartcellcollection)에서 새로운 차트 시리즈를 생성하고 컬렉션에 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | 시리즈 이름을 포함하는 셀들 |
| type | int | 시리즈 유형을 설정하는 타입

--------------------

컬렉션에 이미 동일한 셀에서 만든 차트 시리즈가 있는 경우 메서드는 아무 것도 추가하지 않으며 해당 인덱스를 반환합니다. |

**반환값:**
[IChartSeries](../../com.aspose.slides/ichartseries) - 추가된 차트 시리즈 또는 이미 컬렉션에 존재하는 시리즈.
### add(String name, int type) {#add-java.lang.String-int-}
```
public final IChartSeries add(String name, int type)
```


값에서 새 차트 시리즈를 생성하고 컬렉션에 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 시리즈 이름 |
| type | int | 시리즈 유형을 설정하는 타입 |

**반환값:**
[IChartSeries](../../com.aspose.slides/ichartseries) - 추가된 차트 시리즈.
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public final int indexOf(IChartSeries value)
```


지정된 [ChartSeries](../../com.aspose.slides/chartseries)을 검색하고 전체 컬렉션에서 첫 번째 발생 위치의 0 기반 인덱스를 반환합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | 차트 시리즈 값 |

**반환값:**
int - 값이 전체 CollectionBase 내에서 처음 나타나는 위치의 0 기반 인덱스(찾으면); 없으면 -1.
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public final void remove(IChartSeries value)
```


지정된 값을 제거합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | 값 |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


컬렉션에서 지정된 위치에 저장된 ActiveX 컨트롤을 제거합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| index | int | 제거할 컨트롤의 인덱스 |
### clear() {#clear--}
```
public final void clear()
```


컬렉션의 모든 컨트롤을 제거합니다.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iterator()
```


컬렉션을 반복하는 열거자를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - 컬렉션을 반복하는 데 사용할 수 있는 IGenericEnumerator
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iteratorJava()
```


전체 컬렉션에 대한 java 반복자를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - 전체 컬렉션에 대한 java.util.Iterator
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


전체 컬렉션을 지정된 배열에 복사합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 대상 배열 |
| index | int | 대상 배열에서의 인덱스 |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


컬렉션에 대한 접근이 동기화(스레드 안전)되어 있는지 여부를 나타내는 값을 반환합니다. 읽기 전용 boolean.

**반환값:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


동기화 루트를 반환합니다. 읽기 전용 Object.

**반환값:**
java.lang.Object
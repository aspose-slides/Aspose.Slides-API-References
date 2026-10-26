---
title: ChartSeriesCollection
second_title: Aspose.Slides for Java API 레퍼런스
description: 컬렉션을 나타냅니다
type: docs
url: /ko/com.aspose.slides/chartseriescollection/
---
**상속:**
java.lang.Object, com.aspose.slides.DomObject

**구현된 모든 인터페이스:**
[com.aspose.slides.IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
```
public class ChartSeriesCollection extends DomObject<ChartData> implements IChartSeriesCollection
```

컬렉션을 나타냅니다 [ChartSeries](../../com.aspose.slides/chartseries)
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에 있는 요소를 가져옵니다. |
| [size()](#size--) | 컬렉션에 있는 객체 수를 반환합니다. |
| [add(int type)](#add-int-) | 새 차트 시리즈를 만들고 컬렉션에 추가합니다. |
| [insert(int index, int type)](#insert-int-int-) | 새 차트 시리즈를 만들고 컬렉션에 삽입합니다. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | 새 차트 시리즈를 [ChartDataCell](../../com.aspose.slides/chartdatacell)에서 만들어 컬렉션에 추가합니다. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | 새 차트 시리즈를 [ChartCellCollection](../../com.aspose.slides/chartcellcollection)에서 만들어 컬렉션에 추가합니다. |
| [add(String name, int type)](#add-java.lang.String-int-) | 값에서 새 차트 시리즈를 만들어 컬렉션에 추가합니다. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | 지정된 [ChartSeries](../../com.aspose.slides/chartseries)를 검색하고 전체 컬렉션에서 첫 번째 발생의 0 기반 인덱스를 반환합니다. |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | 지정된 값을 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 지정된 위치에 저장된 ActiveX 컨트롤을 컬렉션에서 제거합니다. |
| [clear()](#clear--) | 컬렉션에서 모든 컨트롤을 제거합니다. |
| [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java 이터레이터를 반환합니다. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 전체 컬렉션을 지정된 배열에 복사합니다. |
| [isSynchronized()](#isSynchronized--) | 컬렉션 접근이 동기화(스레드 안전)되는지 여부를 나타내는 값을 반환합니다. |
| [getSyncRoot()](#getSyncRoot--) | 동기화 루트를 반환합니다. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

지정된 인덱스에 있는 요소를 가져옵니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[IChartSeries](../../com.aspose.slides/ichartseries) - 지정된 인덱스에 있는 요소.

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

새 차트 시리즈를 만들고 컬렉션에 추가합니다.

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

새 차트 시리즈를 만들고 컬렉션에 삽입합니다.

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

새 차트 시리즈를 [ChartDataCell](../../com.aspose.slides/chartdatacell)에서 만들어 컬렉션에 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 시리즈 이름을 포함하는 셀. |
| type | int | 시리즈 유형을 설정하는 유형 |

--------------------

동일한 셀에서 생성된 차트 시리즈가 이미 컬렉션에 있으면 메서드는 아무 것도 추가하지 않고 해당 인덱스를 반환합니다. |

**반환값:**
[IChartSeries](../../com.aspose.slides/ichartseries) - 컬렉션에 추가된 차트 시리즈 또는 이미 존재하는 시리즈.

### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public final IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

새 차트 시리즈를 [ChartCellCollection](../../com.aspose.slides/chartcellcollection)에서 만들어 컬렉션에 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | 시리즈 이름을 포함하는 셀 컬렉션. |
| type | int | 시리즈 유형을 설정하는 유형 |

--------------------

동일한 셀에서 생성된 차트 시리즈가 이미 컬렉션에 있으면 메서드는 아무 것도 추가하지 않고 해당 인덱스를 반환합니다. |

**반환값:**
[IChartSeries](../../com.aspose.slides/ichartseries) - 컬렉션에 추가된 차트 시리즈 또는 이미 존재하는 시리즈.

### add(String name, int type) {#add-java.lang.String-int-}
```
public final IChartSeries add(String name, int type)
```

새 차트 시리즈를 값에서 만들어 컬렉션에 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 시리즈 이름. |
| type | int | 시리즈 유형을 설정하는 유형 |

**반환값:**
[IChartSeries](../../com.aspose.slides/ichartseries) - 추가된 차트 시리즈.

### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public final int indexOf(IChartSeries value)
```

지정된 [ChartSeries](../../com.aspose.slides/chartseries)를 검색하고 전체 컬렉션에서 첫 번째 발생의 0 기반 인덱스를 반환합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | 차트 시리즈 값. |

**반환값:**
int - 값이 전체 CollectionBase에서 첫 번째로 나타나는 0 기반 인덱스, 찾지 못하면 -1.

### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public final void remove(IChartSeries value)
```

지정된 값을 제거합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | 값. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

지정된 위치에 저장된 ActiveX 컨트롤을 컬렉션에서 제거합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| index | int | 제거할 컨트롤의 인덱스. |

### clear() {#clear--}
```
public final void clear()
```

컬렉션에서 모든 컨트롤을 제거합니다.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iterator()
```

컬렉션을 순회하는 열거자를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - 컬렉션을 순회하는 데 사용할 수 있는 IGenericEnumerator.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iteratorJava()
```

전체 컬렉션에 대한 java 이터레이터를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - 전체 컬렉션에 대한 java.util.Iterator.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

전체 컬렉션을 지정된 배열에 복사합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 대상 배열 |
| index | int | 대상 배열의 인덱스. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

컬렉션 접근이 동기화(스레드 안전)되는지 여부를 나타내는 값을 반환합니다. 읽기 전용 boolean.

**반환값:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

동기화 루트를 반환합니다. 읽기 전용 Object.

**반환값:**
java.lang.Object
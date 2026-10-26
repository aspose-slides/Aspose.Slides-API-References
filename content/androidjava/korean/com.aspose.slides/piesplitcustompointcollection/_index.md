---
title: PieSplitCustomPointCollection
second_title: Aspose.Slides for Android을 통한 Java API 레퍼런스
description: 사용자 정의 분할을 사용한 바-오브-파이 또는 파이-오브-파이 차트의 분할 지점을 위한 포인트 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/piesplitcustompointcollection/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
[com.aspose.slides.IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)  
```
public class PieSplitCustomPointCollection implements IPieSplitCustomPointCollection
```

사용자 정의 분할을 가진 바-오브-파이 또는 파이-오브-파이 차트의 분할 지점을 위한 포인트 컬렉션을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에 대한 차트 데이터 포인트를 반환합니다. |
| [add(int dataPointIndex)](#add-int-) | 부모 시리즈 포인트 컬렉션에서 해당 인덱스로 데이터 포인트를 추가합니다. |
| [addItem(IChartDataPoint dataPoint)](#addItem-com.aspose.slides.IChartDataPoint-) | 컬렉션에 데이터 포인트를 추가합니다. |
| [removeItem(IChartDataPoint dataPoint)](#removeItem-com.aspose.slides.IChartDataPoint-) | 컬렉션에서 항목을 제거합니다. |
| [remove(int dataPointIndex)](#remove-int-) | 부모 시리즈 포인트 컬렉션에서 해당 인덱스로 컬렉션에서 항목을 제거합니다. |
| [clear()](#clear--) | 모든 항목을 [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 제거합니다. |
| [containsItem(IChartDataPoint item)](#containsItem-com.aspose.slides.IChartDataPoint-) | [IGenericCollection](../../com.aspose.slides/igenericcollection)에 특정 값이 포함되어 있는지 확인합니다. |
| [copyToTArray(IChartDataPoint[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IChartDataPoint---int-) | 특정 배열 인덱스에서 시작하여 [IGenericCollection](../../com.aspose.slides/igenericcollection)의 요소를 배열에 복사합니다. |
| [size()](#size--) | 차트 데이터 포인트의 개수를 반환하거나 설정합니다. |
| [isReadOnly()](#isReadOnly--) | [IGenericCollection](../../com.aspose.slides/igenericcollection)가 읽기 전용인지 여부를 나타내는 값을 가져옵니다. |
| [isSynchronized()](#isSynchronized--) | 컬렉션에 대한 접근이 동기화(스레드 안전)되어 있는지 여부를 나타내는 값을 반환합니다. |
| [getSyncRoot()](#getSyncRoot--) | 동기화 루트를 반환합니다. |
| [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java iterator를 반환합니다. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

지정된 인덱스에 대한 차트 데이터 포인트를 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 인덱스. |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 차트 데이터 포인트.

### add(int dataPointIndex) {#add-int-}
```
public final void add(int dataPointIndex)
```

부모 시리즈 포인트 컬렉션에서 데이터 포인트의 인덱스로 데이터 포인트를 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| dataPointIndex | int | 부모 시리즈 포인트 컬렉션에서 데이터 포인트의 인덱스. |

### addItem(IChartDataPoint dataPoint) {#addItem-com.aspose.slides.IChartDataPoint-}
```
public void addItem(IChartDataPoint dataPoint)
```

컬렉션에 데이터 포인트를 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | 컬렉션에 추가할 데이터 포인트. |

### removeItem(IChartDataPoint dataPoint) {#removeItem-com.aspose.slides.IChartDataPoint-}
```
public boolean removeItem(IChartDataPoint dataPoint)
```

컬렉션에서 항목을 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | 제거할 데이터 포인트. |

**반환값:**
boolean - 항목이 성공적으로 제거되면 true, 그렇지 않으면 false. 이 메서드는 항목을 System.Collections.Generic.List{T}에서 찾을 수 없을 경우에도 false를 반환합니다.

### remove(int dataPointIndex) {#remove-int-}
```
public final void remove(int dataPointIndex)
```

부모 시리즈 포인트 컬렉션에서 해당 인덱스로 컬렉션에서 항목을 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| dataPointIndex | int | 부모 시리즈 포인트 컬렉션에서 데이터 포인트의 인덱스. |

### clear() {#clear--}
```
public final void clear()
```

[IGenericCollection](../../com.aspose.slides/igenericcollection)에서 모든 항목을 제거합니다.

### containsItem(IChartDataPoint item) {#containsItem-com.aspose.slides.IChartDataPoint-}
```
public boolean containsItem(IChartDataPoint item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection)에 특정 값이 포함되어 있는지 확인합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| item | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 찾을 객체. |

**반환값:**
boolean - 항목이 [IGenericCollection](../../com.aspose.slides/igenericcollection)에 있으면 true, 그렇지 않으면 false.

### copyToTArray(IChartDataPoint[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IChartDataPoint---int-}
```
public void copyToTArray(IChartDataPoint[] array, int arrayIndex)
```

특정 배열 인덱스에서 시작하여 [IGenericCollection](../../com.aspose.slides/igenericcollection)의 요소를 배열에 복사합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| array | [IChartDataPoint\[\]](../../com.aspose.slides/ichartdatapoint) | [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 복사된 요소들의 대상이 되는 1차원 Array입니다. Array는 0 기반 인덱싱이어야 합니다. |
| arrayIndex | int | 복사가 시작되는 배열의 0 기반 인덱스. |

### size() {#size--}
```
public final int size()
```

차트 데이터 포인트의 개수를 반환하거나 설정합니다. 읽기 전용 int.

**반환값:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

[IGenericCollection](../../com.aspose.slides/igenericcollection)가 읽기 전용인지 여부를 나타내는 값을 가져옵니다. 읽기 전용 boolean.

**반환값:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection)가 읽기 전용이면 true, 그렇지 않으면 false.

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

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

컬렉션을 순회하는 열거자를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - 컬렉션을 순회하는 데 사용할 수 있는 IGenericEnumerator.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

전체 컬렉션에 대한 java iterator를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - 전체 컬렉션에 대한 java.util.Iterator.
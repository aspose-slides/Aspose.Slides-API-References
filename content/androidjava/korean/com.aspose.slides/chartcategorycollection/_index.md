---
title: ChartCategoryCollection
second_title: Android용 Aspose.Slides Java API 참조
description: 컬렉션을 나타냅니다
type: docs
url: /ko/com.aspose.slides/chartcategorycollection/
---
**상속:**  
java.lang.Object, com.aspose.slides.DomObject

**구현된 모든 인터페이스:**  
[com.aspose.slides.IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)  
```
public class ChartCategoryCollection extends DomObject<ChartData> implements IChartCategoryCollection
```

[ChartCategory](../../com.aspose.slides/chartcategory) 컬렉션을 나타냅니다  
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스의 요소를 가져옵니다. |
| [getUseCells()](#getUseCells--) | true이면 워크시트를 카테고리 저장에 사용합니다(이 경우 다단계 카테고리를 지원합니다). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | true이면 워크시트를 카테고리 저장에 사용합니다(이 경우 다단계 카테고리를 지원합니다). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | 사용된 카테고리 그룹화 레벨 수를 반환합니다. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | 컬렉션에 카테고리가 존재하면 반환합니다. |
| [add(Object value)](#add-java.lang.Object-) | 값으로부터 새로운 [ChartCategory](../../com.aspose.slides/chartcategory)를 생성하고 컬렉션에 추가합니다. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | 지정된 [ChartCategory](../../com.aspose.slides/chartcategory)를 검색하고 전체 컬렉션에서 첫 번째 발생의 0 기반 인덱스를 반환합니다. |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | 지정된 값을 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 지정된 인덱스의 요소를 제거합니다. |
| [clear()](#clear--) | 컬렉션의 모든 요소를 제거합니다. |
| [iterator()](#iterator--) | 컬렉션을 반복하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java 이터레이터를 반환합니다. |
| [size()](#size--) | 컬렉션의 요소 개수를 반환합니다. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 컬렉션의 모든 요소를 지정된 배열에 복사합니다. |
| [isSynchronized()](#isSynchronized--) | List에 대한 접근이 동기화(스레드 안전)되는지 여부를 나타내는 값을 반환합니다. |
| [getSyncRoot()](#getSyncRoot--) | 컬렉션 접근을 동기화하는 데 사용할 수 있는 객체를 반환합니다. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartCategory get_Item(int index)
```


지정된 인덱스의 요소를 가져옵니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - 지정된 인덱스의 요소.

### getUseCells() {#getUseCells--}
```
public final boolean getUseCells()
```


true이면 워크시트를 카테고리 저장에 사용합니다(이 경우 다단계 카테고리를 지원합니다). false이면 워크시트가 값을 저장하는 데 사용되지 않습니다(이 경우 다단계 카테고리를 지원하지 않습니다). 읽기/쓰기 boolean.

**반환값:**
boolean

### setUseCells(boolean value) {#setUseCells-boolean-}
```
public final void setUseCells(boolean value)
```


true이면 워크시트를 카테고리 저장에 사용합니다(이 경우 다단계 카테고리를 지원합니다). false이면 워크시트가 값을 저장하는 데 사용되지 않습니다(이 경우 다단계 카테고리를 지원하지 않습니다). 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public final int getGroupingLevelCount()
```


사용된 카테고리 그룹화 레벨 수를 반환합니다. 다단계 카테고리의 경우 1보다 큽니다. 읽기 전용 int.

**반환값:**
int

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public final IChartCategory add(IChartDataCell chartDataCell)
```


컬렉션에 카테고리가 존재하면 반환합니다. 그렇지 않으면 [IChartDataCell](../../com.aspose.slides/ichartdatacell)에서 새로운 차트 카테고리를 생성하고 컬렉션에 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 차트 카테고리를 생성하는 데 사용되는 셀. |

**반환값:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - 추가된 또는 기존 카테고리.

### add(Object value) {#add-java.lang.Object-}
```
public final IChartCategory add(Object value)
```


값으로부터 새로운 [ChartCategory](../../com.aspose.slides/chartcategory)를 생성하고 컬렉션에 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | java.lang.Object | 값. |

---  

이 메서드는 AUTO_DATA라는 이름의 워크시트를 추가하고 모든 값을 그곳에 추가합니다. [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook)를 사용하여 셀 값을 추가하거나 편집하는 경우, 이 워크시트를 사용하지 않도록 하세요. 이 메서드를 사용하여 추가된 값의 최대 개수는 16711680을 초과해서는 안 됩니다. |

**반환값:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - 추가된 [IChartCategory](../../com.aspose.slides/ichartcategory).

### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public final int indexOf(IChartCategory value)
```


지정된 [ChartCategory](../../com.aspose.slides/chartcategory)를 검색하고 전체 컬렉션에서 첫 번째 발생의 0 기반 인덱스를 반환합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | 차트 카테고리. |

**반환값:**
int - 값이 전체 CollectionBase 내에서 첫 번째로 발생한 0 기반 인덱스(발견된 경우); 그렇지 않으면 -1.

### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public final void remove(IChartCategory value)
```


지정된 값을 제거합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | 값. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


주어진 인덱스의 요소를 제거합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| index | int | 제거할 카테고리의 인덱스. |

### clear() {#clear--}
```
public final void clear()
```


컬렉션의 모든 요소를 제거합니다.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iterator()
```


컬렉션을 반복하는 열거자를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - 컬렉션을 반복하는 데 사용할 수 있는 IGenericEnumerator.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iteratorJava()
```


전체 컬렉션에 대한 java 이터레이터를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - 전체 컬렉션에 대한 java.util.Iterator.

### size() {#size--}
```
public final int size()
```


컬렉션의 요소 개수를 반환합니다. 읽기 전용 int.

**반환값:**
int

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


컬렉션의 모든 요소를 지정된 배열에 복사합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 대상 배열. |
| index | int | 배열에서 시작 인덱스. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


List에 대한 접근이 동기화(스레드 안전)되는지 여부를 나타내는 값을 반환합니다. 읽기 전용 boolean.

**반환값:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


컬렉션 접근을 동기화하는 데 사용할 수 있는 객체를 반환합니다. 읽기 전용 Object.

동기화 루트를 반환합니다. 읽기 전용 Object.

**반환값:**
java.lang.Object
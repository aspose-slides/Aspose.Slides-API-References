---
title: BehaviorPropertyCollection
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 효과 동작에 대한 타이밍 속성을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/behaviorpropertycollection/
---
**상속:**
java.lang.Object

**모든 구현된 인터페이스:**
[com.aspose.slides.IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
```
public class BehaviorPropertyCollection implements IBehaviorPropertyCollection
```

효과 동작에 대한 타이밍 속성을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [size()](#size--) | 컬렉션에 저장된 속성의 수를 반환합니다. |
| [isReadOnly()](#isReadOnly--) | [IGenericCollection](../../com.aspose.slides/igenericcollection)가 읽기 전용인지 여부를 나타내는 값을 가져옵니다. |
| [add(IBehaviorProperty item)](#add-com.aspose.slides.IBehaviorProperty-) | 컬렉션에 새 속성을 추가합니다. |
| [add(String propertyValue)](#add-java.lang.String-) | 컬렉션에 새 속성을 추가합니다. |
| [indexOf(IBehaviorProperty item)](#indexOf-com.aspose.slides.IBehaviorProperty-) | 리스트에서 특정 항목의 인덱스를 결정합니다. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | 리스트에서 속성 값으로 특정 항목의 인덱스를 결정합니다. |
| [insert(int index, IBehaviorProperty item)](#insert-int-com.aspose.slides.IBehaviorProperty-) | 지정된 인덱스에 새 속성을 컬렉션에 삽입합니다. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | 지정된 인덱스에 지정된 속성 값을 가진 새 속성을 컬렉션에 삽입합니다. |
| [copyTo(IBehaviorProperty[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehaviorProperty---int-) | [IGenericCollection](../../com.aspose.slides/igenericcollection)의 요소를 특정 배열 인덱스에서 시작하여 Array에 복사합니다. |
| [remove(IBehaviorProperty item)](#remove-com.aspose.slides.IBehaviorProperty-) | 컬렉션에서 지정된 속성을 제거합니다. |
| [remove(String propertyValue)](#remove-java.lang.String-) | 컬렉션에서 지정된 속성을 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 지정된 인덱스에서 속성을 제거합니다. |
| [clear()](#clear--) | 컬렉션에서 모든 속성을 제거합니다. |
| [contains(IBehaviorProperty item)](#contains-com.aspose.slides.IBehaviorProperty-) | [IGenericCollection](../../com.aspose.slides/igenericcollection)에 특정 값이 포함되어 있는지 판단합니다. |
| [contains(String propertyValue)](#contains-java.lang.String-) | [IGenericCollection](../../com.aspose.slides/igenericcollection)에 특정 값이 포함되어 있는지 판단합니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에 있는 속성을 반환합니다. |
| [set_Item(int index, IBehaviorProperty value)](#set-Item-int-com.aspose.slides.IBehaviorProperty-) | 지정된 인덱스에 속성을 설정합니다. |
| [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
| [indexOfItem(IBehaviorProperty item)](#indexOfItem-com.aspose.slides.IBehaviorProperty-) |  |
| [insertItem(int index, IBehaviorProperty item)](#insertItem-int-com.aspose.slides.IBehaviorProperty-) |  |
| [addItem(IBehaviorProperty item)](#addItem-com.aspose.slides.IBehaviorProperty-) |  |
| [containsItem(IBehaviorProperty item)](#containsItem-com.aspose.slides.IBehaviorProperty-) |  |
| [copyToTArray(IBehaviorProperty[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IBehaviorProperty---int-) |  |
| [removeItem(IBehaviorProperty item)](#removeItem-com.aspose.slides.IBehaviorProperty-) |  |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java 이터레이터를 반환합니다. |
### size() {#size--}
```
public final int size()
```


컬렉션에 저장된 속성의 수를 반환합니다. 읽기 전용 int.

**반환:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


[IGenericCollection](../../com.aspose.slides/igenericcollection)가 읽기 전용인지 여부를 나타내는 값을 가져옵니다. 읽기 전용 boolean.

**반환:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection)가 읽기 전용이면 true; 그렇지 않으면 false.
### add(IBehaviorProperty item) {#add-com.aspose.slides.IBehaviorProperty-}
```
public final void add(IBehaviorProperty item)
```


컬렉션에 새 속성을 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | 추가할 속성. |

### add(String propertyValue) {#add-java.lang.String-}
```
public final void add(String propertyValue)
```


컬렉션에 새 속성을 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| propertyValue | java.lang.String | 추가할 속성의 값. |

### indexOf(IBehaviorProperty item) {#indexOf-com.aspose.slides.IBehaviorProperty-}
```
public final int indexOf(IBehaviorProperty item)
```


리스트에서 특정 항목의 인덱스를 결정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | 리스트에서 찾을 객체. |

**반환:**
int - 항목이 리스트에서 발견된 경우 그 인덱스; 그렇지 않으면 -1.
### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public final int indexOf(String propertyValue)
```


리스트에서 속성 값으로 특정 항목의 인덱스를 결정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| propertyValue | java.lang.String | 속성 값 |

**반환:**
int - 지정된 값의 속성 인덱스
### insert(int index, IBehaviorProperty item) {#insert-int-com.aspose.slides.IBehaviorProperty-}
```
public final void insert(int index, IBehaviorProperty item)
```


지정된 인덱스에 새 속성을 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 새 속성을 삽입할 인덱스. |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | 추가할 속성. |

### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public final void insert(int index, String propertyValue)
```


지정된 인덱스에 지정된 속성 값을 가진 새 속성을 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 새 속성을 삽입할 인덱스. |
| propertyValue | java.lang.String | 추가할 속성의 값. |

### copyTo(IBehaviorProperty[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehaviorProperty---int-}
```
public final void copyTo(IBehaviorProperty[] array, int arrayIndex)
```


[IGenericCollection](../../com.aspose.slides/igenericcollection)의 요소를 특정 배열 인덱스에서 시작하여 배열에 복사합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) | [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 복사된 요소의 대상이 되는 1차원 배열입니다. 배열은 0 기반 인덱스를 가져야 합니다. |
| arrayIndex | int | 복사가 시작되는 배열의 0 기반 인덱스. |

### remove(IBehaviorProperty item) {#remove-com.aspose.slides.IBehaviorProperty-}
```
public final boolean remove(IBehaviorProperty item)
```


컬렉션에서 지정된 속성을 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | 제거할 속성. |

**반환:**
boolean
### remove(String propertyValue) {#remove-java.lang.String-}
```
public final boolean remove(String propertyValue)
```


컬렉션에서 지정된 속성을 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| propertyValue | java.lang.String | 제거할 속성의 값. |

**반환:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


지정된 인덱스에서 속성을 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 삭제될 속성의 인덱스. |

### clear() {#clear--}
```
public final void clear()
```


컬렉션에서 모든 속성을 제거합니다.

### contains(IBehaviorProperty item) {#contains-com.aspose.slides.IBehaviorProperty-}
```
public final boolean contains(IBehaviorProperty item)
```


[IGenericCollection](../../com.aspose.slides/igenericcollection)에 특정 값이 포함되어 있는지 판단합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 찾을 속성. |

**반환:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection)에 항목이 있으면 true; 그렇지 않으면 false.
### contains(String propertyValue) {#contains-java.lang.String-}
```
public final boolean contains(String propertyValue)
```


[IGenericCollection](../../com.aspose.slides/igenericcollection)에 특정 값이 포함되어 있는지 판단합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| propertyValue | java.lang.String | [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 찾을 속성 값. |

**반환:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection)에 propertyValue가 있으면 true; 그렇지 않으면 false.
### get_Item(int index) {#get-Item-int-}
```
public final IBehaviorProperty get_Item(int index)
```


지정된 인덱스에 있는 속성을 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 반환할 속성의 인덱스. |

**반환:**
[IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) - 애니메이션 동작 속성.
### set_Item(int index, IBehaviorProperty value) {#set-Item-int-com.aspose.slides.IBehaviorProperty-}
```
public final void set_Item(int index, IBehaviorProperty value)
```


지정된 인덱스에 속성을 설정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 반환할 속성의 인덱스. |
| value | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iterator()
```


컬렉션을 순회하는 열거자를 반환합니다.

**반환:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - 컬렉션을 순회하는 데 사용할 수 있는 IGenericEnumerator.
### indexOfItem(IBehaviorProperty item) {#indexOfItem-com.aspose.slides.IBehaviorProperty-}
```
public int indexOfItem(IBehaviorProperty item)
```




**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**반환:**
int
### insertItem(int index, IBehaviorProperty item) {#insertItem-int-com.aspose.slides.IBehaviorProperty-}
```
public void insertItem(int index, IBehaviorProperty item)
```




**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### addItem(IBehaviorProperty item) {#addItem-com.aspose.slides.IBehaviorProperty-}
```
public void addItem(IBehaviorProperty item)
```




**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### containsItem(IBehaviorProperty item) {#containsItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean containsItem(IBehaviorProperty item)
```




**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**반환:**
boolean
### copyToTArray(IBehaviorProperty[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IBehaviorProperty---int-}
```
public void copyToTArray(IBehaviorProperty[] array, int arrayIndex)
```




**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) |  |
| arrayIndex | int |  |

### removeItem(IBehaviorProperty item) {#removeItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean removeItem(IBehaviorProperty item)
```




**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**반환:**
boolean
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iteratorJava()
```


전체 컬렉션에 대한 java 이터레이터를 반환합니다.

**반환:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - 전체 컬렉션에 대한 java.util.Iterator.
---
title: BehaviorCollection
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 동작 효과의 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/behaviorcollection/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
[com.aspose.slides.IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)  
```
public class BehaviorCollection implements IBehaviorCollection
```

동작 효과의 컬렉션을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getCount()](#getCount--) | 컬렉션에 있는 동작 수를 반환합니다. |
| [isReadOnly()](#isReadOnly--) | [IGenericCollection](../../com.aspose.slides/igenericcollection)가 읽기 전용인지 여부를 나타내는 값을 가져옵니다. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | 컬렉션에 새 동작을 추가합니다. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | 목록에서 특정 항목의 인덱스를 결정합니다. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | 지정된 인덱스에 새 동작을 삽입합니다. |
| [copyTo(IBehavior[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehavior---int-) | [IGenericCollection](../../com.aspose.slides/igenericcollection)의 요소를 지정된 배열 인덱스부터 배열에 복사합니다. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | 컬렉션에서 지정된 동작을 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 지정된 인덱스에서 컬렉션의 동작을 제거합니다. |
| [clear()](#clear--) | 컬렉션에서 모든 동작을 제거합니다. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | [IGenericCollection](../../com.aspose.slides/igenericcollection)에 특정 값이 포함되는지 여부를 결정합니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에서 동작을 반환합니다. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | 지정된 인덱스에 동작을 설정합니다. |
| [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java 이터레이터를 반환합니다. |

### getCount() {#getCount--}
```
public final int getCount()
```

컬렉션에 있는 동작 수를 반환합니다. 읽기 전용 int.

**반환값:**  
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

[IGenericCollection](../../com.aspose.slides/igenericcollection)가 읽기 전용인지 여부를 나타내는 값을 가져옵니다. 읽기 전용 boolean.

**반환값:**  
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection)가 읽기 전용이면 true; 그렇지 않으면 false.

### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public final void add(IBehavior item)
```

컬렉션에 새 동작을 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | 추가할 동작. |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public final int indexOf(IBehavior item)
```

목록에서 특정 항목의 인덱스를 결정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | 목록에서 찾을 객체. |

**반환값:**  
int - 목록에서 항목을 찾으면 해당 인덱스; 그렇지 않으면 -1.

### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public final void insert(int index, IBehavior item)
```

지정된 인덱스에 새 동작을 삽입합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 새 동작을 삽입할 인덱스. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | 삽입할 동작. |

### copyTo(IBehavior[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehavior---int-}
```
public final void copyTo(IBehavior[] array, int arrayIndex)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection)의 요소를 지정된 배열 인덱스부터 배열에 복사합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| array | [IBehavior\[\]](../../com.aspose.slides/ibehavior) | 복사된 요소가 저장되는 대상 1차원 배열. [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 복사된 요소가 들어갑니다. 배열은 0부터 인덱싱되어야 합니다. |
| arrayIndex | int | 복사가 시작되는 배열의 0 기반 인덱스. |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public final boolean remove(IBehavior item)
```

컬렉션에서 지정된 동작을 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | 제거할 동작. |

**반환값:**  
boolean

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

지정된 인덱스에서 컬렉션의 동작을 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 제거할 동작의 인덱스. |

### clear() {#clear--}
```
public final void clear()
```

컬렉션에서 모든 동작을 제거합니다.

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public final boolean contains(IBehavior item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection)에 특정 값이 포함되는지 여부를 결정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 찾을 객체. |

**반환값:**  
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 항목을 찾으면 true; 그렇지 않으면 false.

### get_Item(int index) {#get-Item-int-}
```
public final IBehavior get_Item(int index)
```

지정된 인덱스에서 동작을 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 반환할 동작의 인덱스. |

**반환값:**  
[IBehavior](../../com.aspose.slides/ibehavior) - 애니메이션 동작.

### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public final void set_Item(int index, IBehavior value)
```

지정된 인덱스에 동작을 설정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 설정할 동작의 인덱스. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iterator()
```

컬렉션을 순회하는 열거자를 반환합니다.

**반환값:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - 컬렉션을 순회하는 데 사용할 수 있는 IGenericEnumerator.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iteratorJava()
```

전체 컬렉션에 대한 java 이터레이터를 반환합니다.

**반환값:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - 전체 컬렉션에 대한 java.util.Iterator.
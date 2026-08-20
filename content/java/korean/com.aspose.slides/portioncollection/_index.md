---
title: PortionCollection
second_title: Aspose.Slides Java API 레퍼런스
description: 부분의 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/portioncollection/
---
**상속:**  
java.lang.Object, com.aspose.slides.DomObject

**구현된 모든 인터페이스:**  
[com.aspose.slides.IPortionCollection](../../com.aspose.slides/iportioncollection)  
```
public final class PortionCollection extends DomObject<Paragraph> implements IPortionCollection
```

포션 컬렉션을 나타냅니다.
## 메서드

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | 컬렉션에 실제로 포함된 요소의 수를 가져옵니다. |
| [isReadOnly()](#isReadOnly--) | [IGenericCollection](../../com.aspose.slides/igenericcollection)이(가) 읽기 전용인지 여부를 나타내는 값을 가져옵니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스의 요소를 가져옵니다. |
| [set_Item(int index, IPortion value)](#set-Item-int-com.aspose.slides.IPortion-) | 지정된 인덱스의 요소를 가져옵니다. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | 포션을 컬렉션의 끝에 추가합니다. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | 리스트에서 특정 항목의 인덱스를 결정합니다. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | 지정된 인덱스에 포션을 컬렉션에 삽입합니다. |
| [clear()](#clear--) | 컬렉션의 모든 요소를 제거합니다. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | [IGenericCollection](../../com.aspose.slides/igenericcollection)에 특정 값이 포함되어 있는지 확인합니다. |
| [copyTo(IPortion[] array, int arrayIndex)](#copyTo-com.aspose.slides.IPortion---int-) | [IGenericCollection](../../com.aspose.slides/igenericcollection)의 요소를 지정된 배열 인덱스부터 배열에 복사합니다. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 특정 객체의 첫 번째 발생을 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 컬렉션에서 지정된 인덱스의 요소를 제거합니다. |
| [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java 이터레이터를 반환합니다. |

### getCount() {#getCount--}
```
public final int getCount()
```

컬렉션에 실제로 포함된 요소의 수를 가져옵니다. 읽기 전용 int.

**반환값:**  
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

[IGenericCollection](../../com.aspose.slides/igenericcollection)이(가) 읽기 전용인지 여부를 나타내는 값을 가져옵니다. 읽기 전용 boolean.

**반환값:**  
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection)이 읽기 전용이면 true; 그렇지 않으면 false.

### get_Item(int index) {#get-Item-int-}
```
public final IPortion get_Item(int index)
```

지정된 인덱스의 요소를 가져옵니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**  
[IPortion](../../com.aspose.slides/iportion)

### set_Item(int index, IPortion value) {#set-Item-int-com.aspose.slides.IPortion-}
```
public final void set_Item(int index, IPortion value)
```

지정된 인덱스의 요소를 가져옵니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| index | int |  |
| value | [IPortion](../../com.aspose.slides/iportion) |  |

### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public final void add(IPortion value)
```

포션을 컬렉션의 끝에 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | 컬렉션의 끝에 추가될 포션. |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public final int indexOf(IPortion item)
```

리스트에서 특정 항목의 인덱스를 결정합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | 리스트에서 찾을 객체. |

**반환값:**  
int - 리스트에서 항목이 발견되면 해당 인덱스; 그렇지 않으면 -1.

### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public final void insert(int index, IPortion value)
```

지정된 인덱스에 포션을 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| index | int | 포션을 삽입할 0부터 시작하는 인덱스. |
| value | [IPortion](../../com.aspose.slides/iportion) | 삽입할 포션. |

### clear() {#clear--}
```
public final void clear()
```

컬렉션의 모든 요소를 제거합니다.

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public final boolean contains(IPortion item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection)에 특정 값이 포함되어 있는지 확인합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 찾을 객체. |

**반환값:**  
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 항목이 발견되면 true; 그렇지 않으면 false.

### copyTo(IPortion[] array, int arrayIndex) {#copyTo-com.aspose.slides.IPortion---int-}
```
public final void copyTo(IPortion[] array, int arrayIndex)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection)의 요소를 지정된 배열 인덱스부터 배열에 복사합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| array | [IPortion\[\]](../../com.aspose.slides/iportion) | [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 복사된 요소의 대상이 되는 1차원 배열입니다. 배열은 0부터 시작하는 인덱스를 가져야 합니다. |
| arrayIndex | int | 복사를 시작할 배열의 0부터 시작하는 인덱스. |

### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public final boolean remove(IPortion item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection)에서 특정 객체의 첫 번째 발생을 제거합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 제거할 객체. |

**반환값:**  
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 항목이 성공적으로 제거되면 true; 그렇지 않으면 false. 원래 [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 항목을 찾지 못하면 이 메서드도 false를 반환합니다.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

컬렉션에서 지정된 인덱스의 요소를 제거합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| index | int | 제거할 요소의 0부터 시작하는 인덱스. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iterator()
```

컬렉션을 순회하는 열거자를 반환합니다.

**반환값:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - 컬렉션을 순회하는 데 사용할 수 있는 IGenericEnumerator.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iteratorJava()
```

전체 컬렉션에 대한 java 이터레이터를 반환합니다.

**반환값:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - 전체 컬렉션에 대한 java.util.Iterator.
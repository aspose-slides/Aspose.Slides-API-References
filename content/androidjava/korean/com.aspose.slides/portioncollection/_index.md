---
title: PortionCollection
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: Portion 컬렉션을 나타냅니다.
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

Portion 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getCount()](#getCount--) | 컬렉션에 실제로 포함된 요소 수를 반환합니다. |
| [isReadOnly()](#isReadOnly--) | [IGenericCollection](../../com.aspose.slides/igenericcollection)가 읽기 전용인지 여부를 나타내는 값을 반환합니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스의 요소를 반환합니다. |
| [set_Item(int index, IPortion value)](#set-Item-int-com.aspose.slides.IPortion-) | 지정된 인덱스의 요소를 반환합니다. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | 컬렉션 끝에 Portion을 추가합니다. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | List에서 특정 항목의 인덱스를 결정합니다. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | 지정된 인덱스에 Portion을 삽입합니다. |
| [clear()](#clear--) | 컬렉션의 모든 요소를 제거합니다. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | [IGenericCollection](../../com.aspose.slides/igenericcollection)에 특정 값이 포함되어 있는지 확인합니다. |
| [copyTo(IPortion[] array, int arrayIndex)](#copyTo-com.aspose.slides.IPortion---int-) | [IGenericCollection](../../com.aspose.slides/igenericcollection)의 요소를 배열에 복사하며, 지정된 배열 인덱스에서 시작합니다. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 특정 객체의 첫 번째 발생을 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 컬렉션의 지정된 인덱스에 있는 요소를 제거합니다. |
| [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java iterator를 반환합니다. |

### getCount() {#getCount--}
```
public final int getCount()
```

컬렉션에 실제로 포함된 요소 수를 반환합니다. 읽기 전용 int.

**반환값:**  
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

[IGenericCollection](../../com.aspose.slides/igenericcollection)가 읽기 전용인지 여부를 나타내는 값을 반환합니다. 읽기 전용 boolean.

**반환값:**  
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection)이 읽기 전용이면 true; 아니면 false.

### get_Item(int index) {#get-Item-int-}
```
public final IPortion get_Item(int index)
```

지정된 인덱스의 요소를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**  
[IPortion](../../com.aspose.slides/iportion)

### set_Item(int index, IPortion value) {#set-Item-int-com.aspose.slides.IPortion-}
```
public final void set_Item(int index, IPortion value)
```

지정된 인덱스의 요소를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |
| value | [IPortion](../../com.aspose.slides/iportion) |  |

### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public final void add(IPortion value)
```

컬렉션 끝에 Portion을 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | 컬렉션 끝에 추가될 Portion |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public final int indexOf(IPortion item)
```

List에서 특정 항목의 인덱스를 결정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | List에서 찾을 객체 |

**반환값:**  
int - 항목이 리스트에 있으면 해당 인덱스; 없으면 -1.

### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public final void insert(int index, IPortion value)
```

지정된 인덱스에 Portion을 삽입합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | Portion을 삽입할 0 기반 인덱스 |
| value | [IPortion](../../com.aspose.slides/iportion) | 삽입할 Portion |

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 찾을 객체 |

**반환값:**  
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection)에 항목이 있으면 true; 아니면 false.

### copyTo(IPortion[] array, int arrayIndex) {#copyTo-com.aspose.slides.IPortion---int-}
```
public final void copyTo(IPortion[] array, int arrayIndex)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection)의 요소를 배열에 복사하며, 지정된 배열 인덱스에서 시작합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| array | [IPortion\[\]](../../com.aspose.slides/iportion) | [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 복사된 요소를 저장하는 일차원 배열. 배열은 0 기반 인덱스를 가져야 합니다. |
| arrayIndex | int | 복사를 시작할 배열 내 0 기반 인덱스 |

### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public final boolean remove(IPortion item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection)에서 특정 객체의 첫 번째 발생을 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 제거할 객체 |

**반환값:**  
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 항목이 성공적으로 제거되면 true; 아니면 false. 항목이 원래 [IGenericCollection](../../com.aspose.slides/igenericcollection)에 없으면 false를 반환합니다.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

컬렉션의 지정된 인덱스에 있는 요소를 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 제거할 요소의 0 기반 인덱스 |

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

전체 컬렉션에 대한 java iterator를 반환합니다.

**반환값:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - 전체 컬렉션에 대한 java.util.Iterator.
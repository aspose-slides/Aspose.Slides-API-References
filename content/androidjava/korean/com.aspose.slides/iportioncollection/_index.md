---
title: IPortionCollection
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: Portion의 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/iportioncollection/
---
**모든 구현된 인터페이스:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPortionCollection extends System.Collections.Generic.IGenericEnumerable<IPortion>
```

Portion의 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에 있는 요소를 가져옵니다. |
| [getCount()](#getCount--) | 컬렉션에 실제로 포함된 요소 수를 가져옵니다. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Portion을 컬렉션의 끝에 추가합니다. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | 컬렉션에서 특정 Portion의 인덱스를 결정합니다. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | 지정된 인덱스에 Portion을 컬렉션에 삽입합니다. |
| [clear()](#clear--) | 컬렉션의 모든 요소를 제거합니다. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | 특정 값을 [IGenericCollection](../../com.aspose.slides/igenericcollection)에 포함하는지 확인합니다. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 특정 객체의 첫 번째 발생을 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 지정된 인덱스에 있는 요소를 제거합니다. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPortion get_Item(int index)
```

지정된 인덱스에 있는 요소를 가져옵니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[IPortion](../../com.aspose.slides/iportion)
### getCount() {#getCount--}
```
public abstract int getCount()
```

컬렉션에 실제로 포함된 요소 수를 가져옵니다. 읽기 전용 int.

**반환값:**
int
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public abstract void add(IPortion value)
```

Portion을 컬렉션의 끝에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | 컬렉션의 끝에 추가될 Portion. |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public abstract int indexOf(IPortion item)
```

컬렉션에서 특정 Portion의 인덱스를 결정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | 컬렉션에서 찾을 Portion. |

**반환값:**
int - 컬렉션에서 항목이 발견되면 해당 인덱스; 그렇지 않으면 -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public abstract void insert(int index, IPortion value)
```

지정된 인덱스에 Portion을 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | Portion을 삽입할 0부터 시작하는 인덱스. |
| value | [IPortion](../../com.aspose.slides/iportion) | 삽입할 Portion. |

### clear() {#clear--}
```
public abstract void clear()
```

컬렉션의 모든 요소를 제거합니다.

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public abstract boolean contains(IPortion item)
```

특정 값을 [IGenericCollection](../../com.aspose.slides/igenericcollection)에 포함하는지 확인합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 찾을 객체. |

**반환값:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection)에 항목이 있으면 true; 그렇지 않으면 false.
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public abstract boolean remove(IPortion item)
```

특정 객체의 첫 번째 발생을 [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 제거할 객체. |

**반환값:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 항목이 성공적으로 제거되면 true; 그렇지 않으면 false. 항목이 원래 [IGenericCollection](../../com.aspose.slides/igenericcollection)에 없을 경우에도 false를 반환합니다.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

컬렉션에서 지정된 인덱스에 있는 요소를 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 제거할 요소의 0부터 시작하는 인덱스. |
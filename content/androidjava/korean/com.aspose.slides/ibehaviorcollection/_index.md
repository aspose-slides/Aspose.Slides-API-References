---
title: IBehaviorCollection
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 동작 효과의 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ibehaviorcollection/
---
**구현된 모든 인터페이스:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IBehaviorCollection extends System.Collections.Generic.IGenericEnumerable<IBehavior>
```

동작 효과의 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에 있는 동작을 반환합니다. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | 지정된 인덱스에 있는 동작을 반환합니다. |
| [getCount()](#getCount--) | 컬렉션에 있는 동작 수를 반환합니다. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | 컬렉션에 새 동작을 추가합니다. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | 리스트에서 특정 항목의 인덱스를 결정합니다. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | 지정된 인덱스에 새 동작을 컬렉션에 삽입합니다. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | 컬렉션에서 지정된 동작을 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 지정된 인덱스에 있는 컬렉션에서 동작을 제거합니다. |
| [clear()](#clear--) | 컬렉션의 모든 동작을 제거합니다. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | 특정 값이 [IGenericCollection](../../com.aspose.slides/igenericcollection)에 포함되어 있는지 확인합니다. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IBehavior get_Item(int index)
```

지정된 인덱스에 있는 동작을 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 반환할 동작의 인덱스. |

**반환값:**
[IBehavior](../../com.aspose.slides/ibehavior) - 애니메이션 동작.
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public abstract void set_Item(int index, IBehavior value)
```

지정된 인덱스에 있는 동작을 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 반환할 동작의 인덱스. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### getCount() {#getCount--}
```
public abstract int getCount()
```

컬렉션에 있는 동작 수를 반환합니다. 읽기 전용 int.

**반환값:**
int
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public abstract void add(IBehavior item)
```

컬렉션에 새 동작을 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | 추가할 동작. |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public abstract int indexOf(IBehavior item)
```

리스트에서 특정 항목의 인덱스를 결정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | 리스트에서 찾을 개체. |

**반환값:**
int - 항목이 리스트에서 발견된 경우 해당 인덱스; 그렇지 않으면 -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public abstract void insert(int index, IBehavior item)
```

지정된 인덱스에 새 동작을 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 새 동작을 삽입할 인덱스. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | 삽입할 동작. |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public abstract boolean remove(IBehavior item)
```

컬렉션에서 지정된 동작을 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | 제거할 동작. |

**반환값:**
boolean - 동작이 성공적으로 제거된 경우 true, 그렇지 않으면 false
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

지정된 인덱스에 있는 컬렉션에서 동작을 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 제거할 동작의 인덱스. |

### clear() {#clear--}
```
public abstract void clear()
```

컬렉션의 모든 동작을 제거합니다.

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public abstract boolean contains(IBehavior item)
```

특정 값이 [IGenericCollection](../../com.aspose.slides/igenericcollection)에 포함되어 있는지 확인합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 찾을 개체. |

**반환값:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 항목이 발견되면 true, 그렇지 않으면 false.
---
title: SequenceCollection
second_title: Java API 참조를 통해 Android용 Aspose.Slides
description: 대화형 시퀀스 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/sequencecollection/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.ISequenceCollection](../../com.aspose.slides/isequencecollection)
```
public class SequenceCollection implements ISequenceCollection
```

대화형 시퀀스 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getCount()](#getCount--) | 컬렉션의 요소 수를 반환합니다. 읽기 전용 int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | 새 대화형 시퀀스를 추가합니다. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | 컬렉션에서 지정된 시퀀스를 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 지정된 인덱스의 시퀀스를 제거합니다. |
| [clear()](#clear--) | 컬렉션의 모든 시퀀스를 제거합니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스의 시퀀스를 반환합니다. |
| [iterator()](#iterator--) | 컬렉션을 반복하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java 반복자를 반환합니다. |
### getCount() {#getCount--}
```
public final int getCount()
```

컬렉션의 요소 수를 반환합니다. 읽기 전용 int.

**반환:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public final ISequence add(IShape shapeTrigger)
```

새 대화형 시퀀스를 추가합니다. 읽기/쓰기 [Sequence](../../com.aspose.slides/sequence).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) |  |

**반환:**
[ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public final void remove(ISequence item)
```

컬렉션에서 지정된 시퀀스를 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | 제거할 시퀀스. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

지정된 인덱스의 시퀀스를 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 삭제할 시퀀스의 인덱스. |

### clear() {#clear--}
```
public final void clear()
```

컬렉션의 모든 시퀀스를 제거합니다.

### get_Item(int index) {#get-Item-int-}
```
public final ISequence get_Item(int index)
```

지정된 인덱스의 시퀀스를 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 요소의 인덱스. |

**반환:**
[ISequence](../../com.aspose.slides/isequence) - [ISequence](../../com.aspose.slides/isequence) 객체.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iterator()
```

컬렉션을 반복하는 열거자를 반환합니다.

**반환:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - 컬렉션을 반복하는 데 사용할 수 있는 IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iteratorJava()
```

전체 컬렉션에 대한 java 반복자를 반환합니다.

**반환:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - 전체 컬렉션에 대한 java.util.Iterator.
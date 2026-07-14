---
title: ISequenceCollection
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 대화형 시퀀스의 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/isequencecollection/
---
**모든 구현된 인터페이스:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequenceCollection extends System.Collections.Generic.IGenericEnumerable<ISequence>
```

대화형 시퀀스의 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getCount()](#getCount--) | 컬렉션의 요소 수를 반환합니다. 읽기 전용 int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | 새 대화형 시퀀스를 추가합니다. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | 컬렉션에서 지정된 시퀀스를 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 지정된 인덱스에서 시퀀스를 제거합니다. |
| [clear()](#clear--) | 컬렉션에서 모든 시퀀스를 제거합니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에서 시퀀스를 반환합니다. |
### getCount() {#getCount--}
```
public abstract int getCount()
```


컬렉션의 요소 수를 반환합니다. 읽기 전용 int.

**반환값:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public abstract ISequence add(IShape shapeTrigger)
```


새 대화형 시퀀스를 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) | Shape 객체 [IShape](../../com.aspose.slides/ishape) |

**반환값:**
[ISequence](../../com.aspose.slides/isequence) - 새 시퀀스 [ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public abstract void remove(ISequence item)
```


컬렉션에서 지정된 시퀀스를 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | 제거할 시퀀스. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


지정된 인덱스에서 시퀀스를 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 컬렉션에서 요소의 인덱스 int |

### clear() {#clear--}
```
public abstract void clear()
```


컬렉션에서 모든 시퀀스를 제거합니다.

### get_Item(int index) {#get-Item-int-}
```
public abstract ISequence get_Item(int index)
```


지정된 인덱스에서 시퀀스를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 요소의 인덱스. |

**반환값:**
[ISequence](../../com.aspose.slides/isequence) - [ISequence](../../com.aspose.slides/isequence) 객체.
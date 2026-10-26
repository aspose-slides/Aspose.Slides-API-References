---
title: TextAnimationCollection
second_title: Android용 Aspose.Slides Java API 참조
description: 텍스트 애니메이션 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/textanimationcollection/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)
```
public class TextAnimationCollection implements ITextAnimationCollection
```

텍스트 애니메이션 컬렉션을 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [TextAnimationCollection()](#TextAnimationCollection--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [size()](#size--) | 컬렉션의 요소 개수를 반환합니다. |
| [add()](#add--) | 컬렉션에 새로운 텍스트 애니메이션을 추가합니다. |
| [get_Item(int index)](#get-Item-int-) | 인덱스로 요소를 반환합니다. |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | 모든 요소를 반환합니다 |
| [iterator()](#iterator--) | 컬렉션을 반복하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java 반복자를 반환합니다. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 컬렉션의 모든 요소를 지정된 배열에 복사합니다. |
| [isSynchronized()](#isSynchronized--) | 컬렉션에 대한 접근이 동기화(스레드 안전)되는지 여부를 나타내는 값을 반환합니다. |
| [getSyncRoot()](#getSyncRoot--) | 동기화 루트를 반환합니다. |
### TextAnimationCollection() {#TextAnimationCollection--}
```
public TextAnimationCollection()
```


### size() {#size--}
```
public final int size()
```


컬렉션의 요소 개수를 반환합니다. 읽기 전용 int.

**반환:**
int
### add() {#add--}
```
public final TextAnimation add()
```


컬렉션에 새로운 텍스트 애니메이션을 추가합니다.

**반환:**
[TextAnimation](../../com.aspose.slides/textanimation) - 추가된 [TextAnimation](../../com.aspose.slides/textanimation)
### get_Item(int index) {#get-Item-int-}
```
public final ITextAnimation get_Item(int index)
```


인덱스로 요소를 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public final ITextAnimation[] get_Item(IShape shape)
```


모든 요소를 반환합니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) 제거하기 위해. |

**반환:**
com.aspose.slides.ITextAnimation[] - [ITextAnimation](../../com.aspose.slides/itextanimation) 배열
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iterator()
```


컬렉션을 반복하는 데 사용할 수 있는 IGenericEnumerator를 반환합니다.

**반환:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - 컬렉션을 반복하는 데 사용할 수 있는 IGenericEnumerator
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iteratorJava()
```


전체 컬렉션에 대한 java.util.Iterator를 반환합니다.

**반환:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - 전체 컬렉션에 대한 java.util.Iterator
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


컬렉션의 모든 요소를 지정된 배열에 복사합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 채울 배열. |
| index | int | 대상 배열의 시작 위치. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


컬렉션에 대한 접근이 동기화(스레드 안전)되는지 여부를 나타내는 값을 반환합니다. 읽기 전용 boolean.

**반환:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


동기화 루트를 반환합니다. 읽기 전용 Object.

**반환:**
java.lang.Object
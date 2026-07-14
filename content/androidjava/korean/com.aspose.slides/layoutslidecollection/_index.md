---
title: LayoutSlideCollection
second_title: Java API를 통한 Android용 Aspose.Slides 레퍼런스
description: 레이아웃 슬라이드 컬렉션의 기본 클래스를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/layoutslidecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection), com.aspose.slides.IDOMObject
```
public class LayoutSlideCollection implements ILayoutSlideCollection, IDOMObject
```

레이아웃 슬라이드 컬렉션의 기본 클래스를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [size()](#size--) | 컬렉션에 포함된 레이아웃 슬라이드의 수를 반환합니다. |
| [get_Item(int index)](#get-Item-int-) | 인덱스로 레이아웃 슬라이드를 반환합니다. |
| [getByType(byte type)](#getByType-byte-) | 지정된 유형의 첫 번째 레이아웃 슬라이드를 반환합니다. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | 컬렉션에서 레이아웃을 제거합니다. |
| [removeUnused()](#removeUnused--) | 사용되지 않는 레이아웃 슬라이드를 제거합니다(HasDependingSlides가 false인 레이아웃 슬라이드). |
| [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 Java 반복자를 반환합니다. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 컬렉션의 모든 요소를 지정된 배열로 복사합니다. |
| [isSynchronized()](#isSynchronized--) | 컬렉션에 대한 접근이 동기화(스레드 안전)되어 있는지 여부를 나타내는 값을 반환합니다. |
| [getSyncRoot()](#getSyncRoot--) | 동기화 루트를 반환합니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```


컬렉션에 포함된 레이아웃 슬라이드의 수를 반환합니다. 읽기 전용 int.

**반환값:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ILayoutSlide get_Item(int index)
```


인덱스로 레이아웃 슬라이드를 반환합니다. 읽기 전용 [LayoutSlide](../../com.aspose.slides/layoutslide).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public final ILayoutSlide getByType(byte type)
```


지정된 유형의 첫 번째 레이아웃 슬라이드를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | byte | 찾고자 하는 레이아웃 슬라이드의 유형. |

**반환값:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 지정된 유형을 가진 [LayoutSlide](../../com.aspose.slides/layoutslide) 또는 레이아웃이 없으면 null.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public final void remove(ILayoutSlide value)
```


컬렉션에서 레이아웃을 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 컬렉션에서 제거할 레이아웃 슬라이드.

--------------------

1) PptxEditException이 발생하지 않도록 레이아웃의 HasDependingSlides 속성을 먼저 확인하십시오. 2) 코드를 단순화하려면 [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) 메서드도 사용할 수 있습니다. |
### removeUnused() {#removeUnused--}
```
public final void removeUnused()
```


사용되지 않는 레이아웃 슬라이드를 제거합니다(HasDependingSlides가 false인 레이아웃 슬라이드).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iterator()
```


컬렉션을 순회하는 열거자를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - 컬렉션을 순회하는 데 사용할 수 있는 IGenericEnumerator
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iteratorJava()
```


전체 컬렉션에 대한 java.util.Iterator를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - 전체 컬렉션에 대한 java.util.Iterator
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


컬렉션의 모든 요소를 지정된 배열로 복사합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 대상 배열. |
| index | int | 대상 배열에서 시작 인덱스. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


컬렉션에 대한 접근이 동기화(스레드 안전)되어 있는지 여부를 나타내는 값을 반환합니다. 읽기 전용 boolean.

**반환값:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


동기화 루트를 반환합니다. 읽기 전용 Object.

**반환값:**
java.lang.Object
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환값:**
com.aspose.slides.IDOMObject
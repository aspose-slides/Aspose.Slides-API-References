---
title: TabCollection
second_title: Aspose.Slides for Java API 참조
description: 탭 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/tabcollection/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.ITabCollection](../../com.aspose.slides/itabcollection), com.aspose.slides.IDOMObject
```
public final class TabCollection implements ITabCollection, IDOMObject
```

탭 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [size()](#size--) | 컬렉션에 실제로 포함된 요소의 수를 가져옵니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에 있는 요소를 가져옵니다. |
| [add(double position, int align)](#add-double-int-) | 컬렉션에 Tab을 추가합니다. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | 컬렉션에 Tab을 추가합니다. |
| [clear()](#clear--) | 컬렉션에서 모든 요소를 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 컬렉션에서 지정된 인덱스에 있는 요소를 제거합니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 두 TabsEx 인스턴스가 동일한지 판단합니다. |
| [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java iterator를 반환합니다. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 컬렉션의 모든 요소를 지정된 배열에 복사합니다. |
| [isSynchronized()](#isSynchronized--) | 컬렉션에 대한 접근이 동기화(스레드 안전)되어 있는지 여부를 나타내는 값을 반환합니다. |
| [getSyncRoot()](#getSyncRoot--) | 동기화 루트를 반환합니다. |
### size() {#size--}
```
public final int size()
```

컬렉션에 실제로 포함된 요소의 수를 가져옵니다. 읽기 전용 int.

**반환:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ITab get_Item(int index)
```

지정된 인덱스에 있는 요소를 가져옵니다. 읽기 전용 [Tab](../../com.aspose.slides/tab).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public final ITab add(double position, int align)
```

컬렉션에 Tab을 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| position | double |  |
| align | int |  |

**반환:**
[ITab](../../com.aspose.slides/itab) - 추가된 Tab.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public final int add(ITab value)
```

컬렉션에 Tab을 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | 컬렉션 끝에 추가될 Tab 객체. |

**반환:**
int - Tab이 추가된 인덱스.
### clear() {#clear--}
```
public final void clear()
```

컬렉션에서 모든 요소를 제거합니다.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

컬렉션에서 지정된 인덱스에 있는 요소를 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 제거할 요소의 0 기반 인덱스. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환:**
com.aspose.slides.IDOMObject
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

두 TabsEx 인스턴스가 동일한지 판단합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 현재 TabsEx와 비교할 대상 TabsEx. |

**반환:**
boolean - 지정된 TabsEx가 현재 TabsEx와 동일하면 **true**, 그렇지 않으면 **false**.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iterator()
```

컬렉션을 순회하는 열거자를 반환합니다.

**반환:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - 컬렉션을 순회하는 데 사용할 수 있는 IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iteratorJava()
```

전체 컬렉션에 대한 java iterator를 반환합니다.

**반환:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - 전체 컬렉션에 대한 java.util.Iterator.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

컬렉션의 모든 요소를 지정된 배열에 복사합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 대상 배열. |
| index | int | 대상 배열의 시작 인덱스. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

컬렉션에 대한 접근이 동기화(스레드 안전)되어 있는지 여부를 나타내는 값을 반환합니다. 읽기 전용 boolean.

**반환:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

동기화 루트를 반환합니다. 읽기 전용 Object.

**반환:**
java.lang.Object
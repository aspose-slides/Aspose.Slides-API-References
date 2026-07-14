---
title: SmartArtNodeCollection
second_title: Java API를 통한 Aspose.Slides for Android 참조
description: SmartArt 노드 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/smartartnodecollection/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
```
public final class SmartArtNodeCollection implements ISmartArtNodeCollection
```

SmartArt 노드 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 인덱스로 노드를 반환합니다. |
| [size()](#size--) | 컬렉션에 있는 노드 수를 반환합니다. 읽기 전용 int 읽기 전용 int. |
| [addNode()](#addNode--) | 새 스마트 아트 노드 또는 하위 노드를 추가합니다. |
| [removeNode(int index)](#removeNode-int-) | 인덱스로 노드 또는 하위 노드를 제거합니다. |
| [removeNode(ISmartArtNode node)](#removeNode-com.aspose.slides.ISmartArtNode-) | 노드 또는 하위 노드를 제거합니다. |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | 선택된 위치에 새 노드를 추가합니다. |
| [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java 이터레이터를 반환합니다. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 컬렉션의 모든 요소를 지정된 배열에 복사합니다. |
| [isSynchronized()](#isSynchronized--) | 컬렉션에 대한 액세스가 동기화(스레드 안전)되어 있는지 여부를 나타내는 값을 반환합니다. |
| [getSyncRoot()](#getSyncRoot--) | 동기화 루트를 반환합니다. |
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtNode get_Item(int index)
```


인덱스로 노드를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 요소의 0부터 시작하는 인덱스 |

**반환값:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - SmartArt 노드
### size() {#size--}
```
public final int size()
```


컬렉션에 있는 노드 수를 반환합니다. 읽기 전용 int 읽기 전용 int.

**반환값:**
int
### addNode() {#addNode--}
```
public final ISmartArtNode addNode()
```


새 스마트 아트 노드 또는 하위 노드를 추가합니다.

**반환값:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - 추가된 노드
### removeNode(int index) {#removeNode-int-}
```
public final void removeNode(int index)
```


인덱스로 노드 또는 하위 노드를 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 노드의 0부터 시작하는 인덱스 |
### removeNode(ISmartArtNode node) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public final void removeNode(ISmartArtNode node)
```


노드 또는 하위 노드를 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| node | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | 제거할 노드 |
### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public final ISmartArtNode addNodeByPosition(int position)
```


선택된 위치에 새 노드를 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | int | 0부터 시작하는 노드 위치 |

**반환값:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - 추가된 노드
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iterator()
```


컬렉션을 순회하는 열거자를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - 컬렉션을 순회하는 IGenericEnumerator
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iteratorJava()
```


전체 컬렉션에 대한 java 이터레이터를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - 전체 컬렉션에 대한 java.util.Iterator
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


컬렉션의 모든 요소를 지정된 배열에 복사합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 대상 배열. |
| index | int | 대상 배열의 시작 인덱스. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


컬렉션에 대한 액세스가 동기화(스레드 안전)되어 있는지 여부를 나타내는 값을 반환합니다. 읽기 전용 boolean.

**반환값:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


동기화 루트를 반환합니다. 읽기 전용 Object.

**반환값:**
java.lang.Object
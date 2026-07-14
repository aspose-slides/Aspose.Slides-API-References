---
title: SmartArtShapeCollection
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: SmartArt 도형 컬렉션을 나타냅니다
type: docs
url: /ko/com.aspose.slides/smartartshapecollection/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
[com.aspose.slides.ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)  
```
public class SmartArtShapeCollection implements ISmartArtShapeCollection
```

SmartArt shapes의 컬렉션을 나타냅니다

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [size()](#size--) | 컬렉션에 실제로 포함된 요소 수를 가져옵니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에 있는 요소를 가져옵니다. |
| [isSynchronized()](#isSynchronized--) | 컬렉션에 대한 접근이 동기화(스레드 안전)되는지 여부를 나타내는 값을 반환합니다. |
| [getSyncRoot()](#getSyncRoot--) | 동기화 루트를 반환합니다. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 컬렉션의 모든 요소를 지정된 배열에 복사합니다. |
| [iterator()](#iterator--) | 컬렉션을 반복하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java 이터레이터를 반환합니다. |
### size() {#size--}
```
public final int size()
```

컬렉션에 실제로 포함된 요소 수를 가져옵니다. 읽기 전용 int.

**반환:**  
int
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtShape get_Item(int index)
```

지정된 인덱스에 있는 요소를 가져옵니다. 읽기 전용 [SmartArtShape](../../com.aspose.slides/smartartshape).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | shape의 인덱스 |

**반환:**  
[ISmartArtShape](../../com.aspose.slides/ismartartshape) - SmartArt shape
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
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

컬렉션의 모든 요소를 지정된 배열에 복사합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 대상 배열. |
| index | int | 대상 배열에서 시작 인덱스. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iterator()
```

컬렉션을 반복하는 열거자를 반환합니다.

**반환:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - 컬렉션을 반복하는 데 사용할 수 있는 IGenericEnumerator
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iteratorJava()
```

전체 컬렉션에 대한 java 이터레이터를 반환합니다.

**반환:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - 전체 컬렉션에 대한 java.util.Iterator
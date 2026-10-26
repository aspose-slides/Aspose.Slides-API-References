---
title: AdjustValueCollection
second_title: Aspose.Slides for Java API 참조
description: 도형 조정 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/adjustvaluecollection/
---
**상속:**  
java.lang.Object, com.aspose.slides.DomObject

**구현된 모든 인터페이스:**  
[com.aspose.slides.IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)  
```
public final class AdjustValueCollection extends DomObject<GeometryShape> implements IAdjustValueCollection
```

shape의 조정 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [size()](#size--) | 조정 수를 반환합니다. |
| [get_Item(int index)](#get-Item-int-) | 인덱스로 조정을 반환합니다. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 컬렉션의 모든 요소를 지정된 배열에 복사합니다. |
| [isSynchronized()](#isSynchronized--) | 컬렉션에 대한 접근이 동기화(스레드-안전)되는지를 나타내는 값을 반환합니다. |
| [getSyncRoot()](#getSyncRoot--) | 동기화 루트를 반환합니다. |
| [iterator()](#iterator--) | 전체 컬렉션에 대한 열거자를 반환합니다. |
### size() {#size--}
```
public final int size()
```

조정 수를 반환합니다. 읽기 전용 int.

**반환값:**  
int
### get_Item(int index) {#get-Item-int-}
```
public final IAdjustValue get_Item(int index)
```

인덱스로 조정을 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 조정의 인덱스. |

**반환값:**  
[IAdjustValue](../../com.aspose.slides/iadjustvalue) - [AdjustValue](../../com.aspose.slides/adjustvalue).
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

컬렉션에 대한 접근이 동기화(스레드-안전)되는지를 나타내는 값을 반환합니다. 읽기 전용 boolean.

**반환값:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

동기화 루트를 반환합니다. 읽기 전용 Object.

**반환값:**  
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.IEnumerator iterator()
```

전체 컬렉션에 대한 열거자를 반환합니다.

**반환값:**  
com.aspose.ms.System.Collections.IEnumerator
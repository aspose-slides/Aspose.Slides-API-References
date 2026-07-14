---
title: AdjustValueCollection
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 도형 조정값의 컬렉션을 나타냅니다.
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

시형의 조정값 컬렉션을 나타냅니다.
## 메서드

| Method | Description |
| --- | --- |
| [size()](#size--) | 조정값의 수를 반환합니다. |
| [get_Item(int index)](#get-Item-int-) | 인덱스로 조정값을 반환합니다. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 컬렉션의 모든 요소를 지정된 배열에 복사합니다. |
| [isSynchronized()](#isSynchronized--) | 컬렉션에 대한 접근이 동기화(스레드 안전)되는지 여부를 나타내는 값을 반환합니다. |
| [getSyncRoot()](#getSyncRoot--) | 동기화 루트를 반환합니다. |
| [iterator()](#iterator--) | 전체 컬렉션에 대한 열거자를 반환합니다. |
### size() {#size--}
```
public final int size()
```

조정값의 수를 반환합니다. 읽기 전용 int.

**반환:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAdjustValue get_Item(int index)
```

인덱스로 조정값을 반환합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 조정값의 인덱스. |

**반환:**
[IAdjustValue](../../com.aspose.slides/iadjustvalue) - [AdjustValue](../../com.aspose.slides/adjustvalue).
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

컬렉션의 모든 요소를 지정된 배열에 복사합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 대상 배열. |
| index | int | 대상 배열에서 시작 인덱스. |

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
### iterator() {#iterator--}
```
public final System.Collections.IEnumerator iterator()
```

전체 컬렉션에 대한 열거자를 반환합니다.

**반환:**
com.aspose.ms.System.Collections.IEnumerator
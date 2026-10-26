---
title: FillFormatCollection
second_title: Aspose.Slides for Android Java API 레퍼런스
description: 채우기 스타일 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/fillformatcollection/
---
**상속:**  
java.lang.Object, com.aspose.slides.DomObject

**구현된 모든 인터페이스:**  
[com.aspose.slides.IFillFormatCollection](../../com.aspose.slides/ifillformatcollection)  
```
public final class FillFormatCollection extends DomObject<FormatScheme> implements IFillFormatCollection
```

채우기 스타일 컬렉션을 나타냅니다.
## 메서드

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에 있는 요소를 가져옵니다. |
| [iterator()](#iterator--) | 컬렉션을 반복하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java iterator를 반환합니다. |
| [size()](#size--) | 컬렉션에 실제로 포함된 요소 수를 가져옵니다. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 컬렉션의 모든 요소를 지정된 배열에 복사합니다. |
| [isSynchronized()](#isSynchronized--) | 컬렉션에 대한 접근이 동기화(스레드 안전)되어 있는지 여부를 나타내는 값을 반환합니다. |
| [getSyncRoot()](#getSyncRoot--) | 동기화 루트를 반환합니다. |
### get_Item(int index) {#get-Item-int-}
```
public final IFillFormat get_Item(int index)
```

지정된 인덱스에 있는 요소를 가져옵니다. 읽기 전용 [IFillFormat](../../com.aspose.slides/ifillformat).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**반환값:**  
[IFillFormat](../../com.aspose.slides/ifillformat)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFillFormat> iterator()
```

컬렉션을 반복하는 열거자를 반환합니다.

**반환값:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFillFormat> - 컬렉션을 반복하는 데 사용할 수 있는 IGenericEnumerator입니다.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFillFormat> iteratorJava()
```

전체 컬렉션에 대한 java iterator를 반환합니다.

**반환값:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFillFormat> - 전체 컬렉션에 대한 java.util.Iterator입니다.
### size() {#size--}
```
public final int size()
```

컬렉션에 실제로 포함된 요소 수를 가져옵니다. 읽기 전용 int.

**반환값:**  
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

컬렉션의 모든 요소를 지정된 배열에 복사합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 대상 배열. |
| index | int | 대상 배열의 시작 인덱스. |
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
---
title: TagCollection
second_title: Aspose.Slides for Android Java API 참조
description: 사용자 정의 문자열 쌍으로 구성된 태그 컬렉션을 나타냅니다
type: docs
url: /ko/com.aspose.slides/tagcollection/
---
**상속:**
java.lang.Object

**모든 구현된 인터페이스:**
[com.aspose.slides.ITagCollection](../../com.aspose.slides/itagcollection)
```
public final class TagCollection implements ITagCollection
```

태그(사용자 정의 문자열 쌍) 컬렉션을 나타냅니다.

--------------------

> ```
> The following example shows how to add a tag to a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ITagCollection tags = pres.getCustomData().getTags();
>      pres.getCustomData().getTags().add("MyTag", "My Tag Value");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## 메서드

| Method | Description |
| --- | --- |
| [size()](#size--) | 컬렉션에 포함된 태그 수를 반환합니다. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | 새 태그를 컬렉션에 추가합니다. |
| [remove(String name)](#remove-java.lang.String-) | 지정된 이름을 가진 태그를 컬렉션에서 제거합니다. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | 컬렉션에서 지정된 키의 0 기반 인덱스를 반환합니다. |
| [contains(String name)](#contains-java.lang.String-) | 컬렉션에 특정 이름이 포함되어 있는지 확인합니다. |
| [removeAt(int index)](#removeAt-int-) | 지정된 인덱스에 있는 태그를 제거합니다. |
| [clear()](#clear--) | 컬렉션의 모든 태그를 제거합니다. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | 지정된 인덱스에 있는 태그의 값을 반환합니다. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | 지정된 인덱스에 있는 태그의 키를 반환합니다. |
| [getNamesOfTags()](#getNamesOfTags--) | 태그 이름을 반환합니다. |
| [get_Item(String name)](#get-Item-java.lang.String-) | 태그의 키와 값 쌍을 반환하거나 설정합니다. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | 태그의 키와 값 쌍을 반환하거나 설정합니다. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 컬렉션의 모든 요소를 지정된 배열에 복사합니다. |
| [isSynchronized()](#isSynchronized--) | 컬렉션에 대한 접근이 동기화(스레드 안전)되어 있는지 여부를 나타내는 값을 반환합니다. |
| [getSyncRoot()](#getSyncRoot--) | 동기화 루트를 반환합니다. |
| [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java 이터레이터를 반환합니다. |
### size() {#size--}
```
public final int size()
```

컬렉션에 포함된 태그 수를 반환합니다. 읽기 전용 int.

**반환:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final int add(String name, String value)
```

새 태그를 컬렉션에 추가합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | 태그의 이름. |
| value | java.lang.String | 태그의 값. |

**반환:**
int - 추가된 태그의 인덱스.
### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

지정된 이름을 가진 태그를 컬렉션에서 제거합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | 제거할 태그의 이름. |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public final int indexOfName(String name)
```

컬렉션에서 지정된 키의 0 기반 인덱스를 반환합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | 컬렉션에서 찾을 이름. |

**반환:**
int - 컬렉션에 키가 존재하면 그 0 기반 인덱스를 반환하고, 없으면 -1을 반환합니다.
### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```

컬렉션에 특정 이름이 포함되어 있는지 확인합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | 찾을 키. |

**반환:**
boolean - 지정된 키를 가진 태그가 컬렉션에 있으면 true, 그렇지 않으면 false.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

지정된 인덱스에 있는 태그를 제거합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 제거할 태그의 0 기반 인덱스. |
### clear() {#clear--}
```
public final void clear()
```

컬렉션의 모든 태그를 제거합니다.

### getValueByIndex(int index) {#getValueByIndex-int-}
```
public final String getValueByIndex(int index)
```

지정된 인덱스에 있는 태그의 값을 반환합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 반환할 태그의 인덱스. |

**반환:**
java.lang.String - 태그의 값.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public final String getNameByIndex(int index)
```

지정된 인덱스에 있는 태그의 키를 반환합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 반환할 태그의 인덱스. |

**반환:**
java.lang.String - 태그의 키.
### getNamesOfTags() {#getNamesOfTags--}
```
public final String[] getNamesOfTags()
```

태그 이름을 반환합니다.

**반환:**
java.lang.String[] - 태그 이름들.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

태그의 키와 값 쌍을 반환하거나 설정합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | 태그의 키. |

**반환:**
java.lang.String - 태그의 값.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

태그의 키와 값 쌍을 반환하거나 설정합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | 태그의 키. |
| value | java.lang.String |  |
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

컬렉션의 모든 요소를 지정된 배열에 복사합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 채울 배열. |
| index | int | 대상 배열에서 시작 위치. |
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
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

컬렉션을 순회하는 열거자를 반환합니다.

**반환:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

전체 컬렉션에 대한 java 이터레이터를 반환합니다.

**반환:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - An java.util.Iterator for the entire collection.
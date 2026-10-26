---
title: CustomXmlPartCollection
second_title: Java API를 통한 Android용 Aspose.Slides 레퍼런스
description: 커스텀 XML 파트 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/customxmlpartcollection/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
[com.aspose.slides.ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection), com.aspose.slides.IDOMObject  
```
public class CustomXmlPartCollection implements ICustomXmlPartCollection, IDOMObject
```

사용자 정의 XML 파트 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스의 요소를 반환합니다. |
| [size()](#size--) | 컬렉션에 포함된 사용자 정의 XML 파트의 개수를 반환합니다. |
| [add(String xmlString)](#add-java.lang.String-) | 새 사용자 정의 XML 파트를 추가합니다. |
| [add(byte[] xmlData)](#add-byte---) | 새 사용자 정의 XML 파트를 추가합니다. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | 새 사용자 정의 XML 파트를 추가합니다. |
| [removeAt(int index)](#removeAt-int-) | 지정된 인덱스에서 사용자 정의 XML 파트를 제거합니다. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | 컬렉션에서 특정 객체의 첫 번째 발생을 제거합니다. |
| [clear()](#clear--) | 컬렉션의 모든 항목을 제거합니다. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 지정된 배열에 복사합니다. |
| [isSynchronized()](#isSynchronized--) | 컬렉션에 대한 접근이 동기화(스레드 안전)되어 있는지 여부를 나타내는 값을 반환합니다. |
| [getSyncRoot()](#getSyncRoot--) | 동기화 루트를 반환합니다. |
| [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 Java iterator를 반환합니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### get_Item(int index) {#get-Item-int-}
```
public final ICustomXmlPart get_Item(int index)
```

지정된 인덱스의 요소를 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 얻을 요소의 0부터 시작하는 인덱스입니다. |

**반환값:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - 지정된 인덱스의 요소.
### size() {#size--}
```
public final int size()
```

컬렉션에 포함된 사용자 정의 XML 파트의 개수를 반환합니다. 읽기 전용 int.

**반환값:**
int
### add(String xmlString) {#add-java.lang.String-}
```
public final ICustomXmlPart add(String xmlString)
```

새 사용자 정의 XML 파트를 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| xmlString | java.lang.String | 추가될 새 파트의 XML 문자열입니다. |

**반환값:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - 생성된 사용자 정의 XML 파트.
### add(byte[] xmlData) {#add-byte---}
```
public final ICustomXmlPart add(byte[] xmlData)
```

새 사용자 정의 XML 파트를 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| xmlData | byte[] | 추가될 새 파트의 XML 데이터입니다. |

**반환값:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - 생성된 사용자 정의 XML 파트.
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public final ICustomXmlPart add(InputStream inputStream)
```

새 사용자 정의 XML 파트를 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 추가될 새 파트의 XML 데이터를 포함하는 inputStream입니다. |

**반환값:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - 생성된 사용자 정의 XML 파트.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

지정된 인덱스에서 사용자 정의 XML 파트를 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 제거할 요소의 0부터 시작하는 인덱스입니다. |
### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public final boolean remove(ICustomXmlPart item)
```

컬렉션에서 특정 객체의 첫 번째 발생을 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | 제거할 사용자 정의 XML 파트입니다. |

**반환값:**
boolean - 항목이 성공적으로 제거되면 true, 그렇지 않으면 false.
### clear() {#clear--}
```
public final void clear()
```

컬렉션의 모든 항목을 제거합니다.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

지정된 배열에 복사합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 복사 대상 배열입니다. |
| index | int | 복사를 시작할 인덱스입니다. |
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
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iterator()
```

컬렉션을 순회하는 열거자를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - 컬렉션을 순회하는 데 사용할 수 있는 IGenericEnumerator입니다.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iteratorJava()
```

전체 컬렉션에 대한 Java iterator를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - 전체 컬렉션에 대한 java.util.Iterator입니다.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환값:**
com.aspose.slides.IDOMObject
---
title: VbaModuleCollection
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: VBA 프로젝트 모듈의 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/vbamodulecollection/
---
**상속:**  
java.lang.Object

**모든 구현된 인터페이스:**  
[com.aspose.slides.IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)  
```
public final class VbaModuleCollection implements IVbaModuleCollection
```

VBA 프로젝트 모듈의 컬렉션을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [size()](#size--) | 컬렉션에 실제로 포함된 요소 수를 반환합니다. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | 컬렉션에서 특정 객체의 첫 번째 발생을 제거합니다. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | VBA 프로젝트에 새로운 빈 모듈을 추가합니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스의 요소를 반환합니다. |
| [iterator()](#iterator--) | 컬렉션을 반복하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java 이터레이터를 반환합니다. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 컬렉션의 모든 요소를 지정된 배열에 복사합니다. |
| [isSynchronized()](#isSynchronized--) | 컬렉션에 대한 액세스가 동기화(스레드 안전)된 여부를 나타내는 값을 반환합니다. |
| [getSyncRoot()](#getSyncRoot--) | 동기화 루트를 반환합니다. |

### size() {#size--}
```
public final int size()
```

컬렉션에 실제로 포함된 요소 수를 반환합니다. 읽기 전용 int.

**반환값:**  
int

### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public final void remove(IVbaModule value)
```

컬렉션에서 특정 객체의 첫 번째 발생을 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | 컬렉션에서 제거할 모듈 |

### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public final IVbaModule addEmptyModule(String name)
```

VBA 프로젝트에 새로운 빈 모듈을 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 모듈의 이름 |

**반환값:**  
[IVbaModule](../../com.aspose.slides/ivbamodule) - 추가된 모듈.

### get_Item(int index) {#get-Item-int-}
```
public final IVbaModule get_Item(int index)
```

지정된 인덱스의 요소를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**  
[IVbaModule](../../com.aspose.slides/ivbamodule)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iterator()
```

컬렉션을 반복하는 열거자를 반환합니다.

**반환값:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - 컬렉션을 반복하는 데 사용할 수 있는 IGenericEnumerator

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iteratorJava()
```

전체 컬렉션에 대한 java 이터레이터를 반환합니다.

**반환값:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - 전체 컬렉션에 대한 java.util.Iterator

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

컬렉션의 모든 요소를 지정된 배열에 복사합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 대상 배열. |
| index | int | 대상 배열에서 시작 인덱스. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

컬렉션에 대한 액세스가 동기화(스레드 안전)된 여부를 나타내는 값을 반환합니다. 읽기 전용 boolean.

**반환값:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

동기화 루트를 반환합니다. 읽기 전용 Object.

**반환값:**  
java.lang.Object
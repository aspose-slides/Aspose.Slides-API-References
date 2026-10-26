---
title: ControlPropertiesCollection
second_title: Aspose.Slides for Android용 Java API 레퍼런스
description: AcitveX 속성의 컬렉션입니다.
type: docs
url: /ko/com.aspose.slides/controlpropertiescollection/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
[com.aspose.slides.IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)  
```
public class ControlPropertiesCollection implements IControlPropertiesCollection
```

AcitveX 속성의 컬렉션입니다.

## 메서드

| Method | Description |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | 컬렉션에 속성을 추가합니다. |
| [remove(String name)](#remove-java.lang.String-) | 지정된 이름의 속성을 제거합니다. |
| [get_Item(String name)](#get-Item-java.lang.String-) | 속성을 반환하거나 설정합니다. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | 속성을 반환하거나 설정합니다. |
| [getNamesOfProperties()](#getNamesOfProperties--) | 속성 이름들의 컬렉션을 반환합니다. |
| [clear()](#clear--) | 모든 속성을 제거합니다. |
| [getCount()](#getCount--) | 컬렉션에 있는 속성의 개수를 반환합니다. |
| [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java 이터레이터를 반환합니다. |

### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final void add(String name, String value)
```

컬렉션에 속성을 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 속성의 이름. |
| value | java.lang.String | 속성의 값. |

### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

지정된 이름의 속성을 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 제거할 속성의 이름. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

속성을 반환하거나 설정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 속성의 이름. |

**반환:**
java.lang.String - 속성.

### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

속성을 반환하거나 설정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 속성의 이름. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

속성 이름들의 컬렉션을 반환합니다. 읽기 전용 [IGenericCollection](../../com.aspose.slides/igenericcollection).

**반환:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)

### clear() {#clear--}
```
public final void clear()
```

모든 속성을 제거합니다.

### getCount() {#getCount--}
```
public final int getCount()
```

컬렉션에 있는 속성의 개수를 반환합니다. 읽기 전용 int.

**반환:**
int

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

컬렉션을 순회하는 열거자를 반환합니다.

**반환:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - 컬렉션을 반복하는 데 사용할 수 있는 IGenericEnumerator.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

전체 컬렉션에 대한 java 이터레이터를 반환합니다.

**반환:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - 전체 컬렉션에 대한 java.util.Iterator.
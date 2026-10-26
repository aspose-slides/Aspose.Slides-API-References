---
title: IControlPropertiesCollection
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: ActiveX 컨트롤의 컬렉션입니다.
type: docs
url: /ko/com.aspose.slides/icontrolpropertiescollection/
---
**구현된 모든 인터페이스:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IControlPropertiesCollection extends System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,String>>
```

ActiveX 컨트롤의 컬렉션입니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getCount()](#getCount--) | 컬렉션에 있는 속성의 수를 반환합니다. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | 컬렉션에 속성을 추가합니다. |
| [remove(String name)](#remove-java.lang.String-) | 지정된 이름의 속성을 제거합니다. |
| [get_Item(String name)](#get-Item-java.lang.String-) | 속성을 반환하거나 설정합니다. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | 속성을 반환하거나 설정합니다. |
| [getNamesOfProperties()](#getNamesOfProperties--) | 컬렉션에 있는 속성의 수를 반환합니다. |
| [clear()](#clear--) | 모든 속성을 제거합니다. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

컬렉션에 있는 속성의 수를 반환합니다. 읽기 전용 int.

**반환:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract void add(String name, String value)
```

컬렉션에 속성을 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 속성의 이름. |
| value | java.lang.String | 속성의 값. |

### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

지정된 이름의 속성을 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 제거할 속성의 이름. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
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
public abstract void set_Item(String name, String value)
```

속성을 반환하거나 설정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 속성의 이름. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public abstract System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

컬렉션에 있는 속성의 수를 반환합니다. 읽기 전용 [IGenericCollection](../../com.aspose.slides/igenericcollection).

**반환:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public abstract void clear()
```

모든 속성을 제거합니다.
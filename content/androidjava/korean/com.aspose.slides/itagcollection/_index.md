---
title: ITagCollection
second_title: Aspose.Slides for Android - Java API 레퍼런스
description: 태그(사용자 정의 문자열 쌍)의 컬렉션을 나타냅니다
type: docs
url: /ko/com.aspose.slides/itagcollection/
---
**모든 구현된 인터페이스:**
com.aspose.slides.IGenericCollection
```
public interface ITagCollection extends IGenericCollection<System.Collections.Generic.KeyValuePair<String,String>>
```

태그(사용자 정의 문자열 쌍)의 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | 새로운 태그를 컬렉션에 추가합니다. |
| [remove(String name)](#remove-java.lang.String-) | 컬렉션에서 지정된 이름의 태그를 제거합니다. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | 컬렉션에서 지정된 키의 0 기반 인덱스를 반환합니다. |
| [contains(String name)](#contains-java.lang.String-) | 컬렉션에 특정 이름이 포함되어 있는지 확인합니다. |
| [removeAt(int index)](#removeAt-int-) | 지정된 인덱스에 있는 태그를 제거합니다. |
| [clear()](#clear--) | 컬렉션의 모든 태그를 제거합니다. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | 지정된 인덱스에 있는 태그의 값을 반환합니다. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | 지정된 인덱스에 있는 태그의 키를 반환합니다. |
| [getNamesOfTags()](#getNamesOfTags--) | 태그의 이름들을 반환합니다. |
| [get_Item(String name)](#get-Item-java.lang.String-) | 태그의 키와 값 쌍을 반환하거나 설정합니다. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | 태그의 키와 값 쌍을 반환하거나 설정합니다. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract int add(String name, String value)
```

새로운 태그를 컬렉션에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 태그의 이름. |
| value | java.lang.String | 태그의 값. |

**반환값:**
int - 추가된 태그의 인덱스.
### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

컬렉션에서 지정된 이름을 가진 태그를 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 제거할 태그의 이름. |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public abstract int indexOfName(String name)
```

컬렉션에서 지정된 키의 0 기반 인덱스를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 컬렉션에서 찾을 이름. |

**반환값:**
int - 키가 컬렉션에 있으면 그 키의 0 기반 인덱스; 그렇지 않으면 -1.
### contains(String name) {#contains-java.lang.String-}
```
public abstract boolean contains(String name)
```

컬렉션에 특정 이름이 포함되어 있는지 확인합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 찾을 키. |

**반환값:**
boolean - 지정된 키를 가진 태그가 컬렉션에 포함되어 있으면 True; 그렇지 않으면 false.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

지정된 인덱스에 있는 태그를 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 제거할 태그의 0 기반 인덱스. |
### clear() {#clear--}
```
public abstract void clear()
```

컬렉션의 모든 태그를 제거합니다.
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public abstract String getValueByIndex(int index)
```

지정된 인덱스에 있는 태그의 값을 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 반환할 태그의 인덱스. |

**반환값:**
java.lang.String - 태그의 값.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public abstract String getNameByIndex(int index)
```

지정된 인덱스에 있는 태그의 키를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 반환할 태그의 인덱스. |

**반환값:**
java.lang.String - 태그의 키.
### getNamesOfTags() {#getNamesOfTags--}
```
public abstract String[] getNamesOfTags()
```

태그의 이름들을 반환합니다.

**반환값:**
java.lang.String[] - 태그의 이름들.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```

태그의 키와 값 쌍을 반환하거나 설정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 태그의 키. |

**반환값:**
java.lang.String - 태그의 값.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```

태그의 키와 값 쌍을 반환하거나 설정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 태그의 키. |
| value | java.lang.String |  |
---
title: GetAttribute()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 이름을 가진 속성의 값을 반환합니다.
type: docs
weight: 287
url: /ko/system.xml/xmlnodereader/getattribute/
---
## XmlNodeReader::GetAttribute(String) method


지정된 이름을 가진 속성의 값을 반환합니다.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 속성의 한정된 이름. |

### 반환 값

지정된 속성의 값입니다. 속성을 찾을 수 없는 경우 **nullptr**가 반환됩니다.

## XmlNodeReader::GetAttribute(String, String) method


지정된 로컬 이름 및 네임스페이스 URI를 가진 속성의 값을 반환합니다.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name, String namespaceURI) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 속성의 로컬 이름. |
| namespaceURI | [String](../../../system/string/) | 속성의 네임스페이스 URI. |

### 반환 값

지정된 속성의 값입니다. 속성을 찾을 수 없는 경우 **nullptr**가 반환됩니다.

## XmlNodeReader::GetAttribute(int32_t) method


지정된 인덱스를 가진 속성의 값을 반환합니다.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(int32_t attributeIndex) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| attributeIndex | **int32_t** | 속성의 인덱스입니다. 인덱스는 0부터 시작합니다. (첫 번째 속성의 인덱스는 0입니다.) |

### 반환 값

지정된 속성의 값입니다.

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [XmlNodeReader](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)
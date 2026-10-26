---
title: GetAttribute()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 이름을 가진 속성의 값을 반환합니다.
type: docs
weight: 495
url: /ko/system.xml/xmltextreader/getattribute/
---
## XmlTextReader::GetAttribute(String) 메서드


지정된 이름을 가진 속성의 값을 반환합니다.

```cpp
String System::Xml::XmlTextReader::GetAttribute(String name) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 속성의 정규화된 이름. |

### 반환 값

지정된 속성의 값. 속성을 찾을 수 없으면 **nullptr**가 반환됩니다.

## XmlTextReader::GetAttribute(String, String) 메서드


지정된 로컬 이름 및 네임스페이스 URI를 가진 속성의 값을 반환합니다.

```cpp
String System::Xml::XmlTextReader::GetAttribute(String localName, String namespaceURI) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 속성의 로컬 이름. |
| namespaceURI | [String](../../../system/string/) | 속성의 네임스페이스 URI. |

### 반환 값

지정된 속성의 값. 속성을 찾을 수 없으면 **nullptr**가 반환됩니다. 이 메서드는 리더를 이동하지 않습니다.

## XmlTextReader::GetAttribute(int32_t) 메서드


지정된 인덱스를 가진 속성의 값을 반환합니다.

```cpp
String System::Xml::XmlTextReader::GetAttribute(int32_t i) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| i | **int32_t** | 속성의 인덱스. 인덱스는 0부터 시작합니다. (첫 번째 속성의 인덱스는 0입니다.) |

### 반환 값

지정된 속성의 값.

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [XmlTextReader](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)
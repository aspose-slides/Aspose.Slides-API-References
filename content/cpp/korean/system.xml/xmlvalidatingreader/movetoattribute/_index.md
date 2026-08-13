---
title: MoveToAttribute()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 이름을 가진 속성으로 이동합니다.
type: docs
weight: 456
url: /ko/system.xml/xmlvalidatingreader/movetoattribute/
---
## XmlValidatingReader::MoveToAttribute(String) 메서드

지정된 이름을 가진 속성으로 이동합니다.

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String name) override
```

### 인수

| 매개 변수 | 유형 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 속성의 정규화된 이름. |

### 반환값

**true**가 속성을 찾으면; 그렇지 않으면 **false**. **false**인 경우, 리더의 위치는 변경되지 않습니다.

## XmlValidatingReader::MoveToAttribute(String, String) 메서드

지정된 로컬 이름과 네임스페이스 Uniform Resource Identifier (URI)를 가진 속성으로 이동합니다.

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String localName, String namespaceURI) override
```

### 인수

| 매개 변수 | 유형 | 설명 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 속성의 로컬 이름. |
| namespaceURI | [String](../../../system/string/) | 속성의 네임스페이스 URI. |

### 반환값

**true**가 속성을 찾으면; 그렇지 않으면 **false**. **false**인 경우, 리더의 위치는 변경되지 않습니다.

## XmlValidatingReader::MoveToAttribute(int32_t) 메서드

지정된 인덱스를 가진 속성으로 이동합니다.

```cpp
void System::Xml::XmlValidatingReader::MoveToAttribute(int32_t i) override
```

### 인수

| 매개 변수 | 유형 | 설명 |
| --- | --- | --- |
| i | **int32_t** | 속성의 인덱스. |

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [XmlValidatingReader](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)
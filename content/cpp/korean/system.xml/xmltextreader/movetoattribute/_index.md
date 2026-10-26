---
title: MoveToAttribute()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 이름을 가진 속성으로 이동합니다.
type: docs
weight: 508
url: /ko/system.xml/xmltextreader/movetoattribute/
---
## XmlTextReader::MoveToAttribute(String) 메서드

지정된 이름을 가진 속성으로 이동합니다.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String name) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 속성의 정규화된 이름. |

### 반환 값

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

## XmlTextReader::MoveToAttribute(String, String) 메서드

지정된 로컬 이름 및 네임스페이스 URI를 가진 속성으로 이동합니다.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String localName, String namespaceURI) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 속성의 로컬 이름. |
| namespaceURI | [String](../../../system/string/) | 속성의 네임스페이스 URI. |

### 반환 값

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

## XmlTextReader::MoveToAttribute(int32_t) 메서드

지정된 인덱스를 가진 속성으로 이동합니다.

```cpp
void System::Xml::XmlTextReader::MoveToAttribute(int32_t i) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| i | **int32_t** | 속성의 인덱스. |

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [XmlTextReader](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)
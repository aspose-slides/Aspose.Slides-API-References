---
title: MoveToAttribute()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 이름을 가진 속성으로 이동합니다.
type: docs
weight: 300
url: /ko/system.xml/xmlnodereader/movetoattribute/
---
## XmlNodeReader::MoveToAttribute(String) 메서드

지정된 이름을 가진 속성으로 이동합니다.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 속성의 정규화된 이름입니다. |

### 반환값

**true**가 반환되면 속성을 찾은 것이며, 그렇지 않으면 **false**가 반환됩니다. **false**인 경우 리더의 위치는 변경되지 않습니다.

## XmlNodeReader::MoveToAttribute(String, String) 메서드

지정된 로컬 이름 및 네임스페이스 URI를 가진 속성으로 이동합니다.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name, String namespaceURI) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 속성의 로컬 이름입니다. |
| namespaceURI | [String](../../../system/string/) | 속성의 네임스페이스 URI입니다. |

### 반환값

**true**가 반환되면 속성을 찾은 것이며, 그렇지 않으면 **false**가 반환됩니다. **false**인 경우 리더의 위치는 변경되지 않습니다.

## XmlNodeReader::MoveToAttribute(int32_t) 메서드

지정된 인덱스를 가진 속성으로 이동합니다.

```cpp
void System::Xml::XmlNodeReader::MoveToAttribute(int32_t attributeIndex) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| attributeIndex | **int32_t** | 속성의 인덱스입니다. |

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [XmlNodeReader](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)
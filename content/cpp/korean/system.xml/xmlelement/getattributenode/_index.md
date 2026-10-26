---
title: GetAttributeNode()
second_title: Aspose.Slides C++용 API 참조
description: 지정된 이름을 가진 XmlAttribute를 반환합니다.
type: docs
weight: 248
url: /ko/system.xml/xmlelement/getattributenode/
---
## XmlElement::GetAttributeNode(String) 메서드

지정된 이름을 가진 [XmlAttribute](../../xmlattribute/)을 반환합니다.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String name)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 검색할 속성의 이름입니다. 이는 한정된 이름(qualified name)입니다. 일치하는 노드의 **get_Name** 값과 비교됩니다. |

### 반환 값

지정된 [XmlAttribute](../../xmlattribute/) 또는 일치하는 속성을 찾지 못한 경우 **nullptr**를 반환합니다.

## XmlElement::GetAttributeNode(String, String) 메서드

지정된 로컬 이름 및 네임스페이스 URI를 가진 [XmlAttribute](../../xmlattribute/)을 반환합니다.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String localName, String namespaceURI)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 속성의 로컬 이름입니다. |
| namespaceURI | [String](../../../system/string/) | 속성의 네임스페이스 URI입니다. |

### 반환 값

지정된 [XmlAttribute](../../xmlattribute/) 또는 일치하는 속성을 찾지 못한 경우 **nullptr**를 반환합니다.

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlAttribute](../../xmlattribute/)
* 클래스 [String](../../../system/string/)
* 클래스 [XmlElement](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)
---
title: SetAttributeNode()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 XmlAttribute를 추가합니다.
type: docs
weight: 261
url: /ko/system.xml/xmlelement/setattributenode/
---
## XmlElement::SetAttributeNode(SharedPtr\<XmlAttribute\>) 메서드

지정된 [XmlAttribute](../../xmlattribute/)을 추가합니다.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(SharedPtr<XmlAttribute> newAttr)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | 이 요소의 속성 컬렉션에 추가할 [XmlAttribute](../../xmlattribute/) 노드. |

### 반환값

속성이 동일한 이름의 기존 속성을 교체하면, 기존 [XmlAttribute](../../xmlattribute/)가 반환됩니다; 그렇지 않으면 **nullptr**가 반환됩니다.

## XmlElement::SetAttributeNode(String, String) 메서드

지정된 [XmlAttribute](../../xmlattribute/)을 추가합니다.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(String localName, String namespaceURI)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 속성의 로컬 이름. |
| namespaceURI | [String](../../../system/string/) | 속성의 네임스페이스 URI. |

### 반환값

[XmlAttribute](../../xmlattribute/)를 추가합니다.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlElement](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
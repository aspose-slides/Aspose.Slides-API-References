---
title: RemoveAttributeNode()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 XmlAttribute를 제거합니다.
type: docs
weight: 274
url: /ko/system.xml/xmlelement/removeattributenode/
---
## XmlElement::RemoveAttributeNode(SharedPtr\<XmlAttribute\>) 메서드


지정된 [XmlAttribute](../../xmlattribute/)을 제거합니다.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(SharedPtr<XmlAttribute> oldAttr)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| oldAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | 제거할 [XmlAttribute](../../xmlattribute/) 노드입니다. 제거된 속성에 기본값이 있으면 즉시 대체됩니다. |

### 반환 값

제거된 [XmlAttribute](../../xmlattribute/) 또는 **oldAttr**가 [XmlElement](../)의 속성 노드가 아니면 **nullptr**를 반환합니다.

## XmlElement::RemoveAttributeNode(String, String) 메서드


로컬 이름 및 네임스페이스 URI로 지정된 [XmlAttribute](../../xmlattribute/)를 제거합니다. (제거된 속성에 기본값이 있으면 즉시 대체됩니다).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(String localName, String namespaceURI)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 속성의 로컬 이름입니다. |
| namespaceURI | [String](../../../system/string/) | 속성의 네임스페이스 URI입니다. |

### 반환 값

제거된 [XmlAttribute](../../xmlattribute/) 또는 [XmlElement](../)에 일치하는 속성 노드가 없으면 **nullptr**를 반환합니다.

## 또 보기

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlElement](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
---
title: GetNamedItem()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 이름으로 XmlNode를 검색합니다.
type: docs
weight: 14
url: /ko/system.xml/xmlnamednodemap/getnameditem/
---
## XmlNamedNodeMap::GetNamedItem(String) 메서드


지정된 이름으로 [XmlNode](../../xmlnode/)를 검색합니다.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String name)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 검색할 노드의 정규화된 이름입니다. 일치하는 노드의 [XmlNode::get_Name](../../xmlnode/get_name/) 값과 비교됩니다. |

### 반환값

지정된 이름을 가진 [XmlNode](../../xmlnode/)이며, 일치하는 노드가 없으면 **nullptr**을 반환합니다.

## XmlNamedNodeMap::GetNamedItem(String, String) 메서드


일치하는 [XmlNode::get_LocalName](../../xmlnode/get_localname/) 및 [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) 값을 가진 노드를 검색합니다.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String localName, String namespaceURI)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 검색할 노드의 로컬 이름입니다. |
| namespaceURI | [String](../../../system/string/) | 검색할 노드의 네임스페이스 URI(Uniform Resource Identifier)입니다. |

### 반환값

일치하는 로컬 이름과 네임스페이스 URI를 가진 [XmlNode](../../xmlnode/)이며, 일치하는 노드가 없으면 **nullptr**을 반환합니다.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlNode](../../xmlnode/)
* 클래스 [String](../../../system/string/)
* 클래스 [XmlNamedNodeMap](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)
---
title: RemoveNamedItem()
second_title: Aspose.Slides for C++ API 레퍼런스
description: XmlNamedNodeMap에서 노드를 제거합니다.
type: docs
weight: 40
url: /ko/system.xml/xmlnamednodemap/removenameditem/
---
## XmlNamedNodeMap::RemoveNamedItem(String) method

노드를 [XmlNamedNodeMap](../)에서 제거합니다.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String name)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 제거할 노드의 정규화된 이름입니다. 이름은 일치하는 노드의 [XmlNode::get_Name](../../xmlnode/get_name/) 값과 비교됩니다. |

### 반환값

[XmlNode](../../xmlnode/)을(를) 이 [XmlNamedNodeMap](../)에서 제거했으며, 일치하는 노드를 찾지 못하면 **nullptr**를 반환합니다.

## XmlNamedNodeMap::RemoveNamedItem(String, String) method

일치하는 [XmlNode::get_LocalName](../../xmlnode/get_localname/) 및 [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) 값을 가진 노드를 제거합니다.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String localName, String namespaceURI)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 제거할 노드의 로컬 이름입니다. |
| namespaceURI | [String](../../../system/string/) | 제거할 노드의 네임스페이스 URI입니다. |

### 반환값

[XmlNode](../../xmlnode/)을(를) 제거했으며, 일치하는 노드를 찾지 못하면 **nullptr**를 반환합니다.

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlNode](../../xmlnode/)
* 클래스 [String](../../../system/string/)
* 클래스 [XmlNamedNodeMap](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)
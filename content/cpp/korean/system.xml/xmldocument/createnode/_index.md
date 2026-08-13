---
title: CreateNode()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "지정된 XmlNodeType, XmlNode::get_Prefix, XmlDocument::get_Name 및 XmlNode::get_NamespaceURI를 사용하여 XmlNode를 생성합니다."
type: docs
weight: 482
url: /ko/system.xml/xmldocument/createnode/
---
## XmlDocument::CreateNode(XmlNodeType, const String\&, const String\&, const String\&) 메서드

지정된 XmlNodeType, [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_Name](../get_name/) 및 [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/)를 사용하여 [XmlNode](../../xmlnode/)를 생성합니다.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &prefix, const String &name, const String &namespaceURI)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | 새 노드의 XmlNodeType. |
| prefix | const [String](../../../system/string/)\& | 새 노드의 접두사. |
| name | const [String](../../../system/string/)\& | 새 노드의 로컬 이름. |
| namespaceURI | const [String](../../../system/string/)\& | 새 노드의 네임스페이스 URI. |

### 반환값

새 [XmlNode](../../xmlnode/).

## XmlDocument::CreateNode(const String\&, const String\&, const String\&) 메서드

지정된 노드 유형, [XmlDocument::get_Name](../get_name/), 및 [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/)를 사용하여 [XmlNode](../../xmlnode/)를 생성합니다.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(const String &nodeTypeString, const String &name, const String &namespaceURI)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| nodeTypeString | const [String](../../../system/string/)\& | [String](../../../system/string/) 버전의 새 노드의 XmlNodeType. 이 매개변수는 아래 표에 나열된 값 중 하나여야 합니다. |
| name | const [String](../../../system/string/)\& | 새 노드의 한정 이름. 이름에 콜론이 포함된 경우 [XmlNode::get_Prefix](../../xmlnode/get_prefix/)와 [XmlDocument::get_LocalName](../get_localname/) 구성 요소로 구문 분석됩니다. |
| namespaceURI | const [String](../../../system/string/)\& | 새 노드의 네임스페이스 URI. |

### 반환값

새 [XmlNode](../../xmlnode/).

## 비고

**nodeTypeString** 매개변수는 대소문자를 구분하며 다음 표에 있는 값 중 하나여야 합니다:

| nodeTypeString | XmlNodeType |
| --- | --- |
| attribute | [Attribute](../../../system/attribute/) |
| cdatasection | CDATA |
| comment | Comment |
| document | Document |
| documentfragment | DocumentFragment |
| documenttype | DocumentType |
| element | Element |
| entityreference | EntityReference |
| processinginstruction | ProcessingInstruction |
| significantwhitespace | SignificantWhitespace |
| text | [Text](../../../system.text/) |
| whitespace | Whitespace |

## XmlDocument::CreateNode(XmlNodeType, const String\&, const String\&) 메서드

지정된 XmlNodeType, [XmlDocument::get_Name](../get_name/), 및 [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/)를 사용하여 [XmlNode](../../xmlnode/)를 생성합니다.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &name, const String &namespaceURI)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | 새 노드의 XmlNodeType. |
| name | const [String](../../../system/string/)\& | 새 노드의 한정 이름. 이름에 콜론이 포함된 경우 [XmlNode::get_Prefix](../../xmlnode/get_prefix/)와 [XmlDocument::get_LocalName](../get_localname/) 구성 요소로 구문 분석됩니다. |
| namespaceURI | const [String](../../../system/string/)\& | 새 노드의 네임스페이스 URI. |

### 반환값

새 [XmlNode](../../xmlnode/).

## 참조

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
---
title: CreateElement()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 이름으로 요소를 생성합니다.
type: docs
weight: 339
url: /ko/system.xml/xmldocument/createelement/
---
## XmlDocument::CreateElement(const String\&) 메서드

Creates an element with the specified name.

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &name)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 요소의 정규화된 이름입니다. 이름에 콜론이 포함된 경우 [XmlNode::get_Prefix](../../xmlnode/get_prefix/) 값은 콜론 앞부분을, [XmlDocument::get_LocalName](../get_localname/) 값은 콜론 뒤부분을 반영합니다. 정규화된 이름에는 **xmlns** 접두사를 포함할 수 없습니다. |

### 반환 값

새 [XmlElement](../../xmlelement/).

## XmlDocument::CreateElement(const String\&, const String\&) 메서드

Creates an [XmlElement](../../xmlelement/) with the qualified name and [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &qualifiedName, const String &namespaceURI)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | 요소의 정규화된 이름입니다. 이름에 콜론이 포함된 경우 [XmlNode::get_Prefix](../../xmlnode/get_prefix/) 값은 콜론 앞부분을, [XmlDocument::get_LocalName](../get_localname/) 값은 콜론 뒤부분을 반영합니다. 정규화된 이름에는 **xmlns** 접두사를 포함할 수 없습니다. |
| namespaceURI | const [String](../../../system/string/)\& | 요소의 네임스페이스 URI입니다. |

### 반환 값

새 [XmlElement](../../xmlelement/).

## XmlDocument::CreateElement(const String\&, const String\&, const String\&) 메서드

Creates an element with the specified [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_LocalName](../get_localname/), and [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &prefix, const String &localName, const String &namespaceURI)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 새 요소의 접두사(있는 경우). [String::Empty](../../../system/string/empty/) 및 **nullptr**는 동일합니다. |
| localName | const [String](../../../system/string/)\& | 새 요소의 로컬 이름입니다. |
| namespaceURI | const [String](../../../system/string/)\& | 새 요소의 네임스페이스 URI(있는 경우). [String::Empty](../../../system/string/empty/) 및 **nullptr**는 동일합니다. |

### 반환 값

새 [XmlElement](../../xmlelement/).

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlElement](../../xmlelement/)
* 클래스 [String](../../../system/string/)
* 클래스 [XmlDocument](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)
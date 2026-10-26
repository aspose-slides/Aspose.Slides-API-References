---
title: SelectSingleNode()
second_title: Aspose.Slides for C++ API 레퍼런스
description: XPath 표현식과 일치하는 첫 번째 XmlNode를 선택합니다.
type: docs
weight: 352
url: /ko/system.xml/xmlnode/selectsinglenode/
---
## XmlNode::SelectSingleNode(const String\&) 메서드

[XPath](../../../system.xml.xpath/) 표현식과 일치하는 첫 번째 [XmlNode](../)를 선택합니다.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | [XPath](../../../system.xml.xpath/) 표현식. |

### 반환값

[XPath](../../../system.xml.xpath/) 쿼리와 일치하는 첫 번째 [XmlNode](../)를 반환합니다. 일치하는 노드가 없으면 **nullptr**를 반환합니다.

## XmlNode::SelectSingleNode(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) 메서드

[XPath](../../../system.xml.xpath/) 표현식과 일치하는 첫 번째 [XmlNode](../)를 선택합니다. [XPath](../../../system.xml.xpath/) 표현식에서 찾은 모든 접두사는 제공된 [XmlNamespaceManager](../../xmlnamespacemanager/)을 사용하여 해석됩니다.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | [XPath](../../../system.xml.xpath/) 표현식. |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XPath](../../../system.xml.xpath/) 표현식에서 접두사의 네임스페이스를 해석하는 데 사용할 [XmlNamespaceManager](../../xmlnamespacemanager/). |

### 반환값

[XPath](../../../system.xml.xpath/) 쿼리와 일치하는 첫 번째 [XmlNode](../)를 반환합니다. 일치하는 노드가 없으면 **nullptr**를 반환합니다.

## 또한 보기

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../)
* Class [String](../../../system/string/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
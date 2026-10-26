---
title: SelectNodes()
second_title: Aspose.Slides for C++ API 참조
description: XPath 식과 일치하는 노드 목록을 선택합니다.
type: docs
weight: 365
url: /ko/system.xml/xmlnode/selectnodes/
---
## XmlNode::SelectNodes(const String\&) method


[XPath](../../../system.xml.xpath/) 표현식과 일치하는 노드 목록을 선택합니다.

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath)
```


### Arguments

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | [XPath](../../../system.xml.xpath/) 표현식. |

### Return Value

[XPath](../../../system.xml.xpath/) 쿼리와 일치하는 노드 컬렉션을 포함하는 [XmlNodeList](../../xmlnodelist/).

## XmlNode::SelectNodes(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) method


[XPath](../../../system.xml.xpath/) 표현식과 일치하는 노드 목록을 선택합니다. [XPath](../../../system.xml.xpath/) 표현식에서 발견된 모든 접두사는 제공된 [XmlNamespaceManager](../../xmlnamespacemanager/)을 사용하여 해결됩니다.

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```


### Arguments

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | [XPath](../../../system.xml.xpath/) 표현식. |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XPath](../../../system.xml.xpath/) 표현식의 접두사에 대한 네임스페이스를 해결하는 데 사용할 [XmlNamespaceManager](../../xmlnamespacemanager/). |

### Return Value

[XPath](../../../system.xml.xpath/) 쿼리와 일치하는 노드 컬렉션을 포함하는 [XmlNodeList](../../xmlnodelist/).

## See Also

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlNodeList](../../xmlnodelist/)
* 클래스 [String](../../../system/string/)
* 클래스 [XmlNode](../)
* 클래스 [XmlNamespaceManager](../../xmlnamespacemanager/)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)
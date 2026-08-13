---
title: SelectDescendants()
second_title: Aspose.Slides for C++ API 참조
description: 현재 노드의 하위 노드 중 XPathNodeType과 일치하는 모든 하위 노드를 선택합니다.
type: docs
weight: 859
url: /ko/system.xml.xpath/xpathnavigator/selectdescendants/
---
## XPathNavigator::SelectDescendants(XPathNodeType, bool) 메서드

현재 노드의 하위 노드 중 XPathNodeType과 일치하는 모든 하위 노드를 선택합니다.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(XPathNodeType type, bool matchSelf)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | 하위 노드의 XPathNodeType. |
| matchSelf | **bool** | **true** 를 선택에 컨텍스트 노드를 포함하도록; 그렇지 않으면 **false**. |

### Return Value

선택된 노드를 포함하는 [XPathNodeIterator](../../xpathnodeiterator/).

## XPathNavigator::SelectDescendants(String, String, bool) 메서드

지정된 로컬 이름 및 네임스페이스 URI를 가진 현재 노드의 모든 하위 노드를 선택합니다.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(String name, String namespaceURI, bool matchSelf)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 하위 노드의 로컬 이름. |
| namespaceURI | [String](../../../system/string/) | 하위 노드의 네임스페이스 URI. |
| matchSelf | **bool** | **true** 를 선택에 컨텍스트 노드를 포함하도록; 그렇지 않으면 **false**. |

### Return Value

선택된 노드를 포함하는 [XPathNodeIterator](../../xpathnodeiterator/).

## 참고

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)
---
title: SelectChildren()
second_title: Aspose.Slides for C++ API 참조
description: 현재 노드에서 일치하는 XPathNodeType을 가진 모든 하위 노드를 선택합니다.
type: docs
weight: 833
url: /ko/system.xml.xpath/xpathnavigator/selectchildren/
---
## XPathNavigator::SelectChildren(XPathNodeType) 메서드

현재 노드에서 일치하는 XPathNodeType을 가진 모든 하위 노드를 선택합니다.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(XPathNodeType type)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | 하위 노드의 XPathNodeType. |

### 반환값

선택된 노드를 포함하는 [XPathNodeIterator](../../xpathnodeiterator/).

## XPathNavigator::SelectChildren(String, String) 메서드

지정된 로컬 이름과 네임스페이스 URI를 가진 현재 노드의 모든 하위 노드를 선택합니다.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(String name, String namespaceURI)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 하위 노드의 로컬 이름. |
| namespaceURI | [String](../../../system/string/) | 하위 노드의 네임스페이스 URI. |

### 반환값

선택된 노드를 포함하는 [XPathNodeIterator](../../xpathnodeiterator/).

## 참고

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XPathNodeIterator](../../xpathnodeiterator/)
* 클래스 [XPathNavigator](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Xml::XPath](../../)
* 라이브러리 [Aspose.Slides](../../../)
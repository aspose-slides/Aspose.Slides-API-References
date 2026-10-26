---
title: MoveToChild()
second_title: Aspose.Slides for C++ API 레퍼런스
description: XPathNavigator를 지정된 로컬 이름 및 네임스페이스 URI를 가진 자식 노드로 이동합니다.
type: docs
weight: 690
url: /ko/system.xml.xpath/xpathnavigator/movetochild/
---
## XPathNavigator::MoveToChild(String, String) 메서드

[XPathNavigator](../)를 지정된 로컬 이름 및 네임스페이스 URI를 가진 자식 노드로 이동합니다.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(String localName, String namespaceURI)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 이동할 자식 노드의 로컬 이름입니다. |
| namespaceURI | [String](../../../system/string/) | 이동할 자식 노드의 네임스페이스 URI입니다. |

### 반환값

**true** if the [XPathNavigator](../) is successful moving to the child node; otherwise, **false**. If **false**, the position of the [XPathNavigator](../) is unchanged.

## XPathNavigator::MoveToChild(XPathNodeType) 메서드

[XPathNavigator](../)를 지정된 XPathNodeType의 자식 노드로 이동합니다.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(XPathNodeType type)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | 이동할 자식 노드의 XPathNodeType입니다. |

### 반환값

**true** if the [XPathNavigator](../) is successful moving to the child node; otherwise, **false**. If **false**, the position of the [XPathNavigator](../) is unchanged.

## 참조

* 열거형 [XPathNodeType](../../xpathnodetype/)
* 클래스 [String](../../../system/string/)
* 클래스 [XPathNavigator](../)
* 네임스페이스 [System::Xml::XPath](../../)
* 라이브러리 [Aspose.Slides](../../../)
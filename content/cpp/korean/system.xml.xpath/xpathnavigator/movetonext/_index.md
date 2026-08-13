---
title: MoveToNext()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 파생 클래스에서 재정의될 경우, XPathNavigator를 현재 노드의 다음 형제 노드로 이동합니다.
type: docs
weight: 586
url: /ko/system.xml.xpath/xpathnavigator/movetonext/
---
## XPathNavigator::MoveToNext() 메서드


파생 클래스에서 재정의될 경우, [XPathNavigator](../)를 현재 노드의 다음 형제 노드로 이동합니다.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext()=0
```


### 반환값

**true** if the [XPathNavigator](../) is successful moving to the next sibling node; otherwise **false** if there are no more siblings or if the [XPathNavigator](../) is currently positioned on an attribute node. If **false**, the position of the [XPathNavigator](../) is unchanged.

## XPathNavigator::MoveToNext(String, String) 메서드


지정된 로컬 이름 및 네임스페이스 URI를 가진 다음 형제 노드로 [XPathNavigator](../)를 이동합니다.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(String localName, String namespaceURI)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 이동할 다음 형제 노드의 로컬 이름입니다. |
| namespaceURI | [String](../../../system/string/) | 이동할 다음 형제 노드의 네임스페이스 URI입니다. |

### 반환값

**true** if the [XPathNavigator](../) is successful moving to the next sibling node; **false** if there are no more siblings, or if the [XPathNavigator](../) is currently positioned on an attribute node. If **false**, the position of the [XPathNavigator](../) is unchanged.

## XPathNavigator::MoveToNext(XPathNodeType) 메서드


지정된 XPathNodeType과 일치하는 현재 노드의 다음 형제 노드로 [XPathNavigator](../)를 이동합니다.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(XPathNodeType type)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | 이동할 형제 노드의 XPathNodeType입니다. |

### 반환값

**true** if the [XPathNavigator](../) is successful moving to the next sibling node; otherwise, **false** if there are no more siblings or if the [XPathNavigator](../) is currently positioned on an attribute node. If **false**, the position of the [XPathNavigator](../) is unchanged.

## 참고

* Enum [XPathNodeType](../../xpathnodetype/)
* 클래스 [XPathNavigator](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)
---
title: MoveToNextNamespace()
second_title: Aspose.Slides for C++ API 참조
description: 파생 클래스에서 재정의될 경우, 지정된 XPathNamespaceScope와 일치하는 다음 네임스페이스 노드로 XPathNavigator를 이동합니다.
type: docs
weight: 573
url: /ko/system.xml.xpath/xpathnavigator/movetonextnamespace/
---
## XPathNavigator::MoveToNextNamespace(XPathNamespaceScope) 메서드

파생 클래스에서 재정의될 경우, 지정된 XPathNamespaceScope와 일치하는 다음 네임스페이스 노드로 [XPathNavigator](../)를 이동합니다.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNextNamespace(XPathNamespaceScope namespaceScope)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| namespaceScope | [XPathNamespaceScope](../../xpathnamespacescope/) | 네임스페이스 범위를 설명하는 XPathNamespaceScope 값입니다. |

### 반환 값

[XPathNavigator](../)이(가) 다음 네임스페이스 노드로 이동하는 데 성공하면 **true**, 그렇지 않으면 **false**. **false**인 경우, [XPathNavigator](../)의 위치는 변경되지 않습니다.

## XPathNavigator::MoveToNextNamespace() 메서드

[XPathNavigator](../)를 다음 네임스페이스 노드로 이동합니다.

```cpp
bool System::Xml::XPath::XPathNavigator::MoveToNextNamespace()
```

### 반환 값

[XPathNavigator](../)이(가) 다음 네임스페이스 노드로 이동하는 데 성공하면 **true**, 그렇지 않으면 **false**. **false**인 경우, [XPathNavigator](../)의 위치는 변경되지 않습니다.

## 참조

* Enum [XPathNamespaceScope](../../xpathnamespacescope/)
* 클래스 [XPathNavigator](../)
* 네임스페이스 [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)
---
title: MoveToFirstNamespace()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 파생 클래스에서 재정의될 경우, 지정된 XPathNamespaceScope와 일치하는 첫 번째 네임스페이스 노드로 XPathNavigator를 이동합니다.
type: docs
weight: 560
url: /ko/system.xml.xpath/xpathnavigator/movetofirstnamespace/
---
## XPathNavigator::MoveToFirstNamespace(XPathNamespaceScope) 메서드

파생 클래스에서 재정의될 경우, [XPathNavigator](../)를 지정된 XPathNamespaceScope와 일치하는 첫 번째 네임스페이스 노드로 이동합니다.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFirstNamespace(XPathNamespaceScope namespaceScope)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| namespaceScope | [XPathNamespaceScope](../../xpathnamespacescope/) | 네임스페이스 범위를 설명하는 XPathNamespaceScope 값. |

### 반환값

**true**이면 [XPathNavigator](../)가 첫 번째 네임스페이스 노드로 이동하는 데 성공한 것이고, 그렇지 않으면 **false**입니다. **false**인 경우, [XPathNavigator](../)의 위치는 변경되지 않습니다.

## XPathNavigator::MoveToFirstNamespace() 메서드

[XPathNavigator](../)를 현재 노드의 첫 번째 네임스페이스 노드로 이동합니다.

```cpp
bool System::Xml::XPath::XPathNavigator::MoveToFirstNamespace()
```

### 반환값

**true**이면 [XPathNavigator](../)가 첫 번째 네임스페이스 노드로 이동하는 데 성공한 것이고, 그렇지 않으면 **false**입니다. **false**인 경우, [XPathNavigator](../)의 위치는 변경되지 않습니다.

## 참고

* 열거형 [XPathNamespaceScope](../../xpathnamespacescope/)
* 클래스 [XPathNavigator](../)
* 네임스페이스 [System::Xml::XPath](../../)
* 라이브러리 [Aspose.Slides](../../../)
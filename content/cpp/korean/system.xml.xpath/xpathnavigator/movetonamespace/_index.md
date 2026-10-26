---
title: MoveToNamespace()
second_title: Aspose.Slides for C++ API 참조
description: XPathNavigator를 지정된 네임스페이스 접두사가 있는 네임스페이스 노드로 이동합니다.
type: docs
weight: 547
url: /ko/system.xml.xpath/xpathnavigator/movetonamespace/
---
## XPathNavigator::MoveToNamespace(String) 메서드

지정된 네임스페이스 접두사가 있는 네임스페이스 노드로 [XPathNavigator](../)를 이동합니다.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNamespace(String name)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 네임스페이스 노드의 네임스페이스 접두사입니다. |

### 반환값

**true** - [XPathNavigator](../)가 지정된 네임스페이스로 이동에 성공한 경우; **false** - 일치하는 네임스페이스 노드를 찾지 못했거나 [XPathNavigator](../)가 요소 노드에 위치하지 않은 경우. **false**인 경우, [XPathNavigator](../)의 위치는 변경되지 않습니다.

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [XPathNavigator](../)
* 네임스페이스 [System::Xml::XPath](../../)
* 라이브러리 [Aspose.Slides](../../../)
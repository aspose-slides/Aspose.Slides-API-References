---
title: get_Current()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 파생 클래스에서 재정의될 때, 현재 컨텍스트 노드에 위치한 이 XPathNodeIterator에 대한 XPathNavigator 객체를 가져옵니다.
type: docs
weight: 1
url: /ko/system.xml.xpath/xpathnodeiterator/get_current/
---
## XPathNodeIterator::get_Current() 메서드

파생 클래스에서 재정의될 때, 현재 컨텍스트 노드에 위치한 이 [XPathNodeIterator](../)에 대한 [XPathNavigator](../../xpathnavigator/) 객체를 가져옵니다.

```cpp
virtual const SharedPtr<XPathNavigator> & System::Xml::XPath::XPathNodeIterator::get_Current()=0
```

### 반환 값

선택된 노드 집합이 선택된 컨텍스트 노드에 위치한 [XPathNavigator](../../xpathnavigator/) 객체입니다. [XPathNodeIterator::MoveNext](../movenext/) 메서드를 호출해야 [XPathNodeIterator](../)를 선택된 집합의 첫 번째 노드로 이동합니다.

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [XPathNavigator](../../xpathnavigator/)
* 클래스 [XPathNodeIterator](../)
* 네임스페이스 [System::Xml::XPath](../../)
* 라이브러리 [Aspose.Slides](../../../)
---
title: MoveToFirst()
second_title: Aspose.Slides for C++ API 참조
description: XPathNavigator를 현재 노드의 첫 번째 형제 노드로 이동합니다.
type: docs
weight: 612
url: /ko/system.xml.xpath/xpathnavigator/movetofirst/
---
## XPathNavigator::MoveToFirst() 메서드


[XPathNavigator](../)를 현재 노드의 첫 번째 형제 노드로 이동합니다.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFirst()
```


### 반환 값

**true** 는 [XPathNavigator](../)가 현재 노드의 첫 번째 형제 노드로 성공적으로 이동했을 때; **false** 는 첫 번째 형제가 없거나 [XPathNavigator](../)가 현재 속성 노드에 위치해 있을 때 반환됩니다. [XPathNavigator](../)가 이미 첫 번째 형제에 위치해 있으면 [XPathNavigator](../)는 **true** 를 반환하고 위치를 이동하지 않습니다. [XPathNavigator::MoveToFirst](./)가 첫 번째 형제가 없어서 **false** 를 반환하거나 [XPathNavigator](../)가 현재 속성에 위치해 있는 경우, [XPathNavigator](../)의 위치는 변경되지 않습니다.

## See Also

* 클래스 [XPathNavigator](../)
* 네임스페이스 [System::Xml::XPath](../../)
* 라이브러리 [Aspose.Slides](../../../)
---
title: MoveTo()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 파생 클래스에서 재정의될 경우, XPathNavigator를 지정된 XPathNavigator와 동일한 위치로 이동합니다.
type: docs
weight: 664
url: /ko/system.xml.xpath/xpathnavigator/moveto/
---
## XPathNavigator::MoveTo(SharedPtr\<XPathNavigator\>) 메서드

파생 클래스에서 재정의될 경우, 지정된 [XPathNavigator](../)와 동일한 위치로 [XPathNavigator](../)를 이동합니다.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveTo(SharedPtr<XPathNavigator> other)=0
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | 이동하려는 노드에 위치한 [XPathNavigator](../). |

### 반환값

**true**는 [XPathNavigator](../)가 지정된 [XPathNavigator](../)와 동일한 위치로 성공적으로 이동한 경우이며, 그렇지 않으면 **false**입니다. **false**인 경우, [XPathNavigator](../)의 위치는 변경되지 않습니다.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XPathNavigator](../)
* 네임스페이스 [System::Xml::XPath](../../)
* 라이브러리 [Aspose.Slides](../../../)
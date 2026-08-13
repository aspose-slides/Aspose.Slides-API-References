---
title: MoveToId()
second_title: Aspose.Slides for C++ API 참조
description: 파생 클래스에서 재정의될 경우, 지정된 String과 일치하는 값의 ID 유형 속성을 가진 노드로 이동합니다.
type: docs
weight: 677
url: /ko/system.xml.xpath/xpathnavigator/movetoid/
---
## XPathNavigator::MoveToId(String) 메서드


파생 클래스에서 재정의될 경우, 지정된 [String](../../../system/string/)와 일치하는 **ID** 유형의 속성을 가진 노드로 이동합니다.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToId(String id)=0
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| id | [String](../../../system/string/) | [String](../../../system/string/)는 이동하려는 노드의 **ID** 값을 나타냅니다. |

### 반환 값

**true**는 [XPathNavigator](../)가 성공적으로 이동했을 때; 그렇지 않으면 **false**. **false**인 경우, 내비게이터의 위치는 변경되지 않습니다.

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [XPathNavigator](../)
* 네임스페이스 [System::Xml::XPath](../../)
* 라이브러리 [Aspose.Slides](../../../)
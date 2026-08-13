---
title: get_LocalName()
second_title: C++용 Aspose.Slides API 참조
description: "파생 클래스에서 재정의될 경우, 네임스페이스 접두사가 없는 현재 노드의 XPathNavigator::get_Name을 가져옵니다."
type: docs
weight: 144
url: /ko/system.xml.xpath/xpathnavigator/get_localname/
---
## XPathNavigator::get_LocalName() 메서드


파생 클래스에서 재정의되는 경우, 현재 노드의 [XPathNavigator::get_Name](../get_name/)를 네임스페이스 접두사 없이 가져옵니다.

```cpp
virtual String System::Xml::XPath::XPathNavigator::get_LocalName()=0
```


### 반환값

현재 노드의 로컬 이름을 포함하는 [String](../../../system/string/)이며, 현재 노드에 이름이 없는 경우(예: 텍스트 또는 주석 노드) [String::Empty](../../../system/string/empty/)를 반환합니다.

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [XPathNavigator](../)
* 네임스페이스 [System::Xml::XPath](../../)
* 라이브러리 [Aspose.Slides](../../../)
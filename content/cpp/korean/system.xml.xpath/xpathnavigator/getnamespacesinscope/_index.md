---
title: GetNamespacesInScope()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 노드의 범위 내 네임스페이스를 반환합니다.
type: docs
weight: 430
url: /ko/system.xml.xpath/xpathnavigator/getnamespacesinscope/
---
## XPathNavigator::GetNamespacesInScope(XmlNamespaceScope) 메서드


현재 노드의 범위 내 네임스페이스를 반환합니다.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XPath::XPathNavigator::GetNamespacesInScope(XmlNamespaceScope scope) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../../system.xml/xmlnamespacescope/) | 반환할 네임스페이스를 지정하는 XmlNamespaceScope 값입니다. |

### 반환 값

프리픽스로 키가 지정된 네임스페이스 이름의 IDictionary 컬렉션입니다.

## 관련 항목

* 열거형 [XmlNamespaceScope](../../../system.xml/xmlnamespacescope/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IDictionary](../../../system.collections.generic/idictionary/)
* 클래스 [String](../../../system/string/)
* 클래스 [XPathNavigator](../)
* 네임스페이스 [System::Xml::XPath](../../)
* 라이브러리 [Aspose.Slides](../../../)
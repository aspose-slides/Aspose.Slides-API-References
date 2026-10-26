---
title: AddNamespace()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 네임스페이스를 컬렉션에 추가합니다.
type: docs
weight: 66
url: /ko/system.xml/xmlnamespacemanager/addnamespace/
---
## XmlNamespaceManager::AddNamespace(String, String) 메서드

추가된 네임스페이스를 컬렉션에 추가합니다.

```cpp
virtual void System::Xml::XmlNamespaceManager::AddNamespace(String prefix, String uri)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | 추가되는 네임스페이스와 연결할 접두사입니다. 기본 네임스페이스를 추가하려면 [String::Empty](../../../system/string/empty/)를 사용하십시오. [XmlNamespaceManager](../)가 XML Path Language ([XPath](../../../system.xml.xpath/)) 식에서 네임스페이스를 해결하는 데 사용될 경우, 접두사를 지정해야 합니다. [XPath](../../../system.xml.xpath/) 식에 접두사가 포함되지 않은 경우, 네임스페이스 Uniform Resource Identifier (URI)가 빈 네임스페이스라고 가정됩니다. [XPath](../../../system.xml.xpath/) 식 및 [XmlNamespaceManager](../)에 대한 자세한 내용은 XmlNode::SelectNodes(String) 및 XPathExpression::SetContext(SharedPtr<XmlNamespaceManager>) 메서드를 참조하십시오. |
| uri | [String](../../../system/string/) | 추가할 네임스페이스입니다. |

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [XmlNamespaceManager](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)
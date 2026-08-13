---
title: PrependChildElement()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 값과 함께 지정된 네임스페이스 접두사, 로컬 이름 및 네임스페이스 URI를 사용하여 현재 노드의 자식 노드 목록 시작 부분에 새 자식 요소를 생성합니다.
type: docs
weight: 989
url: /ko/system.xml.xpath/xpathnavigator/prependchildelement/
---
## XPathNavigator::PrependChildElement(String, String, String, String) 메서드


Creates a new child element at the beginning of the list of child nodes of the current node using the namespace prefix, local name, and namespace URI specified with the value specified.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChildElement(String prefix, String localName, String namespaceURI, String value)
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | 새 자식 요소의 네임스페이스 접두사(있는 경우). |
| localName | [String](../../../system/string/) | 새 자식 요소의 로컬 이름(있는 경우). |
| namespaceURI | [String](../../../system/string/) | 새 자식 요소의 네임스페이스 URI(있는 경우). [String::Empty](../../../system/string/empty/) 및 **nullptr**는 동등합니다. |
| value | [String](../../../system/string/) | 새 자식 요소의 값. [String::Empty](../../../system/string/empty/) 또는 **nullptr**가 전달되면 빈 요소가 생성됩니다. |

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [XPathNavigator](../)
* 네임스페이스 [System::Xml::XPath](../../)
* 라이브러리 [Aspose.Slides](../../../)
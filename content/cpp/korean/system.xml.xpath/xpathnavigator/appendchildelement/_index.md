---
title: AppendChildElement()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 현재 노드의 자식 노드 목록 끝에 새 자식 요소 노드를 생성합니다. 이때 지정된 값과 함께 지정된 네임스페이스 접두사, 로컬 이름 및 네임스페이스 URI를 사용합니다.
type: docs
weight: 1002
url: /ko/system.xml.xpath/xpathnavigator/appendchildelement/
---
## XPathNavigator::AppendChildElement(String, String, String, String) 메서드

새 자식 요소 노드를 현재 노드의 자식 노드 목록 끝에 지정된 네임스페이스 접두사, 로컬 이름 및 네임스페이스 URI와 함께 생성합니다.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChildElement(String prefix, String localName, String namespaceURI, String value)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | 새 자식 요소 노드의 네임스페이스 접두사(있는 경우). |
| localName | [String](../../../system/string/) | 새 자식 요소 노드의 로컬 이름(있는 경우). |
| namespaceURI | [String](../../../system/string/) | 새 자식 요소 노드의 네임스페이스 URI(있는 경우). [String::Empty](../../../system/string/empty/) 및 **nullptr**는 동일합니다. |
| value | [String](../../../system/string/) | 새 자식 요소 노드의 값. [String::Empty](../../../system/string/empty/) 또는 **nullptr**가 전달되면 빈 요소가 생성됩니다. |

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [XPathNavigator](../)
* 네임스페이스 [System::Xml::XPath](../../)
* 라이브러리 [Aspose.Slides](../../../)
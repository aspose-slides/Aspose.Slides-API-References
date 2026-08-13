---
title: InsertElementAfter()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 네임스페이스 접두사, 로컬 이름 및 네임스페이스 URI와 지정된 값을 사용하여 현재 노드 뒤에 새로운 형제 요소를 생성합니다.
type: docs
weight: 1028
url: /ko/system.xml.xpath/xpathnavigator/insertelementafter/
---
## XPathNavigator::InsertElementAfter(String, String, String, String) 메서드

지정된 네임스페이스 접두사, 로컬 이름 및 네임스페이스 URI와 지정된 값을 사용하여 현재 노드 이후에 새로운 형제 요소를 생성합니다.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertElementAfter(String prefix, String localName, String namespaceURI, String value)
```

### Arguments

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | 새 자식 요소의 네임스페이스 접두사입니다(있을 경우). |
| localName | [String](../../../system/string/) | 새 자식 요소의 로컬 이름입니다(있을 경우). |
| namespaceURI | [String](../../../system/string/) | 새 자식 요소의 네임스페이스 URI입니다(있을 경우). [String::Empty](../../../system/string/empty/)와 **nullptr**는 동등합니다. |
| value | [String](../../../system/string/) | 새 자식 요소의 값입니다. [String::Empty](../../../system/string/empty/) 혹은 **nullptr**가 전달되면 빈 요소가 생성됩니다. |

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [XPathNavigator](../)
* 네임스페이스 [System::Xml::XPath](../../)
* 라이브러리 [Aspose.Slides](../../../)
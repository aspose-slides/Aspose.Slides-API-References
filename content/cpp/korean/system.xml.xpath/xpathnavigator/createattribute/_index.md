---
title: CreateAttribute()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 값을 사용하여 네임스페이스 접두사, 로컬 이름 및 네임스페이스 URI를 지정한 현재 요소 노드에 속성 노드를 생성합니다.
type: docs
weight: 1041
url: /ko/system.xml.xpath/xpathnavigator/createattribute/
---
## XPathNavigator::CreateAttribute(String, String, String, String) 메서드

새 속성 노드를 현재 요소 노드에 네임스페이스 접두사, 로컬 이름 및 지정된 네임스페이스 URI와 함께 지정된 값으로 생성합니다.

```cpp
virtual void System::Xml::XPath::XPathNavigator::CreateAttribute(String prefix, String localName, String namespaceURI, String value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | 새 속성 노드의 네임스페이스 접두사(있는 경우). |
| localName | [String](../../../system/string/) | 새 속성 노드의 로컬 이름이며 [String::Empty](../../../system/string/empty/) 또는 **nullptr**일 수 없습니다. |
| namespaceURI | [String](../../../system/string/) | 새 속성 노드의 네임스페이스 URI(있는 경우). |
| value | [String](../../../system/string/) | 새 속성 노드의 값입니다. [String::Empty](../../../system/string/empty/) 또는 **nullptr**가 전달되면 빈 속성 노드가 생성됩니다. |

## 관련 항목

* 클래스 [String](../../../system/string/)
* 클래스 [XPathNavigator](../)
* 네임스페이스 [System::Xml::XPath](../../)
* 라이브러리 [Aspose.Slides](../../../)
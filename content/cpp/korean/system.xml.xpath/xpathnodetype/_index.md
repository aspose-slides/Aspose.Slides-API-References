---
title: XPathNodeType
second_title: Aspose.Slides for C++ API 레퍼런스
description: XPathNavigator 클래스에서 반환될 수 있는 XPath 노드 유형을 정의합니다.
type: docs
weight: 157
url: /ko/system.xml.xpath/xpathnodetype/
---
## XPathNodeType 열거형

[XPath](../) 노드 유형을 정의하며, 이는 [XPathNavigator](../xpathnavigator/) 클래스에서 반환될 수 있습니다.

```cpp
enum class XPathNodeType
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Root | 0 | XML 문서 또는 노드 트리의 루트 노드. |
| Element | 1 | 요소, 예를 들어 **<element>**. |
| Attribute | 2 | 속성, 예를 들어 **id='123'**. |
| Namespace | 3 | 네임스페이스, 예를 들어 **xmlns=\"namespace\"**. |
| Text | 4 | 노드의 텍스트 내용. Document [Object](../../system/object/) Model (DOM) [Text](../../system.text/) 및 CDATA 노드 유형과 동일합니다. 최소 하나의 문자를 포함합니다. |
| SignificantWhitespace | 5 | 공백 문자를 포함하고 **xml:space**가 **preserve**로 설정된 노드. |
| Whitespace | 6 | 공백 문자만 포함하고 중요한 공백이 없는 노드. 공백 문자는 **'\x20'**, **'\x0d'**, **'\x0a'**, **'\x09'**입니다. |
| ProcessingInstruction | 7 | 처리 지시문, 예를 들어 **<?pi test?>**. 여기에는 XML 선언이 포함되지 않으며, 이는 [XPathNavigator](../xpathnavigator/) 클래스에서 보이지 않습니다. |
| Comment | 8 | 주석, 예를 들어 ****. |
| All | 9 | XPathNodeType 노드 유형 중 하나. |

## 참고

* 네임스페이스 [System::Xml::XPath](../)
* 라이브러리 [Aspose.Slides](../../)
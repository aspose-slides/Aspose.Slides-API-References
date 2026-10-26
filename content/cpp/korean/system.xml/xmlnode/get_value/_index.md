---
title: get_Value()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 노드의 값을 반환합니다.
type: docs
weight: 14
url: /ko/system.xml/xmlnode/get_value/
---
## XmlNode::get_Value() 메서드


노드의 값을 반환합니다.

```cpp
virtual String System::Xml::XmlNode::get_Value()
```


### 반환 값

반환된 값은 노드의 [XmlNode::get_NodeType](../get_nodetype/)에 따라 달라집니다: 

| 형식 | 값 |
| --- | --- |
| [Attribute](../../../system/attribute/)| 속성의 값입니다. |
| CDATASection | CDATA 섹션의 내용입니다. |
| Comment | 주석의 내용입니다. |
| Document | `nullptr`. |
| DocumentFragment | `nullptr`. |
| DocumentType | `nullptr`. |
| Element | `nullptr`. XmlElement::InnerText 또는 [XmlElement::get_InnerXml](../../xmlelement/get_innerxml/) 값을 사용하여 요소 노드의 값을 액세스할 수 있습니다. |
| Entity | `nullptr`. |
| EntityReference | `nullptr`. |
| Notation | `nullptr`. |
| ProcessingInstruction | 대상을 제외한 전체 내용입니다. |
| [Text](../../../system.text/)| 텍스트 노드의 내용입니다. |
| SignificantWhitespace | 공백 문자입니다. 공백은 하나 이상의 공백 문자, 캐리지 리턴, 라인 피드 또는 탭으로 구성될 수 있습니다. |
| Whitespace | 공백 문자입니다. 공백은 하나 이상의 공백 문자, 캐리지 리턴, 라인 피드 또는 탭으로 구성될 수 있습니다. |
| [XmlDeclaration](../../xmldeclaration/)| 선언문의 내용(즉, `<?xml`와 `?>` 사이의 모든 내용)입니다. |

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [XmlNode](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)
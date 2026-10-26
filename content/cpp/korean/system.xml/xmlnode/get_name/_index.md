---
title: get_Name()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 파생 클래스에서 재정의될 때, 노드의 정규화된 이름을 반환합니다.
type: docs
weight: 1
url: /ko/system.xml/xmlnode/get_name/
---
## XmlNode::get_Name() 메서드

Returns the qualified name of the node, when overridden in a derived class.

```cpp
virtual String System::Xml::XmlNode::get_Name()=0
```

### 반환 값

노드의 정규화된 이름입니다.

## 비고

반환된 이름은 노드의 [XmlNode::get_NodeType](../get_nodetype/)에 따라 달라집니다:

| 유형 | 이름 |
| --- | --- |
| [Attribute](../../../system/attribute/)| 속성의 정규화된 이름입니다. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | 문서 유형 이름입니다. |
| Element | 요소의 정규화된 이름입니다. |
| Entity | 엔터티의 이름입니다. |
| EntityReference | 참조된 엔터티의 이름입니다. |
| Notation | 표기법 이름입니다. |
| ProcessingInstruction | 처리 명령문의 대상입니다. |
| [Text](../../../system.text/)| #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| [XmlDeclaration](../../xmldeclaration/)| #xml-declaration |

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [XmlNode](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)
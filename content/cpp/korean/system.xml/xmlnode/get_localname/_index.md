---
title: get_LocalName()
second_title: Aspose.Slides for C++ API 참조
description: 파생 클래스에서 재정의될 경우 노드의 로컬 이름을 반환합니다.
type: docs
weight: 209
url: /ko/system.xml/xmlnode/get_localname/
---
## XmlNode::get_LocalName() 메서드


파생 클래스에서 재정의될 경우 노드의 로컬 이름을 반환합니다.

```cpp
virtual String System::Xml::XmlNode::get_LocalName()=0
```


### 반환값

접두사가 제거된 노드의 이름입니다. 예를 들어, **LocalName** 은 요소 **<bk:book>**에 대해 **book** 입니다.
## 비고



반환된 이름은 노드의 [XmlNode::get_NodeType](../get_nodetype/)에 따라 달라집니다: 

| 유형 | 이름 |
| --- | --- |
| [Attribute](../../../system/attribute/)| 속성의 로컬 이름입니다. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | 문서 유형 이름입니다. |
| Element | 요소의 로컬 이름입니다. |
| Entity | 엔터티의 이름입니다. |
| EntityReference | 참조된 엔터티의 이름입니다. |
| Notation | 표기법 이름입니다. |
| ProcessingInstruction | 처리 명령의 대상입니다. |
| [Text](../../../system.text/)| #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| [XmlDeclaration](../../xmldeclaration/)| #xml-declaration |


## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [XmlNode](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)
---
title: get_Value()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 노드의 텍스트 값을 반환합니다.
type: docs
weight: 79
url: /ko/system.xml/xmlnodereader/get_value/
---
## XmlNodeReader::get_Value() 메서드

현재 노드의 텍스트 값을 반환합니다.

```cpp
String System::Xml::XmlNodeReader::get_Value() override
```

### 반환 값

반환된 값은 노드의 [XmlNodeReader::get_NodeType](../get_nodetype/)에 따라 결정됩니다.

## 비고

다음 표는 반환값이 있는 노드 유형을 나열합니다. 다른 모든 노드 유형은 [String::Empty](../../../system/string/empty/)를 반환합니다.

| Node Type | Value |
| --- | --- |
| [Attribute](../../../system/attribute/)| 속성의 값. |
| CDATA| CDATA 섹션의 내용. |
| Comment| 주석의 내용. |
| DocumentType| 내부 하위 집합. |
| ProcessingInstruction| 대상을 제외한 전체 내용. |
| SignificantWhitespace| 혼합 콘텐츠 모델에서 마크업 사이의 공백. |
| [Text](../../../system.text/)| 텍스트 노드의 내용. |
| Whitespace| 마크업 사이의 공백. |
| [XmlDeclaration](../../xmldeclaration/)| 선언문의 내용. |

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [XmlNodeReader](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)
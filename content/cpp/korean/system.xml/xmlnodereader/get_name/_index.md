---
title: get_Name()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 노드의 정규화된 이름을 반환합니다.
type: docs
weight: 14
url: /ko/system.xml/xmlnodereader/get_name/
---
## XmlNodeReader::get_Name() 메서드

현재 노드의 정규화된 이름을 반환합니다.

```cpp
String System::Xml::XmlNodeReader::get_Name() override
```

### 반환값

현재 노드의 정규화된 이름입니다. 예를 들어, **Name** 은 요소 **<bk:book>** 에 대해 **bk:book** 입니다.

## 비고

반환된 이름은 노드의 [XmlNodeReader::get_NodeType](../get_nodetype/) 값에 따라 달라집니다. 다음 노드 유형은 나열된 값을 반환합니다. 다른 모든 노드 유형은 빈 문자열을 반환합니다.

| 노드 유형 | 이름 |
| --- | --- |
| [Attribute](../../../system/attribute/)| 속성의 이름입니다. |
| DocumentType| 문서 유형 이름입니다. |
| Element| 태그 이름입니다. |
| EntityReference| 참조된 엔터티의 이름입니다. |
| ProcessingInstruction| 처리 지시문의 대상입니다. |
| [XmlDeclaration](../../xmldeclaration/)| `xml` 리터럴 문자열입니다. |

## 또보기

* 클래스 [String](../../../system/string/)
* 클래스 [XmlNodeReader](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)
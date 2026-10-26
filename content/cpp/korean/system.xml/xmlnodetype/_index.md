---
title: XmlNodeType
second_title: Aspose.Slides C++용 API 레퍼런스
description: 노드 유형을 지정합니다.
type: docs
weight: 833
url: /ko/system.xml/xmlnodetype/
---
## XmlNodeType 열거형

노드 유형을 지정합니다.

```cpp
enum class XmlNodeType
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| None | 0 | **Read** 메서드가 호출되지 않은 경우 [XmlReader](../xmlreader/)에 의해 반환됩니다. |
| Element | 1 | 요소 (예: **<item>**). |
| Attribute | 2 | 속성 (예: **id='123'**). |
| Text | 3 | 노드의 텍스트 내용입니다. [XmlNodeType::Text](./) 노드는 자식 노드를 가질 수 없습니다. [XmlNodeType::Attribute](./), [XmlNodeType::DocumentFragment](./), [XmlNodeType::Element](./), [XmlNodeType::EntityReference](./) 노드의 자식 노드로 나타날 수 있습니다. |
| CDATA | 4 | CDATA 섹션 (예: **my escaped text**). |
| EntityReference | 5 | 엔터티에 대한 참조 (예: **&num;**). |
| Entity | 6 | 엔터티 선언 (예: **<!ENTITY...>**). |
| ProcessingInstruction | 7 | 처리 명령 (예: **<?pi test?>**). |
| Comment | 8 | 주석 (예: ****). |
| Document | 9 | 문서 트리의 루트로서 전체 XML 문서에 접근할 수 있는 문서 객체. |
| DocumentType | 10 | 다음 태그로 표시되는 문서 유형 선언 (예: **<!DOCTYPE...>**). |
| DocumentFragment | 11 | 문서 조각. |
| Notation | 12 | 문서 유형 선언 내의 표기법 (예: **<!NOTATION...>**). |
| Whitespace | 13 | 마크업 사이의 공백. |
| SignificantWhitespace | 14 | 혼합 콘텐츠 모델에서 마크업 사이의 공백 또는 **xml:space="preserve"** 범위 내의 공백. |
| EndElement | 15 | 끝 요소 태그 (예: ****). |
| EndEntity | 16 | [XmlReader](../xmlreader/)가 [XmlReader::ResolveEntity](../xmlreader/resolveentity/) 호출의 결과로 엔터티 대체의 끝에 도달했을 때 반환됩니다. |
| XmlDeclaration | 17 | XML 선언 (예: **<?xml version='1.0'?>**). [XmlNodeType::XmlDeclaration](./) 노드는 문서의 첫 번째 노드여야 합니다. 자식 노드를 가질 수 없습니다. [XmlNodeType::Document](./) 노드의 자식입니다. 버전 및 인코딩 정보를 제공하는 속성을 가질 수 있습니다. |

## 참고

* 네임스페이스 [System::Xml](../)
* 라이브러리 [Aspose.Slides](../../)
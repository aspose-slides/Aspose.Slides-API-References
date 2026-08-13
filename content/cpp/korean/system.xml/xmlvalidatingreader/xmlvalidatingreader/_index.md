---
title: XmlValidatingReader()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 XmlReader에서 반환된 내용을 검증하는 XmlValidatingReader 클래스의 새 인스턴스를 초기화합니다.
type: docs
weight: 430
url: /ko/system.xml/xmlvalidatingreader/xmlvalidatingreader/
---
## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<XmlReader\>\&) 생성자


주어진 [XmlReader](../../xmlreader/)에서 반환된 내용을 검증하는 [XmlValidatingReader](../) 클래스의 새 인스턴스를 초기화합니다.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<XmlReader> &reader)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\>\& | 검증하는 동안 읽을 [XmlReader](../../xmlreader/). 현재 구현은 [XmlTextReader](../../xmltextreader/)만 지원합니다. |


## XmlValidatingReader::XmlValidatingReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) 생성자


지정된 값으로 [XmlValidatingReader](../) 클래스의 새 인스턴스를 초기화합니다.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | 구문 분석할 XML 조각을 포함하는 문자열입니다. |
| fragType | [XmlNodeType](../../xmlnodetype/) | XML 조각의 XmlNodeType입니다. 또한 조각 문자열에 포함될 수 있는 내용을 결정합니다(아래 표 참조). |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | XML 조각을 구문 분석할 [XmlParserContext](../../xmlparsercontext/)입니다. 여기에는 사용할 [NameTable](../../nametable/), 인코딩, 네임스페이스 범위, 현재 **xml:lang**, 및 **xml:space** 범위가 포함됩니다. |


## 비고

다음 표는 **fragType**에 대한 유효한 값과 리더가 각 노드 유형을 어떻게 구문 분석하는지 나열합니다.

| XmlNodeType | 조각에 포함될 수 있음 |
| --- | --- |
| Element| 유효한 모든 요소 내용(예: 요소, 주석, 처리 명령, cdata, 텍스트 및 엔터티 참조의 모든 조합). |
| [Attribute](../../../system/attribute/)| 속성의 값(따옴표 안의 부분). |
| Document| 전체 XML 문서의 내용; 이는 문서 수준 규칙을 적용합니다. |


## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) 생성자


지정된 값으로 [XmlValidatingReader](../) 클래스의 새 인스턴스를 초기화합니다.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 구문 분석할 XML 조각을 포함하는 스트림입니다. |
| fragType | [XmlNodeType](../../xmlnodetype/) | XML 조각의 XmlNodeType입니다. 이는 조각에 포함될 수 있는 내용을 결정합니다(아래 표 참조). |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | XML 조각을 구문 분석할 [XmlParserContext](../../xmlparsercontext/)입니다. 여기에는 사용할 [XmlNameTable](../../xmlnametable/), 인코딩, 네임스페이스 범위, 현재 **xml:lang**, 및 **xml:space** 범위가 포함됩니다. |


## 비고

다음 표는 **fragType**에 대한 유효한 값과 리더가 각 노드 유형을 어떻게 구문 분석하는지 나열합니다.

| XmlNodeType | 조각에 포함될 수 있음 |
| --- | --- |
| Element| 유효한 모든 요소 내용(예: 요소, 주석, 처리 명령, cdata, 텍스트 및 엔터티 참조의 모든 조합). |
| [Attribute](../../../system/attribute/)| 속성의 값(따옴표 안의 부분). |
| Document| 전체 XML 문서의 내용; 이는 문서 수준 규칙을 적용합니다. |


## 참고

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../xmlreader/)
* Class [XmlValidatingReader](../)
* Class [String](../../../system/string/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [Stream](../../../system.io/stream/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
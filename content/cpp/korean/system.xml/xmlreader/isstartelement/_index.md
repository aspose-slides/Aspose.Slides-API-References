---
title: IsStartElement()
second_title: Aspose.Slides for C++ API 참조
description: "XmlReader::MoveToContent를 호출하고 현재 콘텐츠 노드가 시작 태그 또는 빈 요소 태그인지 테스트합니다."
type: docs
weight: 885
url: /ko/system.xml/xmlreader/isstartelement/
---
## XmlReader::IsStartElement() 메서드

[XmlReader::MoveToContent](../movetocontent/)를 호출하고 현재 콘텐츠 노드가 시작 태그 또는 빈 요소 태그인지 테스트합니다.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement()
```

### 반환값

[XmlReader::MoveToContent](../movetocontent/)가 시작 태그 또는 빈 요소 태그를 찾으면 **true**, [XmlNodeType::Element](../../xmlnodetype/) 이외의 노드 유형이 발견되면 **false**.

## XmlReader::IsStartElement(String) 메서드

[XmlReader::MoveToContent](../movetocontent/)를 호출하고 현재 콘텐츠 노드가 시작 태그 또는 빈 요소 태그인지와 찾은 요소의 [XmlReader::get_Name](../get_name/) 값이 지정된 인수와 일치하는지를 테스트합니다.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String name)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 찾은 요소의 **Name** 값과 일치시키기 위한 문자열입니다. |

### 반환값

결과 노드가 요소이고 **Name** 값이 지정된 문자열과 일치하면 **true**. [XmlNodeType::Element](../../xmlnodetype/) 이외의 노드 유형이 발견되었거나 요소 **Name** 값이 지정된 문자열과 일치하지 않으면 **false**.

## XmlReader::IsStartElement(String, String) 메서드

[XmlReader::MoveToContent](../movetocontent/)를 호출하고 현재 콘텐츠 노드가 시작 태그 또는 빈 요소 태그인지와 찾은 요소의 [XmlReader::get_LocalName](../get_localname/) 및 [XmlReader::get_NamespaceURI](../get_namespaceuri/) 값이 지정된 문자열과 일치하는지를 테스트합니다.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String localname, String ns)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| localname | [String](../../../system/string/) | 찾은 요소의 **LocalName** 값과 일치시키기 위한 문자열입니다. |
| ns | [String](../../../system/string/) | 찾은 요소의 **NamespaceURI** 값과 일치시키기 위한 문자열입니다. |

### 반환값

결과 노드가 요소이면 **true**. [XmlNodeType::Element](../../xmlnodetype/) 이외의 노드 유형이 발견되었거나 **LocalName** 및 **NamespaceURI** 값이 지정된 문자열과 일치하지 않으면 **false**.

## 참고

* 클래스 [XmlReader](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)
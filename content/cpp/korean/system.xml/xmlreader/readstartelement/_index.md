---
title: ReadStartElement()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 노드가 요소인지 확인하고 리더를 다음 노드로 이동합니다.
type: docs
weight: 846
url: /ko/system.xml/xmlreader/readstartelement/
---
## XmlReader::ReadStartElement() 메서드

현재 노드가 요소인지 확인하고 리더를 다음 노드로 이동합니다.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement()
```

## XmlReader::ReadStartElement(String) 메서드

현재 콘텐츠 노드가 지정된 [XmlReader::get_Name](../get_name/) 값을 가진 요소인지 확인하고 리더를 다음 노드로 이동합니다.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String name)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 요소의 정규화된 이름입니다. |

## XmlReader::ReadStartElement(String, String) 메서드

현재 콘텐츠 노드가 지정된 [XmlReader::get_LocalName](../get_localname/) 및 [XmlReader::get_NamespaceURI](../get_namespaceuri/) 값을 가진 요소인지 확인하고 리더를 다음 노드로 이동합니다.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String localname, String ns)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| localname | [String](../../../system/string/) | 요소의 로컬 이름입니다. |
| ns | [String](../../../system/string/) | 요소의 네임스페이스 URI입니다. |

## 참조

* 클래스 [XmlReader](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)
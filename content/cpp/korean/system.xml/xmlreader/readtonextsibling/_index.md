---
title: ReadToNextSibling()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 정규화된 이름을 가진 다음 형제 요소로 XmlReader를 이동시킵니다.
type: docs
weight: 924
url: /ko/system.xml/xmlreader/readtonextsibling/
---
## XmlReader::ReadToNextSibling(String) 메서드

지정된 정규화된 이름을 가진 다음 형제 요소로 [XmlReader](../)를 이동합니다.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String name)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 이동하려는 형제 요소의 정규화된 이름. |

### 반환 값

**true**가 일치하는 형제 요소를 찾으면 반환됩니다; 그렇지 않으면 **false**. 일치하는 형제 요소를 찾지 못하면, [XmlReader](../)는 부모 요소의 종료 태그([XmlReader::get_NodeType](../get_nodetype/) 값이 [XmlNodeType::EndElement](../../xmlnodetype/))에 위치합니다.

## XmlReader::ReadToNextSibling(String, String) 메서드

지정된 로컬 이름 및 네임스페이스 URI를 가진 다음 형제 요소로 [XmlReader](../)를 이동합니다.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String localName, String namespaceURI)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 이동하려는 형제 요소의 로컬 이름. |
| namespaceURI | [String](../../../system/string/) | 이동하려는 형제 요소의 네임스페이스 URI. |

### 반환 값

**true**가 일치하는 형제 요소를 찾으면 반환됩니다; 그렇지 않으면 **false**. 일치하는 형제 요소를 찾지 못하면, [XmlReader](../)는 부모 요소의 종료 태그([XmlReader::get_NodeType](../get_nodetype/) 값이 [XmlNodeType::EndElement](../../xmlnodetype/))에 위치합니다.

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [XmlReader](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)
---
title: RemoveAttribute()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이름으로 속성을 제거합니다.
type: docs
weight: 235
url: /ko/system.xml/xmlelement/removeattribute/
---
## XmlElement::RemoveAttribute(String) 메서드

이름으로 속성을 제거합니다.

```cpp
virtual void System::Xml::XmlElement::RemoveAttribute(String name)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 제거할 속성의 이름입니다. 이는 한정된 이름이며, 일치하는 노드의 **get_Name** 값과 비교됩니다. |

## XmlElement::RemoveAttribute(String, String) 메서드

지정된 로컬 이름 및 네임스페이스 URI를 가진 속성을 제거합니다. (제거된 속성에 기본값이 있는 경우 즉시 교체됩니다.)

```cpp
virtual void System::Xml::XmlElement::RemoveAttribute(String localName, String namespaceURI)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 제거할 속성의 로컬 이름입니다. |
| namespaceURI | [String](../../../system/string/) | 제거할 속성의 네임스페이스 URI입니다. |

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [XmlElement](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)
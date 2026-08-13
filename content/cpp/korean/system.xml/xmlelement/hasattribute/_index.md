---
title: HasAttribute()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 노드에 지정된 이름을 가진 속성이 있는지 확인합니다.
type: docs
weight: 300
url: /ko/system.xml/xmlelement/hasattribute/
---
## XmlElement::HasAttribute(String) 메서드

현재 노드에 지정된 이름을 가진 속성이 있는지 확인합니다.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String name)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 찾을 속성의 이름입니다. 이는 한정된 이름이며, 일치하는 노드의 **get_Name** 값과 비교됩니다. |

### 반환 값

**true** if the current node has the specified attribute; otherwise, **false**.

## XmlElement::HasAttribute(String, String) 메서드

현재 노드에 지정된 로컬 이름 및 네임스페이스 URI를 가진 속성이 있는지 확인합니다.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String localName, String namespaceURI)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 찾을 속성의 로컬 이름입니다. |
| namespaceURI | [String](../../../system/string/) | 찾을 속성의 네임스페이스 URI입니다. |

### 반환 값

**true** if the current node has the specified attribute; otherwise, **false**.

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [XmlElement](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)
---
title: GetAttribute()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 이름을 가진 속성의 값을 반환합니다.
type: docs
weight: 209
url: /ko/system.xml/xmlelement/getattribute/
---
## XmlElement::GetAttribute(String) 메서드


지정된 이름을 가진 속성의 값을 반환합니다.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String name)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 검색할 속성의 이름입니다. 이는 한정된 이름이며, 일치하는 노드의 **get_Name** 값과 비교됩니다. |

### 반환값

지정된 속성의 값입니다. 일치하는 속성을 찾지 못했거나 속성에 지정된 값이나 기본값이 없는 경우 빈 문자열이 반환됩니다.

## XmlElement::GetAttribute(String, String) 메서드


지정된 로컬 이름 및 네임스페이스 URI를 가진 속성의 값을 반환합니다.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String localName, String namespaceURI)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 검색할 속성의 로컬 이름입니다. |
| namespaceURI | [String](../../../system/string/) | 검색할 속성의 네임스페이스 URI입니다. |

### 반환값

지정된 속성의 값입니다. 일치하는 속성을 찾지 못했거나 속성에 지정된 값이나 기본값이 없는 경우 빈 문자열이 반환됩니다.

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [XmlElement](../)
* 네임스페이스 [System::Xml](../../)
* Library [Aspose.Slides](../../../)
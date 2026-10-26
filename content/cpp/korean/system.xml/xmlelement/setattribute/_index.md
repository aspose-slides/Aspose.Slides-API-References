---
title: SetAttribute()
second_title: C++용 Aspose.Slides API 참조
description: 지정된 이름을 가진 속성의 값을 설정합니다.
type: docs
weight: 222
url: /ko/system.xml/xmlelement/setattribute/
---
## XmlElement::SetAttribute(String, String) 메서드

지정된 이름을 가진 속성의 값을 설정합니다.

```cpp
virtual void System::Xml::XmlElement::SetAttribute(String name, String value)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 속성을 생성하거나 변경하기 위한 이름입니다. 이것은 한정된 이름입니다. 이름에 콜론이 포함된 경우 접두사와 로컬 이름 구성 요소로 구문 분석됩니다. |
| value | [String](../../../system/string/) | 속성에 설정할 값입니다. |

## XmlElement::SetAttribute(String, String, String) 메서드

지정된 로컬 이름 및 네임스페이스 URI를 가진 속성의 값을 설정합니다.

```cpp
virtual String System::Xml::XmlElement::SetAttribute(String localName, String namespaceURI, String value)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 속성의 로컬 이름입니다. |
| namespaceURI | [String](../../../system/string/) | 속성의 네임스페이스 URI입니다. |
| value | [String](../../../system/string/) | 속성에 설정할 값입니다. |

### 반환값

속성 값.

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [XmlElement](../)
* 네임스페이스 [System::Xml](../../)
* Library [Aspose.Slides](../../../)
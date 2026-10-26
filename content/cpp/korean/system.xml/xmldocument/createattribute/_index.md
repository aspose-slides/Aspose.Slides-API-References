---
title: CreateAttribute()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 이름으로 XmlAttribute를 생성합니다.
type: docs
weight: 274
url: /ko/system.xml/xmldocument/createattribute/
---
## XmlDocument::CreateAttribute(const String\&) 메서드

[XmlAttribute](../../xmlattribute/)를 지정된 이름으로 생성합니다.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &name)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 속성의 한정된 이름입니다. 이름에 콜론이 포함된 경우, [XmlNode::get_Prefix](../../xmlnode/get_prefix/) 값은 첫 번째 콜론 앞의 부분을, [XmlDocument::get_LocalName](../get_localname/) 값은 첫 번째 콜론 뒤의 부분을 나타냅니다. [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/)는 접두사가 **xmlns**과 같은 인식된 내장 접두사가 아닌 경우 비워 둡니다. 이 경우 get_NamespaceURI는 [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/) 값을 가집니다. |

### 반환 값

새로운 [XmlAttribute](../../xmlattribute/)를 반환합니다.

## XmlDocument::CreateAttribute(const String\&, const String\&) 메서드

[XmlAttribute](../../xmlattribute/)를 지정된 한정 이름과 [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/)으로 생성합니다.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &qualifiedName, const String &namespaceURI)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | 속성의 한정된 이름입니다. 이름에 콜론이 포함된 경우 [XmlNode::get_Prefix](../../xmlnode/get_prefix/) 값은 콜론 앞의 부분을, [XmlDocument::get_LocalName](../get_localname/) 값은 콜론 뒤의 부분을 나타냅니다. |
| namespaceURI | const [String](../../../system/string/)\& | 속성의 namespaceURI입니다. 한정 이름에 **xmlns** 접두사가 포함된 경우, 이 매개변수는 [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/)이어야 합니다. |

### 반환 값

새로운 [XmlAttribute](../../xmlattribute/)를 반환합니다.

## XmlDocument::CreateAttribute(const String\&, const String\&, const String\&) 메서드

[XmlAttribute](../../xmlattribute/)를 지정된 [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_LocalName](../get_localname/), [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/)와 함께 생성합니다.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &prefix, const String &localName, const String &namespaceURI)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 속성의 접두사(있는 경우)입니다. [String::Empty](../../../system/string/empty/)와 **nullptr**는 동일합니다. |
| localName | const [String](../../../system/string/)\& | 속성의 로컬 이름입니다. |
| namespaceURI | const [String](../../../system/string/)\& | 속성의 namespace URI(있는 경우)입니다. [String::Empty](../../../system/string/empty/)와 **nullptr**는 동일합니다. **prefix**가 **xmlns**인 경우, 이 매개변수는 [http://www.w3.org/2000/xmlns/;](http://www.w3.org/2000/xmlns/;)이어야 하며, 그렇지 않으면 예외가 발생합니다. |

### 반환 값

새로운 [XmlAttribute](../../xmlattribute/)를 반환합니다.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlAttribute](../../xmlattribute/)
* 클래스 [String](../../../system/string/)
* 클래스 [XmlDocument](../)
* 네임스페이스 [System::Xml](../../)
* Library [Aspose.Slides](../../../)
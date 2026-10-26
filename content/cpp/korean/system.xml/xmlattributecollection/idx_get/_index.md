---
title: idx_get()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 인덱스에 해당하는 속성을 반환합니다.
type: docs
weight: 1
url: /ko/system.xml/xmlattributecollection/idx_get/
---
## XmlAttributeCollection::idx_get(int32_t) 메서드

지정된 인덱스에 해당하는 속성을 반환합니다.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(int32_t i)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| i | **int32_t** | The index of the attribute. |

### 반환값

지정된 인덱스에 해당하는 속성.

## XmlAttributeCollection::idx_get(const String\&) 메서드

지정된 이름에 해당하는 속성을 반환합니다.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &name)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | The qualified name of the attribute. |

### 반환값

지정된 이름에 해당하는 속성입니다. 속성이 존재하지 않을 경우, 이 메서드는 **nullptr**를 반환합니다.

## XmlAttributeCollection::idx_get(const String\&, const String\&) 메서드

지정된 로컬 이름 및 네임스페이스 Uniform Resource Identifier (URI)에 해당하는 속성을 반환합니다.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &localName, const String &namespaceURI)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | The local name of the attribute. |
| namespaceURI | const [String](../../../system/string/)\& | The namespace URI of the attribute. |

### 반환값

지정된 로컬 이름 및 네임스페이스 URI에 해당하는 속성입니다. 속성이 존재하지 않을 경우, 이 메서드는 **nullptr**를 반환합니다.

## 또한 보기

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlAttribute](../../xmlattribute/)
* 클래스 [XmlAttributeCollection](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Xml](../../)
* Library [Aspose.Slides](../../../)
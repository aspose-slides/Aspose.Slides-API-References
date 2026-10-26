---
title: idx_get()
second_title: Aspose.Slides for C++ API 참조
description: 주어진 네임스페이스 URI와 연결된 XmlSchema를 반환합니다.
type: docs
weight: 53
url: /ko/system.xml.schema/xmlschemacollection/idx_get/
---
## XmlSchemaCollection::idx_get(const String\&) method


주어진 네임스페이스 URI와 연관된 [XmlSchema](../../xmlschema/)를 반환합니다.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::idx_get(const String &ns)
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | 반환하려는 스키마와 연관된 네임스페이스 URI입니다. 일반적으로 스키마의 **targetNamespace**가 됩니다. |

### 반환 값

네임스페이스 URI와 연관된 [XmlSchema](../../xmlschema/); **nullptr**는 주어진 네임스페이스와 연결된 로드된 스키마가 없거나 네임스페이스가 XDR 스키마와 연결된 경우입니다.

## 또 보기

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlSchema](../../xmlschema/)
* 클래스 [String](../../../system/string/)
* 클래스 [XmlSchemaCollection](../)
* 네임스페이스 [System::Xml::Schema](../../)
* 라이브러리 [Aspose.Slides](../../../)
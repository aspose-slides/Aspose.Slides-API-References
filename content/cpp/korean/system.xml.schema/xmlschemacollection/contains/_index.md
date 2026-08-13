---
title: Contains()
second_title: Aspose.Slides C++ API 레퍼런스
description: 지정된 XmlSchema의 targetNamespace가 컬렉션에 포함되어 있는지 여부를 나타내는 값을 반환합니다.
type: docs
weight: 66
url: /ko/system.xml.schema/xmlschemacollection/contains/
---
## XmlSchemaCollection::Contains(const SharedPtr\<XmlSchema\>\&) method

지정된 [XmlSchema](../../xmlschema/)의 **targetNamespace**가 컬렉션에 포함되어 있는지 여부를 나타내는 값을 반환합니다.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const SharedPtr<XmlSchema> &schema)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | [XmlSchema](../../xmlschema/) 객체. |

### 반환 값

컬렉션에 동일한 **targetNamespace**를 가진 스키마가 있으면 **true**, 그렇지 않으면 **false**.

## XmlSchemaCollection::Contains(const String\&) method

지정된 네임스페이스를 가진 스키마가 컬렉션에 있는지 여부를 나타내는 값을 반환합니다.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const String &ns)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | 스키마와 연결된 네임스페이스 URI입니다. XML Schemas의 경우 일반적으로 대상 네임스페이스가 됩니다. |

### 반환 값

컬렉션에 지정된 네임스페이스를 가진 스키마가 있으면 **true**, 그렇지 않으면 **false**.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaCollection](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)
---
title: Add()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 URL에 있는 XML Schema 정의 언어 (XSD) 스키마를 XmlSchemaSet에 추가합니다.
type: docs
weight: 157
url: /ko/system.xml.schema/xmlschemaset/add/
---
## XmlSchemaSet::Add(String, const String\&) 메서드

지정된 URL에 있는 XML [Schema](../../) 정의 언어 (XSD) 스키마를 [XmlSchemaSet](../)에 추가합니다.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const String &schemaUri)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | 스키마의 **targetNamespace** 값이며, 스키마에 지정된 **targetNamespace**를 사용하려면 **nullptr** 로 설정합니다. |
| schemaUri | const [String](../../../system/string/)\& | 로드할 스키마를 지정하는 URL. |

### 반환 값

[XmlSchema](../../xmlschema/) 객체가 스키마가 유효한 경우 반환됩니다. 스키마가 유효하지 않고 ValidationEventHandler가 지정된 경우 **nullptr** 가 반환되고 해당 검증 이벤트가 발생합니다. 그렇지 않으면 XmlSchemaException이 발생합니다.

## XmlSchemaSet::Add(String, const SharedPtr\<XmlReader\>\&) 메서드

XML [Schema](../../) 정의 언어 (XSD) 스키마를 [XmlReader](../../../system.xml/xmlreader/)에 포함시켜 [XmlSchemaSet](../)에 추가합니다.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const SharedPtr<XmlReader> &schemaDocument)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | 스키마의 **targetNamespace** 값이며, 스키마에 지정된 **targetNamespace**를 사용하려면 **nullptr** 로 설정합니다. |
| schemaDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) 객체. |

### 반환 값

[XmlSchema](../../xmlschema/) 객체가 스키마가 유효한 경우 반환됩니다. 스키마가 유효하지 않고 ValidationEventHandler가 지정된 경우 **nullptr** 가 반환되고 해당 검증 이벤트가 발생합니다. 그렇지 않으면 XmlSchemaException이 발생합니다.

## XmlSchemaSet::Add(const SharedPtr\<XmlSchemaSet\>\&) 메서드

주어진 [XmlSchemaSet](../)에 있는 모든 XML [Schema](../../) 정의 언어 (XSD) 스키마를 [XmlSchemaSet](../)에 추가합니다.

```cpp
void System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchemaSet> &schemas)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../)\>\& | [XmlSchemaSet](../) 객체. |

## XmlSchemaSet::Add(const SharedPtr\<XmlSchema\>\&) 메서드

주어진 [XmlSchema](../../xmlschema/)를 [XmlSchemaSet](../)에 추가합니다.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchema> &schema)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | [XmlSchemaSet](../)에 추가할 [XmlSchema](../../xmlschema/) 객체. |

### 반환 값

[XmlSchema](../../xmlschema/) 객체가 스키마가 유효한 경우 반환됩니다. 스키마가 유효하지 않고 ValidationEventHandler가 지정된 경우 **nullptr** 가 반환되고 해당 검증 이벤트가 발생합니다. 그렇지 않으면 XmlSchemaException이 발생합니다.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlSchema](../../xmlschema/)
* 클래스 [String](../../../system/string/)
* 클래스 [XmlSchemaSet](../)
* 클래스 [XmlReader](../../../system.xml/xmlreader/)
* 네임스페이스 [System::Xml::Schema](../../)
* 라이브러리 [Aspose.Slides](../../../)
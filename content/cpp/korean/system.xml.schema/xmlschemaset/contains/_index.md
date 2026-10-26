---
title: Contains()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 대상 네임스페이스 URI를 가진 XML 스키마 정의 언어 (XSD) 스키마가 XmlSchemaSet에 있는지 여부를 나타냅니다.
type: docs
weight: 196
url: /ko/system.xml.schema/xmlschemaset/contains/
---
## XmlSchemaSet::Contains(String) 메서드

지정된 대상 네임스페이스 URI를 가진 XML [Schema](../../) 정의 언어 (XSD) 스키마가 [XmlSchemaSet](../)에 있는지 여부를 나타냅니다.

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(String targetNamespace)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | 스키마 **targetNamespace** 속성. |

### 반환값

[XmlSchemaSet](../)에 지정된 대상 네임스페이스 URI를 가진 스키마가 있으면 **true**; 그렇지 않으면 **false**.

## XmlSchemaSet::Contains(const SharedPtr\<XmlSchema\>\&) 메서드

지정된 XML [Schema](../../) 정의 언어 (XSD) [XmlSchema](../../xmlschema/) 객체가 [XmlSchemaSet](../)에 있는지 여부를 나타냅니다.

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(const SharedPtr<XmlSchema> &schema)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | [XmlSchema](../../xmlschema/) 객체. |

### 반환값

[XmlSchemaSet](../)에 [XmlSchema](../../xmlschema/) 객체가 있으면 **true**; 그렇지 않으면 **false**.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [XmlSchemaSet](../)
* 클래스 [XmlSchema](../../xmlschema/)
* 네임스페이스 [System::Xml::Schema](../../)
* 라이브러리 [Aspose.Slides](../../../)
---
title: InferSchema()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 XmlReader 객체에 포함된 XML 문서에서 XML 스키마 정의 언어 (XSD) 스키마를 추론합니다.
type: docs
weight: 66
url: /ko/system.xml.schema/xmlschemainference/inferschema/
---
## XmlSchemaInference::InferSchema(const SharedPtr<XmlReader>&) 메서드

지정된 [XmlReader](../../../system.xml/xmlreader/) 객체에 포함된 XML 문서에서 XML [Schema](../../) 정의 언어 (XSD) 스키마를 추론합니다.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 스키마를 추론할 XML 문서를 포함하는 [XmlReader](../../../system.xml/xmlreader/) 객체. |

### 반환값

추론된 스키마를 포함하는 [XmlSchemaSet](../../xmlschemaset/) 객체.

## XmlSchemaInference::InferSchema(const SharedPtr<XmlReader>&, SharedPtr<XmlSchemaSet>) 메서드

지정된 [XmlReader](../../../system.xml/xmlreader/) 객체에 포함된 XML 문서에서 XML [Schema](../../) 정의 언어 (XSD) 스키마를 추론하고, 동일한 대상 네임스페이스를 가진 [XmlSchemaSet](../../xmlschemaset/) 객체에 있는 기존 스키마를 사용하여 추론된 스키마를 정제합니다.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument, SharedPtr<XmlSchemaSet> schemas)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 스키마를 추론할 XML 문서를 포함하는 [XmlReader](../../../system.xml/xmlreader/) 객체. |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\> | 추론된 스키마를 정제하는 데 사용되는 기존 스키마를 포함하는 [XmlSchemaSet](../../xmlschemaset/) 객체. |

### 반환값

추론된 스키마를 포함하는 [XmlSchemaSet](../../xmlschemaset/) 객체.

## 또 보기

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlSchemaSet](../../xmlschemaset/)
* 클래스 [XmlReader](../../../system.xml/xmlreader/)
* 클래스 [XmlSchemaInference](../)
* 네임스페이스 [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)
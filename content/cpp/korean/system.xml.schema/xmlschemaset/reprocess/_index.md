---
title: Reprocess()
second_title: Aspose.Slides for C++ API 참조
description: 이미 XmlSchemaSet에 존재하는 XML 스키마 정의 언어 (XSD) 스키마를 다시 처리합니다.
type: docs
weight: 222
url: /ko/system.xml.schema/xmlschemaset/reprocess/
---
## XmlSchemaSet::Reprocess(SharedPtr\<XmlSchema\>) 메서드


이미 [XmlSchemaSet](../)에 존재하는 XML [Schema](../../) 정의 언어 (XSD) 스키마를 다시 처리합니다.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Reprocess(SharedPtr<XmlSchema> schema)
```


### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| schema | [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\> | 다시 처리할 스키마. |

### 반환 값

스키마가 유효한 경우 [XmlSchema](../../xmlschema/) 객체가 반환됩니다. 스키마가 유효하지 않고 ValidationEventHandler가 지정된 경우 **nullptr**가 반환되고 적절한 검증 이벤트가 발생합니다. 그렇지 않으면 XmlSchemaException이 발생합니다.

## 또 보기

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlSchema](../../xmlschema/)
* 클래스 [XmlSchemaSet](../)
* 네임스페이스 [System::Xml::Schema](../../)
* 라이브러리 [Aspose.Slides](../../../)
---
title: Remove()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 XML 스키마 정의 언어 (XSD) 스키마를 XmlSchemaSet에서 제거합니다.
type: docs
weight: 170
url: /ko/system.xml.schema/xmlschemaset/remove/
---
## XmlSchemaSet::Remove(const SharedPtr\<XmlSchema\>\&) 메서드


지정된 XML [Schema](../../) 정의 언어 (XSD) 스키마를 [XmlSchemaSet](../)에서 제거합니다.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Remove(const SharedPtr<XmlSchema> &schema)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | [XmlSchemaSet](../)에서 제거할 [XmlSchema](../../xmlschema/) 객체. |

### 반환 값

[XmlSchemaSet](../)에서 제거된 [XmlSchema](../../xmlschema/) 객체이며, [XmlSchemaSet](../)에서 스키마를 찾을 수 없으면 **nullptr**를 반환합니다.

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlSchema](../../xmlschema/)
* 클래스 [XmlSchemaSet](../)
* 네임스페이스 [System::Xml::Schema](../../)
* 라이브러리 [Aspose.Slides](../../../)
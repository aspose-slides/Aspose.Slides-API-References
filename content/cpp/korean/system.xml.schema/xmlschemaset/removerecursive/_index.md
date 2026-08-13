---
title: RemoveRecursive()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 XML 스키마 정의 언어 (XSD) 스키마와 해당 스키마가 XmlSchemaSet에서 가져오는 모든 스키마를 제거합니다.
type: docs
weight: 183
url: /ko/system.xml.schema/xmlschemaset/removerecursive/
---
## XmlSchemaSet::RemoveRecursive(const SharedPtr\<XmlSchema\>\&) 메서드

지정된 XML [Schema](../../) 정의 언어 (XSD) 스키마와 해당 스키마가 [XmlSchemaSet](../)에서 가져온 모든 스키마를 제거합니다.

```cpp
bool System::Xml::Schema::XmlSchemaSet::RemoveRecursive(const SharedPtr<XmlSchema> &schemaToRemove)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| schemaToRemove | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | [XmlSchema](../../xmlschema/) 객체를 [XmlSchemaSet](../)에서 제거합니다. |

### 반환값

**true** if the [XmlSchema](../../xmlschema/) object and all its imports were successfully removed; otherwise, **false**.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlSchema](../../xmlschema/)
* 클래스 [XmlSchemaSet](../)
* 네임스페이스 [System::Xml::Schema](../../)
* 라이브러리 [Aspose.Slides](../../../)
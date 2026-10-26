---
title: Schemas()
second_title: Aspose.Slides for C++ API 레퍼런스
description: XmlSchemaSet에 있는 모든 XML 스키마 정의 언어 (XSD) 스키마의 컬렉션을 반환합니다.
type: docs
weight: 248
url: /ko/system.xml.schema/xmlschemaset/schemas/
---
## XmlSchemaSet::Schemas() 메서드

XML [Schema](../../) 정의 언어 (XSD) 스키마를 모두 포함하는 컬렉션을 [XmlSchemaSet](../)에서 반환합니다.

```cpp
SharedPtr<Collections::Generic::IList<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas()
```

### 반환 값

[XmlSchemaSet](../)에 추가된 모든 스키마를 포함하는 IList 객체입니다. [XmlSchemaSet](../)에 스키마가 추가되지 않은 경우, 빈 컬렉션이 반환됩니다.

## XmlSchemaSet::Schemas(String) 메서드

주어진 네임스페이스에 속하는 [XmlSchemaSet](../)의 모든 XML [Schema](../../) 정의 언어 (XSD) 스키마를 포함하는 컬렉션을 반환합니다.

```cpp
SharedPtr<Collections::Generic::List<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas(String targetNamespace)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | 스키마 **targetNamespace** 속성. |

### 반환 값

[XmlSchemaSet](../)에 추가된, 주어진 네임스페이스에 속하는 모든 스키마를 포함하는 IList 객체입니다. [XmlSchemaSet](../)에 스키마가 추가되지 않은 경우, 빈 컬렉션이 반환됩니다.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IList](../../../system.collections.generic/ilist/)
* 클래스 [XmlSchema](../../xmlschema/)
* 클래스 [XmlSchemaSet](../)
* 클래스 [List](../../../system.collections.generic/list/)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Xml::Schema](../../)
* 라이브러리 [Aspose.Slides](../../../)
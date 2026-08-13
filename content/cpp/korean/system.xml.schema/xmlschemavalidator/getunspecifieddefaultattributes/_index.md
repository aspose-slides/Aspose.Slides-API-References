---
title: GetUnspecifiedDefaultAttributes()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "요소 컨텍스트에서 XmlSchemaValidator::ValidateAttribute 메서드를 사용하여 이전에 검증되지 않은 기본값을 가진 속성에 대해 XmlSchemaAttribute 객체로 지정된 List를 채우면서 기본 속성에 대한 식별 제약을 검증합니다."
type: docs
weight: 157
url: /ko/system.xml.schema/xmlschemavalidator/getunspecifieddefaultattributes/
---
## XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr\<Collections::Generic::List\<SharedPtr\<Object\>\>\>\&) 메서드

기본 속성에 대한 식별 제약을 검증하고, 요소 컨텍스트에서 [XmlSchemaValidator::ValidateAttribute](../validateattribute/) 메서드를 사용하여 이전에 검증되지 않은 기본값을 가진 속성에 대해 [XmlSchemaAttribute](../../xmlschemaattribute/) 객체로 지정된 List를 채웁니다.

```cpp
void System::Xml::Schema::XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr<Collections::Generic::List<SharedPtr<Object>>> &defaultAttributes)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| defaultAttributes | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::List](../../../system.collections.generic/list/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\>\& | 요소 컨텍스트에서 검증 중 아직 만나지 않은 속성에 대해 [XmlSchemaAttribute](../../xmlschemaattribute/) 객체로 List를 채웁니다. |

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [List](../../../system.collections.generic/list/)
* 클래스 [Object](../../../system/object/)
* 클래스 [XmlSchemaValidator](../)
* 네임스페이스 [System::Xml::Schema](../../)
* 라이브러리 [Aspose.Slides](../../../)
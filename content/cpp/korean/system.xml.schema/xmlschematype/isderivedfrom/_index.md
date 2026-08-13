---
title: IsDerivedFrom()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 파생 스키마 유형이 지정된 기본 스키마 유형에서 파생되었는지 여부를 나타내는 값을 반환합니다.
type: docs
weight: 209
url: /ko/system.xml.schema/xmlschematype/isderivedfrom/
---
## XmlSchemaType::IsDerivedFrom(SharedPtr\<XmlSchemaType\>, const SharedPtr\<XmlSchemaType\>\&, XmlSchemaDerivationMethod) 메서드

지정된 파생 스키마 유형이 지정된 기본 스키마 유형에서 파생되었는지 여부를 나타내는 값을 반환합니다.

```cpp
static bool System::Xml::Schema::XmlSchemaType::IsDerivedFrom(SharedPtr<XmlSchemaType> derivedType, const SharedPtr<XmlSchemaType> &baseType, XmlSchemaDerivationMethod except)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| derivedType | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\> | 테스트할 파생 [XmlSchemaType](../). |
| baseType | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\>\& | 파생 [XmlSchemaType](../)를 테스트하기 위한 기본 [XmlSchemaType](../). |
| except | [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/) | 테스트에서 제외할 유형 파생 방법을 나타내는 XmlSchemaDerivationMethod 값 중 하나. |

### 반환 값

**true** 파생 유형이 기본 유형에서 파생된 경우; 그렇지 않으면 **false**.

## 참조

* 열거형 [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/)
* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlSchemaType](../)
* 네임스페이스 [System::Xml::Schema](../../)
* 라이브러리 [Aspose.Slides](../../../)
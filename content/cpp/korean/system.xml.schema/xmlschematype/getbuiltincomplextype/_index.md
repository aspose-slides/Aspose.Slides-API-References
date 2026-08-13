---
title: GetBuiltInComplexType()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 복합 유형의 내장 복합 유형을 나타내는 XmlSchemaComplexType을 반환합니다.
type: docs
weight: 196
url: /ko/system.xml.schema/xmlschematype/getbuiltincomplextype/
---
## XmlSchemaType::GetBuiltInComplexType(XmlTypeCode) 메서드

지정된 복합 유형의 내장 복합 유형을 나타내는 [XmlSchemaComplexType](../../xmlschemacomplextype/)을 반환합니다.

```cpp
static SharedPtr<XmlSchemaComplexType> System::Xml::Schema::XmlSchemaType::GetBuiltInComplexType(XmlTypeCode typeCode)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| typeCode | [XmlTypeCode](../../xmltypecode/) | 복합 유형을 나타내는 XmlTypeCode 값 중 하나입니다. |

### 반환 값

내장 복합 유형을 나타내는 [XmlSchemaComplexType](../../xmlschemacomplextype/)입니다.

## XmlSchemaType::GetBuiltInComplexType(const SharedPtr\<XmlQualifiedName\>\&) 메서드

자격 이름으로 지정된 복합 유형의 내장 복합 유형을 나타내는 [XmlSchemaComplexType](../../xmlschemacomplextype/)을 반환합니다.

```cpp
static SharedPtr<XmlSchemaComplexType> System::Xml::Schema::XmlSchemaType::GetBuiltInComplexType(const SharedPtr<XmlQualifiedName> &qualifiedName)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| qualifiedName | const [SharedPtr](../../../system/sharedptr/)\<[XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\>\& | 복합 유형의 [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)입니다. |

### 반환 값

내장 복합 유형을 나타내는 [XmlSchemaComplexType](../../xmlschemacomplextype/)입니다.

## 참고

* 열거형 [XmlTypeCode](../../xmltypecode/)
* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlSchemaComplexType](../../xmlschemacomplextype/)
* 클래스 [XmlSchemaType](../)
* 클래스 [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* 네임스페이스 [System::Xml::Schema](../../)
* 라이브러리 [Aspose.Slides](../../../)
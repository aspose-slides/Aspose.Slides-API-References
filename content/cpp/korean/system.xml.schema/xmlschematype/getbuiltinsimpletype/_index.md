---
title: GetBuiltInSimpleType()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 정규화된 이름에 의해 지정된 단순 유형의 기본 제공 단순 유형을 나타내는 XmlSchemaSimpleType을 반환합니다.
type: docs
weight: 183
url: /ko/system.xml.schema/xmlschematype/getbuiltinsimpletype/
---
## XmlSchemaType::GetBuiltInSimpleType(const SharedPtr\<XmlQualifiedName\>\&) 메서드

Returns an [XmlSchemaSimpleType](../../xmlschemasimpletype/) that represents the built-in simple type of the simple type that is specified by the qualified name.

```cpp
static SharedPtr<XmlSchemaSimpleType> System::Xml::Schema::XmlSchemaType::GetBuiltInSimpleType(const SharedPtr<XmlQualifiedName> &qualifiedName)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| qualifiedName | const [SharedPtr](../../../system/sharedptr/)\<[XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\>\& | 단순 유형의 [XmlQualifiedName](../../../system.xml/xmlqualifiedname/). |

### 반환값

The [XmlSchemaSimpleType](../../xmlschemasimpletype/) that represents the built-in simple type.

## XmlSchemaType::GetBuiltInSimpleType(XmlTypeCode) 메서드

Returns an [XmlSchemaSimpleType](../../xmlschemasimpletype/) that represents the built-in simple type of the specified simple type.

```cpp
static SharedPtr<XmlSchemaSimpleType> System::Xml::Schema::XmlSchemaType::GetBuiltInSimpleType(XmlTypeCode typeCode)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| typeCode | [XmlTypeCode](../../xmltypecode/) | 단순 유형을 나타내는 XmlTypeCode 값 중 하나. |

### 반환값

The [XmlSchemaSimpleType](../../xmlschemasimpletype/) that represents the built-in simple type.

## 참조

* 열거형 [XmlTypeCode](../../xmltypecode/)
* typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlSchemaSimpleType](../../xmlschemasimpletype/)
* 클래스 [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* 클래스 [XmlSchemaType](../)
* 네임스페이스 [System::Xml::Schema](../../)
* 라이브러리 [Aspose.Slides](../../../)
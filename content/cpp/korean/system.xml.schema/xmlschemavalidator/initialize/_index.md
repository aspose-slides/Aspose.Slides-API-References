---
title: Initialize()
second_title: Aspose.Slides for C++ API 레퍼런스
description: XmlSchemaValidator 객체의 상태를 초기화합니다.
type: docs
weight: 118
url: /ko/system.xml.schema/xmlschemavalidator/initialize/
---
## XmlSchemaValidator::Initialize() method

[XmlSchemaValidator](../) 객체의 상태를 초기화합니다.

```cpp
void System::Xml::Schema::XmlSchemaValidator::Initialize()
```

## XmlSchemaValidator::Initialize(const SharedPtr\<XmlSchemaObject\>\&) method

[XmlSchemaValidator](../) 객체의 상태를 [XmlSchemaObject](../../xmlschemaobject/)를 사용하여 부분 검증을 위해 초기화합니다.

```cpp
void System::Xml::Schema::XmlSchemaValidator::Initialize(const SharedPtr<XmlSchemaObject> &partialValidationType)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| partialValidationType | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaObject](../../xmlschemaobject/)\>\& | 부분 검증을 위해 [XmlSchemaValidator](../) 객체의 검증 컨텍스트를 초기화하는 데 사용되는 [XmlSchemaElement](../../xmlschemaelement/), [XmlSchemaAttribute](../../xmlschemaattribute/) 또는 [XmlSchemaType](../../xmlschematype/) 객체입니다. |

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlSchemaValidator](../)
* 클래스 [XmlSchemaObject](../../xmlschemaobject/)
* 네임스페이스 [System::Xml::Schema](../../)
* 라이브러리 [Aspose.Slides](../../../)
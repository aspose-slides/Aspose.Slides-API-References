---
title: ValidateEndElement()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 요소가 단순 콘텐츠인 경우 해당 데이터 유형에 따라 텍스트 내용이 유효한지 확인하고, 복합 콘텐츠인 경우 현재 요소의 내용이 완전한지 확인합니다.
type: docs
weight: 209
url: /ko/system.xml.schema/xmlschemavalidator/validateendelement/
---
## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&) 메서드

요소의 텍스트 내용이 단순 콘텐츠인 경우 해당 데이터 유형에 따라 유효한지 확인하고, 복합 콘텐츠인 경우 현재 요소의 내용이 완전한지 확인합니다.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | 요소 검증이 성공적으로 완료될 때 속성이 설정되는 [XmlSchemaInfo](../../xmlschemainfo/) 객체입니다. 이 매개변수는 **nullptr**일 수 있습니다. |

### 반환값

요소가 단순 콘텐츠인 경우 구문 분석된 형식이 지정된 텍스트 값입니다.

## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&, const SharedPtr\<Object\>\&) 메서드

지정된 요소의 텍스트 내용이 해당 데이터 유형에 따라 유효한지 확인합니다.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo, const SharedPtr<Object> &typedValue)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | 요소의 텍스트 내용 검증이 성공적으로 완료될 때 속성이 설정되는 [XmlSchemaInfo](../../xmlschemainfo/) 객체입니다. 이 매개변수는 **nullptr**일 수 있습니다. |
| typedValue | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 요소의 형식이 지정된 텍스트 내용입니다. |

### 반환값

요소의 구문 분석된 형식이 지정된 단순 콘텐츠입니다.

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [XmlSchemaInfo](../../xmlschemainfo/)
* 클래스 [XmlSchemaValidator](../)
* 네임스페이스 [System::Xml::Schema](../../)
* 라이브러리 [Aspose.Slides](../../../)
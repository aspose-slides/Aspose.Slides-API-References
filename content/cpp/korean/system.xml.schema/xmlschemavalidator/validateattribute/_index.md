---
title: ValidateAttribute()
second_title: Aspose.Slides C++ API 레퍼런스
description: 현재 요소 컨텍스트에서 속성 이름, 네임스페이스 URI 및 값을 검증합니다.
type: docs
weight: 144
url: /ko/system.xml.schema/xmlschemavalidator/validateattribute/
---
## XmlSchemaValidator::ValidateAttribute(const String&, const String&, const String&, const SharedPtr<XmlSchemaInfo>&) 메서드

현재 요소 컨텍스트에서 속성 이름, 네임스페이스 URI 및 값을 검증합니다.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, const String &attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 검증할 속성의 로컬 이름. |
| namespaceUri | const [String](../../../system/string/)\& | 검증할 속성의 네임스페이스 URI. |
| attributeValue | const [String](../../../system/string/)\& | 검증할 속성의 값. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | 검증이 성공하면 속성이 설정되는 [XmlSchemaInfo](../../xmlschemainfo/) 객체입니다. 이 매개변수는 **nullptr**일 수 있습니다. |

### 반환 값

검증된 속성의 값.

## XmlSchemaValidator::ValidateAttribute(const String&, const String&, XmlValueGetter, const SharedPtr<XmlSchemaInfo>&) 메서드

현재 요소 컨텍스트에서 속성 이름, 네임스페이스 URI 및 값을 검증합니다.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, XmlValueGetter attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 검증할 속성의 로컬 이름. |
| namespaceUri | const [String](../../../system/string/)\& | 검증할 속성의 네임스페이스 URI. |
| attributeValue | [XmlValueGetter](../../xmlvaluegetter/) | 속성의 XML [Schema](../../) 정의 언어 (XSD) 타입과 호환되는 유형으로 속성 값을 전달하기 위해 사용되는 XmlValueGetter 콜백입니다. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | 검증이 성공하면 속성이 설정되는 [XmlSchemaInfo](../../xmlschemainfo/) 객체입니다. 이 매개변수는 **nullptr**일 수 있습니다. |

### 반환 값

검증된 속성의 값.

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 타입정의 [XmlValueGetter](../../xmlvaluegetter/)
* 클래스 [Object](../../../system/object/)
* 클래스 [String](../../../system/string/)
* 클래스 [XmlSchemaInfo](../../xmlschemainfo/)
* 클래스 [XmlSchemaValidator](../)
* 네임스페이스 [System::Xml::Schema](../../)
* 라이브러리 [Aspose.Slides](../../../)
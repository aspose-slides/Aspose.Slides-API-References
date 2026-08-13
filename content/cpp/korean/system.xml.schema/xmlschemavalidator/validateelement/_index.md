---
title: ValidateElement()
second_title: Aspose.Slides for C++ API 참조
description: 현재 컨텍스트에서 요소를 검증합니다.
type: docs
weight: 131
url: /ko/system.xml.schema/xmlschemavalidator/validateelement/
---
## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) 메서드

현재 컨텍스트에서 요소를 검증합니다.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### 매개변수

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 검증할 요소의 로컬 이름입니다. |
| namespaceUri | const [String](../../../system/string/)\& | 검증할 요소의 네임스페이스 URI입니다. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | [XmlSchemaInfo](../../xmlschemainfo/) 객체이며, 요소 이름이 성공적으로 검증될 때 해당 속성이 설정됩니다. 이 매개변수는 **nullptr**일 수 있습니다. |

## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&, const String\&, const String\&, const String\&, const String\&) 메서드

지정된 **xsi:Type**, **xsi:Nil**, **xsi:SchemaLocation**, **xsi:NoNamespaceSchemaLocation** 속성 값을 사용하여 현재 컨텍스트에서 요소를 검증합니다.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo, const String &xsiType, const String &xsiNil, const String &xsiSchemaLocation, const String &xsiNoNamespaceSchemaLocation)
```

### 매개변수

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 검증할 요소의 로컬 이름입니다. |
| namespaceUri | const [String](../../../system/string/)\& | 검증할 요소의 네임스페이스 URI입니다. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | [XmlSchemaInfo](../../xmlschemainfo/) 객체이며, 요소 이름이 성공적으로 검증될 때 해당 속성이 설정됩니다. 이 매개변수는 **nullptr**일 수 있습니다. |
| xsiType | const [String](../../../system/string/)\& | 요소의 **xsi:Type** 속성 값입니다. 이 매개변수는 **nullptr**일 수 있습니다. |
| xsiNil | const [String](../../../system/string/)\& | 요소의 **xsi:Nil** 속성 값입니다. 이 매개변수는 **nullptr**일 수 있습니다. |
| xsiSchemaLocation | const [String](../../../system/string/)\& | 요소의 **xsi:SchemaLocation** 속성 값입니다. 이 매개변수는 **nullptr**일 수 있습니다. |
| xsiNoNamespaceSchemaLocation | const [String](../../../system/string/)\& | 요소의 **xsi:NoNamespaceSchemaLocation** 속성 값입니다. 이 매개변수는 **nullptr**일 수 있습니다. |

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [XmlSchemaInfo](../../xmlschemainfo/)
* 클래스 [XmlSchemaValidator](../)
* 네임스페이스 [System::Xml::Schema](../../)
* 라이브러리 [Aspose.Slides](../../../)
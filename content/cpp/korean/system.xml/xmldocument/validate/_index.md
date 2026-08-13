---
title: Validate()
second_title: Aspose.Slides for C++ API 참조
description: "XmlDocument::get_Schemas 목록에 포함된 XML 스키마 정의 언어 (XSD) 스키마에 대해 XmlDocument를 검증합니다."
type: docs
weight: 573
url: /ko/system.xml/xmldocument/validate/
---
## XmlDocument::Validate(Schema::ValidationEventHandler) 메서드


[XmlDocument](../)을(를) XML [Schema](../../../system.xml.schema/) 정의 언어 (XSD) 스키마가 포함된 [XmlDocument::get_Schemas](../get_schemas/) 목록에 대해 검증합니다.

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | 스키마 검증 경고 및 오류에 대한 정보를 수신하는 [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) 객체입니다. |

## XmlDocument::Validate(Schema::ValidationEventHandler, const SharedPtr\<XmlNode\>\&) 메서드


지정된 [XmlNode](../../xmlnode/) 객체를 XML [Schema](../../../system.xml.schema/) 정의 언어 (XSD) 스키마가 포함된 [XmlDocument::get_Schemas](../get_schemas/) 목록에 대해 검증합니다.

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler, const SharedPtr<XmlNode> &nodeToValidate)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | 스키마 검증 경고 및 오류에 대한 정보를 수신하는 [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) 객체입니다. |
| nodeToValidate | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | 검증할 [XmlDocument](../)에서 만든 [XmlNode](../../xmlnode/) 객체입니다. |

## 참고

* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlDocument](../)
* Class [XmlNode](../../xmlnode/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
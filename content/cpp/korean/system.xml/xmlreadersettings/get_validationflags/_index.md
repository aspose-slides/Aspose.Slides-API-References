---
title: get_ValidationFlags()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "스키마 검증 설정을 나타내는 값을 반환합니다. 이 설정은 스키마를 검증하는 XmlReader 객체에 적용됩니다 (XmlReaderSettings::get_ValidationType 값은 ValidationType::Schema입니다)."
type: docs
weight: 378
url: /ko/system.xml/xmlreadersettings/get_validationflags/
---
## XmlReaderSettings::get_ValidationFlags() 메서드


스키마 검증 설정을 나타내는 값을 반환합니다. 이 설정은 스키마를 검증하는 [XmlReader](../../xmlreader/) 객체에 적용됩니다 ([XmlReaderSettings::get_ValidationType](../get_validationtype/) 값은 [ValidationType::Schema](../../validationtype/)입니다).

```cpp
Schema::XmlSchemaValidationFlags System::Xml::XmlReaderSettings::get_ValidationFlags()
```


### 반환 값

검증 옵션을 지정하는 열거형 값들의 비트 조합입니다. XmlSchemaValidationFlags::ProcessIdentityConstraints와 XmlSchemaValidationFlags::AllowXmlAttributes는 기본적으로 활성화됩니다. XmlSchemaValidationFlags::ProcessInlineSchema, XmlSchemaValidationFlags::ProcessSchemaLocation 및 XmlSchemaValidationFlags::ReportValidationWarnings는 기본적으로 비활성화됩니다.

## 참조

* 열거형 [XmlSchemaValidationFlags](../../../system.xml.schema/xmlschemavalidationflags/)
* 클래스 [XmlReaderSettings](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)
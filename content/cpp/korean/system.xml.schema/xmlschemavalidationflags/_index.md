---
title: XmlSchemaValidationFlags
second_title: Aspose.Slides for C++ API 참조
description: XmlSchemaValidator 및 XmlReader 클래스에서 사용하는 스키마 검증 옵션을 지정합니다.
type: docs
weight: 1054
url: /ko/system.xml.schema/xmlschemavalidationflags/
---
## XmlSchemaValidationFlags enum

Specifies schema validation options used by the [XmlSchemaValidator](../xmlschemavalidator/) and [XmlReader](../../system.xml/xmlreader/) classes.

```cpp
enum class XmlSchemaValidationFlags
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| None | 0 | 식별 제약 조건, 인라인 스키마, 스키마 위치 힌트를 처리하지 않으며 스키마 유효성 검사 경고를 보고하지 않습니다. |
| ProcessInlineSchema | 1 | 유효성 검사 중에 발견된 인라인 스키마를 처리합니다. |
| ProcessSchemaLocation | 2 | 유효성 검사 중에 발견된 스키마 위치 힌트(**xsi:schemaLocation**, **xsi:noNamespaceSchemaLocation**)를 처리합니다. |
| ReportValidationWarnings | 4 | 유효성 검사 중에 발견된 스키마 유효성 검사 경고를 보고합니다. |
| ProcessIdentityConstraints | 8 | 유효성 검사 중에 발견된 식별 제약 조건(**xs:ID**, **xs:IDREF**, **xs:key**, **xs:keyref**, **xs:unique**)을 처리합니다. |
| AllowXmlAttributes | 16 | 스키마에 정의되지 않은 경우에도 xml:* 속성을 허용합니다. 해당 속성은 데이터 유형에 따라 유효성 검사가 수행됩니다. |

## 참조

* 네임스페이스 [System::Xml::Schema](../)
* 라이브러리 [Aspose.Slides](../../)
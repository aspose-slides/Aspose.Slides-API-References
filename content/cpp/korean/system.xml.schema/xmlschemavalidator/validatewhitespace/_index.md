---
title: ValidateWhitespace()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 문자열의 공백이 현재 요소 컨텍스트에서 허용되는지 확인하고, 현재 요소가 단순 내용을 가지고 있는 경우 검증을 위해 공백을 누적합니다.
type: docs
weight: 196
url: /ko/system.xml.schema/xmlschemavalidator/validatewhitespace/
---
## XmlSchemaValidator::ValidateWhitespace(const String\&) 메서드

지정된 **string**의 공백이 현재 요소 컨텍스트에서 허용되는지 확인하고, 현재 요소가 단순 내용을 가지고 있는 경우 검증을 위해 공백을 누적합니다.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace(const String &elementValue)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | 현재 요소 컨텍스트에서 검증할 공백 **string**입니다. |

## XmlSchemaValidator::ValidateWhitespace(XmlValueGetter) 메서드

지정된 XmlValueGetter 객체에서 반환된 공백이 현재 요소 컨텍스트에서 허용되는지 확인하고, 현재 요소가 단순 내용을 가지고 있는 경우 검증을 위해 공백을 누적합니다.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace(XmlValueGetter elementValue)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | 속성의 XML [Schema](../../) 정의 언어 (XSD) 타입과 호환되는 유형으로 공백 값을 전달하는 데 사용되는 XmlValueGetter 콜백입니다. |

## 참고

* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* 클래스 [String](../../../system/string/)
* 클래스 [XmlSchemaValidator](../)
* 네임스페이스 [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)
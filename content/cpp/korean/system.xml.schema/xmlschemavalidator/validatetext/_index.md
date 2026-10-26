---
title: ValidateText()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 텍스트 문자열이 현재 요소 컨텍스트에서 허용되는지 확인하고, 현재 요소가 단순 콘텐츠를 가지고 있는 경우 검증을 위해 텍스트를 누적합니다.
type: docs
weight: 183
url: /ko/system.xml.schema/xmlschemavalidator/validatetext/
---
## XmlSchemaValidator::ValidateText(const String\&) method

현재 요소 컨텍스트에서 지정된 텍스트 **string**이 허용되는지 확인하고, 현재 요소가 단순 콘텐츠를 갖는 경우 검증을 위해 텍스트를 누적합니다.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(const String &elementValue)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | 현재 요소 컨텍스트에서 검증할 텍스트 **string**입니다. |

## XmlSchemaValidator::ValidateText(XmlValueGetter) method

지정된 XmlValueGetter 객체가 반환하는 텍스트가 현재 요소 컨텍스트에서 허용되는지 확인하고, 현재 요소가 단순 콘텐츠를 갖는 경우 검증을 위해 텍스트를 누적합니다.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(XmlValueGetter elementValue)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | 속성의 XML [Schema](../../) 정의 언어 (XSD) 유형과 호환되는 유형으로 텍스트 값을 전달하기 위해 사용되는 XmlValueGetter 콜백입니다. |

## 참고

* 타입정의 [XmlValueGetter](../../xmlvaluegetter/)
* 클래스 [String](../../../system/string/)
* 클래스 [XmlSchemaValidator](../)
* 네임스페이스 [System::Xml::Schema](../../)
* 라이브러리 [Aspose.Slides](../../../)
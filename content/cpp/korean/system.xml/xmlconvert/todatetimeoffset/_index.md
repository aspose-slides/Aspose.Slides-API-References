---
title: ToDateTimeOffset()
second_title: Aspose.Slides for C++ API 참조
description: 제공된 String을 DateTimeOffset과 동등한 형태로 변환합니다.
type: docs
weight: 430
url: /ko/system.xml/xmlconvert/todatetimeoffset/
---
## XmlConvert::ToDateTimeOffset(const String\&) 메서드


제공된 [String](../../../system/string/)를 [DateTimeOffset](../../../system/datetimeoffset/)와 동등한 형태로 변환합니다.

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | 변환할 문자열입니다. 문자열은 XML dateTime 유형에 대한 W3C 권고안의 하위 집합을 따라야 합니다. 자세한 내용은 XML [Schema](../../../system.xml.schema/) 사양의 [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) 섹션을 참조하십시오. |

### 반환 값

제공된 문자열의 [DateTimeOffset](../../../system/datetimeoffset/)와 동등한 형태입니다.

## XmlConvert::ToDateTimeOffset(const String\&, const String\&) 메서드


제공된 [String](../../../system/string/)를 [DateTimeOffset](../../../system/datetimeoffset/)와 동등한 형태로 변환합니다.

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const String &format)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | 변환할 문자열입니다. |
| format | const [String](../../../system/string/)\& | **s**가 변환되는 형식입니다. 형식 매개변수는 XML dateTime 유형에 대한 W3C 권고안의 하위 집합일 수 있습니다. 자세한 내용은 XML [Schema](../../../system.xml.schema/) 사양의 [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) 섹션을 참조하십시오. 문자열 **s**는 이 형식에 따라 검증됩니다. |

### 반환 값

제공된 문자열의 [DateTimeOffset](../../../system/datetimeoffset/)와 동등한 형태입니다.

## XmlConvert::ToDateTimeOffset(const String\&, const ArrayPtr\<String\>\&) 메서드


제공된 [String](../../../system/string/)를 [DateTimeOffset](../../../system/datetimeoffset/)와 동등한 형태로 변환합니다.

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const ArrayPtr<String> &formats)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | 변환할 문자열입니다. |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | **s**를 변환할 수 있는 형식들의 배열입니다. **formats**의 각 형식은 XML dateTime 유형에 대한 W3C 권고안의 하위 집합일 수 있습니다. 자세한 내용은 XML [Schema](../../../system.xml.schema/) 사양의 [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) 섹션을 참조하십시오. 문자열 **s**는 이러한 형식 중 하나에 따라 검증됩니다. |

### 반환 값

제공된 문자열의 [DateTimeOffset](../../../system/datetimeoffset/)와 동등한 형태입니다.

## 참고

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [DateTimeOffset](../../../system/datetimeoffset/)
* 클래스 [String](../../../system/string/)
* 클래스 [XmlConvert](../)
* 네임스페이스 [System::Xml](../../)
* Library [Aspose.Slides](../../../)
---
title: ToDateTime()
second_title: Aspose.Slides for C++ API 레퍼런스
description: String을 DateTime과 동등한 형태로 변환합니다.
type: docs
weight: 417
url: /ko/system.xml/xmlconvert/todatetime/
---
## XmlConvert::ToDateTime(const String\&) 메서드

[String](../../../system/string/)를 [DateTime](../../../system/datetime/)와 동등한 형태로 변환합니다.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | 변환할 문자열입니다. |

### 반환 값

문자열과 동등한 [DateTime](../../../system/datetime/)입니다.

## XmlConvert::ToDateTime(const String\&, const String\&) 메서드

[String](../../../system/string/)를 [DateTime](../../../system/datetime/)와 동등한 형태로 변환합니다.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const String &format)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | 변환할 문자열입니다. |
| format | const [String](../../../system/string/)\& | 변환된 [DateTime](../../../system/datetime/)에 적용할 형식 구조입니다. 유효한 형식에는 \"yyyy-MM-ddTHH:mm:sszzzzzz\" 및 그 하위 형식이 포함됩니다. 문자열은 이 형식에 따라 검증됩니다. |

### 반환 값

문자열과 동등한 [DateTime](../../../system/datetime/)입니다.

## XmlConvert::ToDateTime(const String\&, const ArrayPtr\<String\>\&) 메서드

[String](../../../system/string/)를 [DateTime](../../../system/datetime/)와 동등한 형태로 변환합니다.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const ArrayPtr<String> &formats)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | 변환할 문자열입니다. |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | 변환된 [DateTime](../../../system/datetime/)에 적용할 형식 구조를 포함하는 배열입니다. 유효한 형식에는 \"yyyy-MM-ddTHH:mm:sszzzzzz\" 및 그 하위 형식이 포함됩니다. |

### 반환 값

문자열과 동등한 [DateTime](../../../system/datetime/)입니다.

## XmlConvert::ToDateTime(const String\&, XmlDateTimeSerializationMode) 메서드

[String](../../../system/string/)를 지정된 XmlDateTimeSerializationMode를 사용하여 [DateTime](../../../system/datetime/)로 변환합니다.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, XmlDateTimeSerializationMode dateTimeOption)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | 변환할 [String](../../../system/string/) 값입니다. |
| dateTimeOption | [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/) | 날짜를 로컬 시간으로 변환할지, UTC 날짜인 경우 협정 세계시(UTC)로 유지할지 지정하는 열거형 값 중 하나입니다. |

### 반환 값

[String](../../../system/string/)와 동등한 [DateTime](../../../system/datetime/)입니다.

## 참조

* Enum [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [DateTime](../../../system/datetime/)
* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
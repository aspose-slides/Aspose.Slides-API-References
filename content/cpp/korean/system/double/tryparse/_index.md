---
title: TryParse()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 문자열(숫자의 문자열 표현을 포함) 을 해당 double-precision 부동 소수점 값으로 변환합니다.
type: docs
weight: 14
url: /ko/system/double/tryparse/
---
## Double::TryParse(const String&, double&) 메서드

지정된 문자열(숫자의 문자열 표현을 포함한)을 해당 double-precision 부동 소수점 값으로 변환합니다.

```cpp
static bool System::Double::TryParse(const String &value, double &result)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)& | 변환할 문자열. |
| result | **double**& | 변환 결과가 저장되는 double-precision 부동 소수점 변수에 대한 참조. |

### 반환 값

변환이 성공하면 true, 그렇지 않으면 false.

## Double::TryParse(const String&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>&, double&) 메서드

제공된 형식 정보와 숫자 스타일을 사용하여 지정된 문자열(숫자의 문자열 표현을 포함한)을 해당 double-precision 부동 소수점 값으로 변환합니다.

```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, double &result)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)& | 변환할 문자열. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 숫자의 문자열 표현에 허용되는 스타일을 지정하는 NumberStyles 열거형 값들의 비트별 조합. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>& | 문자열 형식 정보를 포함하는 객체에 대한 포인터. |
| result | **double**& | 변환 결과가 저장되는 double-precision 부동 소수점 변수에 대한 참조. |

### 반환 값

변환이 성공하면 true, 그렇지 않으면 false.

## Double::TryParse(const String&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>&, double&) 메서드




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, double &result)
```

## Double::TryParse(const String&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>&, double&) 메서드




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, double &result)
```

## Double::TryParse(const String&, Globalization::NumberStyles, std::nullptr_t, double&) 메서드




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, double &result)
```

## 관련 항목

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Double](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
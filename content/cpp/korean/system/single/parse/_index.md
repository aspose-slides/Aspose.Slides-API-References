---
title: Parse()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 문자열(숫자의 문자열 표현을 포함) 을 단정밀도 부동소수점 값으로 변환합니다.
type: docs
weight: 1
url: /ko/system/single/parse/
---
## Single::Parse(const String\&) 메서드

지정된 문자열(숫자의 문자열 표현을 포함) 을 단정밀도 부동소수점 값으로 변환합니다.

```cpp
static float System::Single::Parse(const String &value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열. |

### 반환 값

지정된 문자열이 나타내는 숫자와 동일한 단정밀도 부동소수점 값입니다.

## Single::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) 메서드

제공된 형식 정보를 사용하여 지정된 문자열(숫자의 문자열 표현을 포함) 을 단정밀도 부동소수점 값으로 변환합니다.

```cpp
static float System::Single::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문자열 형식 정보를 포함하는 객체에 대한 포인터입니다. |

### 반환 값

지정된 문자열이 나타내는 숫자와 동일한 단정밀도 부동소수점 값입니다.

## Single::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) 메서드




```cpp
static float System::Single::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Single::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 메서드




```cpp
static float System::Single::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Single::Parse(const String\&, std::nullptr_t) 메서드




```cpp
static float System::Single::Parse(const String &value, std::nullptr_t)
```

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) 메서드

제공된 형식 정보와 숫자 스타일을 사용하여 지정된 문자열(숫자의 문자열 표현을 포함) 을 단정밀도 부동소수점 값으로 변환합니다.

```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 열거형 값의 비트별 조합으로, 숫자 문자열 표현에 허용되는 스타일을 지정합니다. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문자열 형식 정보를 포함하는 객체에 대한 포인터입니다. |

### 반환 값

지정된 문자열이 나타내는 숫자와 동일한 단정밀도 부동소수점 값입니다.

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) 메서드




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 메서드




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Single::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) 메서드




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## 참고

* 열거형 [NumberStyles](../../../system.globalization/numberstyles/)
* 타입정의 [SharedPtr](../../sharedptr/)
* 클래스 [String](../../string/)
* 클래스 [IFormatProvider](../../iformatprovider/)
* 클래스 [CultureInfo](../../../system.globalization/cultureinfo/)
* 클래스 [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 구조체 [Single](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)
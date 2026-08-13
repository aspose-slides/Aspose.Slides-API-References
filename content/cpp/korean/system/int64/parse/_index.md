---
title: Parse()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 문자열(숫자의 문자열 표현을 포함)을 64비트 부호 있는 정수로 변환합니다.
type: docs
weight: 1
url: /ko/system/int64/parse/
---
## Int64::Parse(const String\&) method


지정된 문자열(숫자의 문자열 표현을 포함)을 64비트 부호 있는 정수로 변환합니다.

```cpp
static int64_t System::Int64::Parse(const String &value)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열. |

### 반환 값

지정된 문자열이 나타내는 숫자와 같은 64비트 부호 있는 정수.

## Int64::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) method


제공된 서식 정보를 사용하여 지정된 문자열(숫자의 문자열 표현을 포함)을 64비트 부호 있는 정수로 변환합니다.

```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문자열 서식 정보를 포함하는 객체에 대한 포인터. |

### 반환 값

지정된 문자열이 나타내는 숫자와 같은 64비트 부호 있는 정수.

## Int64::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) method




```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int64::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) method




```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int64::Parse(const String\&, std::nullptr_t) method




```cpp
static int64_t System::Int64::Parse(const String &value, std::nullptr_t)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) method


제공된 서식 정보와 숫자 스타일을 사용하여 지정된 문자열(숫자의 문자열 표현을 포함)을 64비트 부호 있는 정수로 변환합니다.

```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 허용되는 숫자 문자열 표현 스타일을 지정하는 NumberStyles 열거형 값들의 비트 조합. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문자열 서식 정보를 포함하는 객체에 대한 포인터. |

### 반환 값

지정된 문자열이 나타내는 숫자와 같은 64비트 부호 있는 정수.

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) method




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) method




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) method




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## 참고

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Int64](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
---
title: Double
second_title: Aspose.Slides for C++ API 레퍼런스
description: double-precision 부동소수점 숫자를 다루는 메서드를 포함합니다.
type: docs
weight: 1574
url: /ko/system/double/
---
## Double 구조체

double-precision 부동소수점 숫자를 다루는 메서드를 포함합니다.

```cpp
class Double
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static **double** [Parse](./parse/)(const [String](../string/)\&) | 지정된 문자열(숫자의 문자열 표현을 포함)을 해당 double-precision 부동소수점 값으로 변환합니다. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 제공된 서식 정보를 사용하여 지정된 문자열(숫자의 문자열 표현을 포함)을 해당 double-precision 부동소수점 값으로 변환합니다. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 제공된 서식 정보와 숫자 스타일을 사용하여 지정된 문자열(숫자의 문자열 표현을 포함)을 해당 double-precision 부동소수점 값으로 변환합니다. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **double**\&) | 지정된 문자열(숫자의 문자열 표현을 포함)을 해당 double-precision 부동소수점 값으로 변환합니다. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **double**\&) | 제공된 서식 정보와 숫자 스타일을 사용하여 지정된 문자열(숫자의 문자열 표현을 포함)을 해당 double-precision 부동소수점 값으로 변환합니다. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **double**\&) |  |

## 필드

| 필드 | 설명 |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | 0보다 큰 가장 작은 양수 값. |
| static constexpr [MaxValue](./maxvalue/) | 가능한 가장 큰 값. |
| static constexpr [MinValue](./minvalue/) | 가능한 가장 작은 값. |
| static constexpr [NaN](./nan/) | 숫자가 아닌 값. |
| static constexpr [NegativeInfinity](./negativeinfinity/) | 음의 무한대. |
| static constexpr [PositiveInfinity](./positiveinfinity/) | 양의 무한대. |

## 참고

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)
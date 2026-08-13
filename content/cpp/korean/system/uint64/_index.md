---
title: UInt64
second_title: Aspose.Slides for C++ API 레퍼런스
description: 부호 없는 64비트 정수를 다루는 메서드를 포함합니다.
type: docs
weight: 1990
url: /ko/system/uint64/
---
## UInt64 구조체

부호 없는 64비트 정수를 다루는 메서드를 포함합니다.

```cpp
class UInt64
```

## 메서드

| Method | Description |
| --- | --- |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&) | 지정된 문자열(숫자의 문자열 표현을 포함)을 64비트 부호 없는 정수와 동등한 값으로 변환합니다. |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 제공된 서식 정보를 사용하여 지정된 문자열(숫자의 문자열 표현을 포함)을 64비트 부호 없는 정수와 동등한 값으로 변환합니다. |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 제공된 서식 정보와 숫자 스타일을 사용하여 지정된 문자열(숫자의 문자열 표현을 포함)을 64비트 부호 없는 정수와 동등한 값으로 변환합니다. |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint64_t**\&) | 지정된 문자열(숫자의 문자열 표현을 포함)을 64비트 부호 없는 정수와 동등한 값으로 변환합니다. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint64_t**\&) | 제공된 서식 정보와 숫자 스타일을 사용하여 지정된 문자열(숫자의 문자열 표현을 포함)을 64비트 부호 없는 정수와 동등한 값으로 변환합니다. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint64_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint64_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint64_t**\&) |  |

## 필드

| Field | Description |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | 가능한 최댓값. |
| static constexpr [MinValue](./minvalue/) | 가능한 최솟값. |

## 참고

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)
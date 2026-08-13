---
title: Int64
second_title: Aspose.Slides for C++ API 레퍼런스
description: 64비트 정수를 다루는 메서드를 포함합니다.
type: docs
weight: 1054
url: /ko/system/int64/
---
## Int64 클래스

64비트 정수를 다루는 메서드를 포함합니다.

```cpp
class Int64
```

## 메서드

| Method | Description |
| --- | --- |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&) | 지정된 문자열(숫자의 문자열 표현 포함)을 64비트 부호 있는 정수로 변환합니다. |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 문자열(숫자의 문자열 표현 포함)을 제공된 형식 정보와 함께 64비트 부호 있는 정수로 변환합니다. |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 문자열(숫자의 문자열 표현 포함)을 제공된 형식 정보와 숫자 스타일을 사용하여 64비트 부호 있는 정수로 변환합니다. |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **int64_t**\&) | 지정된 문자열(숫자의 문자열 표현 포함)을 64비트 부호 있는 정수로 변환합니다. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **int64_t**\&) | 지정된 문자열(숫자의 문자열 표현 포함)을 제공된 형식 정보와 숫자 스타일을 사용하여 64비트 부호 있는 정수로 변환합니다. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **int64_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **int64_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **int64_t**\&) |  |

## 필드

| Field | Description |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | 가능한 가장 큰 값. |
| static constexpr [MinValue](./minvalue/) | 가능한 가장 작은 값. |

## 참고

* Namespace [System](../)
* Library [Aspose.Slides](../../)
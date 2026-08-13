---
title: MathF
second_title: C++용 Aspose.Slides API 참조
description: 단정도 부동 소수점 값을 위한 수학 함수를 포함합니다. 이것은 인스턴스 서비스를 제공하지 않는 정적 타입입니다. 어떠한 방법으로도 인스턴스를 생성해서는 안 됩니다.
type: docs
weight: 1795
url: /ko/system/mathf/
---
## MathF struct

단정도 부동 소수점 값을 위한 수학 함수를 포함합니다. 이것은 인스턴스 서비스를 제공하지 않는 정적 타입입니다. 어떠한 방법으로도 인스턴스를 생성해서는 안 됩니다.

```cpp
class MathF
```

## 메서드

| Method | Description |
| --- | --- |
| static T [Abs](./abs/)(T) | 지정된 값의 절대값을 반환합니다. |
| static **float** [Acos](./acos/)(**float**) | 지정된 값의 아크코사인을 계산합니다. |
| static **float** [Asin](./asin/)(**float**) | 지정된 값의 아크사인을 계산합니다. |
| static **float** [Atan](./atan/)(**float**) | 지정된 값의 아크탄젠트를 계산합니다. |
| static **float** [Atan2](./atan2/)(**float**, **float**) | 지정된 값들의 비율에 대한 아크탄젠트를 계산합니다. |
| static **float** [Ceiling](./ceiling/)(**float**) | 지정된 값보다 크거나 같은 가장 작은 정수 값을 반환합니다. |
| static **float** [Cos](./cos/)(**float**) | 지정된 값의 코사인을 계산합니다. |
| static **float** [Cosh](./cosh/)(**float**) | 지정된 값의 쌍곡선 코사인을 계산합니다. |
| static **float** [Exp](./exp/)(**float**) | 지정된 지수만큼 거듭 제곱한 e 상수를 반환합니다. |
| static **float** [Floor](./floor/)(**float**) | 지정된 값보다 작거나 같은 가장 큰 정수 값을 반환합니다. |
| static **float** [IEEERemainder](./ieeeremainder/)(**float**, **float**) | 지정된 숫자를 다른 지정된 숫자로 나눈 나머지를 반환합니다. |
| static **float** [Log](./log/)(**float**) | 지정된 값의 자연 로그를 반환합니다. |
| static **float** [Log](./log/)(**float**, **float**) | 지정된 밑을 사용하여 지정된 값의 로그를 반환합니다. |
| static **float** [Log10](./log10/)(**float**) | 지정된 값의 상용 로그(밑 10)를 반환합니다. |
| static **float** [Pow](./pow/)(**float**, **float**) | 지정된 값을 지정된 지수만큼 거듭 제곱하여 반환합니다. |
| static **float** [Round](./round/)(**float**) | 지정된 값을 가장 가까운 정수값으로 반올림합니다. |
| static **float** [Round](./round/)(**float**, int) | 지정된 값을 지정된 소수 자리수와 가장 가까운 값으로 반올림합니다. |
| static **float** [Round](./round/)(**float**, [MidpointRounding](../midpointrounding/)) | 지정된 값을 가장 가까운 정수로 반올림합니다. 매개변수는 지정된 값이 두 근접한 수와 거리가 동일할 때 함수의 동작을 지정합니다. |
| static **float** [Round](./round/)(**float**, int, [MidpointRounding](../midpointrounding/)) | 지정된 값을 지정된 소수 자리수와 가장 가까운 값으로 반올림합니다. 매개변수는 지정된 값이 두 근접한 수와 거리가 동일할 때 함수의 동작을 지정합니다. |
| static **float** [RoundImpl](./roundimpl/)(**float**, int, [MidpointRounding](../midpointrounding/)) | 지정된 값을 지정된 소수 자리수와 가장 가까운 값으로 반올림합니다. 매개변수는 지정된 값이 두 근접한 수와 거리가 동일할 때 함수의 동작을 지정합니다. |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | 지정된 부호 있는 정수 값의 부호를 결정합니다. |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | 지정된 부동 소수점 값의 부호를 결정합니다. |
| static **float** [Sin](./sin/)(**float**) | 지정된 값의 사인을 계산합니다. |
| static **float** [Sinh](./sinh/)(**float**) | 지정된 값의 쌍곡선 사인을 계산합니다. |
| static **float** [Sqrt](./sqrt/)(**float**) | 지정된 값의 제곱근을 반환합니다. |
| static **float** [Tan](./tan/)(**float**) | 지정된 값의 탄젠트를 계산합니다. |
| static **float** [Tanh](./tanh/)(**float**) | 지정된 값의 쌍곡선 탄젠트를 계산합니다. |
| static **float** [Truncate](./truncate/)(**float**) | 지정된 값과 동일한 정수 부분을 가지고 소수점 이하를 모두 버린 부동소수점(float) 값을 반환합니다. |

## 필드

| Field | Description |
| --- | --- |
| static [E](./e/) | 자연 로그의 밑. |
| static constexpr [MaxRoundingDigits](./maxroundingdigits/) |  |
| static [PI](./pi/) | 원주율 파이 상수. |
| static [Tau](./tau/) | 타우 값. |

## 참조

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)
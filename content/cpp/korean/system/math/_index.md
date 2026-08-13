---
title: Math
second_title: Aspose.Slides for C++ API 레퍼런스
description: 수학 함수를 포함합니다. 이는 인스턴스 서비스를 제공하지 않는 정적 타입입니다. 어떠한 방법으로도 해당 타입의 인스턴스를 생성해서는 안 됩니다.
type: docs
weight: 1782
url: /ko/system/math/
---
## Math 구조체

수학 함수를 포함합니다. 인스턴스 서비스를 제공하지 않는 정적 타입입니다. 어떠한 방법으로도 인스턴스를 생성해서는 안 됩니다.

```cpp
class Math
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static T [Abs](./abs/)(T) | 지정된 값의 절대값을 반환합니다. |
| static [Decimal](../decimal/) [Abs](./abs/)(const [Decimal](../decimal/)\&) | 지정된 [Decimal](../decimal/) 객체가 나타내는 값의 절대값을 반환합니다. |
| static **double** [Acos](./acos/)(**double**) | 지정된 값의 아크코사인(arccosine)을 계산합니다. |
| static **double** [Asin](./asin/)(**double**) | 지정된 값의 아크사인(arcsin)을 계산합니다. |
| static **double** [Atan](./atan/)(**double**) | 지정된 값의 아크탄젠트(arctan)을 계산합니다. |
| static **double** [Atan2](./atan2/)(**double**, **double**) | 지정된 값들의 비율에 대한 아크탄젠트를 계산합니다. |
| static **int64_t** [BigMul](./bigmul/)(int, int) | 두 개의 32비트 정수의 전체 곱을 반환합니다. |
| static [Decimal](../decimal/) [Ceiling](./ceiling/)(const [Decimal](../decimal/)\&) | 지정된 값보다 크거나 같은 가장 작은 정수 값을 반환합니다. |
| static **double** [Ceiling](./ceiling/)(**double**) | 지정된 값보다 크거나 같은 가장 작은 정수 값을 반환합니다. |
| static **double** [Cos](./cos/)(**double**) | 지정된 값의 코사인을 계산합니다. |
| static **double** [Cosh](./cosh/)(**double**) | 지정된 값의 쌍곡선 코사인을 계산합니다. |
| static int [DivRem](./divrem/)(int, int, int\&) | 두 개의 32비트 정수에 대한 몫과 나머지를 계산합니다. |
| static **int64_t** [DivRem](./divrem/)(**int64_t**, **int64_t**, **int64_t**\&) | 두 개의 64비트 정수에 대한 몫과 나머지를 계산합니다. |
| static **double** [Exp](./exp/)(**double**) | 지정된 지수로 e 상수를 거듭 제곱한 값을 반환합니다. |
| static [Decimal](../decimal/) [Floor](./floor/)(const [Decimal](../decimal/)\&) | 지정된 값보다 작거나 같은 가장 큰 정수 값을 반환합니다. |
| static **double** [Floor](./floor/)(**double**) | 지정된 값보다 작거나 같은 가장 큰 정수 값을 반환합니다. |
| static **double** [IEEERemainder](./ieeeremainder/)(**double**, **double**) | 지정된 수를 다른 지정된 수로 나눈 나머지를 반환합니다. |
| static **double** [Log](./log/)(**double**) | 지정된 값의 자연 로그를 반환합니다. |
| static **double** [Log](./log/)(**double**, **double**) | 지정된 밑을 사용하여 지정된 값의 로그를 반환합니다. |
| static **double** [Log10](./log10/)(**double**) | 지정된 값의 상용 로그(밑 10)를 반환합니다. |
| static auto [Max](./max/)(T0, T1) | 지정된 두 숫자 중 가장 큰 값을 반환합니다. |
| static T0 [Max](./max/)(T0, T1) | 지정된 두 숫자 중 가장 큰 값을 반환합니다. |
| **float** [Max_](./max_/)(**float**, **float**) | 두 지정된 단정도 부동소수점 값 중 가장 큰 값을 반환합니다. |
| **double** [Max_](./max_/)(**double**, **double**) | 두 지정된 배정도 부동소수점 값 중 가장 큰 값을 반환합니다. |
| static auto [Min](./min/)(T0, T1) | 지정된 두 숫자 중 가장 작은 값을 반환합니다. |
| static T0 [Min](./min/)(T0, T1) | 지정된 두 숫자 중 가장 작은 값을 반환합니다. |
| **float** [Min_](./min_/)(**float**, **float**) | 두 지정된 단정도 부동소수점 값 중 가장 작은 값을 반환합니다. |
| **double** [Min_](./min_/)(**double**, **double**) | 두 지정된 배정도 부동소수점 값 중 가장 작은 값을 반환합니다. |
| static T [Modulus](./modulus/)(T, T) | 한 지정된 값을 다른 지정된 값으로 나눈 나머지를 계산합니다. |
| static **double** [Pow](./pow/)(**double**, **double**) | 지정된 값을 지정된 지수만큼 제곱한 결과를 반환합니다. |
| static **double** [Round](./round/)(**double**) | 지정된 값을 가장 가까운 정수로 반올림합니다. |
| static **double** [Round](./round/)(**double**, int) | 지정된 값을 지정된 소수점 자리수만큼 가장 가까운 값으로 반올림합니다. |
| static **double** [Round](./round/)(**double**, [MidpointRounding](../midpointrounding/)) | 지정된 값을 가장 가까운 정수로 반올림합니다. 매개변수는 지정된 값이 두 가장 가까운 수와 동일한 거리에 있을 때 함수의 동작을 지정합니다. |
| static **double** [Round](./round/)(**double**, int, [MidpointRounding](../midpointrounding/)) | 지정된 값을 지정된 소수점 자리수만큼 가장 가까운 값으로 반올림합니다. 매개변수는 지정된 값이 두 가장 가까운 수와 동일한 거리에 있을 때 함수의 동작을 지정합니다. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&) | 지정된 값을 가장 가까운 정수로 반올림합니다. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, int) | 지정된 값을 지정된 소수점 자리수만큼 가장 가까운 값으로 반올림합니다. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, [MidpointRounding](../midpointrounding/)) | 지정된 값을 가장 가까운 정수로 반올림합니다. 매개변수는 지정된 값이 두 가장 가까운 수와 동일한 거리에 있을 때 함수의 동작을 지정합니다. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, int, [MidpointRounding](../midpointrounding/)) | 지정된 값을 지정된 소수점 자리수만큼 가장 가까운 값으로 반올림합니다. 매개변수는 지정된 값이 두 가장 가까운 수와 동일한 거리에 있을 때 함수의 동작을 지정합니다. |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | 지정된 부호가 있는 정수 값의 부호를 결정합니다. |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | 지정된 부동소수점 값의 부호를 결정합니다. |
| static int [Sign](./sign/)(const [Decimal](../decimal/)\&) | 지정된 십진수 값의 부호를 결정합니다. |
| static **double** [Sin](./sin/)(**double**) | 지정된 값의 사인을 계산합니다. |
| static **double** [Sinh](./sinh/)(**double**) | 지정된 값의 쌍곡선 사인을 계산합니다. |
| static **double** [Sqrt](./sqrt/)(**double**) | 지정된 값의 제곱근을 반환합니다. |
| static **double** [Tan](./tan/)(**double**) | 지정된 값의 탄젠트를 계산합니다. |
| static **double** [Tanh](./tanh/)(**double**) | 지정된 값의 쌍곡선 탄젠트를 계산합니다. |
| static [Decimal](../decimal/) [Truncate](./truncate/)(const [Decimal](../decimal/)\&) | 지정된 [Decimal](../decimal/) 객체가 나타내는 값에서 모든 소수점 이하를 버린 후 정수부가 동일한 [Decimal](../decimal/) 객체를 반환합니다. |
| static **double** [Truncate](./truncate/)(**double**) | 지정된 값에서 모든 소수점 이하를 버린 후 정수부가 동일한 배정도 부동소수점 값을 반환합니다. |

## 필드

| 필드 | 설명 |
| --- | --- |
| static [E](./e/) | 자연 로그의 밑. |
| static [NaN](./nan/) | Not-a-Number 값을 나타냅니다. |
| static [NegativeInfinity](./negativeinfinity/) | 음의 무한대를 나타냅니다. |
| static [PI](./pi/) | 원주율(Pi) 상수를 나타냅니다. |
| static [PositiveInfinity](./positiveinfinity/) | 양의 무한대를 나타냅니다. |

## 비고



```cpp
#include "system/math.h"
#include <iostream>

int main()
{
  using namespace System;

  // 절대값을 출력합니다.
  for (int i = -1; i < 2; ++i)
  {
    std::cout << Math::Abs(i) << " ";
  }
  std::cout << std::endl;

  // PI/2의 사인과 PI의 코사인을 출력합니다.
  std::cout << "sin(PI/2)=" << Math::Sin(Math::PI/2) << "; cos(PI)=" << Math::Cos(Math::PI) << std::endl;

  return 0;
}
/*
이 코드 예제는 다음과 같은 출력을 생성합니다:
1 0 1
sin(PI/2)=1; cos(PI)=-1
*/
```

## 참조

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)
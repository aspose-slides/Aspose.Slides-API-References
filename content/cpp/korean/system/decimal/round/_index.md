---
title: Round()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 값을 가장 가까운 정수로 반올림합니다. 매개변수는 지정된 값이 두 가장 가까운 숫자에 동일하게 가까운 경우 함수의 동작을 지정합니다.
type: docs
weight: 404
url: /ko/system/decimal/round/
---
## Decimal::Round(const Decimal\&, MidpointRounding) 메서드


지정된 값을 가장 가까운 정수로 반올림합니다. 매개변수는 지정된 값이 두 가장 가까운 숫자에 동일하게 가까운 경우 함수의 동작을 지정합니다.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, MidpointRounding mode=MidpointRounding::ToEven)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| d | const [Decimal](../)\& | 반올림할 값 |
| mode | [MidpointRounding](../../midpointrounding/) | **값**이 두 가장 가까운 숫자에 동일하게 가까울 때 반올림 방법을 지정합니다. |

### 반환 값

**d** 를 가장 가까운 정수값으로 반올림

## Decimal::Round(const Decimal\&, int, MidpointRounding) 메서드


지정된 값을 지정된 소수 자리수만큼 가장 가까운 값으로 반올림합니다. 매개변수는 지정된 값이 두 가장 가까운 숫자에 동일하게 가까운 경우 함수의 동작을 지정합니다.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, int digits, MidpointRounding mode=MidpointRounding::ToEven)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| d | const [Decimal](../)\& | 반올림할 값 |
| digits | int | 반올림된 값의 소수 자리수 |
| mode | [MidpointRounding](../../midpointrounding/) | **값**이 두 가장 가까운 숫자에 동일하게 가까울 때 반올림 방법을 지정합니다. |

### 반환 값

지정된 자리수를 가진 숫자이며 **값**에 가장 가깝습니다

## 또 보기

* 열거형 [MidpointRounding](../../midpointrounding/)
* 클래스 [Decimal](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)
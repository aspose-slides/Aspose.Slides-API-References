---
title: Round()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 값을 가장 가까운 정수값으로 반올림합니다.
type: docs
weight: 157
url: /ko/system/math/round/
---
## Math::Round(double) 메서드

지정된 값을 가장 가까운 정수 값으로 반올림합니다.

```cpp
static double System::Math::Round(double a)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | **double** | 반올림할 값 |

### 반환값

**a** 를 가장 가까운 정수 값으로 반올림한 결과

## Math::Round(double, int) 메서드

지정된 값을 지정된 소수 자릿수로 가장 가까운 값으로 반올림합니다.

```cpp
static double System::Math::Round(double value, int digits)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **double** | 반올림할 값 |
| digits | int | 반올림된 값의 소수 자릿수 |

### 반환값

지정된 자릿수로 **value** 에 가장 가까운 숫자

## Math::Round(double, MidpointRounding) 메서드

지정된 값을 가장 가까운 정수로 반올림합니다. 지정된 값이 두 가장 가까운 수와 같은 거리에 있을 경우 동작을 지정하는 매개변수가 있습니다.

```cpp
static double System::Math::Round(double value, MidpointRounding mode)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **double** | 반올림할 값 |
| mode | [MidpointRounding](../../midpointrounding/) | **value** 가 두 가장 가까운 수와 같은 거리에 있을 때 반올림 방식을 지정합니다. |

### 반환값

**value** 를 가장 가까운 정수 값으로 반올림한 결과

## Math::Round(double, int, MidpointRounding) 메서드

지정된 값을 지정된 소수 자릿수로 가장 가까운 값으로 반올림합니다. 지정된 값이 두 가장 가까운 수와 같은 거리에 있을 경우 동작을 지정하는 매개변수가 있습니다.

```cpp
static double System::Math::Round(double value, int digits, MidpointRounding mode)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **double** | 반올림할 값 |
| digits | int | 반올림된 값의 소수 자릿수 |
| mode | [MidpointRounding](../../midpointrounding/) | **value** 가 두 가장 가까운 수와 같은 거리에 있을 때 반올림 방식을 지정합니다. |

### 반환값

지정된 자릿수로 **value** 에 가장 가까운 숫자

## Math::Round(const Decimal\&) 메서드

지정된 값을 가장 가까운 정수 값으로 반올림합니다.

```cpp
static Decimal System::Math::Round(const Decimal &d)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | 반올림할 값 |

### 반환값

**d** 를 가장 가까운 정수 값으로 반올림한 결과

## Math::Round(const Decimal\&, int) 메서드

지정된 값을 지정된 소수 자릿수로 가장 가까운 값으로 반올림합니다.

```cpp
static Decimal System::Math::Round(const Decimal &value, int digits)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | 반올림할 값 |
| digits | int | 반올림된 값의 소수 자릿수 |

### 반환값

지정된 자릿수로 **value** 에 가장 가까운 숫자

## Math::Round(const Decimal\&, MidpointRounding) 메서드

지정된 값을 가장 가까운 정수로 반올림합니다. 지정된 값이 두 가장 가까운 수와 같은 거리에 있을 경우 동작을 지정하는 매개변수가 있습니다.

```cpp
static Decimal System::Math::Round(const Decimal &d, MidpointRounding mode)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | 반올림할 값 |
| mode | [MidpointRounding](../../midpointrounding/) | **value** 가 두 가장 가까운 수와 같은 거리에 있을 때 반올림 방식을 지정합니다. |

### 반환값

**d** 를 가장 가까운 정수 값으로 반올림한 결과

## Math::Round(const Decimal\&, int, MidpointRounding) 메서드

지정된 값을 지정된 소수 자릿수로 가장 가까운 값으로 반올림합니다. 지정된 값이 두 가장 가까운 수와 같은 거리에 있을 경우 동작을 지정하는 매개변수가 있습니다.

```cpp
static Decimal System::Math::Round(const Decimal &d, int digits, MidpointRounding mode)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | 반올림할 값 |
| digits | int | 반올림된 값의 소수 자릿수 |
| mode | [MidpointRounding](../../midpointrounding/) | **value** 가 두 가장 가까운 수와 같은 거리에 있을 때 반올림 방식을 지정합니다. |

### 반환값

지정된 자릿수로 **value** 에 가장 가까운 숫자

## 참고

* Enum [MidpointRounding](../../midpointrounding/)
* 클래스 [Decimal](../../decimal/)
* Struct [Math](../)
* 네임스페이스 [System](../../)
* Library [Aspose.Slides](../../../)
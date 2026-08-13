---
title: Round()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 값을 가장 가까운 정수값으로 반올림합니다.
type: docs
weight: 157
url: /ko/system/mathf/round/
---
## MathF::Round(float) 메서드


지정된 값을 가장 가까운 정수값으로 반올림합니다.

```cpp
static float System::MathF::Round(float a)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | **float** | 반올림할 값 |

### 반환 값

**a**를 가장 가까운 정수값으로 반올림

## MathF::Round(float, int) 메서드


지정된 값을 지정된 소수 자리 수를 가진 가장 가까운 값으로 반올림합니다.

```cpp
static float System::MathF::Round(float value, int digits)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **float** | 반올림할 값 |
| digits | int | 반올림된 값의 소수 자리 수 |

### 반환 값

지정된 자리 수를 갖는, **value**에 가장 가까운 숫자

## MathF::Round(float, MidpointRounding) 메서드


지정된 값을 가장 가까운 정수값으로 반올림합니다. 매개변수는 지정된 값이 두 가장 가까운 숫자와 동일한 거리에 있을 때 함수의 동작 방식을 지정합니다.

```cpp
static float System::MathF::Round(float value, MidpointRounding mode)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **float** | 반올림할 값 |
| mode | [MidpointRounding](../../midpointrounding/) | **value**가 두 가장 가까운 숫자와 동일한 거리에 있을 때 반올림을 수행하는 방법을 지정합니다. |

### 반환 값

**value**를 가장 가까운 정수값으로 반올림

## MathF::Round(float, int, MidpointRounding) 메서드


지정된 값을 지정된 소수 자리 수를 가진 가장 가까운 값으로 반올림합니다. 매개변수는 지정된 값이 두 가장 가까운 숫자와 동일한 거리에 있을 때 함수의 동작 방식을 지정합니다.

```cpp
static float System::MathF::Round(float value, int digits, MidpointRounding mode)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **float** | 반올림할 값 |
| digits | int | 반올림된 값의 소수 자리 수 |
| mode | [MidpointRounding](../../midpointrounding/) | **value**가 두 가장 가까운 숫자와 동일한 거리에 있을 때 반올림을 수행하는 방법을 지정합니다. |

### 반환 값

지정된 자리 수를 갖는, **value**에 가장 가까운 숫자

## See Also

* Enum [MidpointRounding](../../midpointrounding/)
* Struct [MathF](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
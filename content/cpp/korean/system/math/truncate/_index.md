---
title: Truncate()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 Decimal 객체가 나타내는 값과 동일한 정수 부분을 가지며 모든 소수 자릿수가 제거된 값을 나타내는 Decimal 객체를 반환합니다.
type: docs
weight: 170
url: /ko/system/math/truncate/
---
## Math::Truncate(const Decimal\&) 메서드

Returns the [Decimal](../../decimal/) object representing a value that has integral part equal to that of the value represented by the specified [Decimal](../../decimal/) object of the with all fractional digits discarded.

```cpp
static Decimal System::Math::Truncate(const Decimal &d)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | 십진수 |

### 반환 값

[Decimal](../../decimal/) 객체는 지정된 값과 동일한 정수 부분을 가지며 모든 소수 자릿수가 0인 십진수 값을 나타냅니다.

## Math::Truncate(double) 메서드

Returns a double-precision floating point value that has integral part equal to that of the specified value with all fractional digits discarded.

```cpp
static double System::Math::Truncate(double d)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| d | **double** | 십진수 |

### 반환 값

double-precision 부동 소수점 값은 지정된 값과 동일한 정수 부분을 가지며 모든 소수 자릿수가 0입니다.

## 참조

* 클래스 [Decimal](../../decimal/)
* 구조체 [Math](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)
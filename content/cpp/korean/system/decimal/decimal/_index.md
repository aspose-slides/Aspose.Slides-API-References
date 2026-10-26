---
title: Decimal()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 값이 0인 인스턴스를 생성합니다.
type: docs
weight: 1
url: /ko/system/decimal/decimal/
---
## Decimal::Decimal() 생성자

값이 0인 인스턴스를 생성합니다.

```cpp
System::Decimal::Decimal()
```

## Decimal::Decimal(std::int8_t) 생성자

지정된 값을 나타내는 인스턴스를 생성합니다.

```cpp
System::Decimal::Decimal(std::int8_t i)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| i | std::int8_t | 구성되는 [Decimal](../) 객체가 나타내는 8비트 정수 값 |

## Decimal::Decimal(std::int16_t) 생성자

지정된 값을 나타내는 인스턴스를 생성합니다.

```cpp
System::Decimal::Decimal(std::int16_t i)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| i | std::int16_t | 구성되는 [Decimal](../) 객체가 나타내는 16비트 정수 값 |

## Decimal::Decimal(std::int32_t) 생성자

지정된 값을 나타내는 인스턴스를 생성합니다.

```cpp
System::Decimal::Decimal(std::int32_t i)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| i | std::int32_t | 구성되는 [Decimal](../) 객체가 나타내는 32비트 정수 값 |

## Decimal::Decimal(std::int64_t) 생성자

지정된 값을 나타내는 인스턴스를 생성합니다.

```cpp
System::Decimal::Decimal(std::int64_t i)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| i | std::int64_t | 구성되는 [Decimal](../) 객체가 나타내는 64비트 정수 값 |

## Decimal::Decimal(std::uint8_t) 생성자

지정된 값을 나타내는 인스턴스를 생성합니다.

```cpp
System::Decimal::Decimal(std::uint8_t i)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| i | std::uint8_t | 구성되는 [Decimal](../) 객체가 나타내는 부호 없는 8비트 정수 값 |

## Decimal::Decimal(std::uint16_t) 생성자

지정된 값을 나타내는 인스턴스를 생성합니다.

```cpp
System::Decimal::Decimal(std::uint16_t i)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| i | std::uint16_t | 구성되는 [Decimal](../) 객체가 나타내는 부호 없는 16비트 정수 값 |

## Decimal::Decimal(std::uint32_t) 생성자

지정된 값을 나타내는 인스턴스를 생성합니다.

```cpp
System::Decimal::Decimal(std::uint32_t i)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| i | std::uint32_t | 구성되는 [Decimal](../) 객체가 나타내는 부호 없는 32비트 정수 값 |

## Decimal::Decimal(std::uint64_t) 생성자

지정된 값을 나타내는 인스턴스를 생성합니다.

```cpp
System::Decimal::Decimal(std::uint64_t i)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| i | std::uint64_t | 구성되는 [Decimal](../) 객체가 나타내는 부호 없는 64비트 정수 값 |

## Decimal::Decimal(float) 생성자

지정된 값을 나타내는 인스턴스를 생성합니다.

```cpp
System::Decimal::Decimal(float f)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| f | **float** | 구성되는 [Decimal](../) 객체가 나타내는 단정밀도 부동소수점 값 |

## Decimal::Decimal(double) 생성자

지정된 값을 나타내는 인스턴스를 생성합니다.

```cpp
System::Decimal::Decimal(double d)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| d | **double** | 구성되는 [Decimal](../) 객체가 나타내는 배정밀도 부동소수점 값 |

## Decimal::Decimal(const std::string\&) 생성자

std::string 클래스의 인스턴스로 지정된 문자열 표현을 가지는 값을 나타내는 인스턴스를 생성합니다.

```cpp
System::Decimal::Decimal(const std::string &str)
```

## Decimal::Decimal(int32_t, int32_t, int32_t, bool, uint8_t) 생성자

지정된 구성 요소들로부터 [Decimal](../) 객체를 생성합니다.

```cpp
System::Decimal::Decimal(int32_t lo, int32_t mid, int32_t hi, bool isNegative, uint8_t scale)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lo | **int32_t** | 값의 낮은 32비트 |
| mid | **int32_t** | 값의 중간 32비트 |
| hi | **int32_t** | 값의 높은 32비트 |
| isNegative | **bool** | 값이 음수인지 여부를 지정합니다 |
| scale | **uint8_t** | 0부터 28까지의 10의 거듭제곱 |

## Decimal::Decimal(const Decimal\&) 생성자

지정된 [Decimal](../) 객체와 동일한 수를 나타내는 [Decimal](../) 클래스의 인스턴스를 생성합니다.

```cpp
System::Decimal::Decimal(const Decimal &d)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| d | const [Decimal](../)\& | [Decimal](../) 객체에서 값을 복사합니다 |

## Decimal::Decimal(const ArrayPtr\<int32_t\>\&) 생성자

이진 표현을 포함하는 정수 배열로부터 [Decimal](../) 클래스의 인스턴스를 생성합니다.

```cpp
System::Decimal::Decimal(const ArrayPtr<int32_t> &bits)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bits | const [ArrayPtr](../../arrayptr/)\<**int32_t**\>\& | 이진 표현을 포함하는 정수 배열 |

## Decimal::Decimal(std::nullptr_t) 생성자

항상 ArgumentNullException을 발생시킵니다.

```cpp
System::Decimal::Decimal(std::nullptr_t bits)
```

## Decimal::Decimal(const number_type\&) 생성자

[Decimal](../) 클래스의 지정된 값을 나타내는 인스턴스를 생성합니다.

```cpp
System::Decimal::Decimal(const number_type &value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [number_type](../number_type/)\& | 구성되는 객체가 나타낼 값에 대한 상수 레퍼런스 |

## 관련 항목

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [number_type](../number_type/)
* Class [Decimal](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
---
title: Sign()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 부호가 있는 정수값의 부호를 결정합니다.
type: docs
weight: 274
url: /ko/system/math/sign/
---
## Math::Sign(T) 메서드


지정된 부호가 있는 정수값의 부호를 결정합니다.

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::Math::Sign(T value)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 정수형 부호 있는 타입 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | T | 부호를 결정할 값 |

### 반환값

- 1이면 **value**가 0보다 작고; 0이면 **value**가 0과 같으며; 1이면 **value**가 0보다 큽니다.

## Math::Sign(T) 메서드


지정된 부동소수점 값의 부호를 결정합니다.

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::Math::Sign(T value)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 인수의 부동 소수점 타입 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | T | 부호를 결정할 값 |

### 반환값

- 1이면 **value**가 0보다 작고; 0이면 **value**가 0과 같으며; 1이면 **value**가 0보다 큽니다.

## Math::Sign(const Decimal\&) 메서드


지정된 십진수 값의 부호를 결정합니다.

```cpp
static int System::Math::Sign(const Decimal &value)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | 부호를 결정할 값 |

### 반환값

- 1이면 **value**가 0보다 작고; 0이면 **value**가 0과 같으며; 1이면 **value**가 0보다 큽니다.

## 관련 항목

* 클래스 [Decimal](../../decimal/)
* 구조체 [Math](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)
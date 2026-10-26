---
title: Sign()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 부호가 있는 정수 값의 부호를 결정합니다.
type: docs
weight: 274
url: /ko/system/mathf/sign/
---
## MathF::Sign(T) 메서드

지정된 부호가 있는 정수 값의 부호를 결정합니다.

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::MathF::Sign(T value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 정수 부호 있는 형식 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | T | 부호를 결정할 값 |

### 반환값

- 1이면 **value**가 0보다 작고; 0이면 **value**가 0과 같으며; 1이면 **value**가 0보다 큽니다

## MathF::Sign(T) 메서드

지정된 부동 소수점 값의 부호를 결정합니다.

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::MathF::Sign(T value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 인수의 부동 소수점 형식 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | T | 부호를 결정할 값 |

### 반환값

- 1이면 **value**가 0보다 작고; 0이면 **value**가 0과 같으며; 1이면 **value**가 0보다 큽니다

## 관련 보기

* 구조체 [MathF](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)
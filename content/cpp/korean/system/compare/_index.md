---
title: Compare()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 두 값을 비교합니다.
type: docs
weight: 2731
url: /ko/system/compare/
---
## System::Compare(const TA\&, const TB\&) function

두 값을 비교합니다.

```cpp
template<typename TA,typename TB> std::enable_if_t<!std::is_floating_point<TA>::value &&!std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TA | 첫 번째 비교 대상의 유형 |
| TB | 두 번째 비교 대상의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | const TA\& | 첫 번째 비교 대상 |
| b | const TB\& | 두 번째 비교 대상 |

### 반환값

- 1: **a**가 **b**보다 작게 비교되는 경우; 0: 값이 같은 경우; 1: **a**가 **b**보다 크게 비교되는 경우

## System::Compare(const TA\&, const TB\&) function

두 개의 부동소수점 값을 비교합니다.

```cpp
template<typename TA,typename TB> std::enable_if_t<std::is_floating_point<TA>::value &&std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TA | 첫 번째 비교 대상의 유형 |
| TB | 두 번째 비교 대상의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | const TA\& | 첫 번째 비교 대상 |
| b | const TB\& | 두 번째 비교 대상 |

### 반환값

- 1: **a**가 **b**보다 작게 비교되는 경우; 0: 값이 같은 경우; 1: **a**가 **b**보다 크게 비교되는 경우

## 참조

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)
---
title: AreFPNaN()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 네임스페이스 세부 정보
type: docs
weight: 1
url: /ko/system.testpredicates/arefpnan/
---
## System::TestPredicates::AreFPNaN(T1, T2) 함수


네임스페이스 [Details](../../system.testpredicates.details/)

```cpp
template<typename T1,typename T2> std::enable_if<std::numeric_limits<T1>::has_quiet_NaN &&std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | 첫 번째 부동 소수점 타입. |
| T2 | 두 번째 부동 소수점 타입. |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| lhs | T1 | 첫 번째 부동 소수점 값. |
| rhs | T2 | 두 번째 부동 소수점 값. |

### 반환값

lhs와 rhs가 모두 부동 소수점 값이면 true, 그렇지 않으면 false.
## 비고


두 부동 소수점 값이 모두 NaN인지 확인합니다. 비신호 NaN이 지원되는 상황을 처리합니다. 
## System::TestPredicates::AreFPNaN(T1, T2) 함수


두 부동 소수점 값이 모두 NaN인지 확인합니다. 비신호 NaN이 지원되지 않는 상황을 처리합니다.

```cpp
template<typename T1,typename T2> std::enable_if<!std::numeric_limits<T1>::has_quiet_NaN||!std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | 첫 번째 부동 소수점 타입. |
| T2 | 두 번째 부동 소수점 타입. |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| lhs | T1 | 첫 번째 부동 소수점 값. |
| rhs | T2 | 두 번째 부동 소수점 값. |

### 반환값

NaN 값이 지원되지 않으므로 항상 false를 반환합니다.

## 참조

* 네임스페이스 [System::TestPredicates](../)
* 라이브러리 [Aspose.Slides](../../)
---
title: AreNotSameImpl()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 같지 않음 비교는 스마트 포인터를 비교합니다.
type: docs
weight: 105
url: /ko/system.testpredicates/arenotsameimpl/
---
## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1\&, const T2\&, long long) 함수

같지 않음 비교는 스마트 포인터를 비교합니다.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T1 | LHS 객체 유형. |
| T2 | RHS 객체 유형. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS 표현식. |
| rhs_expr | const char * | RHS 표현식. |
| lhs | const T1\& | LHS 값. |
| rhs | const T2\& | RHS 값. |
| s | long long | 함수 구현을 선택하는 서비스 매개변수; 매개변수 값은 무시됩니다. |

### 반환값

gtest 스타일의 단언 결과.

## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1\&, const T2\&, int) 함수

같지 않음 비교는 포인터가 아닌 값을 비교합니다.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T1 | LHS 객체 유형. |
| T2 | RHS 객체 유형. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS 표현식. |
| rhs_expr | const char * | RHS 표현식. |
| lhs | const T1\& | LHS 값. |
| rhs | const T2\& | RHS 값. |

### 반환값

gtest 스타일의 단언 결과.

## 참고

* 구조체 [IsSmartPtr](../../system/issmartptr/)
* 네임스페이스 [System::TestPredicates](../)
* 라이브러리 [Aspose.Slides](../../)
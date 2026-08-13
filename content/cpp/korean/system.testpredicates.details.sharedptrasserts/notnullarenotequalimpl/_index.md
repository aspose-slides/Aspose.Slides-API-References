---
title: NotNullAreNotEqualImpl()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 배열 또는 리스트를 같지 않게 비교합니다.
type: docs
weight: 105
url: /ko/system.testpredicates.details.sharedptrasserts/notnullarenotequalimpl/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

배열 또는 리스트를 같지 않음 비교합니다.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | LHS 컨테이너 유형. |
| T2 | RHS 컨테이너 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 표현식. |
| rhs_expr | const char * | RHS 표현식. |
| lhs | const T1\& | LHS 값. |
| rhs | const T2\& | RHS 값. |
| s | long long | 함수 구현을 선택하는 서비스 매개변수이며, 매개변수의 값은 무시됩니다. |

### 반환 값

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

IEnumerable 인스턴스를 같지 않음 비교합니다.

```cpp
template<typename T1,typename T2> std::enable_if<!TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value &&TypeTraits::BothEnumerable<typenameT1::Pointee_, typenameT2::Pointee_>::value &&(!TypeTraits::has_data_method<typenameT1::Pointee_>::value||!TypeTraits::has_data_method<typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | LHS 요소 유형. |
| T2 | RHS 요소 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 표현식. |
| rhs_expr | const char * | RHS 표현식. |
| lhs | const T1\& | LHS 값. |
| rhs | const T2\& | RHS 값. |
| s | long long | 함수 구현을 선택하는 서비스 매개변수이며, 매개변수의 값은 무시됩니다. |

### 반환 값

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, int32_t) function

알 수 없는 유형을 Eqauals 메서드를 사용해 같지 않음 비교합니다.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int32_t)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | LHS 객체 유형. |
| T2 | RHS 객체 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 표현식. |
| rhs_expr | const char * | RHS 표현식. |
| lhs | const T1\& | LHS 값. |
| rhs | const T2\& | RHS 값. |

### 반환 값

gtest-styled assertion result.

## 또 보기

* Typedef [BothArrayOrList](../../system.testpredicates.typetraits/botharrayorlist/)
* Typedef [BothEnumerable](../../system.testpredicates.typetraits/bothenumerable/)
* Struct [has_data_method](../../system.testpredicates.typetraits/has_data_method/)
* 네임스페이스 [System::TestPredicates::Details::SharedPtrAsserts](../)
* 라이브러리 [Aspose.Slides](../../)
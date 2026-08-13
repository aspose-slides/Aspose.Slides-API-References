---
title: NotNullAreEqualImpl()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 배열 또는 리스트를 동등 비교합니다.
type: docs
weight: 40
url: /ko/system.testpredicates.details.sharedptrasserts/notnullareequalimpl/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1&, const T2&, long long) 함수


배열 또는 리스트를 동등 비교합니다.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T1 | 좌변 컨테이너 유형. |
| T2 | 우변 컨테이너 유형. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | 좌변 식. |
| rhs_expr | const char * | 우변 식. |
| lhs | const T1\& | 좌변 값. |
| rhs | const T2\& | 우변 값. |
| s | long long | 함수 구현을 선택하는 서비스 매개변수; 매개변수 값은 무시됩니다 |

### 반환값

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1&, const T2&, long long) 함수


IEnumerable 인스턴스를 동등 비교합니다.

```cpp
template<typename T1,typename T2> std::enable_if<!TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value &&TypeTraits::BothEnumerable<typenameT1::Pointee_, typenameT2::Pointee_>::value &&(!TypeTraits::has_data_method<typenameT1::Pointee_>::value||!TypeTraits::has_data_method<typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T1 | 좌변 요소 유형. |
| T2 | 우변 요소 유형. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | 좌변 식. |
| rhs_expr | const char * | 우변 식. |
| lhs | const T1\& | 좌변 값. |
| rhs | const T2\& | 우변 값. |
| s | long long | 함수 구현을 선택하는 서비스 매개변수; 매개변수 값은 무시됩니다 |

### 반환값

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1&, const T2&, int32_t) 함수


Equals 메서드를 사용하여 알 수 없는 유형을 동등 비교합니다.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int32_t)
```


### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T1 | 좌변 객체 유형. |
| T2 | 우변 객체 유형. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | 좌변 식. |
| rhs_expr | const char * | 우변 식. |
| lhs | const T1\& | 좌변 값. |
| rhs | const T2\& | 우변 값. |

### 반환값

gtest-styled assertion result.

## 참고

* 타입 정의 [BothArrayOrList](../../system.testpredicates.typetraits/botharrayorlist/)
* 타입 정의 [BothEnumerable](../../system.testpredicates.typetraits/bothenumerable/)
* 구조체 [has_data_method](../../system.testpredicates.typetraits/has_data_method/)
* 네임스페이스 [System::TestPredicates::Details::SharedPtrAsserts](../)
* 라이브러리 [Aspose.Slides](../../)
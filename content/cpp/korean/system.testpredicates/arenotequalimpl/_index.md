---
title: AreNotEqualImpl()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 동등하지 않음 비교는 값 하나 또는 두 개가 Decimal인 경우를 비교합니다.
type: docs
weight: 53
url: /ko/system.testpredicates/arenotequalimpl/
---
## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) 함수


동등하지 않음 비교는 [Decimal](../../system/decimal/)인 값 하나 또는 두 개를 비교합니다.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | LHS 객체 유형. |
| T2 | RHS 객체 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| lhs | const T1\& | LHS 값. |
| rhs | const T2\& | RHS 값. |
| s | long long | 구현 선택자를 제공하는 서비스 매개변수; 매개변수 값은 무시됩니다. |

### 반환 값

gtest 스타일의 어설션 결과.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) 함수


동등하지 않음 비교는 제공된 Equals 메서드를 사용하여 포인터가 아닌 유형을 비교합니다.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Object](../../system/object/) 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| lhs | const T\& | LHS 값. |
| rhs | const T\& | RHS 값. |
| s | long long | 구현 선택자를 제공하는 서비스 매개변수; 매개변수 값은 무시됩니다. |

### 반환 값

gtest 스타일의 어설션 결과.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T\&, const T\&, long long) 함수


동등하지 않음 비교는 제공된 Equals 메서드를 사용하여 포인터가 아닌 유형을 비교합니다.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Object](../../system/object/) 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| lhs | T\& | LHS 값. |
| rhs | const T\& | RHS 값. |
| s | long long | 구현 선택자를 제공하는 서비스 매개변수; 매개변수 값은 무시됩니다. |

### 반환 값

gtest 스타일의 어설션 결과.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) 함수


동등하지 않음 비교는 제공된 operator != 를 사용하여 포인터가 아닌 유형을 비교합니다.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Object](../../system/object/) 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| lhs | const T\& | LHS 값. |
| rhs | const T\& | RHS 값. |
| s | long long | 구현 선택자를 제공하는 서비스 매개변수; 매개변수 값은 무시됩니다. |

### 반환 값

gtest 스타일의 어설션 결과.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) 함수


동등하지 않음 비교는 [SmartPtr](../../system/smartptr/) 값을 사용하여 박싱된 객체를 언박싱합니다.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Object](../../system/object/) 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| lhs | T | LHS 값. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | RHS 값. |
| s | long long | 구현 선택자를 제공하는 서비스 매개변수; 매개변수 값은 무시됩니다. |

### 반환 값

gtest 스타일의 어설션 결과.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) 함수


동등하지 않음 비교는 [SmartPtr](../../system/smartptr/) 값을 사용하여 박싱된 객체를 언박싱합니다.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Object](../../system/object/) 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | LHS 값. |
| rhs | T | RHS 값. |
| s | long long | 구현 선택자를 제공하는 서비스 매개변수; 매개변수 값은 무시됩니다. |

### 반환 값

gtest 스타일의 어설션 결과.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, std::nullptr_t, long long) 함수


동등하지 않음 비교는 nullptr와 임의 유형을 비교합니다.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Object](../../system/object/) 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| lhs | T | LHS 값. |
| s | std::nullptr_t | 구현 선택자를 제공하는 서비스 매개변수; 매개변수 값은 무시됩니다. |

### 반환 값

gtest 스타일의 어설션 결과.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, std::nullptr_t, T, long long) 함수


동등하지 않음 비교는 nullptr와 임의 유형을 비교합니다.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Object](../../system/object/) 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| rhs | std::nullptr_t | RHS 값. |
| s | T | 구현 선택자를 제공하는 서비스 매개변수; 매개변수 값은 무시됩니다. |

### 반환 값

gtest 스타일의 어설션 결과.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) 함수


동등 비교는 포인터 유형을 비교합니다.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | LHS 유형. |
| T2 | RHS 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| lhs | const T1\& | LHS 값. |
| rhs | const T2\& | RHS 값. |
| s | long long | 구현 선택자를 제공하는 서비스 매개변수; 매개변수 값은 무시됩니다. |

### 반환 값

gtest 스타일의 어설션 결과.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T1, T2, int) 함수


동등 비교는 gtest 알고리즘을 사용하여 임의 유형을 비교합니다.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | LHS 유형. |
| T2 | RHS 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| lhs | T1 | LHS 값. |
| rhs | T2 | RHS 값. |

### 반환 값

gtest 스타일의 어설션 결과.

## 또 보기

* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Object](../../system/object/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsBoxable](../../system/isboxable/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)
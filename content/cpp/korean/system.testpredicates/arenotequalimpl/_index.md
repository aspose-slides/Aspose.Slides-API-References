---
title: AreNotEqualImpl()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 값 중 하나 또는 두 개가 Decimal인 경우에 같지 않음을 비교합니다.
type: docs
weight: 53
url: /ko/system.testpredicates/arenotequalimpl/
---
## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) 함수

같지 않음 비교는 값 중 하나 또는 두 개가 [Decimal](../../system/decimal/)인 경우에 수행됩니다.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | LHS 객체 타입. |
| T2 | RHS 객체 타입. |

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| lhs | const T1\& | LHS 값. |
| rhs | const T2\& | RHS 값. |
| s | long long | 함수 구현을 선택하는 서비스 매개변수이며, 매개변수 값은 무시됩니다. |

### 반환값

gtest 스타일의 어설션 결과.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) 함수

같지 않음 비교는 두 [System::String](../../system/string/) 값을 비교하며, null [String](../../system/string/)에 대해 멤버 함수를 호출하는 것을 방지합니다. 위의 AreEqualImpl [String](../../system/string/) 오버로드와 동일한 연역 기반 제외 이유를 위해 템플릿화되었습니다.

```cpp
template<typename T> std::enable_if<std::is_same<T, System::String>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Object](../../system/object/) 타입, [System::String](../../system/string/) 로 제한됩니다. |

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| lhs | const T\& | LHS 값. |
| rhs | const T\& | RHS 값. |
| s | long long | 함수 구현을 선택하는 서비스 매개변수이며, 매개변수 값은 무시됩니다. |

### 반환값

gtest 스타일의 어설션 결과.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) 함수

같지 않음 비교는 제공된 Equals 메서드를 사용하여 포인터가 아닌 타입을 비교합니다.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Object](../../system/object/) 타입. |

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| lhs | const T\& | LHS 값. |
| rhs | const T\& | RHS 값. |
| s | long long | 함수 구현을 선택하는 서비스 매개변수이며, 매개변수 값은 무시됩니다. |

### 반환값

gtest 스타일의 어설션 결과.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T\&, const T\&, long long) 함수

같지 않음 비교는 제공된 Equals 메서드를 사용하여 포인터가 아닌 타입을 비교합니다.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Object](../../system/object/) 타입. |

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| lhs | T\& | LHS 값. |
| rhs | const T\& | RHS 값. |
| s | long long | 함수 구현을 선택하는 서비스 매개변수이며, 매개변수 값은 무시됩니다. |

### 반환값

gtest 스타일의 어설션 결과.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) 함수

같지 않음 비교는 제공된 != 연산자를 사용하여 포인터가 아닌 타입을 비교합니다.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Object](../../system/object/) 타입. |

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| lhs | const T\& | LHS 값. |
| rhs | const T\& | RHS 값. |
| s | long long | 함수 구현을 선택하는 서비스 매개변수이며, 매개변수 값은 무시됩니다. |

### 반환값

gtest 스타일의 어설션 결과.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) 함수

같지 않음 비교는 언박싱을 사용하여 [SmartPtr](../../system/smartptr/) 값을 가진 박스 가능한 유형을 비교합니다.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Object](../../system/object/) 타입. |

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| lhs | T | LHS 값. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | RHS 값. |
| s | long long | 함수 구현을 선택하는 서비스 매개변수이며, 매개변수 값은 무시됩니다. |

### 반환값

gtest 스타일의 어설션 결과.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) 함수

같지 않음 비교는 언박싱을 사용하여 [SmartPtr](../../system/smartptr/) 값을 가진 박스 가능한 유형을 비교합니다.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Object](../../system/object/) 타입. |

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | LHS 값. |
| rhs | T | RHS 값. |
| s | long long | 함수 구현을 선택하는 서비스 매개변수이며, 매개변수 값은 무시됩니다. |

### 반환값

gtest 스타일의 어설션 결과.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, std::nullptr_t, long long) 함수

같지 않음 비교는 임의의 타입을 nullptr와 비교합니다.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Object](../../system/object/) 타입. |

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| lhs | T | LHS 값. |
| s | std::nullptr_t | 함수 구현을 선택하는 서비스 매개변수이며, 매개변수 값은 무시됩니다. |

### 반환값

gtest 스타일의 어설션 결과.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, std::nullptr_t, T, long long) 함수

같지 않음 비교는 임의의 타입을 nullptr와 비교합니다.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Object](../../system/object/) 타입. |

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| rhs | std::nullptr_t | RHS 값. |
| s | T | 함수 구현을 선택하는 서비스 매개변수이며, 매개변수 값은 무시됩니다. |

### 반환값

gtest 스타일의 어설션 결과.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) 함수

동일 비교는 포인터 타입을 비교합니다.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | LHS 타입. |
| T2 | RHS 타입. |

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| lhs | const T1\& | LHS 값. |
| rhs | const T2\& | RHS 값. |
| s | long long | 함수 구현을 선택하는 서비스 매개변수이며, 매개변수 값은 무시됩니다. |

### 반환값

gtest 스타일의 어설션 결과.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T1, T2, int) 함수

동일 비교는 gtest 알고리즘을 사용하여 임의의 타입을 비교합니다.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | LHS 타입. |
| T2 | RHS 타입. |

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| lhs | T1 | LHS 값. |
| rhs | T2 | RHS 값. |

### 반환값

gtest 스타일의 어설션 결과.

## 참조

* 타입 정의 [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* 타입 정의 [SharedPtr](../../system/sharedptr/)
* 클래스 [String](../../system/string/)
* 클래스 [Object](../../system/object/)
* 구조체 [IsSmartPtr](../../system/issmartptr/)
* 구조체 [IsBoxable](../../system/isboxable/)
* 네임스페이스 [System::TestPredicates](../)
* 라이브러리 [Aspose.Slides](../../)
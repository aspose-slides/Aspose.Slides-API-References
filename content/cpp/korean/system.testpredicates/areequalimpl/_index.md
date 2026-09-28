---
title: AreEqualImpl()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 부동소수점과 산술 타입을 동등 비교합니다.
type: docs
weight: 27
url: /ko/system.testpredicates/areequalimpl/
---
## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1, const T2, long long) 함수

부동소수점과 산술 타입을 동등 비교합니다.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AreFPandArithmetic<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 lhs, const T2 rhs, long long s)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T1 | LHS 객체 유형. |
| T2 | RHS 객체 유형. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| lhs | const T1 | LHS 값. |
| rhs | const T2 | RHS 값. |
| s | long long | 함수 구현을 선택하는 서비스 매개변수; 매개변수의 값은 무시됩니다. |

### 반환 값

gtest 스타일의 단언 결과.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) 함수

[Decimal](../../system/decimal/)인 하나 혹은 두 값의 동등성을 비교합니다.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T1 | LHS 객체 유형. |
| T2 | RHS 객체 유형. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| lhs | const T1\& | LHS 값. |
| rhs | const T2\& | RHS 값. |
| s | long long | 함수 구현을 선택하는 서비스 매개변수; 매개변수의 값은 무시됩니다. |

### 반환 값

gtest 스타일의 단언 결과.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) 함수

제공된 Equals 메서드를 사용하여 포인터가 아닌 타입을 동등 비교합니다.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) 타입. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| lhs | const T\& | LHS 값. |
| rhs | const T\& | RHS 값. |
| s | long long | 함수 구현을 선택하는 서비스 매개변수; 매개변수의 값은 무시됩니다. |

### 반환 값

gtest 스타일의 단언 결과.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T\&, const T\&, long long) 함수

제공된 Equals 메서드를 사용하여 포인터가 아닌 타입을 동등 비교합니다.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) 타입. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| lhs | T\& | LHS 값. |
| rhs | const T\& | RHS 값. |
| s | long long | 함수 구현을 선택하는 서비스 매개변수; 매개변수의 값은 무시됩니다. |

### 반환 값

gtest 스타일의 단언 결과.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) 함수

제공된 operator == 를 사용하여 포인터가 아닌 타입을 동등 비교합니다.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) 타입. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| lhs | const T\& | LHS 값. |
| rhs | const T\& | RHS 값. |
| s | long long | 함수 구현을 선택하는 서비스 매개변수; 매개변수의 값은 무시됩니다. |

### 반환 값

gtest 스타일의 단언 결과.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) 함수

boxable을 [SmartPtr](../../system/smartptr/) 값과 동등 비교합니다.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) 타입. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| lhs | T | LHS 값. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | RHS 값. |
| s | long long | 함수 구현을 선택하는 서비스 매개변수; 매개변수의 값은 무시됩니다. |

### 반환 값

gtest 스타일의 단언 결과.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) 함수

boxable을 [SmartPtr](../../system/smartptr/) 값과 동등 비교합니다.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) 타입. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | LHS 값. |
| rhs | T | RHS 값. |
| s | long long | 함수 구현을 선택하는 서비스 매개변수; 매개변수의 값은 무시됩니다. |

### 반환 값

gtest 스타일의 단언 결과.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const char16_t *, const System::SharedPtr\<Object\>\&, long long) 함수

언박싱을 사용하여 문자열 리터럴을 [SmartPtr](../../system/smartptr/) 값과 동등 비교합니다.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const char16_t *lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| lhs | const char16_t * | LHS 값. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | RHS 값. |
| s | long long | 함수 구현을 선택하는 서비스 매개변수; 매개변수의 값은 무시됩니다. |

### 반환 값

gtest 스타일의 단언 결과.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, const char16_t *, long long) 함수

언박싱을 사용하여 문자열 리터럴을 [SmartPtr](../../system/smartptr/) 값과 동등 비교합니다.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, const char16_t *rhs, long long s)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | LHS 값. |
| rhs | const char16_t * | RHS 값. |
| s | long long | 함수 구현을 선택하는 서비스 매개변수; 매개변수의 값은 무시됩니다. |

### 반환 값

gtest 스타일의 단언 결과.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, std::nullptr_t, long long) 함수

무작위 타입을 nullptr와 동등 비교합니다.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) 타입. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| lhs | T | LHS 값. |
| s | std::nullptr_t | 함수 구현을 선택하는 서비스 매개변수; 매개변수의 값은 무시됩니다. |

### 반환 값

gtest 스타일의 단언 결과.

## System::TestPredicates::AreEqualImpl(const char *, const char *, std::nullptr_t, T, long long) 함수

무작위 타입을 nullptr와 동등 비교합니다.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) 타입. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| rhs | std::nullptr_t | RHS 값. |
| s | T | 함수 구현을 선택하는 서비스 매개변수; 매개변수의 값은 무시됩니다. |

### 반환 값

gtest 스타일의 단언 결과.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) 함수

포인터 타입을 동등 비교합니다.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&(!std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value||!std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T1 | LHS 타입. |
| T2 | RHS 타입. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| lhs | const T1\& | LHS 값. |
| rhs | const T2\& | RHS 값. |
| s | long long | 함수 구현을 선택하는 서비스 매개변수; 매개변수의 값은 무시됩니다. |

### 반환 값

gtest 스타일의 단언 결과.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) 함수

포인터 타입을 동등 비교합니다.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value &&std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T1 | LHS 타입. |
| T2 | RHS 타입. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| lhs | const T1\& | LHS 값. |
| rhs | const T2\& | RHS 값. |
| s | long long | 함수 구현을 선택하는 서비스 매개변수; 매개변수의 값은 무시됩니다. |

### 반환 값

gtest 스타일의 단언 결과.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, const Nullable\<T2\>\&, long long) 함수

무작위 타입을 [Nullable](../../system/nullable/) 값과 동등 비교합니다.

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T1>::value &&!IsNullable<T1>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, const Nullable<T2> &rhs, long long s)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T1 | LHS 타입. |
| T2 | RHS 타입. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| lhs | T1 | LHS 값. |
| rhs | const [Nullable](../../system/nullable/)\<T2\>\& | RHS 값. |
| s | long long | 함수 구현을 선택하는 서비스 매개변수; 매개변수의 값은 무시됩니다. |

### 반환 값

gtest 스타일의 단언 결과.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const Nullable\<T1\>\&, T2, long long) 함수

[Nullable](../../system/nullable/) 값을 무작위 타입과 동등 비교합니다.

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T2>::value &&!IsNullable<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const Nullable<T1> &lhs, T2 rhs, long long s)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T1 | LHS 타입. |
| T2 | RHS 타입. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| lhs | const [Nullable](../../system/nullable/)\<T1\>\& | LHS 값. |
| rhs | T2 | RHS 값. |
| s | long long | 함수 구현을 선택하는 서비스 매개변수; 매개변수의 값은 무시됩니다. |

### 반환 값

gtest 스타일의 단언 결과.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, T2, int) 함수

gtest 알고리즘을 사용하여 무작위 타입을 동등 비교합니다.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T1 | LHS 타입. |
| T2 | RHS 타입. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| lhs | T1 | LHS 값. |
| rhs | T2 | RHS 값. |

### 반환 값

gtest 스타일의 단언 결과.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) 함수

두 [System::String](../../system/string/) 값을 동등 비교하며, null [String](../../system/string/) 에서 멤버 함수를 호출하는 것을 방지합니다. const [String](../../system/string/)& 를 받는 일반 오버로드가 아니라 템플릿화되어 혼합 타입 호출—예: char16_t 문자열 리터럴과 [String](../../system/string/) 를 비교하는 경우—단일 일관된 T 를 유추하지 못하고 이 후보에서 완전히 제외되며, 대신 long long/int 선택자 매개변수를 통한 AreEqualImpl<T1,T2> 템플릿과 경쟁하여 모호한 오버로드 해석을 발생시키는 것을 방지합니다.

```cpp
template<typename T> std::enable_if<std::is_same<T, System::String>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) 타입, [System::String](../../system/string/) 로 제한됨. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| lhs | const T\& | LHS 값. |
| rhs | const T\& | RHS 값. |
| s | long long | 함수 구현을 선택하는 서비스 매개변수; 매개변수의 값은 무시됩니다. |

### 반환 값

gtest 스타일의 단언 결과.

## 참고

* Typedef [AreFPandArithmetic](../../system.testpredicates.typetraits/arefpandarithmetic/)
* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [String](../../system/string/)
* Class [Object](../../system/object/)
* Class [Stream](../../system.io/stream/)
* Class [Nullable](../../system/nullable/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsBoxable](../../system/isboxable/)
* Struct [IsStringByteSequence](../../system/isstringbytesequence/)
* Struct [IsNullable](../../system/isnullable/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)
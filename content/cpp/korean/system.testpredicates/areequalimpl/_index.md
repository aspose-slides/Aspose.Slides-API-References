---
title: AreEqualImpl()
second_title: Aspose.Slides for C++ API 참조
description: 부동 소수점과 산술형을 동등 비교합니다.
type: docs
weight: 27
url: /ko/system.testpredicates/areequalimpl/
---
## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1, const T2, long long) 함수

부동 소수점과 산술형을 동등 비교합니다.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AreFPandArithmetic<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 lhs, const T2 rhs, long long s)
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
| lhs | const T1 | LHS 값. |
| rhs | const T2 | RHS 값. |
| s | long long | 구현 선택자를 지정하는 서비스 매개변수; 매개변수 값은 무시됩니다. |

### 반환 값

gtest 스타일의 어서션 결과.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) 함수

값이 하나 또는 둘 다 [Decimal](../../system/decimal/)인 경우 동등 비교합니다.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
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
| s | long long | 구현 선택자를 지정하는 서비스 매개변수; 매개변수 값은 무시됩니다. |

### 반환 값

gtest 스타일의 어서션 결과.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) 함수

제공된 Equals 메서드를 사용하여 비포인터 타입을 동등 비교합니다.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Object](../../system/object/) 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 표현식. |
| rhs_expr | const char * | RHS 표현식. |
| lhs | const T\& | LHS 값. |
| rhs | const T\& | RHS 값. |
| s | long long | 구현 선택자를 지정하는 서비스 매개변수; 매개변수 값은 무시됩니다. |

### 반환 값

gtest 스타일의 어서션 결과.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T\&, const T\&, long long) 함수

제공된 Equals 메서드를 사용하여 비포인터 타입을 동등 비교합니다.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Object](../../system/object/) 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 표현식. |
| rhs_expr | const char * | RHS 표현식. |
| lhs | T\& | LHS 값. |
| rhs | const T\& | RHS 값. |
| s | long long | 구현 선택자를 지정하는 서비스 매개변수; 매개변수 값은 무시됩니다. |

### 반환 값

gtest 스타일의 어서션 결과.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) 함수

제공된 operator == 를 사용하여 비포인터 타입을 동등 비교합니다.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Object](../../system/object/) 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 표현식. |
| rhs_expr | const char * | RHS 표현식. |
| lhs | const T\& | LHS 값. |
| rhs | const T\& | RHS 값. |
| s | long long | 구현 선택자를 지정하는 서비스 매개변수; 매개변수 값은 무시됩니다. |

### 반환 값

gtest 스타일의 어서션 결과.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) 함수

[SmartPtr](../../system/smartptr/) 값을 포함하는 박스 가능한 타입을 동등 비교합니다.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Object](../../system/object/) 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 표현식. |
| rhs_expr | const char * | RHS 표현식. |
| lhs | T | LHS 값. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | RHS 값. |
| s | long long | 구현 선택자를 지정하는 서비스 매개변수; 매개변수 값은 무시됩니다. |

### 반환 값

gtest 스타일의 어서션 결과.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) 함수

[SmartPtr](../../system/smartptr/) 값을 포함하는 박스 가능한 타입을 동등 비교합니다.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Object](../../system/object/) 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 표현식. |
| rhs_expr | const char * | RHS 표현식. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | LHS 값. |
| rhs | T | RHS 값. |
| s | long long | 구현 선택자를 지정하는 서비스 매개변수; 매개변수 값은 무시됩니다. |

### 반환 값

gtest 스타일의 어서션 결과.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const char16_t *, const System::SharedPtr\<Object\>\&, long long) 함수

언박싱을 통해 [SmartPtr](../../system/smartptr/) 값을 포함하는 문자열 리터럴을 동등 비교합니다.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const char16_t *lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 표현식. |
| rhs_expr | const char * | RHS 표현식. |
| lhs | const char16_t * | LHS 값. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | RHS 값. |
| s | long long | 구현 선택자를 지정하는 서비스 매개변수; 매개변수 값은 무시됩니다. |

### 반환 값

gtest 스타일의 어서션 결과.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, const char16_t *, long long) 함수

언박싱을 통해 [SmartPtr](../../system/smartptr/) 값을 포함하는 문자열 리터럴을 동등 비교합니다.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, const char16_t *rhs, long long s)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 표현식. |
| rhs_expr | const char * | RHS 표현식. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | LHS 값. |
| rhs | const char16_t * | RHS 값. |
| s | long long | 구현 선택자를 지정하는 서비스 매개변수; 매개변수 값은 무시됩니다. |

### 반환 값

gtest 스타일의 어서션 결과.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, std::nullptr_t, long long) 함수

nullptr와 함께 임의 타입을 동등 비교합니다.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Object](../../system/object/) 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 표현식. |
| rhs_expr | const char * | RHS 표현식. |
| lhs | T | LHS 값. |
| s | std::nullptr_t | 구현 선택자를 지정하는 서비스 매개변수; 매개변수 값은 무시됩니다. |

### 반환 값

gtest 스타일의 어서션 결과.

## System::TestPredicates::AreEqualImpl(const char *, const char *, std::nullptr_t, T, long long) 함수

nullptr와 함께 임의 타입을 동등 비교합니다.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Object](../../system/object/) 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 표현식. |
| rhs_expr | const char * | RHS 표현식. |
| rhs | std::nullptr_t | RHS 값. |
| s | T | 구현 선택자를 지정하는 서비스 매개변수; 매개변수 값은 무시됩니다. |

### 반환 값

gtest 스타일의 어서션 결과.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) 함수

포인터 타입을 동등 비교합니다.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&(!std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value||!std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | LHS 유형. |
| T2 | RHS 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 표현식. |
| rhs_expr | const char * | RHS 표현식. |
| lhs | const T1\& | LHS 값. |
| rhs | const T2\& | RHS 값. |
| s | long long | 구현 선택자를 지정하는 서비스 매개변수; 매개변수 값은 무시됩니다. |

### 반환 값

gtest 스타일의 어서션 결과.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) 함수

포인터 타입을 동등 비교합니다.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value &&std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | LHS 유형. |
| T2 | RHS 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 표현식. |
| rhs_expr | const char * | RHS 표현식. |
| lhs | const T1\& | LHS 값. |
| rhs | const T2\& | RHS 값. |
| s | long long | 구현 선택자를 지정하는 서비스 매개변수; 매개변수 값은 무시됩니다. |

### 반환 값

gtest 스타일의 어서션 결과.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, const Nullable\<T2\>\&, long long) 함수

[Nullable](../../system/nullable/) 값을 포함하는 임의 타입을 동등 비교합니다.

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T1>::value &&!IsNullable<T1>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, const Nullable<T2> &rhs, long long s)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | LHS 유형. |
| T2 | RHS 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 표현식. |
| rhs_expr | const char * | RHS 표현식. |
| lhs | T1 | LHS 값. |
| rhs | const [Nullable](../../system/nullable/)\<T2\>\& | RHS 값. |
| s | long long | 구현 선택자를 지정하는 서비스 매개변수; 매개변수 값은 무시됩니다. |

### 반환 값

gtest 스타일의 어서션 결과.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const Nullable\<T1\>\&, T2, long long) 함수

임의 타입을 포함하는 [Nullable](../../system/nullable/) 값을 동등 비교합니다.

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T2>::value &&!IsNullable<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const Nullable<T1> &lhs, T2 rhs, long long s)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | LHS 유형. |
| T2 | RHS 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 표현식. |
| rhs_expr | const char * | RHS 표현식. |
| lhs | const [Nullable](../../system/nullable/)\<T1\>\& | LHS 값. |
| rhs | T2 | RHS 값. |
| s | long long | 구현 선택자를 지정하는 서비스 매개변수; 매개변수 값은 무시됩니다. |

### 반환 값

gtest 스타일의 어서션 결과.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, T2, int) 함수

gtest 알고리즘을 사용하여 임의 타입을 동등 비교합니다.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | LHS 유형. |
| T2 | RHS 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 표현식. |
| rhs_expr | const char * | RHS 표현식. |
| lhs | T1 | LHS 값. |
| rhs | T2 | RHS 값. |

### 반환 값

gtest 스타일의 어서션 결과.

## 참고

* Typedef [AreFPandArithmetic](../../system.testpredicates.typetraits/arefpandarithmetic/)
* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Object](../../system/object/)
* Class [Stream](../../system.io/stream/)
* Class [Nullable](../../system/nullable/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsBoxable](../../system/isboxable/)
* Struct [IsStringByteSequence](../../system/isstringbytesequence/)
* Struct [IsNullable](../../system/isnullable/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)
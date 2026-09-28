---
title: AreNotEqualImpl()
second_title: Aspose.Slides för C++ API-referens
description: Inte lika jämför värden där en eller båda är Decimal.
type: docs
weight: 53
url: /sv/system.testpredicates/arenotequalimpl/
---
## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) funktion

Inte lika jämför värden där ett eller båda är [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Mallparametrar

| Parameter | Description |
| --- | --- |
| T1 | LHS object type. |
| T2 | RHS object type. |

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1\& | LHS value. |
| rhs | const T2\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Returvärde

gtest-stylat påståenderesultat.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) funktion

Inte lika jämför två [System::String](../../system/string/)-värden och skyddar mot att anropa en medlemsfunktion på en null [String](../../system/string/). Mallad för samma deduktions-baserade uteslutningsorsaker som AreEqualImpl [String](../../system/string/)-överlagring ovan.

```cpp
template<typename T> std::enable_if<std::is_same<T, System::String>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Mallparametrar

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) type, constrained to [System::String](../../system/string/). |

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T\& | LHS value. |
| rhs | const T\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Returvärde

gtest-stylat påståenderesultat.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) funktion

Inte lika jämför icke-pekartyper med den medföljande Equals-metoden.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Mallparametrar

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T\& | LHS value. |
| rhs | const T\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Returvärde

gtest-stylat påståenderesultat.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T\&, const T\&, long long) funktion

Inte lika jämför icke-pekartyper med den medföljande Equals-metoden.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### Mallparametrar

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T\& | LHS value. |
| rhs | const T\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Returvärde

gtest-stylat påståenderesultat.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) funktion

Inte lika jämför icke-pekartyper med operatorn != som tillhandahålls.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Mallparametrar

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T\& | LHS value. |
| rhs | const T\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Returvärde

gtest-stylat påståenderesultat.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) funktion

Inte lika jämför boxbara med [SmartPtr](../../system/smartptr/)-värden genom unboxing.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### Mallparametrar

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T | LHS value. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Returvärde

gtest-stylat påståenderesultat.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) funktion

Inte lika jämför boxbara med [SmartPtr](../../system/smartptr/)-värden genom unboxing.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### Mallparametrar

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | LHS value. |
| rhs | T | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Returvärde

gtest-stylat påståenderesultat.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, std::nullptr_t, long long) funktion

Inte lika jämför slumpmässig typ med nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### Mallparametrar

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T | LHS value. |
| s | std::nullptr_t | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Returvärde

gtest-stylat påståenderesultat.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, std::nullptr_t, T, long long) funktion

Inte lika jämför slumpmässig typ med nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### Mallparametrar

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| rhs | std::nullptr_t | RHS value. |
| s | T | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Returvärde

gtest-stylat påståenderesultat.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) funktion

Equal-jämför pekartyper.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Mallparametrar

| Parameter | Description |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1\& | LHS value. |
| rhs | const T2\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Returvärde

gtest-stylat påståenderesultat.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T1, T2, int) funktion

Equal-jämför slumpmässiga typer med gtest-algoritmer.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### Mallparametrar

| Parameter | Description |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T1 | LHS value. |
| rhs | T2 | RHS value. |

### Returvärde

gtest-stylat påståenderesultat.

## Se även

* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Klass [String](../../system/string/)
* Klass [Object](../../system/object/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsBoxable](../../system/isboxable/)
* Namnrymd [System::TestPredicates](../)
* Library [Aspose.Slides](../../)
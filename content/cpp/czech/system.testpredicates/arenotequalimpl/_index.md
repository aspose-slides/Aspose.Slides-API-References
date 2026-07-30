---
title: AreNotEqualImpl()
second_title: Aspose.Slides pro C++ API Reference
description: Porovnává nerovnost hodnot, přičemž jedna nebo obě jsou typu Decimal.
type: docs
weight: 53
url: /cs/system.testpredicates/arenotequalimpl/
---
## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) funkce


Porovnání nerovnosti hodnot, přičemž jedna nebo obě jsou [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | LHS object type. |
| T2 | RHS object type. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1\& | LHS value. |
| rhs | const T2\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Návratová hodnota

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) funkce


Porovnání nerovnosti neukazatelových typů pomocí poskytované metody Equals.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T\& | LHS value. |
| rhs | const T\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Návratová hodnota

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T\&, const T\&, long long) funkce


Porovnání nerovnosti neukazatelových typů pomocí poskytované metody Equals.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T\& | LHS value. |
| rhs | const T\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Návratová hodnota

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) funkce


Porovnání nerovnosti neukazatelových typů pomocí operátoru != poskytovaného.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T\& | LHS value. |
| rhs | const T\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Návratová hodnota

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) funkce


Porovnání nerovnosti boxovatelných s hodnotami [SmartPtr](../../system/smartptr/) pomocí rozbalení.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T | LHS value. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Návratová hodnota

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) funkce


Porovnání nerovnosti boxovatelných s hodnotami [SmartPtr](../../system/smartptr/) pomocí rozbalení.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | LHS value. |
| rhs | T | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Návratová hodnota

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, std::nullptr_t, long long) funkce


Porovnání nerovnosti náhodného typu s nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T | LHS value. |
| s | std::nullptr_t | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Návratová hodnota

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, std::nullptr_t, T, long long) funkce


Porovnání nerovnosti náhodného typu s nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| rhs | std::nullptr_t | RHS value. |
| s | T | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Návratová hodnota

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) funkce


Porovnání rovnosti ukazatelových typů.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1\& | LHS value. |
| rhs | const T2\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Návratová hodnota

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T1, T2, int) funkce


Porovnání rovnosti náhodných typů pomocí algoritmů gtest.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T1 | LHS value. |
| rhs | T2 | RHS value. |

### Návratová hodnota

gtest-styled assertion result.

## Viz také

* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Object](../../system/object/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsBoxable](../../system/isboxable/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)
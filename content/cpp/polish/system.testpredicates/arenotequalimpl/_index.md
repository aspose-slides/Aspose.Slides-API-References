---
title: AreNotEqualImpl()
second_title: Aspose.Slides dla C++ API Reference
description: Porównuje nierówność wartości, przy czym jedna lub obie są typu Decimal.
type: docs
weight: 53
url: /pl/system.testpredicates/arenotequalimpl/
---
## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) funkcja


Porównuje nierówność wartości, z których jedna lub obie są [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T1 | Typ obiektu LHS. |
| T2 | Typ obiektu RHS. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Wyrażenie LHS. |
| rhs_expr | const char * | Wyrażenie RHS. |
| lhs | const T1\& | Wartość LHS. |
| rhs | const T2\& | Wartość RHS. |
| s | long long | Parametr serwisowy służący jako selektor implementacji funkcji; wartość tego parametru jest ignorowana |

### Wartość zwracana

wynik asercji w stylu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) funkcja


Porównuje nierówność typów nie-wskaźnikowych przy użyciu dostarczonej metody Equals.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Wyrażenie LHS. |
| rhs_expr | const char * | Wyrażenie RHS. |
| lhs | const T\& | Wartość LHS. |
| rhs | const T\& | Wartość RHS. |
| s | long long | Parametr serwisowy służący jako selektor implementacji funkcji; wartość tego parametru jest ignorowana |

### Wartość zwracana

wynik asercji w stylu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T\&, const T\&, long long) funkcja


Porównuje nierówność typów nie-wskaźnikowych przy użyciu dostarczonej metody Equals.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Wyrażenie LHS. |
| rhs_expr | const char * | Wyrażenie RHS. |
| lhs | T\& | Wartość LHS. |
| rhs | const T\& | Wartość RHS. |
| s | long long | Parametr serwisowy służący jako selektor implementacji funkcji; wartość tego parametru jest ignorowana |

### Wartość zwracana

wynik asercji w stylu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) funkcja


Porównuje nierówność typów nie-wskaźnikowych przy użyciu operatora !=.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Wyrażenie LHS. |
| rhs_expr | const char * | Wyrażenie RHS. |
| lhs | const T\& | Wartość LHS. |
| rhs | const T\& | Wartość RHS. |
| s | long long | Parametr serwisowy służący jako selektor implementacji funkcji; wartość tego parametru jest ignorowana |

### Wartość zwracana

wynik asercji w stylu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) funkcja


Porównuje nierówność typów możliwych do spakowania z [SmartPtr](../../system/smartptr/) wartościami przy użyciu rozpakowywania.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Wyrażenie LHS. |
| rhs_expr | const char * | Wyrażenie RHS. |
| lhs | T | Wartość LHS. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Wartość RHS. |
| s | long long | Parametr serwisowy służący jako selektor implementacji funkcji; wartość tego parametru jest ignorowana |

### Wartość zwracana

wynik asercji w stylu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) funkcja


Porównuje nierówność typów możliwych do spakowania z [SmartPtr](../../system/smartptr/) wartościami przy użyciu rozpakowywania.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Wyrażenie LHS. |
| rhs_expr | const char * | Wyrażenie RHS. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Wartość LHS. |
| rhs | T | Wartość RHS. |
| s | long long | Parametr serwisowy służący jako selektor implementacji funkcji; wartość tego parametru jest ignorowana |

### Wartość zwracana

wynik asercji w stylu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, std::nullptr_t, long long) funkcja


Porównuje nierówność losowego typu z nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Wyrażenie LHS. |
| rhs_expr | const char * | Wyrażenie RHS. |
| lhs | T | Wartość LHS. |
| s | std::nullptr_t | Parametr serwisowy służący jako selektor implementacji funkcji; wartość tego parametru jest ignorowana |

### Wartość zwracana

wynik asercji w stylu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, std::nullptr_t, T, long long) funkcja


Porównuje nierówność losowego typu z nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Wyrażenie LHS. |
| rhs_expr | const char * | Wyrażenie RHS. |
| rhs | std::nullptr_t | Wartość RHS. |
| s | T | Parametr serwisowy służący jako selektor implementacji funkcji; wartość tego parametru jest ignorowana |

### Wartość zwracana

wynik asercji w stylu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) funkcja


Porównuje równość typów wskaźnikowych.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T1 | Typ LHS. |
| T2 | Typ RHS. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Wyrażenie LHS. |
| rhs_expr | const char * | Wyrażenie RHS. |
| lhs | const T1\& | Wartość LHS. |
| rhs | const T2\& | Wartość RHS. |
| s | long long | Parametr serwisowy służący jako selektor implementacji funkcji; wartość tego parametru jest ignorowana |

### Wartość zwracana

wynik asercji w stylu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T1, T2, int) funkcja


Porównuje równość losowych typów przy użyciu algorytmów gtest.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T1 | Typ LHS. |
| T2 | Typ RHS. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Wyrażenie LHS. |
| rhs_expr | const char * | Wyrażenie RHS. |
| lhs | T1 | Wartość LHS. |
| rhs | T2 | Wartość RHS. |

### Wartość zwracana

wynik asercji w stylu gtest.

## Zobacz także

* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Object](../../system/object/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsBoxable](../../system/isboxable/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)
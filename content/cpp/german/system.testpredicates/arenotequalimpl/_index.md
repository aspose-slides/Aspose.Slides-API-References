---
title: AreNotEqualImpl()
second_title: Aspose.Slides für C++ API Referenz
description: Nicht-gleich vergleicht Werte, von denen einer oder beide Dezimal sind.
type: docs
weight: 53
url: /de/system.testpredicates/arenotequalimpl/
---
## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) Funktion

Nicht-gleich vergleicht Werte, von denen einer oder beide [Decimal](../../system/decimal/) sind.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | LHS object type. |
| T2 | RHS object type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1\& | LHS value. |
| rhs | const T2\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Rückgabewert

gtest-stilisiertes Assertion-Ergebnis.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) Funktion

Nicht-gleich vergleicht Nicht-Pointer-Typen mit der bereitgestellten Equals-Methode.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T\& | LHS value. |
| rhs | const T\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Rückgabewert

gtest-stilisiertes Assertion-Ergebnis.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T\&, const T\&, long long) Funktion

Nicht-gleich vergleicht Nicht-Pointer-Typen mit der bereitgestellten Equals-Methode.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T\& | LHS value. |
| rhs | const T\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Rückgabewert

gtest-stilisiertes Assertion-Ergebnis.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) Funktion

Nicht-gleich vergleicht Nicht-Pointer-Typen mit dem bereitgestellten Operator !=.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T\& | LHS value. |
| rhs | const T\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Rückgabewert

gtest-stilisiertes Assertion-Ergebnis.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) Funktion

Nicht-gleich vergleicht Boxable mit [SmartPtr](../../system/smartptr/)-Werten durch Unboxing.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T | LHS value. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Rückgabewert

gtest-stilisiertes Assertion-Ergebnis.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) Funktion

Nicht-gleich vergleicht Boxable mit [SmartPtr](../../system/smartptr/)-Werten durch Unboxing.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | LHS value. |
| rhs | T | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Rückgabewert

gtest-stilisiertes Assertion-Ergebnis.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, std::nullptr_t, long long) Funktion

Nicht-gleich vergleicht zufälligen Typ mit nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T | LHS value. |
| s | std::nullptr_t | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Rückgabewert

gtest-stilisiertes Assertion-Ergebnis.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, std::nullptr_t, T, long long) Funktion

Nicht-gleich vergleicht zufälligen Typ mit nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| rhs | std::nullptr_t | RHS value. |
| s | T | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Rückgabewert

gtest-stilisiertes Assertion-Ergebnis.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) Funktion

Gleich-vergleicht Zeigertypen.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1\& | LHS value. |
| rhs | const T2\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Rückgabewert

gtest-stilisiertes Assertion-Ergebnis.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T1, T2, int) Funktion

Gleich-vergleicht zufällige Typen mit gtest-Algorithmen.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T1 | LHS value. |
| rhs | T2 | RHS value. |

### Rückgabewert

gtest-stilisiertes Assertion-Ergebnis.

## Siehe auch

* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Klasse [Object](../../system/object/)
* Struktur [IsSmartPtr](../../system/issmartptr/)
* Struktur [IsBoxable](../../system/isboxable/)
* Namensraum [System::TestPredicates](../)
* Bibliothek [Aspose.Slides](../../)
---
title: AreNotEqualImpl()
second_title: Aspose.Slides für C++ API Referenz
description: Nicht-Gleich-Vergleicht Werte, von denen einer oder beide Dezimal sind.
type: docs
weight: 53
url: /de/system.testpredicates/arenotequalimpl/
---
## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) Funktion

Nicht-Gleich-Vergleiche Werte, wobei einer oder beide [Decimal](../../system/decimal/) sind.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Template-Parameter

| Parameter | Description |
| --- | --- |
| T1 | LHS object type. |
| T2 | RHS object type. |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1\& | LHS value. |
| rhs | const T2\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Rückgabewert

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) Funktion

Nicht-Gleich-Vergleiche zwei [System::String](../../system/string/) Werte und verhindern das Aufrufen einer Mitgliedsfunktion auf einem null [String](../../system/string/). Vorlagenbasiert aus denselben deduktionsbasierten Ausschlussgründen wie die AreEqualImpl [String](../../system/string/) Überladung oben.

```cpp
template<typename T> std::enable_if<std::is_same<T, System::String>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Template-Parameter

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) type, constrained to [System::String](../../system/string/). |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T\& | LHS value. |
| rhs | const T\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Rückgabewert

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) Funktion

Nicht-Gleich-Vergleiche Nicht-Zeiger-Typen mittels bereitgestellter Equals-Methode.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Template-Parameter

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T\& | LHS value. |
| rhs | const T\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Rückgabewert

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T\&, const T\&, long long) Funktion

Nicht-Gleich-Vergleiche Nicht-Zeiger-Typen mittels bereitgestellter Equals-Methode.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### Template-Parameter

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T\& | LHS value. |
| rhs | const T\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Rückgabewert

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) Funktion

Nicht-Gleich-Vergleicht Nicht-Zeiger-Typen mittels bereitgestelltem Operator !=.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Template-Parameter

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T\& | LHS value. |
| rhs | const T\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Rückgabewert

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) Funktion

Nicht-Gleich-Vergleiche boxbare Typen mit [SmartPtr](../../system/smartptr/) Werten mittels Unboxing.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### Template-Parameter

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T | LHS value. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Rückgabewert

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) Funktion

Nicht-Gleich-Vergleiche boxbare Typen mit [SmartPtr](../../system/smartptr/) Werten mittels Unboxing.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### Template-Parameter

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | LHS value. |
| rhs | T | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Rückgabewert

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, std::nullptr_t, long long) Funktion

Nicht-Gleich-Vergleiche beliebigen Typ mit nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### Template-Parameter

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T | LHS value. |
| s | std::nullptr_t | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Rückgabewert

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, std::nullptr_t, T, long long) Funktion

Nicht-Gleich-Vergleiche beliebigen Typ mit nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### Template-Parameter

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| rhs | std::nullptr_t | RHS value. |
| s | T | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Rückgabewert

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) Funktion

Gleich-Vergleicht Zeigertypen.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Template-Parameter

| Parameter | Description |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1\& | LHS value. |
| rhs | const T2\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Rückgabewert

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T1, T2, int) Funktion

Gleich-Vergleicht beliebige Typen mittels gtest-Algorithmen.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### Template-Parameter

| Parameter | Description |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T1 | LHS value. |
| rhs | T2 | RHS value. |

### Rückgabewert

gtest-styled assertion result.

## Siehe auch

* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Klasse [String](../../system/string/)
* Klasse [Object](../../system/object/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsBoxable](../../system/isboxable/)
* Namensraum [System::TestPredicates](../)
* Library [Aspose.Slides](../../)
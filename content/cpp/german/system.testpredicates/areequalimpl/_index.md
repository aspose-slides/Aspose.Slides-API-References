---
title: AreEqualImpl()
second_title: Aspose.Slides für C++ API Referenz
description: Vergleicht Gleitkommawerte mit arithmetischen Typen.
type: docs
weight: 27
url: /de/system.testpredicates/areequalimpl/
---
## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1, const T2, long long) Funktion

Vergleicht Gleitkommazahlen mit arithmetischen Typen.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AreFPandArithmetic<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 lhs, const T2 rhs, long long s)
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
| lhs | const T1 | LHS value. |
| rhs | const T2 | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Rückgabewert

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) Funktion

Vergleicht Werte, von denen einer oder beide [Decimal](../../system/decimal/) sind.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
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

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) Funktion

Vergleicht Nicht-Zeiger-Typen mit der bereitgestellten Equals-Methode.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
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

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T\&, const T\&, long long) Funktion

Vergleicht Nicht-Zeiger-Typen mit der bereitgestellten Equals-Methode.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
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

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) Funktion

Vergleicht Nicht-Zeiger-Typen mit dem bereitgestellten Operator ==.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
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

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) Funktion

Vergleicht Boxable mit [SmartPtr](../../system/smartptr/)-Werten.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
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

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) Funktion

Vergleicht Boxable mit [SmartPtr](../../system/smartptr/)-Werten.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
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

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const char16_t *, const System::SharedPtr\<Object\>\&, long long) Funktion

Vergleicht Zeichenketten-Literal mit [SmartPtr](../../system/smartptr/)-Werten mittels Unboxing.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const char16_t *lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const char16_t * | LHS value. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Rückgabewert

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, const char16_t *, long long) Funktion

Vergleicht Zeichenketten-Literal mit [SmartPtr](../../system/smartptr/)-Werten mittels Unboxing.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, const char16_t *rhs, long long s)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | LHS value. |
| rhs | const char16_t * | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Rückgabewert

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, std::nullptr_t, long long) Funktion

Vergleicht einen zufälligen Typ mit nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
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

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, std::nullptr_t, T, long long) Funktion

Vergleicht einen zufälligen Typ mit nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
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

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) Funktion

Vergleicht Zeiger-Typen.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&(!std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value||!std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
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

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) Funktion

Vergleicht Zeiger-Typen.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value &&std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
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

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, const Nullable\<T2\>\&, long long) Funktion

Vergleicht einen zufälligen Typ mit einem [Nullable](../../system/nullable/)-Wert.

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T1>::value &&!IsNullable<T1>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, const Nullable<T2> &rhs, long long s)
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
| rhs | const [Nullable](../../system/nullable/)\<T2\>\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Rückgabewert

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const Nullable\<T1\>\&, T2, long long) Funktion

Vergleicht einen [Nullable](../../system/nullable/)-Wert mit einem zufälligen Typ.

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T2>::value &&!IsNullable<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const Nullable<T1> &lhs, T2 rhs, long long s)
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
| lhs | const [Nullable](../../system/nullable/)\<T1\>\& | LHS value. |
| rhs | T2 | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Rückgabewert

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, T2, int) Funktion

Vergleicht zufällige Typen mit gtest-Algorithmen.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
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

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) Funktion

Vergleicht zwei [System::String](../../system/string/)-Werte und schützt davor, eine Member-Funktion auf einem null [String](../../system/string/) aufzurufen. Templatisiert (statt einer einfachen Überladung, die const [String](../../system/string/)& nimmt), damit Aufrufe mit gemischten Typen – z. B. ein char16_t-String-Literal im Vergleich zu einem [String](../../system/string/) – keinen einzigen konsistenten T ableiten können und deshalb vollständig von diesem Kandidaten ausgeschlossen werden, anstatt mit der Catch-All-Vorlage AreEqualImpl<T1,T2> über den long long/int-Selektor-Parameter zu konkurrieren und eine mehrdeutige Überladungsauflösung zu erzeugen.

```cpp
template<typename T> std::enable_if<std::is_same<T, System::String>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | [Object](../../system/object/) type, constrained to [System::String](../../system/string/). |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T\& | LHS value. |
| rhs | const T\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Rückgabewert

gtest-styled assertion result.

## Siehe auch

* Typedef [AreFPandArithmetic](../../system.testpredicates.typetraits/arefpandarithmetic/)
* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Klasse [String](../../system/string/)
* Klasse [Object](../../system/object/)
* Klasse [Stream](../../system.io/stream/)
* Klasse [Nullable](../../system/nullable/)
* Struktur [IsSmartPtr](../../system/issmartptr/)
* Struktur [IsBoxable](../../system/isboxable/)
* Struktur [IsStringByteSequence](../../system/isstringbytesequence/)
* Struktur [IsNullable](../../system/isnullable/)
* Namensraum [System::TestPredicates](../)
* Bibliothek [Aspose.Slides](../../)
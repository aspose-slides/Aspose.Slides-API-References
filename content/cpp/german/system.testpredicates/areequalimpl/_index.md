---
title: AreEqualImpl()
second_title: Aspose.Slides für C++ API Referenz
description: Vergleicht Gleitkommazahlen mit arithmetischen Typen auf Gleichheit.
type: docs
weight: 27
url: /de/system.testpredicates/areequalimpl/
---
## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1, const T2, long long) Funktion

Vergleicht Gleitkommazahlen mit arithmetischen Typen auf Gleichheit.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AreFPandArithmetic<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 lhs, const T2 rhs, long long s)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | LHS-Objekttyp. |
| T2 | RHS-Objekttyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS-Ausdruck. |
| rhs_expr | const char * | RHS-Ausdruck. |
| lhs | const T1 | LHS-Wert. |
| rhs | const T2 | RHS-Wert. |
| s | long long | Ein Dienstparameter, der als Auswahlmerkmal für die Implementierung der Funktion dient; der Wert des Parameters wird ignoriert. |

### Rückgabewert

gtest-stilisiertes Assertion-Ergebnis.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1&, const T2&, long long) Funktion

Vergleicht Werte, von denen einer oder beide [Decimal](../../system/decimal/) sind, auf Gleichheit.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | LHS-Objekttyp. |
| T2 | RHS-Objekttyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS-Ausdruck. |
| rhs_expr | const char * | RHS-Ausdruck. |
| lhs | const T1& | LHS-Wert. |
| rhs | const T2& | RHS-Wert. |
| s | long long | Ein Dienstparameter, der als Auswahlmerkmal für die Implementierung der Funktion dient; der Wert des Parameters wird ignoriert. |

### Rückgabewert

gtest-stilisiertes Assertion-Ergebnis.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T&, const T&, long long) Funktion

Vergleicht Nicht-Zeiger-Typen mithilfe der bereitgestellten Equals-Methode.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | [Object](../../system/object/)-Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS-Ausdruck. |
| rhs_expr | const char * | RHS-Ausdruck. |
| lhs | const T& | LHS-Wert. |
| rhs | const T& | RHS-Wert. |
| s | long long | Ein Dienstparameter, der als Auswahlmerkmal für die Implementierung der Funktion dient; der Wert des Parameters wird ignoriert. |

### Rückgabewert

gtest-stilisiertes Assertion-Ergebnis.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T&, const T&, long long) Funktion

Vergleicht Nicht-Zeiger-Typen mithilfe der bereitgestellten Equals-Methode.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | [Object](../../system/object/)-Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS-Ausdruck. |
| rhs_expr | const char * | RHS-Ausdruck. |
| lhs | T& | LHS-Wert. |
| rhs | const T& | RHS-Wert. |
| s | long long | Ein Dienstparameter, der als Auswahlmerkmal für die Implementierung der Funktion dient; der Wert des Parameters wird ignoriert. |

### Rückgabewert

gtest-stilisiertes Assertion-Ergebnis.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T&, const T&, long long) Funktion

Vergleicht Nicht-Zeiger-Typen mithilfe des bereitgestellten Operators ==.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | [Object](../../system/object/)-Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS-Ausdruck. |
| rhs_expr | const char * | RHS-Ausdruck. |
| lhs | const T& | LHS-Wert. |
| rhs | const T& | RHS-Wert. |
| s | long long | Ein Dienstparameter, der als Auswahlmerkmal für die Implementierung der Funktion dient; der Wert des Parameters wird ignoriert. |

### Rückgabewert

gtest-stilisiertes Assertion-Ergebnis.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>&, long long) Funktion

Vergleicht boxbare Werte mit [SmartPtr](../../system/smartptr/)-Werten.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | [Object](../../system/object/)-Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS-Ausdruck. |
| rhs_expr | const char * | RHS-Ausdruck. |
| lhs | T | LHS-Wert. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>& | RHS-Wert. |
| s | long long | Ein Dienstparameter, der als Auswahlmerkmal für die Implementierung der Funktion dient; der Wert des Parameters wird ignoriert. |

### Rückgabewert

gtest-stilisiertes Assertion-Ergebnis.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>&, T, long long) Funktion

Vergleicht boxbare Werte mit [SmartPtr](../../system/smartptr/)-Werten.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | [Object](../../system/object/)-Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS-Ausdruck. |
| rhs_expr | const char * | RHS-Ausdruck. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>& | LHS-Wert. |
| rhs | T | RHS-Wert. |
| s | long long | Ein Dienstparameter, der als Auswahlmerkmal für die Implementierung der Funktion dient; der Wert des Parameters wird ignoriert. |

### Rückgabewert

gtest-stilisiertes Assertion-Ergebnis.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const char16_t *, const System::SharedPtr\<Object\>&, long long) Funktion

Vergleicht Zeichenketten-Literal mit [SmartPtr](../../system/smartptr/)-Werten mittels Unboxing.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const char16_t *lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS-Ausdruck. |
| rhs_expr | const char * | RHS-Ausdruck. |
| lhs | const char16_t * | LHS-Wert. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>& | RHS-Wert. |
| s | long long | Ein Dienstparameter, der als Auswahlmerkmal für die Implementierung der Funktion dient; der Wert des Parameters wird ignoriert. |

### Rückgabewert

gtest-stilisiertes Assertion-Ergebnis.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>&, const char16_t *, long long) Funktion

Vergleicht Zeichenketten-Literal mit [SmartPtr](../../system/smartptr/)-Werten mittels Unboxing.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, const char16_t *rhs, long long s)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS-Ausdruck. |
| rhs_expr | const char * | RHS-Ausdruck. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>& | LHS-Wert. |
| rhs | const char16_t * | RHS-Wert. |
| s | long long | Ein Dienstparameter, der als Auswahlmerkmal für die Implementierung der Funktion dient; der Wert des Parameters wird ignoriert. |

### Rückgabewert

gtest-stilisiertes Assertion-Ergebnis.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, std::nullptr_t, long long) Funktion

Vergleicht zufälligen Typ mit nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | [Object](../../system/object/)-Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS-Ausdruck. |
| rhs_expr | const char * | RHS-Ausdruck. |
| lhs | T | LHS-Wert. |
| s | std::nullptr_t | Ein Dienstparameter, der als Auswahlmerkmal für die Implementierung der Funktion dient; der Wert des Parameters wird ignoriert. |

### Rückgabewert

gtest-stilisiertes Assertion-Ergebnis.

## System::TestPredicates::AreEqualImpl(const char *, const char *, std::nullptr_t, T, long long) Funktion

Vergleicht zufälligen Typ mit nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | [Object](../../system/object/)-Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS-Ausdruck. |
| rhs_expr | const char * | RHS-Ausdruck. |
| rhs | std::nullptr_t | RHS-Wert. |
| s | T | Ein Dienstparameter, der als Auswahlmerkmal für die Implementierung der Funktion dient; der Wert des Parameters wird ignoriert. |

### Rückgabewert

gtest-stilisiertes Assertion-Ergebnis.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1&, const T2&, long long) Funktion

Vergleicht Zeiger-Typen.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&(!std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value||!std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | LHS-Typ. |
| T2 | RHS-Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS-Ausdruck. |
| rhs_expr | const char * | RHS-Ausdruck. |
| lhs | const T1& | LHS-Wert. |
| rhs | const T2& | RHS-Wert. |
| s | long long | Ein Dienstparameter, der als Auswahlmerkmal für die Implementierung der Funktion dient; der Wert des Parameters wird ignoriert. |

### Rückgabewert

gtest-stilisiertes Assertion-Ergebnis.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1&, const T2&, long long) Funktion

Vergleicht Zeiger-Typen.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value &&std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | LHS-Typ. |
| T2 | RHS-Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS-Ausdruck. |
| rhs_expr | const char * | RHS-Ausdruck. |
| lhs | const T1& | LHS-Wert. |
| rhs | const T2& | RHS-Wert. |
| s | long long | Ein Dienstparameter, der als Auswahlmerkmal für die Implementierung der Funktion dient; der Wert des Parameters wird ignoriert. |

### Rückgabewert

gtest-stilisiertes Assertion-Ergebnis.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, const Nullable<T2>&, long long) Funktion

Vergleicht einen zufälligen Typ mit einem [Nullable](../../system/nullable/)-Wert.

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T1>::value &&!IsNullable<T1>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, const Nullable<T2> &rhs, long long s)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | LHS-Typ. |
| T2 | RHS-Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS-Ausdruck. |
| rhs_expr | const char * | RHS-Ausdruck. |
| lhs | T1 | LHS-Wert. |
| rhs | const [Nullable](../../system/nullable/)\<T2\>& | RHS-Wert. |
| s | long long | Ein Dienstparameter, der als Auswahlmerkmal für die Implementierung der Funktion dient; der Wert des Parameters wird ignoriert. |

### Rückgabewert

gtest-stilisiertes Assertion-Ergebnis.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const Nullable<T1>&, T2, long long) Funktion

Vergleicht einen [Nullable](../../system/nullable/)-Wert mit einem zufälligen Typ.

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T2>::value &&!IsNullable<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const Nullable<T1> &lhs, T2 rhs, long long s)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | LHS-Typ. |
| T2 | RHS-Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS-Ausdruck. |
| rhs_expr | const char * | RHS-Ausdruck. |
| lhs | const [Nullable](../../system/nullable/)\<T1\>& | LHS-Wert. |
| rhs | T2 | RHS-Wert. |
| s | long long | Ein Dienstparameter, der als Auswahlmerkmal für die Implementierung der Funktion dient; der Wert des Parameters wird ignoriert. |

### Rückgabewert

gtest-stilisiertes Assertion-Ergebnis.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, T2, int) Funktion

Vergleicht zufällige Typen mithilfe von gtest-Algorithmen.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | LHS-Typ. |
| T2 | RHS-Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS-Ausdruck. |
| rhs_expr | const char * | RHS-Ausdruck. |
| lhs | T1 | LHS-Wert. |
| rhs | T2 | RHS-Wert. |

### Rückgabewert

gtest-stilisiertes Assertion-Ergebnis.

## Siehe auch

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
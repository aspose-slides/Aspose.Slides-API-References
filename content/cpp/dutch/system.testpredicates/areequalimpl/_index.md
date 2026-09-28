---
title: AreEqualImpl()
second_title: Aspose.Slides voor C++ API-referentie
description: Vergelijkt zwevendekommagetallen met rekenkundige typen op gelijkheid.
type: docs
weight: 27
url: /nl/system.testpredicates/areequalimpl/
---
## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1, const T2, long long) functie

Vergelijkt zwevendekommagetallen met rekenkundige typen op gelijkheid.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AreFPandArithmetic<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 lhs, const T2 rhs, long long s)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | type van LHS-object. |
| T2 | type van RHS-object. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs_expr | const char * | LHS-expressie. |
| rhs_expr | const char * | RHS-expressie. |
| lhs | const T1 | LHS-waarde. |
| rhs | const T2 | RHS-waarde. |
| s | long long | Een serviceparameter die dient als selector van de implementatie van de functie; de waarde van de parameter wordt genegeerd |

### Retourwaarde

gtest-gestyleerd assertieresultaat.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1&, const T2&, long long) functie

Vergelijkt waarden waarvan één of beide [Decimal](../../system/decimal/) zijn.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | type van LHS-object. |
| T2 | type van RHS-object. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs_expr | const char * | LHS-expressie. |
| rhs_expr | const char * | RHS-expressie. |
| lhs | const T1\& | LHS-waarde. |
| rhs | const T2\& | RHS-waarde. |
| s | long long | Een serviceparameter die dient als selector van de implementatie van de functie; de waarde van de parameter wordt genegeerd |

### Retourwaarde

gtest-gestyleerd assertieresultaat.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) functie

Vergelijkt niet-pointer types met behulp van de verstrekte Equals-methode.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs_expr | const char * | LHS-expressie. |
| rhs_expr | const char * | RHS-expressie. |
| lhs | const T\& | LHS-waarde. |
| rhs | const T\& | RHS-waarde. |
| s | long long | Een serviceparameter die dient als selector van de implementatie van de functie; de waarde van de parameter wordt genegeerd |

### Retourwaarde

gtest-gestyleerd assertieresultaat.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T\&, const T\&, long long) functie

Vergelijkt niet-pointer types met behulp van de verstrekte Equals-methode.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs_expr | const char * | LHS-expressie. |
| rhs_expr | const char * | RHS-expressie. |
| lhs | T\& | LHS-waarde. |
| rhs | const T\& | RHS-waarde. |
| s | long long | Een serviceparameter die dient als selector van de implementatie van de functie; de waarde van de parameter wordt genegeerd |

### Retourwaarde

gtest-gestyleerd assertieresultaat.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) functie

Vergelijkt niet-pointer types met behulp van de verstrekte operator ==.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs_expr | const char * | LHS-expressie. |
| rhs_expr | const char * | RHS-expressie. |
| lhs | const T\& | LHS-waarde. |
| rhs | const T\& | RHS-waarde. |
| s | long long | Een serviceparameter die dient als selector van de implementatie van de functie; de waarde van de parameter wordt genegeerd |

### Retourwaarde

gtest-gestyleerd assertieresultaat.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) functie

Vergelijkt boxable met [SmartPtr](../../system/smartptr/)-waarden.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs_expr | const char * | LHS-expressie. |
| rhs_expr | const char * | RHS-expressie. |
| lhs | T | LHS-waarde. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | RHS-waarde. |
| s | long long | Een serviceparameter die dient als selector van de implementatie van de functie; de waarde van de parameter wordt genegeerd |

### Retourwaarde

gtest-gestyleerd assertieresultaat.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) functie

Vergelijkt boxable met [SmartPtr](../../system/smartptr/)-waarden.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs_expr | const char * | LHS-expressie. |
| rhs_expr | const char * | RHS-expressie. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | LHS-waarde. |
| rhs | T | RHS-waarde. |
| s | long long | Een serviceparameter die dient als selector van de implementatie van de functie; de waarde van de parameter wordt genegeerd |

### Retourwaarde

gtest-gestyleerd assertieresultaat.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const char16_t *, const System::SharedPtr\<Object\>\&, long long) functie

Vergelijkt stringliteral met [SmartPtr](../../system/smartptr/)-waarden met behulp van unboxing.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const char16_t *lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs_expr | const char * | LHS-expressie. |
| rhs_expr | const char * | RHS-expressie. |
| lhs | const char16_t * | LHS-waarde. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | RHS-waarde. |
| s | long long | Een serviceparameter die dient als selector van de implementatie van de functie; de waarde van de parameter wordt genegeerd |

### Retourwaarde

gtest-gestyleerd assertieresultaat.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, const char16_t *, long long) functie

Vergelijkt stringliteral met [SmartPtr](../../system/smartptr/)-waarden met behulp van unboxing.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, const char16_t *rhs, long long s)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs_expr | const char * | LHS-expressie. |
| rhs_expr | const char * | RHS-expressie. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | LHS-waarde. |
| rhs | const char16_t * | RHS-waarde. |
| s | long long | Een serviceparameter die dient als selector van de implementatie van de functie; de waarde van de parameter wordt genegeerd |

### Retourwaarde

gtest-gestyleerd assertieresultaat.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, std::nullptr_t, long long) functie

Vergelijkt willekeurig type met nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs_expr | const char * | LHS-expressie. |
| rhs_expr | const char * | RHS-expressie. |
| lhs | T | LHS-waarde. |
| s | std::nullptr_t | Een serviceparameter die dient als selector van de implementatie van de functie; de waarde van de parameter wordt genegeerd |

### Retourwaarde

gtest-gestyleerd assertieresultaat.

## System::TestPredicates::AreEqualImpl(const char *, const char *, std::nullptr_t, T, long long) functie

Vergelijkt willekeurig type met nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs_expr | const char * | LHS-expressie. |
| rhs_expr | const char * | RHS-expressie. |
| rhs | std::nullptr_t | RHS-waarde. |
| s | T | Een serviceparameter die dient als selector van de implementatie van de functie; de waarde van de parameter wordt genegeerd |

### Retourwaarde

gtest-gestyleerd assertieresultaat.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1&, const T2&, long long) functie

Vergelijkt pointertypes.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&(!std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value||!std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs_expr | const char * | LHS-expressie. |
| rhs_expr | const char * | RHS-expressie. |
| lhs | const T1\& | LHS-waarde. |
| rhs | const T2\& | RHS-waarde. |
| s | long long | Een serviceparameter die dient als selector van de implementatie van de functie; de waarde van de parameter wordt genegeerd |

### Retourwaarde

gtest-gestyleerd assertieresultaat.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1&, const T2&, long long) functie

Vergelijkt pointertypes.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value &&std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs_expr | const char * | LHS-expressie. |
| rhs_expr | const char * | RHS-expressie. |
| lhs | const T1\& | LHS-waarde. |
| rhs | const T2\& | RHS-waarde. |
| s | long long | Een serviceparameter die dient als selector van de implementatie van de functie; de waarde van de parameter wordt genegeerd |

### Retourwaarde

gtest-gestyleerd assertieresultaat.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, const Nullable\<T2\>\&, long long) functie

Vergelijkt een willekeurig type met een [Nullable](../../system/nullable/)-waarde.

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T1>::value &&!IsNullable<T1>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, const Nullable<T2> &rhs, long long s)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs_expr | const char * | LHS-expressie. |
| rhs_expr | const char * | RHS-expressie. |
| lhs | T1 | LHS-waarde. |
| rhs | const [Nullable](../../system/nullable/)\<T2\>\& | RHS-waarde. |
| s | long long | Een serviceparameter die dient als selector van de implementatie van de functie; de waarde van de parameter wordt genegeerd |

### Retourwaarde

gtest-gestyleerd assertieresultaat.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const Nullable\<T1\>\&, T2, long long) functie

Vergelijkt een [Nullable](../../system/nullable/)-waarde met een willekeurig type.

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T2>::value &&!IsNullable<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const Nullable<T1> &lhs, T2 rhs, long long s)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs_expr | const char * | LHS-expressie. |
| rhs_expr | const char * | RHS-expressie. |
| lhs | const [Nullable](../../system/nullable/)\<T1\>\& | LHS-waarde. |
| rhs | T2 | RHS-waarde. |
| s | long long | Een serviceparameter die dient als selector van de implementatie van de functie; de waarde van de parameter wordt genegeerd |

### Retourwaarde

gtest-gestyleerd assertieresultaat.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, T2, int) functie

Vergelijkt willekeurige types met behulp van gtest-algoritmen.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs_expr | const char * | LHS-expressie. |
| rhs_expr | const char * | RHS-expressie. |
| lhs | T1 | LHS-waarde. |
| rhs | T2 | RHS-waarde. |

### Retourwaarde

gtest-gestyleerd assertieresultaat.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) functie

Vergelijkt twee [System::String](../../system/string/)-waarden, met bescherming tegen het aanroepen van een lidfunctie op een null [String](../../system/string/). Gesjabloneerd (in plaats van een gewone overload die const [String](../../system/string/)& neemt) zodat gemengde typeaanroepen – bijvoorbeeld een char16_t stringliteral vergeleken met een [String](../../system/string/) – geen enkel consistent T kunnen afleiden en volledig worden uitgesloten van deze kandidaat, in plaats van te concurreren met de catch-all AreEqualImpl<T1,T2>-sjabloon via de long long/int-selectorparameter en een ambigue overloadresolutie veroorzaken.

```cpp
template<typename T> std::enable_if<std::is_same<T, System::String>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | [Object](../../system/object/) type, beperkt tot [System::String](../../system/string/). |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs_expr | const char * | LHS-expressie. |
| rhs_expr | const char * | RHS-expressie. |
| lhs | const T\& | LHS-waarde. |
| rhs | const T\& | RHS-waarde. |
| s | long long | Een serviceparameter die dient als selector van de implementatie van de functie; de waarde van de parameter wordt genegeerd |

### Retourwaarde

gtest-gestyleerd assertieresultaat.

## Zie ook

* Typedef [AreFPandArithmetic](../../system.testpredicates.typetraits/arefpandarithmetic/)
* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Klasse [String](../../system/string/)
* Klasse [Object](../../system/object/)
* Klasse [Stream](../../system.io/stream/)
* Klasse [Nullable](../../system/nullable/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsBoxable](../../system/isboxable/)
* Struct [IsStringByteSequence](../../system/isstringbytesequence/)
* Struct [IsNullable](../../system/isnullable/)
* Naamruimte [System::TestPredicates](../)
* Library [Aspose.Slides](../../)
---
title: AreEqualImpl()
second_title: Aspose.Slides för C++ API-referens
description: Jämför lika flyttal med aritmetiska typer.
type: docs
weight: 27
url: /sv/system.testpredicates/areequalimpl/
---
## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1, const T2, long long) funktion

Jämför lika flyttal med aritmetiska typer.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AreFPandArithmetic<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 lhs, const T2 rhs, long long s)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | LHS-objekttyp. |
| T2 | RHS-objekttyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster uttryck. |
| rhs_expr | const char * | Höger uttryck. |
| lhs | const T1 | Vänster värde. |
| rhs | const T2 | Höger värde. |
| s | long long | En serviceparameter som fungerar som en väljare för funktionens implementation; värdet av parametern ignoreras |

### Returvärde

gtest-stylat påståendedatum.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) funktion

Jämför lika värden där en eller båda är [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | LHS-objekttyp. |
| T2 | RHS-objekttyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster uttryck. |
| rhs_expr | const char * | Höger uttryck. |
| lhs | const T1\& | Vänster värde. |
| rhs | const T2\& | Höger värde. |
| s | long long | En serviceparameter som fungerar som en väljare för funktionens implementation; värdet av parametern ignoreras |

### Returvärde

gtest-stylat påståendedatum.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) funktion

Jämför lika icke-pekartyper med den tillhandahållna Equals-metoden.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | [Object](../../system/object/)-typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster uttryck. |
| rhs_expr | const char * | Höger uttryck. |
| lhs | const T\& | Vänster värde. |
| rhs | const T\& | Höger värde. |
| s | long long | En serviceparameter som fungerar som en väljare för funktionens implementation; värdet av parametern ignoreras |

### Returvärde

gtest-stylat påståendedatum.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T\&, const T\&, long long) funktion

Jämför lika icke-pekartyper med den tillhandahållna Equals-metoden.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | [Object](../../system/object/)-typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster uttryck. |
| rhs_expr | const char * | Höger uttryck. |
| lhs | T\& | Vänster värde. |
| rhs | const T\& | Höger värde. |
| s | long long | En serviceparameter som fungerar som en väljare för funktionens implementation; värdet av parametern ignoreras |

### Returvärde

gtest-stylat påståendedatum.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) funktion

Jämför lika icke-pekartyper med den tillhandahållna operator ==.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | [Object](../../system/object/)-typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster uttryck. |
| rhs_expr | const char * | Höger uttryck. |
| lhs | const T\& | Vänster värde. |
| rhs | const T\& | Höger värde. |
| s | long long | En serviceparameter som fungerar som en väljare för funktionens implementation; värdet av parametern ignoreras |

### Returvärde

gtest-stylat påståendedatum.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) funktion

Jämför lika boxbara med [SmartPtr](../../system/smartptr/)-värden.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | [Object](../../system/object/)-typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster uttryck. |
| rhs_expr | const char * | Höger uttryck. |
| lhs | T | Vänster värde. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Höger värde. |
| s | long long | En serviceparameter som fungerar som en väljare för funktionens implementation; värdet av parametern ignoreras |

### Returvärde

gtest-stylat påståendedatum.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) funktion

Jämför lika boxbara med [SmartPtr](../../system/smartptr/)-värden.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | [Object](../../system/object/)-typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster uttryck. |
| rhs_expr | const char * | Höger uttryck. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Vänster värde. |
| rhs | T | Höger värde. |
| s | long long | En serviceparameter som fungerar som en väljare för funktionens implementation; värdet av parametern ignoreras |

### Returvärde

gtest-stylat påståendedatum.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const char16_t *, const System::SharedPtr\<Object\>\&, long long) funktion

Jämför lika strängliteral med [SmartPtr](../../system/smartptr/)-värden med avpakning.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const char16_t *lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster uttryck. |
| rhs_expr | const char * | Höger uttryck. |
| lhs | const char16_t * | Vänster värde. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Höger värde. |
| s | long long | En serviceparameter som fungerar som en väljare för funktionens implementation; värdet av parametern ignoreras |

### Returvärde

gtest-stylat påståendedatum.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, const char16_t *, long long) funktion

Jämför lika strängliteral med [SmartPtr](../../system/smartptr/)-värden med avpakning.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, const char16_t *rhs, long long s)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster uttryck. |
| rhs_expr | const char * | Höger uttryck. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Vänster värde. |
| rhs | const char16_t * | Höger värde. |
| s | long long | En serviceparameter som fungerar som en väljare för funktionens implementation; värdet av parametern ignoreras |

### Returvärde

gtest-stylat påståendedatum.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, std::nullptr_t, long long) funktion

Jämför lika slumpmässig typ med nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | [Object](../../system/object/)-typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster uttryck. |
| rhs_expr | const char * | Höger uttryck. |
| lhs | T | Vänster värde. |
| s | std::nullptr_t | En serviceparameter som fungerar som en väljare för funktionens implementation; värdet av parametern ignoreras |

### Returvärde

gtest-stylat påståendedatum.

## System::TestPredicates::AreEqualImpl(const char *, const char *, std::nullptr_t, T, long long) funktion

Jämför lika slumpmässig typ med nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | [Object](../../system/object/)-typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster uttryck. |
| rhs_expr | const char * | Höger uttryck. |
| rhs | std::nullptr_t | Höger värde. |
| s | T | En serviceparameter som fungerar som en väljare för funktionens implementation; värdet av parametern ignoreras |

### Returvärde

gtest-stylat påståendedatum.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) funktion

Jämför lika pekartyper.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&(!std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value||!std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | LHS-typ. |
| T2 | RHS-typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster uttryck. |
| rhs_expr | const char * | Höger uttryck. |
| lhs | const T1\& | Vänster värde. |
| rhs | const T2\& | Höger värde. |
| s | long long | En serviceparameter som fungerar som en väljare för funktionens implementation; värdet av parametern ignoreras |

### Returvärde

gtest-stylat påståendedatum.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) funktion

Jämför lika pekartyper.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value &&std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | LHS-typ. |
| T2 | RHS-typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster uttryck. |
| rhs_expr | const char * | Höger uttryck. |
| lhs | const T1\& | Vänster värde. |
| rhs | const T2\& | Höger värde. |
| s | long long | En serviceparameter som fungerar som en väljare för funktionens implementation; värdet av parametern ignoreras |

### Returvärde

gtest-stylat påståendedatum.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, const Nullable\<T2\>\&, long long) funktion

Jämför lika en slumpmässig typ med ett [Nullable](../../system/nullable/)-värde.

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T1>::value &&!IsNullable<T1>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, const Nullable<T2> &rhs, long long s)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | LHS-typ. |
| T2 | RHS-typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster uttryck. |
| rhs_expr | const char * | Höger uttryck. |
| lhs | T1 | Vänster värde. |
| rhs | const [Nullable](../../system/nullable/)\<T2\>\& | Höger värde. |
| s | long long | En serviceparameter som fungerar som en väljare för funktionens implementation; värdet av parametern ignoreras |

### Returvärde

gtest-stylat påståendedatum.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const Nullable\<T1\>\&, T2, long long) funktion

Jämför lika ett [Nullable](../../system/nullable/)-värde med en slumpmässig typ.

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T2>::value &&!IsNullable<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const Nullable<T1> &lhs, T2 rhs, long long s)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | LHS-typ. |
| T2 | RHS-typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster uttryck. |
| rhs_expr | const char * | Höger uttryck. |
| lhs | const [Nullable](../../system/nullable/)\<T1\>\& | Vänster värde. |
| rhs | T2 | Höger värde. |
| s | long long | En serviceparameter som fungerar som en väljare för funktionens implementation; värdet av parametern ignoreras |

### Returvärde

gtest-stylat påståendedatum.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, T2, int) funktion

Jämför lika slumpmässiga typer med gtest-algoritmer.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | LHS-typ. |
| T2 | RHS-typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster uttryck. |
| rhs_expr | const char * | Höger uttryck. |
| lhs | T1 | Vänster värde. |
| rhs | T2 | Höger värde. |

### Returvärde

gtest-stylat påståendedatum.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) funktion

Jämför lika två [System::String](../../system/string/)-värden och skyddar mot att anropa en medlemsfunktion på en null [String](../../system/string/). Mallad (snarare än en enkel överlagring som tar const [String](../../system/string/)&) så att blandade typer – t.ex. en char16_t-strängliteral jämfört med en [String](../../system/string/) – misslyckas med att härleda en enda konsekvent T och utesluts helt från denna kandidat, i stället för att konkurrera med catch-all-varianten AreEqualImpl<T1,T2> via long long/int-selector-parametern och orsaka en tvetydig överlagringsupplösning.

```cpp
template<typename T> std::enable_if<std::is_same<T, System::String>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | [Object](../../system/object/)-typ, begränsad till [System::String](../../system/string/). |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | Vänster uttryck. |
| rhs_expr | const char * | Höger uttryck. |
| lhs | const T\& | Vänster värde. |
| rhs | const T\& | Höger värde. |
| s | long long | En serviceparameter som fungerar som en väljare för funktionens implementation; värdet av parametern ignoreras |

### Returvärde

gtest-stylat påståendedatum.

## Se också

* Typedef [AreFPandArithmetic](../../system.testpredicates.typetraits/arefpandarithmetic/)
* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Klass [String](../../system/string/)
* Klass [Object](../../system/object/)
* Klass [Stream](../../system.io/stream/)
* Klass [Nullable](../../system/nullable/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsBoxable](../../system/isboxable/)
* Struct [IsStringByteSequence](../../system/isstringbytesequence/)
* Struct [IsNullable](../../system/isnullable/)
* Namnrymd [System::TestPredicates](../)
* Bibliotek [Aspose.Slides](../../)
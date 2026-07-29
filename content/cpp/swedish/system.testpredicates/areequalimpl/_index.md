---
title: AreEqualImpl()
second_title: Aspose.Slides för C++ API-referens
description: Jämför lika flyttal med aritmetiska typer.
type: docs
weight: 27
url: /sv/system.testpredicates/areequalimpl/
---
## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1, const T2, long long) function

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
| lhs_expr | const char * | LHS-uttryck. |
| rhs_expr | const char * | RHS-uttryck. |
| lhs | const T1 | LHS-värde. |
| rhs | const T2 | RHS-värde. |
| s | long long | En serviceparameter som fungerar som en väljare av funktionens implementation; parametervärdet ignoreras |

### Returvärde

gtest-stylat påståenderesultat.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

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
| lhs_expr | const char * | LHS-uttryck. |
| rhs_expr | const char * | RHS-uttryck. |
| lhs | const T1\& | LHS-värde. |
| rhs | const T2\& | RHS-värde. |
| s | long long | En serviceparameter som fungerar som en väljare av funktionens implementation; parametervärdet ignoreras |

### Returvärde

gtest-stylat påståenderesultat.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) function

Jämför lika icke-pekartyper med den tillhandahållna Equals-metoden.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | LHS-uttryck. |
| rhs_expr | const char * | RHS-uttryck. |
| lhs | const T\& | LHS-värde. |
| rhs | const T\& | RHS-värde. |
| s | long long | En serviceparameter som fungerar som en väljare av funktionens implementation; parametervärdet ignoreras |

### Returvärde

gtest-stylat påståenderesultat.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T\&, const T\&, long long) function

Jämför lika icke-pekartyper med den tillhandahållna Equals-metoden.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | LHS-uttryck. |
| rhs_expr | const char * | RHS-uttryck. |
| lhs | T\& | LHS-värde. |
| rhs | const T\& | RHS-värde. |
| s | long long | En serviceparameter som fungerar som en väljare av funktionens implementation; parametervärdet ignoreras |

### Returvärde

gtest-stylat påståenderesultat.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) function

Jämför lika icke-pekartyper med den tillhandahållna operatorn ==.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | LHS-uttryck. |
| rhs_expr | const char * | RHS-uttryck. |
| lhs | const T\& | LHS-värde. |
| rhs | const T\& | RHS-värde. |
| s | long long | En serviceparameter som fungerar som en väljare av funktionens implementation; parametervärdet ignoreras |

### Returvärde

gtest-stylat påståenderesultat.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) function

Jämför lika boxbara med [SmartPtr](../../system/smartptr/) värden.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | LHS-uttryck. |
| rhs_expr | const char * | RHS-uttryck. |
| lhs | T | LHS-värde. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | RHS-värde. |
| s | long long | En serviceparameter som fungerar som en väljare av funktionens implementation; parametervärdet ignoreras |

### Returvärde

gtest-stylat påståenderesultat.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) function

Jämför lika boxbara med [SmartPtr](../../system/smartptr/) värden.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | LHS-uttryck. |
| rhs_expr | const char * | RHS-uttryck. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | LHS-värde. |
| rhs | T | RHS-värde. |
| s | long long | En serviceparameter som fungerar som en väljare av funktionens implementation; parametervärdet ignoreras |

### Returvärde

gtest-stylat påståenderesultat.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const char16_t *, const System::SharedPtr\<Object\>\&, long long) function

Jämför lika stränglitteraler med [SmartPtr](../../system/smartptr/) värden med avpackning.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const char16_t *lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | LHS-uttryck. |
| rhs_expr | const char * | RHS-uttryck. |
| lhs | const char16_t * | LHS-värde. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | RHS-värde. |
| s | long long | En serviceparameter som fungerar som en väljare av funktionens implementation; parametervärdet ignoreras |

### Returvärde

gtest-stylat påståenderesultat.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, const char16_t *, long long) function

Jämför lika stränglitteraler med [SmartPtr](../../system/smartptr/) värden med avpackning.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, const char16_t *rhs, long long s)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | LHS-uttryck. |
| rhs_expr | const char * | RHS-uttryck. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | LHS-värde. |
| rhs | const char16_t * | RHS-värde. |
| s | long long | En serviceparameter som fungerar som en väljare av funktionens implementation; parametervärdet ignoreras |

### Returvärde

gtest-stylat påståenderesultat.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, std::nullptr_t, long long) function

Jämför lika slumpmässig typ med nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | LHS-uttryck. |
| rhs_expr | const char * | RHS-uttryck. |
| lhs | T | LHS-värde. |
| s | std::nullptr_t | En serviceparameter som fungerar som en väljare av funktionens implementation; parametervärdet ignoreras |

### Returvärde

gtest-stylat påståenderesultat.

## System::TestPredicates::AreEqualImpl(const char *, const char *, std::nullptr_t, T, long long) function

Jämför lika slumpmässig typ med nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | LHS-uttryck. |
| rhs_expr | const char * | RHS-uttryck. |
| rhs | std::nullptr_t | RHS-värde. |
| s | T | En serviceparameter som fungerar som en väljare av funktionens implementation; parametervärdet ignoreras |

### Returvärde

gtest-stylat påståenderesultat.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

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
| lhs_expr | const char * | LHS-uttryck. |
| rhs_expr | const char * | RHS-uttryck. |
| lhs | const T1\& | LHS-värde. |
| rhs | const T2\& | RHS-värde. |
| s | long long | En serviceparameter som fungerar som en väljare av funktionens implementation; parametervärdet ignoreras |

### Returvärde

gtest-stylat påståenderesultat.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

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
| lhs_expr | const char * | LHS-uttryck. |
| rhs_expr | const char * | RHS-uttryck. |
| lhs | const T1\& | LHS-värde. |
| rhs | const T2\& | RHS-värde. |
| s | long long | En serviceparameter som fungerar som en väljare av funktionens implementation; parametervärdet ignoreras |

### Returvärde

gtest-stylat påståenderesultat.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, const Nullable\<T2\>\&, long long) function

Jämför lika en slumpmässig typ med ett [Nullable](../../system/nullable/) värde.

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
| lhs_expr | const char * | LHS-uttryck. |
| rhs_expr | const char * | RHS-uttryck. |
| lhs | T1 | LHS-värde. |
| rhs | const [Nullable](../../system/nullable/)\<T2\>\& | RHS-värde. |
| s | long long | En serviceparameter som fungerar som en väljare av funktionens implementation; parametervärdet ignoreras |

### Returvärde

gtest-stylat påståenderesultat.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const Nullable\<T1\>\&, T2, long long) function

Jämför lika ett [Nullable](../../system/nullable/) värde med en slumpmässig typ.

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
| lhs_expr | const char * | LHS-uttryck. |
| rhs_expr | const char * | RHS-uttryck. |
| lhs | const [Nullable](../../system/nullable/)\<T1\>\& | LHS-värde. |
| rhs | T2 | RHS-värde. |
| s | long long | En serviceparameter som fungerar som en väljare av funktionens implementation; parametervärdet ignoreras |

### Returvärde

gtest-stylat påståenderesultat.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, T2, int) function

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
| lhs_expr | const char * | LHS-uttryck. |
| rhs_expr | const char * | RHS-uttryck. |
| lhs | T1 | LHS-värde. |
| rhs | T2 | RHS-värde. |

### Returvärde

gtest-stylat påståenderesultat.

## Se även

* Typedef [AreFPandArithmetic](../../system.testpredicates.typetraits/arefpandarithmetic/)
* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Klass [Object](../../system/object/)
* Klass [Stream](../../system.io/stream/)
* Klass [Nullable](../../system/nullable/)
* Struktur [IsSmartPtr](../../system/issmartptr/)
* Struktur [IsBoxable](../../system/isboxable/)
* Struktur [IsStringByteSequence](../../system/isstringbytesequence/)
* Struktur [IsNullable](../../system/isnullable/)
* Namnrymd [System::TestPredicates](../)
* Bibliotek [Aspose.Slides](../../)
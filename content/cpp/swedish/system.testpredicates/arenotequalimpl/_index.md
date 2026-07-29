---
title: AreNotEqualImpl()
second_title: Aspose.Slides för C++ API-referens
description: Inte lika jämför värden där en eller båda av dem är Decimal.
type: docs
weight: 53
url: /sv/system.testpredicates/arenotequalimpl/
---
## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) funktion


Inte lika jämför värden där en eller båda av dem är [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
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
| s | long long | En serviceparameter som fungerar som en selektor för implementeringen av funktionen; parametervärdet ignoreras |

### Returvärde

gtest-stylat påståenderesultat.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) funktion


Inte lika jämför icke-pekartyper med den medföljande Equals-metoden.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
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
| s | long long | En serviceparameter som fungerar som en selektor för implementeringen av funktionen; parametervärdet ignoreras |

### Returvärde

gtest-stylat påståenderesultat.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T\&, const T\&, long long) funktion


Inte lika jämför icke-pekartyper med den medföljande Equals-metoden.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
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
| s | long long | En serviceparameter som fungerar som en selektor för implementeringen av funktionen; parametervärdet ignoreras |

### Returvärde

gtest-stylat påståenderesultat.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) funktion


Inte lika jämför icke-pekartyper med den medföljande operator !=-operatorn.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
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
| s | long long | En serviceparameter som fungerar som en selektor för implementeringen av funktionen; parametervärdet ignoreras |

### Returvärde

gtest-stylat påståenderesultat.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) funktion


Inte lika jämför boxbara med [SmartPtr](../../system/smartptr/)-värden med avpakning.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
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
| s | long long | En serviceparameter som fungerar som en selektor för implementeringen av funktionen; parametervärdet ignoreras |

### Returvärde

gtest-stylat påståenderesultat.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) funktion


Inte lika jämför boxbara med [SmartPtr](../../system/smartptr/)-värden med avpakning.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
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
| s | long long | En serviceparameter som fungerar som en selektor för implementeringen av funktionen; parametervärdet ignoreras |

### Returvärde

gtest-stylat påståenderesultat.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, std::nullptr_t, long long) funktion


Inte lika jämför slumpmässig typ med nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
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
| s | std::nullptr_t | En serviceparameter som fungerar som en selektor för implementeringen av funktionen; parametervärdet ignoreras |

### Returvärde

gtest-stylat påståenderesultat.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, std::nullptr_t, T, long long) funktion


Inte lika jämför slumpmässig typ med nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
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
| s | T | En serviceparameter som fungerar som en selektor för implementeringen av funktionen; parametervärdet ignoreras |

### Returvärde

gtest-stylat påståenderesultat.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) funktion


Equal jämför pekartyper.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
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
| s | long long | En serviceparameter som fungerar som en selektor för implementeringen av funktionen; parametervärdet ignoreras |

### Returvärde

gtest-stylat påståenderesultat.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T1, T2, int) funktion


Equal jämför slumpmässiga typer med hjälp av gtest-algoritmer.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
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

* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Klass [Object](../../system/object/)
* Struktur [IsSmartPtr](../../system/issmartptr/)
* Struktur [IsBoxable](../../system/isboxable/)
* Namnrymd [System::TestPredicates](../)
* Bibliotek [Aspose.Slides](../../)
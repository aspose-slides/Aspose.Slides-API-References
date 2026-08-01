---
title: AreNotEqualImpl()
second_title: Aspose.Slides voor C++ API-referentie
description: Niet-gelijk vergelijkt waarden waarvan één of beide Decimal zijn.
type: docs
weight: 53
url: /nl/system.testpredicates/arenotequalimpl/
---
## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) functie


Niet-gelijk vergelijkt waarden waarvan één of beide [Decimal](../../system/decimal/) zijn.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | LHS objecttype. |
| T2 | RHS objecttype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs_expr | const char * | LHS-expressie. |
| rhs_expr | const char * | RHS-expressie. |
| lhs | const T1\& | LHS-waarde. |
| rhs | const T2\& | RHS-waarde. |
| s | long long | Een serviceparameter die dient als selector van de implementatie van de functie; de waarde van de parameter wordt genegeerd |

### Retourwaarde

gtest-gestyleerde assertieresultaat.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) functie


Niet-gelijk vergelijkt niet-pointer types met de geleverde Equals-methode.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
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

gtest-gestyleerde assertieresultaat.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T\&, const T\&, long long) functie


Niet-gelijk vergelijkt niet-pointer types met de geleverde Equals-methode.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
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

gtest-gestyleerde assertieresultaat.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) functie


Niet-gelijk vergelijkt niet-pointer types met de geleverde operator !=.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
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

gtest-gestyleerde assertieresultaat.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) functie


Niet-gelijk vergelijkt boxable met [SmartPtr](../../system/smartptr/) waarden met behulp van unboxing.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
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

gtest-gestyleerde assertieresultaat.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) functie


Niet-gelijk vergelijkt boxable met [SmartPtr](../../system/smartptr/) waarden met behulp van unboxing.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
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

gtest-gestyleerde assertieresultaat.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, std::nullptr_t, long long) functie


Niet-gelijk vergelijkt willekeurig type met nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
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

gtest-gestyleerde assertieresultaat.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, std::nullptr_t, T, long long) functie


Niet-gelijk vergelijkt willekeurig type met nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
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

gtest-gestyleerde assertieresultaat.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) functie


Gelijk vergelijkt pointer types.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
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

gtest-gestyleerde assertieresultaat.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T1, T2, int) functie


Gelijk vergelijkt willekeurige types met behulp van gtest-algoritmen.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
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

gtest-gestyleerde assertieresultaat.

## Zie ook

* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Object](../../system/object/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsBoxable](../../system/isboxable/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)
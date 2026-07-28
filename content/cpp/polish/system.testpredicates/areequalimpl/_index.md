---
title: AreEqualImpl()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Porównuje równość liczb zmiennoprzecinkowych z typami arytmetycznymi.
type: docs
weight: 27
url: /pl/system.testpredicates/areequalimpl/
---
## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1, const T2, long long) funkcja


Porównuje równość typów zmiennoprzecinkowych z typami arytmetycznymi.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AreFPandArithmetic<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 lhs, const T2 rhs, long long s)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | typ obiektu LHS. |
| T2 | typ obiektu RHS. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs_expr | const char * | wyrażenie LHS. |
| rhs_expr | const char * | wyrażenie RHS. |
| lhs | const T1 | wartość LHS. |
| rhs | const T2 | wartość RHS. |
| s | long long | Parametr serwisowy służący jako selektor implementacji funkcji; wartość tego parametru jest ignorowana |

### Wartość zwracana

wynik asercji w stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) funkcja


Porównuje równość wartości, z których jedna lub obie są [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | typ obiektu LHS. |
| T2 | typ obiektu RHS. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs_expr | const char * | wyrażenie LHS. |
| rhs_expr | const char * | wyrażenie RHS. |
| lhs | const T1\& | wartość LHS. |
| rhs | const T2\& | wartość RHS. |
| s | long long | Parametr serwisowy służący jako selektor implementacji funkcji; wartość tego parametru jest ignorowana |

### Wartość zwracana

wynik asercji w stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) funkcja


Porównuje równość typów niebędących wskaźnikami przy użyciu dostarczonej metody Equals.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | typ [Object](../../system/object/). |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs_expr | const char * | wyrażenie LHS. |
| rhs_expr | const char * | wyrażenie RHS. |
| lhs | const T\& | wartość LHS. |
| rhs | const T\& | wartość RHS. |
| s | long long | Parametr serwisowy służący jako selektor implementacji funkcji; wartość tego parametru jest ignorowana |

### Wartość zwracana

wynik asercji w stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T\&, const T\&, long long) funkcja


Porównuje równość typów niebędących wskaźnikami przy użyciu dostarczonej metody Equals.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | typ [Object](../../system/object/). |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs_expr | const char * | wyrażenie LHS. |
| rhs_expr | const char * | wyrażenie RHS. |
| lhs | T\& | wartość LHS. |
| rhs | const T\& | wartość RHS. |
| s | long long | Parametr serwisowy służący jako selektor implementacji funkcji; wartość tego parametru jest ignorowana |

### Wartość zwracana

wynik asercji w stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) funkcja


Porównuje równość typów niebędących wskaźnikami przy użyciu operatora ==.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | typ [Object](../../system/object/). |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs_expr | const char * | wyrażenie LHS. |
| rhs_expr | const char * | wyrażenie RHS. |
| lhs | const T\& | wartość LHS. |
| rhs | const T\& | wartość RHS. |
| s | long long | Parametr serwisowy służący jako selektor implementacji funkcji; wartość tego parametru jest ignorowana |

### Wartość zwracana

wynik asercji w stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) funkcja


Porównuje równość obiektów możliwych do spakowania z wartościami [SmartPtr](../../system/smartptr/).

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | typ [Object](../../system/object/). |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs_expr | const char * | wyrażenie LHS. |
| rhs_expr | const char * | wyrażenie RHS. |
| lhs | T | wartość LHS. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | wartość RHS. |
| s | long long | Parametr serwisowy służący jako selektor implementacji funkcji; wartość tego parametru jest ignorowana |

### Wartość zwracana

wynik asercji w stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) funkcja


Porównuje równość obiektów możliwych do spakowania z wartościami [SmartPtr](../../system/smartptr/).

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | typ [Object](../../system/object/). |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs_expr | const char * | wyrażenie LHS. |
| rhs_expr | const char * | wyrażenie RHS. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | wartość LHS. |
| rhs | T | wartość RHS. |
| s | long long | Parametr serwisowy służący jako selektor implementacji funkcji; wartość tego parametru jest ignorowana |

### Wartość zwracana

wynik asercji w stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const char16_t *, const System::SharedPtr\<Object\>\&, long long) funkcja


Porównuje równość literału znakowego z wartościami [SmartPtr](../../system/smartptr/) przy użyciu odpakowywania.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const char16_t *lhs, const System::SharedPtr<Object> &rhs, long long s)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs_expr | const char * | wyrażenie LHS. |
| rhs_expr | const char * | wyrażenie RHS. |
| lhs | const char16_t * | wartość LHS. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | wartość RHS. |
| s | long long | Parametr serwisowy służący jako selektor implementacji funkcji; wartość tego parametru jest ignorowana |

### Wartość zwracana

wynik asercji w stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, const char16_t *, long long) funkcja


Porównuje równość literału znakowego z wartościami [SmartPtr](../../system/smartptr/) przy użyciu odpakowywania.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, const char16_t *rhs, long long s)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs_expr | const char * | wyrażenie LHS. |
| rhs_expr | const char * | wyrażenie RHS. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | wartość LHS. |
| rhs | const char16_t * | wartość RHS. |
| s | long long | Parametr serwisowy służący jako selektor implementacji funkcji; wartość tego parametru jest ignorowana |

### Wartość zwracana

wynik asercji w stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, std::nullptr_t, long long) funkcja


Porównuje równość losowego typu z nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | typ [Object](../../system/object/). |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs_expr | const char * | wyrażenie LHS. |
| rhs_expr | const char * | wyrażenie RHS. |
| lhs | T | wartość LHS. |
| s | std::nullptr_t | Parametr serwisowy służący jako selektor implementacji funkcji; wartość tego parametru jest ignorowana |

### Wartość zwracana

wynik asercji w stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, std::nullptr_t, T, long long) funkcja


Porównuje równość losowego typu z nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | typ [Object](../../system/object/). |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs_expr | const char * | wyrażenie LHS. |
| rhs_expr | const char * | wyrażenie RHS. |
| rhs | std::nullptr_t | wartość RHS. |
| s | T | Parametr serwisowy służący jako selektor implementacji funkcji; wartość tego parametru jest ignorowana |

### Wartość zwracana

wynik asercji w stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) funkcja


Porównuje równość typów wskaźnikowych.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&(!std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value||!std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | typ LHS. |
| T2 | typ RHS. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs_expr | const char * | wyrażenie LHS. |
| rhs_expr | const char * | wyrażenie RHS. |
| lhs | const T1\& | wartość LHS. |
| rhs | const T2\& | wartość RHS. |
| s | long long | Parametr serwisowy służący jako selektor implementacji funkcji; wartość tego parametru jest ignorowana |

### Wartość zwracana

wynik asercji w stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) funkcja


Porównuje równość typów wskaźnikowych.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value &&std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | typ LHS. |
| T2 | typ RHS. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs_expr | const char * | wyrażenie LHS. |
| rhs_expr | const char * | wyrażenie RHS. |
| lhs | const T1\& | wartość LHS. |
| rhs | const T2\& | wartość RHS. |
| s | long long | Parametr serwisowy służący jako selektor implementacji funkcji; wartość tego parametru jest ignorowana |

### Wartość zwracana

wynik asercji w stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, const Nullable\<T2\>\&, long long) funkcja


Porównuje równość losowego typu z wartością [Nullable](../../system/nullable/).

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T1>::value &&!IsNullable<T1>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, const Nullable<T2> &rhs, long long s)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | typ LHS. |
| T2 | typ RHS. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs_expr | const char * | wyrażenie LHS. |
| rhs_expr | const char * | wyrażenie RHS. |
| lhs | T1 | wartość LHS. |
| rhs | const [Nullable](../../system/nullable/)\<T2\>\& | wartość RHS. |
| s | long long | Parametr serwisowy służący jako selektor implementacji funkcji; wartość tego parametru jest ignorowana |

### Wartość zwracana

wynik asercji w stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const Nullable\<T1\>\&, T2, long long) funkcja


Porównuje równość wartości [Nullable](../../system/nullable/) z losowym typem.

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T2>::value &&!IsNullable<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const Nullable<T1> &lhs, T2 rhs, long long s)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | typ LHS. |
| T2 | typ RHS. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs_expr | const char * | wyrażenie LHS. |
| rhs_expr | const char * | wyrażenie RHS. |
| lhs | const [Nullable](../../system/nullable/)\<T1\>\& | wartość LHS. |
| rhs | T2 | wartość RHS. |
| s | long long | Parametr serwisowy służący jako selektor implementacji funkcji; wartość tego parametru jest ignorowana |

### Wartość zwracana

wynik asercji w stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, T2, int) funkcja


Porównuje równość losowych typów przy użyciu algorytmów gtest.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | typ LHS. |
| T2 | typ RHS. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs_expr | const char * | wyrażenie LHS. |
| rhs_expr | const char * | wyrażenie RHS. |
| lhs | T1 | wartość LHS. |
| rhs | T2 | wartość RHS. |

### Wartość zwracana

wynik asercji w stylu gtest.

## Zobacz także

* Typedef [AreFPandArithmetic](../../system.testpredicates.typetraits/arefpandarithmetic/)
* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Klasa [Object](../../system/object/)
* Klasa [Stream](../../system.io/stream/)
* Klasa [Nullable](../../system/nullable/)
* Struktura [IsSmartPtr](../../system/issmartptr/)
* Struktura [IsBoxable](../../system/isboxable/)
* Struktura [IsStringByteSequence](../../system/isstringbytesequence/)
* Struktura [IsNullable](../../system/isnullable/)
* Przestrzeń nazw [System::TestPredicates](../)
* Biblioteka [Aspose.Slides](../../)
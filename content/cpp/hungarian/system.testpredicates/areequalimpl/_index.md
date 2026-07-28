---
title: AreEqualImpl()
second_title: Aspose.Slides C++ API Referencia
description: Egyenlő-összehasonlítja a lebegőpontos számokat aritmetikai típusokkal.
type: docs
weight: 27
url: /hu/system.testpredicates/areequalimpl/
---
## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1, const T2, long long) function

Egyenlő-összehasonlítja a lebegőpontos számokat aritmetikai típusokkal.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AreFPandArithmetic<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 lhs, const T2 rhs, long long s)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | Bal oldal objektumtípus. |
| T2 | Jobb oldal objektumtípus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Bal oldal kifejezés. |
| rhs_expr | const char * | Jobb oldal kifejezés. |
| lhs | const T1 | Bal oldal érték. |
| rhs | const T2 | Jobb oldal érték. |
| s | long long | A szolgáltatási paraméter, amely a függvény implementációjának kiválasztására szolgál; a paraméter értéke figyelmen kívül marad. |

### Visszatérési érték

gtest-stílusú állítási eredmény.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

Egyenlő-összehasonlítja az értékeket, amelyek egyike vagy mindkettő [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | Bal oldal objektumtípus. |
| T2 | Jobb oldal objektumtípus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Bal oldal kifejezés. |
| rhs_expr | const char * | Jobb oldal kifejezés. |
| lhs | const T1\& | Bal oldal érték. |
| rhs | const T2\& | Jobb oldal érték. |
| s | long long | A szolgáltatási paraméter, amely a függvény implementációjának kiválasztására szolgál; a paraméter értéke figyelmen kívül marad. |

### Visszatérési érték

gtest-stílusú állítási eredmény.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) function

Egyenlő-összehasonlítja a nem mutató típusokat a biztosított Equals metódus használatával.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Object](../../system/object/) típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Bal oldal kifejezés. |
| rhs_expr | const char * | Jobb oldal kifejezés. |
| lhs | const T\& | Bal oldal érték. |
| rhs | const T\& | Jobb oldal érték. |
| s | long long | A szolgáltatási paraméter, amely a függvény implementációjának kiválasztására szolgál; a paraméter értéke figyelmen kívül marad. |

### Visszatérési érték

gtest-stílusú állítási eredmény.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T\&, const T\&, long long) function

Egyenlő-összehasonlítja a nem mutató típusokat a biztosított Equals metódus használatával.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Object](../../system/object/) típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Bal oldal kifejezés. |
| rhs_expr | const char * | Jobb oldal kifejezés. |
| lhs | T\& | Bal oldal érték. |
| rhs | const T\& | Jobb oldal érték. |
| s | long long | A szolgáltatási paraméter, amely a függvény implementációjának kiválasztására szolgál; a paraméter értéke figyelmen kívül marad. |

### Visszatérési érték

gtest-stílusú állítási eredmény.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) function

Egyenlő-összehasonlítja a nem mutató típusokat a biztosított == operátor használatával.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Object](../../system/object/) típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Bal oldal kifejezés. |
| rhs_expr | const char * | Jobb oldal kifejezés. |
| lhs | const T\& | Bal oldal érték. |
| rhs | const T\& | Jobb oldal érték. |
| s | long long | A szolgáltatási paraméter, amely a függvény implementációjának kiválasztására szolgál; a paraméter értéke figyelmen kívül marad. |

### Visszatérési érték

gtest-stílusú állítási eredmény.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) function

Egyenlő-összehasonlítja a dobozható típusokat [SmartPtr](../../system/smartptr/) értékekkel.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Object](../../system/object/) típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Bal oldal kifejezés. |
| rhs_expr | const char * | Jobb oldal kifejezés. |
| lhs | T | Bal oldal érték. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Jobb oldal érték. |
| s | long long | A szolgáltatási paraméter, amely a függvény implementációjának kiválasztására szolgál; a paraméter értéke figyelmen kívül marad. |

### Visszatérési érték

gtest-stílusú állítási eredmény.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) function

Egyenlő-összehasonlítja a dobozható típusokat [SmartPtr](../../system/smartptr/) értékekkel.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Object](../../system/object/) típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Bal oldal kifejezés. |
| rhs_expr | const char * | Jobb oldal kifejezés. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Bal oldal érték. |
| rhs | T | Jobb oldal érték. |
| s | long long | A szolgáltatási paraméter, amely a függvény implementációjának kiválasztására szolgál; a paraméter értéke figyelmen kívül marad. |

### Visszatérési érték

gtest-stílusú állítási eredmény.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const char16_t *, const System::SharedPtr\<Object\>\&, long long) function

Egyenlő-összehasonlítja a string literált [SmartPtr](../../system/smartptr/) értékekkel az unboxing használatával.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const char16_t *lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Bal oldal kifejezés. |
| rhs_expr | const char * | Jobb oldal kifejezés. |
| lhs | const char16_t * | Bal oldal érték. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Jobb oldal érték. |
| s | long long | A szolgáltatási paraméter, amely a függvény implementációjának kiválasztására szolgál; a paraméter értéke figyelmen kívül marad. |

### Visszatérési érték

gtest-stílusú állítási eredmény.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, const char16_t *, long long) function

Egyenlő-összehasonlítja a string literált [SmartPtr](../../system/smartptr/) értékekkel az unboxing használatával.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, const char16_t *rhs, long long s)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Bal oldal kifejezés. |
| rhs_expr | const char * | Jobb oldal kifejezés. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Bal oldal érték. |
| rhs | const char16_t * | Jobb oldal érték. |
| s | long long | A szolgáltatási paraméter, amely a függvény implementációjának kiválasztására szolgál; a paraméter értéke figyelmen kívül marad. |

### Visszatérési érték

gtest-stílusú állítási eredmény.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, std::nullptr_t, long long) function

Egyenlő-összehasonlít egy tetszőleges típust a nullptr-vel.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Object](../../system/object/) típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Bal oldal kifejezés. |
| rhs_expr | const char * | Jobb oldal kifejezés. |
| lhs | T | Bal oldal érték. |
| s | std::nullptr_t | A szolgáltatási paraméter, amely a függvény implementációjának kiválasztására szolgál; a paraméter értéke figyelmen kívül marad. |

### Visszatérési érték

gtest-stílusú állítási eredmény.

## System::TestPredicates::AreEqualImpl(const char *, const char *, std::nullptr_t, T, long long) function

Egyenlő-összehasonlít egy tetszőleges típust a nullptr-vel.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Object](../../system/object/) típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Bal oldal kifejezés. |
| rhs_expr | const char * | Jobb oldal kifejezés. |
| rhs | std::nullptr_t | Jobb oldal érték. |
| s | T | A szolgáltatási paraméter, amely a függvény implementációjának kiválasztására szolgál; a paraméter értéke figyelmen kívül marad. |

### Visszatérési érték

gtest-stílusú állítási eredmény.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

Egyenlő-összehasonlítja a mutató típusokat.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&(!std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value||!std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | Bal oldal típus. |
| T2 | Jobb oldal típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Bal oldal kifejezés. |
| rhs_expr | const char * | Jobb oldal kifejezés. |
| lhs | const T1\& | Bal oldal érték. |
| rhs | const T2\& | Jobb oldal érték. |
| s | long long | A szolgáltatási paraméter, amely a függvény implementációjának kiválasztására szolgál; a paraméter értéke figyelmen kívül marad. |

### Visszatérési érték

gtest-stílusú állítási eredmény.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

Egyenlő-összehasonlítja a mutató típusokat.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value &&std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | Bal oldal típus. |
| T2 | Jobb oldal típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Bal oldal kifejezés. |
| rhs_expr | const char * | Jobb oldal kifejezés. |
| lhs | const T1\& | Bal oldal érték. |
| rhs | const T2\& | Jobb oldal érték. |
| s | long long | A szolgáltatási paraméter, amely a függvény implementációjának kiválasztására szolgál; a paraméter értéke figyelmen kívül marad. |

### Visszatérési érték

gtest-stílusú állítási eredmény.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, const Nullable\<T2\>\&, long long) function

Egyenlő-összehasonlít egy tetszőleges típust egy [Nullable](../../system/nullable/) értékkel.

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T1>::value &&!IsNullable<T1>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, const Nullable<T2> &rhs, long long s)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | Bal oldal típus. |
| T2 | Jobb oldal típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Bal oldal kifejezés. |
| rhs_expr | const char * | Jobb oldal kifejezés. |
| lhs | T1 | Bal oldal érték. |
| rhs | const [Nullable](../../system/nullable/)\<T2\>\& | Jobb oldal érték. |
| s | long long | A szolgáltatási paraméter, amely a függvény implementációjának kiválasztására szolgál; a paraméter értéke figyelmen kívül marad. |

### Visszatérési érték

gtest-stílusú állítási eredmény.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const Nullable\<T1\>\&, T2, long long) function

Egyenlő-összehasonlít egy [Nullable](../../system/nullable/) értéket egy tetszőleges típussal.

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T2>::value &&!IsNullable<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const Nullable<T1> &lhs, T2 rhs, long long s)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | Bal oldal típus. |
| T2 | Jobb oldal típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Bal oldal kifejezés. |
| rhs_expr | const char * | Jobb oldal kifejezés. |
| lhs | const [Nullable](../../system/nullable/)\<T1\>\& | Bal oldal érték. |
| rhs | T2 | Jobb oldal érték. |
| s | long long | A szolgáltatási paraméter, amely a függvény implementációjának kiválasztására szolgál; a paraméter értéke figyelmen kívül marad. |

### Visszatérési érték

gtest-stílusú állítási eredmény.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, T2, int) function

Egyenlő-összehasonlítja a tetszőleges típusokat gtest algoritmusok használatával.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | Bal oldal típus. |
| T2 | Jobb oldal típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Bal oldal kifejezés. |
| rhs_expr | const char * | Jobb oldal kifejezés. |
| lhs | T1 | Bal oldal érték. |
| rhs | T2 | Jobb oldal érték. |

### Visszatérési érték

gtest-stílusú állítási eredmény.

## Lásd még

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
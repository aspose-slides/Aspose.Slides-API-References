---
title: AreNotEqualImpl()
second_title: Aspose.Slides for C++ API referencia
description: Nem-egyenlő összehasonlít értékeket, amelyek egyike vagy mindkettő Decimal.
type: docs
weight: 53
url: /hu/system.testpredicates/arenotequalimpl/
---
## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

A nem-egyenlő összehasonlítás értékeket vizsgál, amelyek egyike vagy mindkettő [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T1 | LHS object type. |
| T2 | RHS object type. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1\& | LHS value. |
| rhs | const T2\& | RHS value. |
| s | long long | Egy szolgáltatási paraméter, amely a függvény megvalósításának kiválasztójaként szolgál; a paraméter értéke figyelmen kívül van hagyva |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) function

A nem-egyenlő összehasonlítás a nem mutatótípusokat a biztosított Equals metódussal végzi.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T\& | LHS value. |
| rhs | const T\& | RHS value. |
| s | long long | Egy szolgáltatási paraméter, amely a függvény megvalósításának kiválasztójaként szolgál; a paraméter értéke figyelmen kívül van hagyva |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T\&, const T\&, long long) function

A nem-egyenlő összehasonlítás a nem mutatótípusokat a biztosított Equals metódussal végzi.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T\& | LHS value. |
| rhs | const T\& | RHS value. |
| s | long long | Egy szolgáltatási paraméter, amely a függvény megvalósításának kiválasztójaként szolgál; a paraméter értéke figyelmen kívül van hagyva |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) function

A nem-egyenlő összehasonlítás a nem mutatótípusokat a != operátorral végzi.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T\& | LHS value. |
| rhs | const T\& | RHS value. |
| s | long long | Egy szolgáltatási paraméter, amely a függvény megvalósításának kiválasztójaként szolgál; a paraméter értéke figyelmen kívül van hagyva |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) function

A nem-egyenlő összehasonlítás dobozolható [SmartPtr](../../system/smartptr/) értékekkel unboxing használatával.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T | LHS value. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | RHS value. |
| s | long long | Egy szolgáltatási paraméter, amely a függvény megvalósításának kiválasztójaként szolgál; a paraméter értéke figyelmen kívül van hagyva |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) function

A nem-egyenlő összehasonlítás dobozolható [SmartPtr](../../system/smartptr/) értékekkel unboxing használatával.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | LHS value. |
| rhs | T | RHS value. |
| s | long long | Egy szolgáltatási paraméter, amely a függvény megvalósításának kiválasztójaként szolgál; a paraméter értéke figyelmen kívül van hagyva |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, std::nullptr_t, long long) function

A nem-egyenlő összehasonlítás véletlenszerű típust hasonlít össze a nullptr értékkel.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T | LHS value. |
| s | std::nullptr_t | Egy szolgáltatási paraméter, amely a függvény megvalósításának kiválasztójaként szolgál; a paraméter értéke figyelmen kívül van hagyva |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, std::nullptr_t, T, long long) function

A nem-egyenlő összehasonlítás véletlenszerű típust hasonlít össze a nullptr értékkel.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| rhs | std::nullptr_t | RHS value. |
| s | T | Egy szolgáltatási paraméter, amely a függvény megvalósításának kiválasztójaként szolgál; a paraméter értéke figyelmen kívül van hagyva |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

Az egyenlő-összehasonlítás mutatótípusokat végez.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1\& | LHS value. |
| rhs | const T2\& | RHS value. |
| s | long long | Egy szolgáltatási paraméter, amely a függvény megvalósításának kiválasztójaként szolgál; a paraméter értéke figyelmen kívül van hagyva |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T1, T2, int) function

Az egyenlő-összehasonlítás véletlenszerű típusokat használ a gtest algoritmusokkal.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T1 | LHS value. |
| rhs | T2 | RHS value. |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## Lásd még

* Típusdefiníció [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Típusdefiníció [SharedPtr](../../system/sharedptr/)
* Osztály [Object](../../system/object/)
* Struktúra [IsSmartPtr](../../system/issmartptr/)
* Struktúra [IsBoxable](../../system/isboxable/)
* Névtér [System::TestPredicates](../)
* Könyvtár [Aspose.Slides](../../)
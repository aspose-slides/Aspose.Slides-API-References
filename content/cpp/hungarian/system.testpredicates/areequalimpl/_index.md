---
title: AreEqualImpl()
second_title: Aspose.Slides C++ API referencia
description: Egyenlőség-összehasonlítja a lebegőpontos típusokat aritmetikai típusokkal.
type: docs
weight: 27
url: /hu/system.testpredicates/areequalimpl/
---
## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1, const T2, long long) függvény


Egyenlőség-összehasonlítás lebegőpontos és aritmetikai típusok között.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AreFPandArithmetic<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 lhs, const T2 rhs, long long s)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | LHS object type. |
| T2 | RHS object type. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1 | LHS value. |
| rhs | const T2 | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) függvény


Értékeket hasonlít össze, amelyek egyike vagy mindkettő [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | LHS object type. |
| T2 | RHS object type. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1\& | LHS value. |
| rhs | const T2\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) függvény


Pointer nélküli típusokat hasonlít össze a biztosított Equals metódus használatával.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T\& | LHS value. |
| rhs | const T\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T\&, const T\&, long long) függvény


Pointer nélküli típusokat hasonlít össze a biztosított Equals metódus használatával.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T\& | LHS value. |
| rhs | const T\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) függvény


Pointer nélküli típusokat hasonlít össze az operator == használatával.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T\& | LHS value. |
| rhs | const T\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) függvény


Boxolható típusokat hasonlít össze [SmartPtr](../../system/smartptr/) értékekkel.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T | LHS value. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) függvény


Boxolható típusokat hasonlít össze [SmartPtr](../../system/smartptr/) értékekkel.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | LHS value. |
| rhs | T | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const char16_t *, const System::SharedPtr\<Object\>\&, long long) függvény


Karakterlánc literált hasonlít össze [SmartPtr](../../system/smartptr/) értékekkel az unboxing használatával.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const char16_t *lhs, const System::SharedPtr<Object> &rhs, long long s)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const char16_t * | LHS value. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, const char16_t *, long long) függvény


Karakterlánc literált hasonlít össze [SmartPtr](../../system/smartptr/) értékekkel az unboxing használatával.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, const char16_t *rhs, long long s)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | LHS value. |
| rhs | const char16_t * | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, std::nullptr_t, long long) függvény


Véletlenszerű típust hasonlít össze nullptr értékkel.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T | LHS value. |
| s | std::nullptr_t | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## System::TestPredicates::AreEqualImpl(const char *, const char *, std::nullptr_t, T, long long) függvény


Véletlenszerű típust hasonlít össze nullptr értékkel.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| rhs | std::nullptr_t | RHS value. |
| s | T | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) függvény


Pointer típusokat hasonlít össze.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&(!std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value||!std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1\& | LHS value. |
| rhs | const T2\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) függvény


Pointer típusokat hasonlít össze.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value &&std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1\& | LHS value. |
| rhs | const T2\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, const Nullable\<T2\>\&, long long) függvény


Véletlenszerű típust hasonlít össze egy [Nullable](../../system/nullable/) értékkel.

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T1>::value &&!IsNullable<T1>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, const Nullable<T2> &rhs, long long s)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T1 | LHS value. |
| rhs | const [Nullable](../../system/nullable/)\<T2\>\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const Nullable\<T1\>\&, T2, long long) függvény


[Nullable](../../system/nullable/) értéket hasonlít össze egy véletlenszerű típussal.

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T2>::value &&!IsNullable<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const Nullable<T1> &lhs, T2 rhs, long long s)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const [Nullable](../../system/nullable/)\<T1\>\& | LHS value. |
| rhs | T2 | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, T2, int) függvény


Véletlenszerű típusokat hasonlít össze a gtest algoritmusok használatával.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T1 | LHS value. |
| rhs | T2 | RHS value. |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) függvény


Két [System::String](../../system/string/) értéket hasonlít össze, megakadályozva egy tagfüggvény hívását egy null [String](../../system/string/) esetén. Sablonos (ahelyett, hogy egy egyszerű overload lenne, amely const [String](../../system/string/)&-t vesz), hogy a vegyes típusú hívások – például egy char16_t karakterlánc literál összehasonlítása egy [String](../../system/string/)-val – ne tudjanak egyetlen konzisztens T-t levezetni, és teljesen kizárják ezt a jelöltet a hosszú long long/int selector paraméterrel ellátott általános AreEqualImpl<T1,T2> sablon helyett, elkerülve az ambivalens overload feloldást.

```cpp
template<typename T> std::enable_if<std::is_same<T, System::String>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Object](../../system/object/) type, constrained to [System::String](../../system/string/). |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T\& | LHS value. |
| rhs | const T\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## Lásd még

* Typedef [AreFPandArithmetic](../../system.testpredicates.typetraits/arefpandarithmetic/)
* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Osztály [String](../../system/string/)
* Osztály [Object](../../system/object/)
* Osztály [Stream](../../system.io/stream/)
* Osztály [Nullable](../../system/nullable/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsBoxable](../../system/isboxable/)
* Struct [IsStringByteSequence](../../system/isstringbytesequence/)
* Struct [IsNullable](../../system/isnullable/)
* Névtér [System::TestPredicates](../)
* Library [Aspose.Slides](../../)
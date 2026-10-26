---
title: AreNotEqualImpl()
second_title: Aspose.Slides C++ API referencia
description: A nem-egyenlő összehasonlítás értékeket végez, ha az egyik vagy mindkettő Decimal típusú.
type: docs
weight: 53
url: /hu/system.testpredicates/arenotequalimpl/
---
## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) függvény


A nem-egyenlő összehasonlítás olyan értékek esetén, amikor az egyik vagy mindkettő [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | LHS object type. |
| T2 | RHS object type. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Baloldali kifejezés. |
| rhs_expr | const char * | Jobboldali kifejezés. |
| lhs | const T1\& | Baloldali érték. |
| rhs | const T2\& | Jobboldali érték. |
| s | long long | Egy szolgáltatási paraméter, amely a függvény implementációjának kiválasztására szolgál; a paraméter értéke figyelmen kívül marad |

### Visszatérési érték

gtest-stílusú állítás eredmény.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) függvény


A nem-egyenlő összehasonlítás két [System::String](../../system/string/) értéket, megakadályozva egy tagfüggvény meghívását egy null [String](../../system/string/) objektumon. Sablonosítva ugyanazokkal a deduktió-alapú kizárási okokkal, mint a fenti AreEqualImpl [String](../../system/string/) túlterhelés.

```cpp
template<typename T> std::enable_if<std::is_same<T, System::String>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Object](../../system/object/) típus, korlátozva [System::String](../../system/string/)-ra. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Baloldali kifejezés. |
| rhs_expr | const char * | Jobboldali kifejezés. |
| lhs | const T\& | Baloldali érték. |
| rhs | const T\& | Jobboldali érték. |
| s | long long | Egy szolgáltatási paraméter, amely a függvény implementációjának kiválasztására szolgál; a paraméter értéke figyelmen kívül marad |

### Visszatérési érték

gtest-stílusú állítás eredmény.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) függvény


A nem-egyenlő összehasonlítás a nem-mutató típusokat a biztosított Equals metódus segítségével hajtja végre.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Object](../../system/object/) típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Baloldali kifejezés. |
| rhs_expr | const char * | Jobboldali kifejezés. |
| lhs | const T\& | Baloldali érték. |
| rhs | const T\& | Jobboldali érték. |
| s | long long | Egy szolgáltatási paraméter, amely a függvény implementációjának kiválasztására szolgál; a paraméter értéke figyelmen kívül marad |

### Visszatérési érték

gtest-stílusú állítás eredmény.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T\&, const T\&, long long) függvény


A nem-egyenlő összehasonlítás a nem-mutató típusokat a biztosított Equals metódus segítségével hajtja végre.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Object](../../system/object/) típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Baloldali kifejezés. |
| rhs_expr | const char * | Jobboldali kifejezés. |
| lhs | T\& | Baloldali érték. |
| rhs | const T\& | Jobboldali érték. |
| s | long long | Egy szolgáltatási paraméter, amely a függvény implementációjának kiválasztására szolgál; a paraméter értéke figyelmen kívül marad |

### Visszatérési érték

gtest-stílusú állítás eredmény.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) függvény


A nem-egyenlő összehasonlítás a nem-mutató típusokat a != operátor segítségével hajtja végre.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Object](../../system/object/) típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Baloldali kifejezés. |
| rhs_expr | const char * | Jobboldali kifejezés. |
| lhs | const T\& | Baloldali érték. |
| rhs | const T\& | Jobboldali érték. |
| s | long long | Egy szolgáltatási paraméter, amely a függvény implementációjának kiválasztására szolgál; a paraméter értéke figyelmen kívül marad |

### Visszatérési érték

gtest-stílusú állítás eredmény.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) függvény


A nem-egyenlő összehasonlítás a becsomagolható [SmartPtr](../../system/smartptr/) értékeket unwrap-eléssel hajtja végre.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Object](../../system/object/) típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Baloldali kifejezés. |
| rhs_expr | const char * | Jobboldali kifejezés. |
| lhs | T | Baloldali érték. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Jobboldali érték. |
| s | long long | Egy szolgáltatási paraméter, amely a függvény implementációjának kiválasztására szolgál; a paraméter értéke figyelmen kívül marad |

### Visszatérési érték

gtest-stílusú állítás eredmény.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) függvény


A nem-egyenlő összehasonlítás a becsomagolható [SmartPtr](../../system/smartptr/) értékeket unwrap-eléssel hajtja végre.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Object](../../system/object/) típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Baloldali kifejezés. |
| rhs_expr | const char * | Jobboldali kifejezés. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Baloldali érték. |
| rhs | T | Jobboldali érték. |
| s | long long | Egy szolgáltatási paraméter, amely a függvény implementációjának kiválasztására szolgál; a paraméter értéke figyelmen kívül marad |

### Visszatérési érték

gtest-stílusú állítás eredmény.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, std::nullptr_t, long long) függvény


A nem-egyenlő összehasonlítás tetszőleges típust a nullptr-al végzi.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Object](../../system/object/) típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Baloldali kifejezés. |
| rhs_expr | const char * | Jobboldali kifejezés. |
| lhs | T | Baloldali érték. |
| s | std::nullptr_t | Egy szolgáltatási paraméter, amely a függvény implementációjának kiválasztására szolgál; a paraméter értéke figyelmen kívül marad |

### Visszatérési érték

gtest-stílusú állítás eredmény.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, std::nullptr_t, T, long long) függvény


A nem-egyenlő összehasonlítás tetszőleges típust a nullptr-al végzi.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Object](../../system/object/) típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Baloldali kifejezés. |
| rhs_expr | const char * | Jobboldali kifejezés. |
| rhs | std::nullptr_t | Jobboldali érték. |
| s | T | Egy szolgáltatási paraméter, amely a függvény implementációjának kiválasztására szolgál; a paraméter értéke figyelmen kívül marad |

### Visszatérési érték

gtest-stílusú állítás eredmény.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) függvény


Egyenlő-összehasonlítja a mutató típusokat.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Baloldali kifejezés. |
| rhs_expr | const char * | Jobboldali kifejezés. |
| lhs | const T1\& | Baloldali érték. |
| rhs | const T2\& | Jobboldali érték. |
| s | long long | Egy szolgáltatási paraméter, amely a függvény implementációjának kiválasztására szolgál; a paraméter értéke figyelmen kívül marad |

### Visszatérési érték

gtest-stílusú állítás eredmény.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T1, T2, int) függvény


Egyenlő-összehasonlítja a tetszőleges típusokat a gtest algoritmusokkal.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Baloldali kifejezés. |
| rhs_expr | const char * | Jobboldali kifejezés. |
| lhs | T1 | Baloldali érték. |
| rhs | T2 | Jobboldali érték. |

### Visszatérési érték

gtest-stílusú állítás eredmény.

## Lásd még

* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [String](../../system/string/)
* Class [Object](../../system/object/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsBoxable](../../system/isboxable/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)
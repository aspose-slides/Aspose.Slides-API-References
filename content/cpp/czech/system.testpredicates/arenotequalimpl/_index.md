---
title: AreNotEqualImpl()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Porovnává nerovnost hodnot, přičemž jedna nebo obě jsou desetinné.
type: docs
weight: 53
url: /cs/system.testpredicates/arenotequalimpl/
---
## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) funkce

Porovnává nerovnost hodnot, kdy jedna nebo obě jsou [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ objektu vlevo (LHS). |
| T2 | Typ objektu vpravo (RHS). |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | Výraz vlevo (LHS). |
| rhs_expr | const char * | Výraz vpravo (RHS). |
| lhs | const T1\& | Hodnota vlevo (LHS). |
| rhs | const T2\& | Hodnota vpravo (RHS). |
| s | long long | Parametr služby, který slouží jako selektor implementace funkce; hodnota parametru je ignorována |

### Návratová hodnota

Výsledek tvrzení ve stylu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) funkce

Porovnává nerovnost dvou [System::String](../../system/string/) hodnot, chrání před voláním členské funkce na nulovém [String](../../system/string/). Šablonová pro stejné důvody vyloučení založené na dedukci jako přetížení AreEqualImpl [String](../../system/string/) výše.

```cpp
template<typename T> std::enable_if<std::is_same<T, System::String>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Object](../../system/object/) typ, omezený na [System::String](../../system/string/). |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | Výraz vlevo (LHS). |
| rhs_expr | const char * | Výraz vpravo (RHS). |
| lhs | const T\& | Hodnota vlevo (LHS). |
| rhs | const T\& | Hodnota vpravo (RHS). |
| s | long long | Parametr služby, který slouží jako selektor implementace funkce; hodnota parametru je ignorována |

### Návratová hodnota

Výsledek tvrzení ve stylu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) funkce

Porovnává nerovnost neukazatelových typů pomocí poskytované metody Equals.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | Výraz vlevo (LHS). |
| rhs_expr | const char * | Výraz vpravo (RHS). |
| lhs | const T\& | Hodnota vlevo (LHS). |
| rhs | const T\& | Hodnota vpravo (RHS). |
| s | long long | Parametr služby, který slouží jako selektor implementace funkce; hodnota parametru je ignorována |

### Návratová hodnota

Výsledek tvrzení ve stylu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T\&, const T\&, long long) funkce

Porovnává nerovnost neukazatelových typů pomocí poskytované metody Equals.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | Výraz vlevo (LHS). |
| rhs_expr | const char * | Výraz vpravo (RHS). |
| lhs | T\& | Hodnota vlevo (LHS). |
| rhs | const T\& | Hodnota vpravo (RHS). |
| s | long long | Parametr služby, který slouží jako selektor implementace funkce; hodnota parametru je ignorována |

### Návratová hodnota

Výsledek tvrzení ve stylu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) funkce

Porovnává nerovnost neukazatelových typů pomocí operátoru !=.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | Výraz vlevo (LHS). |
| rhs_expr | const char * | Výraz vpravo (RHS). |
| lhs | const T\& | Hodnota vlevo (LHS). |
| rhs | const T\& | Hodnota vpravo (RHS). |
| s | long long | Parametr služby, který slouží jako selektor implementace funkce; hodnota parametru je ignorována |

### Návratová hodnota

Výsledek tvrzení ve stylu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) funkce

Porovnává nerovnost typů, které lze zabalit, s hodnotami [SmartPtr](../../system/smartptr/) pomocí rozbalení (unboxing).

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | Výraz vlevo (LHS). |
| rhs_expr | const char * | Výraz vpravo (RHS). |
| lhs | T | Hodnota vlevo (LHS). |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Hodnota vpravo (RHS). |
| s | long long | Parametr služby, který slouží jako selektor implementace funkce; hodnota parametru je ignorována |

### Návratová hodnota

Výsledek tvrzení ve stylu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) funkce

Porovnává nerovnost typů, které lze zabalit, s hodnotami [SmartPtr](../../system/smartptr/) pomocí rozbalení (unboxing).

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | Výraz vlevo (LHS). |
| rhs_expr | const char * | Výraz vpravo (RHS). |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Hodnota vlevo (LHS). |
| rhs | T | Hodnota vpravo (RHS). |
| s | long long | Parametr služby, který slouží jako selektor implementace funkce; hodnota parametru je ignorována |

### Návratová hodnota

Výsledek tvrzení ve stylu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, std::nullptr_t, long long) funkce

Porovnává nerovnost náhodného typu s nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | Výraz vlevo (LHS). |
| rhs_expr | const char * | Výraz vpravo (RHS). |
| lhs | T | Hodnota vlevo (LHS). |
| s | std::nullptr_t | Parametr služby, který slouží jako selektor implementace funkce; hodnota parametru je ignorována |

### Návratová hodnota

Výsledek tvrzení ve stylu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, std::nullptr_t, T, long long) funkce

Porovnává nerovnost náhodného typu s nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | Výraz vlevo (LHS). |
| rhs_expr | const char * | Výraz vpravo (RHS). |
| rhs | std::nullptr_t | Hodnota vpravo (RHS). |
| s | T | Parametr služby, který slouží jako selektor implementace funkce; hodnota parametru je ignorována |

### Návratová hodnota

Výsledek tvrzení ve stylu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) funkce

Porovnává rovnost ukazatelových typů.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ vlevo (LHS). |
| T2 | Typ vpravo (RHS). |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | Výraz vlevo (LHS). |
| rhs_expr | const char * | Výraz vpravo (RHS). |
| lhs | const T1\& | Hodnota vlevo (LHS). |
| rhs | const T2\& | Hodnota vpravo (RHS). |
| s | long long | Parametr služby, který slouží jako selektor implementace funkce; hodnota parametru je ignorována |

### Návratová hodnota

Výsledek tvrzení ve stylu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T1, T2, int) funkce

Porovnává rovnost náhodných typů pomocí algoritmů gtest.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ vlevo (LHS). |
| T2 | Typ vpravo (RHS). |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | Výraz vlevo (LHS). |
| rhs_expr | const char * | Výraz vpravo (RHS). |
| lhs | T1 | Hodnota vlevo (LHS). |
| rhs | T2 | Hodnota vpravo (RHS). |

### Návratová hodnota

Výsledek tvrzení ve stylu gtest.

## Viz také

* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Třída [String](../../system/string/)
* Třída [Object](../../system/object/)
* Struktura [IsSmartPtr](../../system/issmartptr/)
* Struktura [IsBoxable](../../system/isboxable/)
* Jmenný prostor [System::TestPredicates](../)
* Knihovna [Aspose.Slides](../../)
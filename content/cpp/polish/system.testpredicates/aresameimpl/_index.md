---
title: AreSameImpl()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Are-same porównuje inteligentne wskaźniki.
type: docs
weight: 79
url: /pl/system.testpredicates/aresameimpl/
---
## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, long long) function

Are-same porównuje inteligentne wskaźniki.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Typ obiektu LHS. |
| T2 | Typ obiektu RHS. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs_expr | const char * | Wyrażenie LHS. |
| rhs_expr | const char * | Wyrażenie RHS. |
| lhs | const T1\& | Wartość LHS. |
| rhs | const T2\& | Wartość RHS. |
| s | long long | Parametr serwisowy służący jako selektor implementacji funkcji; wartość tego parametru jest pomijana |

### Wartość zwracana

Wynik asercji w stylu gtest.

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, long long) function

Are-same porównuje wyjątki.

```cpp
template<typename T1,typename T2> std::enable_if<IsExceptionWrapper<T1>::value &&IsExceptionWrapper<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Typ obiektu LHS. |
| T2 | Typ obiektu RHS. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs_expr | const char * | Wyrażenie LHS. |
| rhs_expr | const char * | Wyrażenie RHS. |
| lhs | const T1\& | Wartość LHS. |
| rhs | const T2\& | Wartość RHS. |
| s | long long | Parametr serwisowy służący jako selektor implementacji funkcji; wartość tego parametru jest pomijana |

### Wartość zwracana

Wynik asercji w stylu gtest.

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, int) function

Are-same porównuje wartości niebędące wskaźnikami.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Typ obiektu LHS. |
| T2 | Typ obiektu RHS. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs_expr | const char * | Wyrażenie LHS. |
| rhs_expr | const char * | Wyrażenie RHS. |
| lhs | const T1\& | Wartość LHS. |
| rhs | const T2\& | Wartość RHS. |

### Wartość zwracana

Wynik asercji w stylu gtest.

## Zobacz także

* Struktura [IsSmartPtr](../../system/issmartptr/)
* Struktura [IsExceptionWrapper](../../system/isexceptionwrapper/)
* Przestrzeń nazw [System::TestPredicates](../)
* Biblioteka [Aspose.Slides](../../)
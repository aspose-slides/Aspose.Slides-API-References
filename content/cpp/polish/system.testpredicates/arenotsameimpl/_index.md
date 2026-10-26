---
title: AreNotSameImpl()
second_title: Aspose.Slides dla C++ – Referencja API
description: Are-not-same porównuje inteligentne wskaźniki.
type: docs
weight: 105
url: /pl/system.testpredicates/arenotsameimpl/
---
## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1\&, const T2\&, long long) funkcja


Are-not-same porównuje inteligentne wskaźniki.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
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
| s | long long | Parametr serwisowy służący jako selektor implementacji funkcji; wartość tego parametru jest ignorowana |

### Wartość zwracana

Wynik asercji w stylu gtest.

## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1\&, const T2\&, int) funkcja


Are-not-same porównuje wartości niebędące wskaźnikami.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
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
* Przestrzeń nazw [System::TestPredicates](../)
* Biblioteka [Aspose.Slides](../../)
---
title: AreNotSame()
second_title: Aspose.Slides dla dokumentacji API C++
description: Are-not-same porównuje argumenty dla asercji AreSame.
type: docs
weight: 92
url: /pl/system.testpredicates/arenotsame/
---
## System::TestPredicates::AreNotSame(const char *, const char *, const T1\&, const T2\&) funkcja

Are-not-same porównuje argumenty dla asercji AreSame tłumaczenie.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSame(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
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

gtest-styled assertion result.

## Zobacz także

* Przestrzeń nazw [System::TestPredicates](../)
* Biblioteka [Aspose.Slides](../../)
---
title: AreSame()
second_title: Aspose.Slides dla API C++
description: Are-same porównuje argumenty dla asercji AreSame.
type: docs
weight: 66
url: /pl/system.testpredicates/aresame/
---
## System::TestPredicates::AreSame(const char *, const char *, const T1\&, const T2\&) funkcja

Are-same porównuje argumenty dla asercji AreSame.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreSame(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
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

### Wartość zwracana

wynik asercji w stylu gtest.

## Zobacz także

* Przestrzeń nazw [System::TestPredicates](../)
* Biblioteka [Aspose.Slides](../../)
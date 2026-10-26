---
title: NotEqFailure()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Formatuje niepowodzenie asercji != dla wyjścia.
type: docs
weight: 40
url: /pl/system.testpredicates.details/noteqfailure/
---
## System::TestPredicates::Details::NotEqFailure(const char *, const char *, T1\&, T2\&) funkcja


Formatuje niepowodzenie asercji != dla wyjścia.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::NotEqFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Typ wartości LHS. |
| T2 | Typ wartości RHS. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs_expr | const char * | Wyrażenie LHS. |
| rhs_expr | const char * | Wyrażenie RHS. |
| lhs | T1\& | Wartość LHS. |
| rhs | T2\& | Wartość RHS. |

### Wartość zwracana

[Object](../../system/object/) zawijający tekst niepowodzenia.

## Zobacz także

* Przestrzeń nazw [System::TestPredicates::Details](../)
* Biblioteka [Aspose.Slides](../../)
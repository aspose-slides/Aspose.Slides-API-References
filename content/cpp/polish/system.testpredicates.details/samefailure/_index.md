---
title: SameFailure()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Formatuje niepowodzenie asercji 'same' dla wyjścia.
type: docs
weight: 53
url: /pl/system.testpredicates.details/samefailure/
---
## System::TestPredicates::Details::SameFailure(const char *, const char *, T1\&, T2\&) funkcja


Formatuje niepowodzenie asercji 'same' dla wyjścia.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SameFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
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

[Object](../../system/object/) opakowujący tekst niepowodzenia.

## Zobacz także

* Przestrzeń nazw [System::TestPredicates::Details](../)
* Library [Aspose.Slides](../../)
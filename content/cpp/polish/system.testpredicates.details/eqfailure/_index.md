---
title: EqFailure()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Formatuje niepowodzenie asercji == dla wyjścia.
type: docs
weight: 27
url: /pl/system.testpredicates.details/eqfailure/
---
## System::TestPredicates::Details::EqFailure(const char *, const char *, T1\&, T2\&) funkcja


Formatuje niepowodzenie asercji == dla wyjścia.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::EqFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | LHS value type. |
| T2 | RHS value type. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T1\& | LHS value. |
| rhs | T2\& | RHS value. |

### Wartość zwracana

[Object](../../system/object/) opakowujący tekst niepowodzenia.

## Zobacz także

* Przestrzeń nazw [System::TestPredicates::Details](../)
* Biblioteka [Aspose.Slides](../../)
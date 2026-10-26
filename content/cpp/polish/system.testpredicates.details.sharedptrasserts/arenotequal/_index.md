---
title: AreNotEqual()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Porównuje nierówne argumenty dla asercji AreNotEqual.
type: docs
weight: 131
url: /pl/system.testpredicates.details.sharedptrasserts/arenotequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreNotEqual(const char *, const char *, const T1\&, const T2\&) funkcja

Porównuje nierówne argumenty dla asercji AreNotEqual.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::AreNotEqual(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
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

* Przestrzeń nazw [System::TestPredicates::Details::SharedPtrAsserts](../)
* Biblioteka [Aspose.Slides](../../)
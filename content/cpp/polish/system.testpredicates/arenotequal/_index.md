---
title: AreNotEqual()
second_title: Aspose.Slides dla C++ – referencja API
description: Porównuje nierówność argumentów w tłumaczeniu asercji AreEqual.
type: docs
weight: 40
url: /pl/system.testpredicates/arenotequal/
---
## System::TestPredicates::AreNotEqual(const char *, const char *, T1\&&, T2\&&) funkcja

Porównuje nierówność argumentów dla tłumaczenia asercji AreEqual.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqual(const char *lhs_expr, const char *rhs_expr, T1 &&lhs, T2 &&rhs)
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
| lhs | T1\&& | Wartość LHS. |
| rhs | T2\&& | Wartość RHS. |

### Wartość zwracana

Wynik asercji w stylu gtest.

## Zobacz także

* Przestrzeń nazw [System::TestPredicates](../)
* Biblioteka [Aspose.Slides](../../)
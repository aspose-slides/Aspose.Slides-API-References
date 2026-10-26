---
title: AreEqual()
second_title: Odwołanie API Aspose.Slides dla C++
description: Porównuje argumenty pod kątem równości dla asercji AreEqual.
type: docs
weight: 14
url: /pl/system.testpredicates/areequal/
---
## System::TestPredicates::AreEqual(const char *, const char *, T1\&&, T2\&&) funkcja

Porównuje argumenty pod kątem równości dla asercji AreEqual.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqual(const char *lhs_expr, const char *rhs_expr, T1 &&lhs, T2 &&rhs)
```

### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T1 | Typ obiektu po lewej stronie. |
| T2 | Typ obiektu po prawej stronie. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Wyrażenie po lewej stronie. |
| rhs_expr | const char * | Wyrażenie po prawej stronie. |
| lhs | T1\&& | Wartość po lewej stronie. |
| rhs | T2\&& | Wartość po prawej stronie. |

### Wartość zwracana

Wynik asercji w stylu gtest.

## Zobacz także

* przestrzeń nazw [System::TestPredicates](../)
* biblioteka [Aspose.Slides](../../)
---
title: AreEqual()
second_title: Aspose.Slides dla C++ - referencja API
description: Porównuje argumenty pod kątem równości dla asercji AreEqual.
type: docs
weight: 92
url: /pl/system.testpredicates.details.sharedptrasserts/areequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqual(const char *, const char *, const T1\&, const T2\&) funkcja

Porównuje argumenty pod kątem równości dla asercji AreEqual.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::AreEqual(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
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
| lhs | const T1\& | Wartość po lewej stronie. |
| rhs | const T2\& | Wartość po prawej stronie. |

### Wartość zwracana

Wynik asercji w stylu gtest.

## Zobacz także

* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)
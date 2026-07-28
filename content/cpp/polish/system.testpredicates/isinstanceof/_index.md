---
title: IsInstanceOf()
second_title: Aspose.Slides dla C++ Referencja API
description: Is-instance-of porównuje argumenty dla asercji IsInstanceOf.
type: docs
weight: 118
url: /pl/system.testpredicates/isinstanceof/
---
## System::TestPredicates::IsInstanceOf(const char *, const char *, const TypeInfo\&, const T\&) funkcja

Is-instance-of porównuje argumenty dla asercji IsInstanceOf.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::IsInstanceOf(const char *lhs_expr, const char *rhs_expr, const TypeInfo &typeInfo, const T &obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ argumentu. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs_expr | const char * | Wyrażenie LHS. |
| rhs_expr | const char * | Wyrażenie RHS. |
| typeInfo | const [TypeInfo](../../system/typeinfo/)\& | Obiekt typeInfo, który reprezentuje typ, wobec którego typ **obj** ma być porównany |
| obj | const T\& | Obiekt, którego typ ma być porównany z określonym typem |

### Wartość zwracana

Wynik asercji w stylu gtest.

## Zobacz także

* Klasa [TypeInfo](../../system/typeinfo/)
* Przestrzeń nazw [System::TestPredicates](../)
* Biblioteka [Aspose.Slides](../../)
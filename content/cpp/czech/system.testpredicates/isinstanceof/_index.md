---
title: IsInstanceOf()
second_title: Aspose.Slides pro rozhraní API C++
description: Is-instance-of porovnává argumenty pro překlad aserce IsInstanceOf.
type: docs
weight: 118
url: /cs/system.testpredicates/isinstanceof/
---
## System::TestPredicates::IsInstanceOf(const char *, const char *, const TypeInfo\&, const T\&) funkce

Is-instance-of porovnává argumenty pro překlad aserce IsInstanceOf.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::IsInstanceOf(const char *lhs_expr, const char *rhs_expr, const TypeInfo &typeInfo, const T &obj)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ argumentu. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | Výraz LHS. |
| rhs_expr | const char * | Výraz RHS. |
| typeInfo | const [TypeInfo](../../system/typeinfo/)\& | Objekt typeInfo, který představuje typ, vůči kterému se má porovnat typ **obj** |
| obj | const T\& | Objekt, jehož typ se má porovnat se zadaným typem |

### Návratová hodnota

Výsledek aserce ve stylu gtest.

## Viz také

* Třída [TypeInfo](../../system/typeinfo/)
* Jmenný prostor [System::TestPredicates](../)
* Knihovna [Aspose.Slides](../../)
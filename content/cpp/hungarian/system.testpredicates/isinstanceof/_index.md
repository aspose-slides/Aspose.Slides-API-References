---
title: IsInstanceOf()
second_title: Aspose.Slides C++ API hivatkozás
description: Az Is-instance-of összehasonlítja az argumentumokat az IsInstanceOf állítás fordításához.
type: docs
weight: 118
url: /hu/system.testpredicates/isinstanceof/
---
## System::TestPredicates::IsInstanceOf(const char *, const char *, const TypeInfo\&, const T\&) függvény

Az Is-instance-of összehasonlítja az argumentumokat az IsInstanceOf állítás fordításához.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::IsInstanceOf(const char *lhs_expr, const char *rhs_expr, const TypeInfo &typeInfo, const T &obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Argument type. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Bal oldal kifejezés. |
| rhs_expr | const char * | Jobb oldal kifejezés. |
| typeInfo | const [TypeInfo](../../system/typeinfo/)\& | Egy typeInfo objektum, amely egy típust képvisel, amelyhez a **obj** típusa összehasonlítandó |
| obj | const T\& | Egy objektum, amelynek típusát a megadott típussal kell összehasonlítani |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## Lásd még

* Osztály [TypeInfo](../../system/typeinfo/)
* Névterület [System::TestPredicates](../)
* Könyvtár [Aspose.Slides](../../)
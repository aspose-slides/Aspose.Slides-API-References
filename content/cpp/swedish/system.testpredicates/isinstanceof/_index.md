---
title: IsInstanceOf()
second_title: Aspose.Slides för C++ API-referens
description: Is-instance-of jämför argument för IsInstanceOf-assertionens översättning.
type: docs
weight: 118
url: /sv/system.testpredicates/isinstanceof/
---
## System::TestPredicates::IsInstanceOf(const char *, const char *, const TypeInfo\&, const T\&) funktion

Is-instance-of jämför argument för IsInstanceOf-assertionens översättning.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::IsInstanceOf(const char *lhs_expr, const char *rhs_expr, const TypeInfo &typeInfo, const T &obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Argumenttyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | LHS-uttryck. |
| rhs_expr | const char * | RHS-uttryck. |
| typeInfo | const [TypeInfo](../../system/typeinfo/)\& | Ett typeInfo-objekt som representerar en typ som typen för **obj** ska jämföras med |
| obj | const T\& | Ett objekt vars typ ska jämföras med den angivna typen |

### Returvärde

gtest-stilat påståenderesultat.

## Se också

* Klass [TypeInfo](../../system/typeinfo/)
* Namnrymd [System::TestPredicates](../)
* Bibliotek [Aspose.Slides](../../)
---
title: IsInstanceOf()
second_title: Aspose.Slides voor C++ API-referentie
description: Is-instance-of vergelijkt argumenten voor de vertaling van de IsInstanceOf-assertie.
type: docs
weight: 118
url: /nl/system.testpredicates/isinstanceof/
---
## System::TestPredicates::IsInstanceOf(const char *, const char *, const TypeInfo\&, const T\&) function


Is-instance-of vergelijkt argumenten voor de vertaling van de IsInstanceOf-assertie.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::IsInstanceOf(const char *lhs_expr, const char *rhs_expr, const TypeInfo &typeInfo, const T &obj)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Argumenttype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs_expr | const char * | LHS-expressie. |
| rhs_expr | const char * | RHS-expressie. |
| typeInfo | const [TypeInfo](../../system/typeinfo/)\& | Een typeInfo-object dat een type vertegenwoordigt waarmee het type van **obj** moet worden vergeleken |
| obj | const T\& | Een object waarvan het type moet worden vergeleken met het opgegeven type |

### Retourwaarde

gtest-gestileerd assertieresultaat.

## Zie ook

* Klasse [TypeInfo](../../system/typeinfo/)
* Naamruimte [System::TestPredicates](../)
* Bibliotheek [Aspose.Slides](../../)
---
title: CoalesceAssign()
second_title: Aspose.Slides voor C++ API-referentie
description: Implementatie van de vertaling van de '??=' operator.
type: docs
weight: 183
url: /nl/system/objectext/coalesceassign/
---
## ObjectExt::CoalesceAssign(T0\&, T1) methode

Implementatie van de vertaling van de '??=' operator.

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::CoalesceAssign(T0 &value, T1 func) -> T0 &
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T0 | Type van de LHS-waarde. |
| T1 | Type van lambda die de RHS-expressie encapsuleert. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | T0\& | LHS-waarde. |
| func | T1 | RHS-expressie. |

### Retourwaarde

Als de LHS-waarde niet null is, wordt de LHS geretourneerd; anders wordt de RHS-expressie berekend en het resultaat geretourneerd.

## Zie ook

* Klasse [ObjectExt](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)
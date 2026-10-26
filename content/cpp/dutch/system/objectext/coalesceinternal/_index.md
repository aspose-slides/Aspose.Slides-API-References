---
title: CoalesceInternal()
second_title: Aspose.Slides voor C++ API Referentie
description: Implementatie van de '??'-operatorvertaling voor niet-nullbare types. Overbelasting voor het geval dat RT2 converteerbaar is naar RT1.
type: docs
weight: 157
url: /nl/system/objectext/coalesceinternal/
---
## ObjectExt::CoalesceInternal(RT1, F) methode

Implementatie van de '??'-operatorvertaling voor niet-nullbare types. Overbelasting voor het geval dat RT2 converteerbaar is naar RT1.

```cpp
template<typename RT1,typename RT2,typename F> static std::conditional<std::is_convertible<RT2, RT1>::value, RT1, RT2>::type System::ObjectExt::CoalesceInternal(RT1 value, F func)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T0 | LHS-waarde type. |
| T1 | Type van lambda die RHS-expressie encapsuleert. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | RT1 | LHS-waarde. |
| func | F | RHS-expressie. |

### Retourwaarde

Als de LHS-waarde niet null is, wordt de LHS geretourneerd, anders wordt de RHS-expressie berekend en wordt het resultaat geretourneerd.

## Zie ook

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
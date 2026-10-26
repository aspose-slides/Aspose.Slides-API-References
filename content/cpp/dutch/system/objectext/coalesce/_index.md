---
title: Coalesce()
second_title: Aspose.Slides voor C++ API-referentie
description: Implementatie van de vertaling van de '??' operator voor niet-nullbare types.
type: docs
weight: 170
url: /nl/system/objectext/coalesce/
---
## ObjectExt::Coalesce(T0, T1) methode


Implementatie van de '??' operatorvertaling voor niet-nullbare types.

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::Coalesce(T0 value, T1 func)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T0 | LHS-waarde type. |
| T1 | Type van lambda dat de RHS-expressie omsluit. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | T0 | LHS-waarde. |
| func | T1 | RHS-expressie. |

### Retourwaarde

Als LHS-waarde niet null is, wordt LHS geretourneerd, anders wordt de RHS-expressie berekend en het resultaat geretourneerd.

## ObjectExt::Coalesce(System::Nullable\<T0\>, T1) methode


Implementatie van de '??' operatorvertaling voor nullable typen.

```cpp
template<typename T0,typename T1> static T0 System::ObjectExt::Coalesce(System::Nullable<T0> value, T1 func)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T0 | LHS-waarde type. |
| T1 | Type van lambda dat de RHS-expressie omsluit. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [System::Nullable](../../nullable/)\<T0\> | LHS-waarde. |
| func | T1 | RHS-expressie. |

### Retourwaarde

Als LHS-waarde niet null is, wordt LHS geretourneerd, anders wordt de RHS-expressie berekend en het resultaat geretourneerd.

## Zie ook

* Klasse [ObjectExt](../)
* Klasse [Nullable](../../nullable/)
* Namespace [System](../../)
* Bibliotheek [Aspose.Slides](../../../)
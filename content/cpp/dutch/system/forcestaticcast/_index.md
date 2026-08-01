---
title: ForceStaticCast()
second_title: Aspose.Slides voor C++ API-referentie
description: Voert een echte statische cast uit op SmartPtr-objecten.
type: docs
weight: 2588
url: /nl/system/forcestaticcast/
---
## System::ForceStaticCast(SmartPtr\<TFrom\> const\&) functie

Voert een echte statische cast uit op [SmartPtr](../smartptr/) objecten.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ForceStaticCast(SmartPtr<TFrom> const &obj)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TTo | Doel-pointee type. |
| TFrom | Bron-pointee type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Bron-pointer. |

### Retourwaarde

Het castresultaat indien de cast is toegestaan, anders is het gedrag ongedefinieerd.

## Zie ook

* Klasse [SmartPtr](../smartptr/)
* Struct [CastResult](../castresult/)
* Namespace [System](../)
* Bibliotheek [Aspose.Slides](../../)
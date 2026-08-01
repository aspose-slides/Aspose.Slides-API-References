---
title: Cast()
second_title: Aspose.Slides voor C++ API-referentie
description: Voert cast uit op SmartPtr-objecten.
type: docs
weight: 2510
url: /nl/system/cast/
---
## System::Cast(SmartPtr\<TFrom\> const\&) functie

Voert cast uit op [SmartPtr](../smartptr/) objecten.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast(SmartPtr<TFrom> const &obj)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TTo | Doel-pointee-type. |
| TFrom | Bron-pointee-type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Bron-pointer. |

### Retourwaarde

Cast-resultaat indien cast is toegestaan.

## Zie ook

* Klasse [SmartPtr](../smartptr/)
* Struct [IsExceptionWrapper](../isexceptionwrapper/)
* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)
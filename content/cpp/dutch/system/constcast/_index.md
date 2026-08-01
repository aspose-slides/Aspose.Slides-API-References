---
title: ConstCast()
second_title: Aspose.Slides voor C++ API-referentie
description: Einde van verouderde casts.
type: docs
weight: 2575
url: /nl/system/constcast/
---
## System::ConstCast(const SmartPtr\<TFrom\>\&) functie

Einde van verouderde casts.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ConstCast(const SmartPtr<TFrom> &obj)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TTo | Doel-pointee type. |
| TFrom | Bron-pointee type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const [SmartPtr](../smartptr/)\<TFrom\>\& | Bronpointer. |

### Retourwaarde

Castresultaat als de cast is toegestaan, anders nullptr.

## Opmerkingen

Voert const cast uit op [SmartPtr](../smartptr/) objecten.

## Zie ook

* Klasse [SmartPtr](../smartptr/)
* Structuur [CastResult](../castresult/)
* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)
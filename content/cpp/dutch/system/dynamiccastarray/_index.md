---
title: DynamicCastArray()
second_title: Aspose.Slides voor C++ API-referentie
description: Voert een cast uit van elementen van de opgegeven array naar een ander type.
type: docs
weight: 2991
url: /nl/system/dynamiccastarray/
---
## System::DynamicCastArray(const SharedPtr\<Array\<From\>\>\&) functie


Voert een cast uit van elementen van de opgegeven array naar een ander type.

```cpp
template<class To,class From> SharedPtr<Array<To>> System::DynamicCastArray(const SharedPtr<Array<From>> &from)
```


### Sjabloonparameters

| Parameter | Description |
| --- | --- |
| To | Het type waarnaar de elementen van de opgegeven array worden gecast |
| From | Het type van de elementen van de elementen van de array waarvan gecast moet worden |

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| from | const [SharedPtr](../sharedptr/)\<[Array](../array/)\<From\>\>\& | Gedeelde pointer naar de array die de te casten elementen bevat |

### Retourwaarde

Een pointer naar een nieuwe array die elementen van type **To** bevat die equivalent zijn aan de elementen van **from**

Verouderd
:   Toegevoegd voor achterwaartse compatibiliteit. Gebruik ExplicitCast in plaats daarvan.

## Zie ook

* Typedef [SharedPtr](../sharedptr/)
* Klasse [Array](../array/)
* Namespace [System](../)
* Bibliotheek [Aspose.Slides](../../)
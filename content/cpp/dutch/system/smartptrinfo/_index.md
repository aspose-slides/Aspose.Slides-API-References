---
title: SmartPtrInfo
second_title: Aspose.Slides voor C++ API-referentie
description: Serviceklasse om de inhoud van SmartPtr te testen en te wijzigen zonder het uiteindelijke type te kennen. Gebruikt voor garbage collection en detectie van lusreferenties, enz. Beschouw het als een 'pointer naar pointer'. We kunnen de basistype van SmartPtr niet gebruiken omdat die er niet bestaat; in plaats daarvan gebruiken we deze 'info' klasse.
type: docs
weight: 1249
url: /nl/system/smartptrinfo/
---
## SmartPtrInfo klasse

Serviceklasse om de inhoud van [SmartPtr](../smartptr/) te testen en te wijzigen zonder het uiteindelijke type te kennen. Gebruikt voor garbage collection en detectie van lussendreferenties, enz. Beschouw het als een ‘pointer naar pointer’. We kunnen de basistype van [SmartPtr](../smartptr/) niet gebruiken omdat die niet bestaat; in plaats daarvan gebruiken we deze ‘info’ klasse.

```cpp
class SmartPtrInfo
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| const void * [getInternalPtr](./getinternalptr/)() const | Haalt het ruwe object op waar de verwijzende pointer naar wijst. |
| [Object](../object/) * [getObject](./getobject/)() const | Haalt het object op waar de verwijzende pointer naar wijst. |
| [Object](../object/) * [getOwned](./getowned/)() const | Haalt de eigendomspointer van het object op. |
| [operator bool](./operator_bool/)() const | Controleert of het info-object naar een niet-null pointer wijst. |
| **bool** [operator!](./operator_not/)() const | Controleert of het info-object niet naar een niet-null pointer wijst. |
| [Object](../object/) * [operator->](./operator_minus_greater/)() const | Staat toe methoden van [Object](../object/) aan te roepen die door de verwijzende pointer worden aangewezen. |
| **bool** [operator<](./operator_less/)(const [SmartPtrInfo](./)\&) const | Vergelijkt de waarden van pointers die door twee info-objecten worden verwezen met een minder-dan vergelijking. |
| [SmartPtrInfo](./smartptrinfo/)() | Maakt een leeg [SmartPtrInfo](./)-object. |
| explicit [SmartPtrInfo](./smartptrinfo/)(const [SmartPtr](../smartptr/)\<T\>\&) | Maakt een [SmartPtrInfo](./)-object met informatie over een specifieke smart pointer. |

## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)
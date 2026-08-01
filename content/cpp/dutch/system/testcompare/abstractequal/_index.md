---
title: AbstractEqual()
second_title: Aspose.Slides voor C++ API-referentie
description: Vergelijkt twee collecties van onbekend type.
type: docs
weight: 14
url: /nl/system/testcompare/abstractequal/
---
## TestCompare::AbstractEqual(SCG::ICollection\<T\> *const, SCG::ICollection\<T\> *const) methode


Vergelijkt twee collecties van onbekend type.

```cpp
template<typename T> static bool System::TestCompare::AbstractEqual(SCG::ICollection<T> *const collA, SCG::ICollection<T> *const collB)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Collectie-elementtype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| collA | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | LHS-collectie. |
| collB | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | RHS-collectie. |

### Retourwaarde

true als de collecties overeenkomen (bijv. beide zijn null), of als de groottes overeenkomen en de elementen overeenkomen, false anders.

## Zie ook

* Klasse [ICollection](../../../system.collections.generic/icollection/)
* Struct [TestCompare](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)
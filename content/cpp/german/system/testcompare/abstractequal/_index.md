---
title: AbstractEqual()
second_title: Aspose.Slides für C++ API-Referenz
description: Vergleicht zwei Sammlungen unbekannten Typs.
type: docs
weight: 14
url: /de/system/testcompare/abstractequal/
---
## TestCompare::AbstractEqual(SCG::ICollection\<T\> *const, SCG::ICollection\<T\> *const) Methode


Vergleicht zwei Sammlungen unbekannten Typs.

```cpp
template<typename T> static bool System::TestCompare::AbstractEqual(SCG::ICollection<T> *const collA, SCG::ICollection<T> *const collB)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Typ des Sammlungs-Elements. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| collA | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | LHS-Sammlung. |
| collB | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | RHS-Sammlung. |

### Rückgabewert

true, wenn die Sammlungen übereinstimmen (z. B. beide sind null), oder wenn die Größen und Elemente übereinstimmen, false sonst.

## Siehe auch

* Klasse [ICollection](../../../system.collections.generic/icollection/)
* Struktur [TestCompare](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)
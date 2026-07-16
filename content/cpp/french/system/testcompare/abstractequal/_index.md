---
title: AbstractEqual()
second_title: Référence API Aspose.Slides pour C++
description: Compare deux collections de type inconnu.
type: docs
weight: 14
url: /fr/system/testcompare/abstractequal/
---
## TestCompare::AbstractEqual(SCG::ICollection\<T\> *const, SCG::ICollection\<T\> *const) méthode

Compare deux collections de type inconnu.

```cpp
template<typename T> static bool System::TestCompare::AbstractEqual(SCG::ICollection<T> *const collA, SCG::ICollection<T> *const collB)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | type d'élément de collection. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| collA | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | collection du côté gauche. |
| collB | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | collection du côté droit. |

### Valeur de retour

true si les collections correspondent (p. ex. les deux sont null), ou si les tailles correspondent et les éléments correspondent, false sinon.

## Voir aussi

* Classe [ICollection](../../../system.collections.generic/icollection/)
* Structure [TestCompare](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)
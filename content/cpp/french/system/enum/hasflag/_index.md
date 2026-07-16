---
title: HasFlag()
second_title: Référence API Aspose.Slides pour C++
description: Détermine si les bits spécifiés sont définis dans une représentation binaire de la valeur d'énumération spécifiée.
type: docs
weight: 14
url: /fr/system/enum/hasflag/
---
## Enum::HasFlag(E, E) méthode

Détermine si les bits spécifiés sont définis dans une représentation bitaire de la valeur d’énumération spécifiée.

```cpp
static bool System::Enum<E, Guard>::HasFlag(E value, E mask)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | E | La valeur d'énumération à tester |
| mask | E | Le masque contre lequel vérifier les bits de la valeur |

### Valeur de retour

Vrai si les bits qui sont définis dans **mask** sont également définis dans **value**, sinon - false

## Voir aussi

* Struct [Enum](../)
* Namespace [System](../../)
* Bibliothèque [Aspose.Slides](../../../)
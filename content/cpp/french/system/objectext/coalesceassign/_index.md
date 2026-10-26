---
title: CoalesceAssign()
second_title: Référence de l'API Aspose.Slides pour C++
description: Implémentation de la traduction de l'opérateur '??='.
type: docs
weight: 183
url: /fr/system/objectext/coalesceassign/
---
## ObjectExt::CoalesceAssign(T0\&, T1) méthode

Implémentation de la traduction de l'opérateur '??='.

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::CoalesceAssign(T0 &value, T1 func) -> T0 &
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T0 | LHS value type. |
| T1 | Type of lambda encapsulating RHS expression. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | T0\& | LHS value. |
| func | T1 | RHS expression. |

### Valeur de retour

Si la valeur LHS n'est pas nulle, renvoie LHS, sinon calcule l'expression RHS et renvoie le résultat.

## Voir aussi

* Classe [ObjectExt](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)
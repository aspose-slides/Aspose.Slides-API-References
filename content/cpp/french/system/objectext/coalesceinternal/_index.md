---
title: CoalesceInternal()
second_title: Référence de l'API Aspose.Slides pour C++
description: Implémentation de la traduction de l'opérateur '??' pour les types non nullables. Surcharge pour le cas où RT2 est convertible en RT1.
type: docs
weight: 157
url: /fr/system/objectext/coalesceinternal/
---
## ObjectExt::CoalesceInternal(RT1, F) méthode

Implémentation de la traduction de l'opérateur '??' pour les types non nullables. Surcharge pour le cas où RT2 est convertible en RT1.

```cpp
template<typename RT1,typename RT2,typename F> static std::conditional<std::is_convertible<RT2, RT1>::value, RT1, RT2>::type System::ObjectExt::CoalesceInternal(RT1 value, F func)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T0 | Type de valeur LHS. |
| T1 | Type du lambda encapsulant l'expression RHS. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | RT1 | Valeur LHS. |
| func | F | Expression RHS. |

### Valeur de retour

Si la valeur LHS n'est pas nulle, renvoie LHS, sinon calcule l'expression RHS et renvoie le résultat.

## Voir aussi

* Classe [ObjectExt](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)
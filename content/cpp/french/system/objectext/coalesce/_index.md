---
title: Coalesce()
second_title: Référence API Aspose.Slides pour C++
description: Implémentation de la traduction de l'opérateur '??' pour les types non nullables.
type: docs
weight: 170
url: /fr/system/objectext/coalesce/
---
## ObjectExt::Coalesce(T0, T1) méthode

Implémentation de la traduction de l'opérateur '??' pour les types non nullables.

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::Coalesce(T0 value, T1 func)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T0 | Type de valeur LHS. |
| T1 | Type du lambda encapsulant l'expression RHS. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | T0 | Valeur LHS. |
| func | T1 | Expression RHS. |

### Valeur de retour

Si la valeur LHS n'est pas nulle, renvoie LHS, sinon calcule l'expression RHS et renvoie le résultat.

## ObjectExt::Coalesce(System::Nullable\<T0\>, T1) méthode

Implémentation de la traduction de l'opérateur '??' pour les types nullables.

```cpp
template<typename T0,typename T1> static T0 System::ObjectExt::Coalesce(System::Nullable<T0> value, T1 func)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T0 | Type de valeur LHS. |
| T1 | Type du lambda encapsulant l'expression RHS. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | [System::Nullable](../../nullable/)\<T0\> | Valeur LHS. |
| func | T1 | Expression RHS. |

### Valeur de retour

Si la valeur LHS n'est pas nulle, renvoie LHS, sinon calcule l'expression RHS et renvoie le résultat.

## Voir aussi

* Class [ObjectExt](../)
* Class [Nullable](../../nullable/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
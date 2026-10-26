---
title: operator()()
second_title: Référence de l'API Aspose.Slides for C++
description: Appelle tous les délégués actuellement présents dans la collection de délégués. Les délégués sont appelés dans le même ordre que celui dans lequel ils ont été ajoutés à la collection. L'opérateur bloque tant que les délégués sont exécutés.
type: docs
weight: 235
url: /fr/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/operator_call/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::operator()(ArgumentTypes...) const méthode

Appelle tous les délégués actuellement présents dans la collection de délégués. Les délégués sont appelés dans le même ordre que celui dans lequel ils ont été ajoutés à la collection. L'opérateur bloque tant que les délégués sont exécutés.

```cpp
ReturnType System::MulticastDelegate<ReturnType(ArgumentTypes...)>::operator()(ArgumentTypes... args) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| args | ArgumentTypes... | Arguments à transmettre aux délégués à invoquer |

### Valeur de retour

Valeur de retour du dernier délégué invoqué

## Voir aussi

* Classe [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)
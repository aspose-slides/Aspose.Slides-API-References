---
title: invoke()
second_title: Référence de l'API Aspose.Slides pour C++
description: Appelle tous les délégués actuellement présents dans la collection de délégués. Les délégués sont appelés dans le même ordre que celui dans lequel ils ont été ajoutés à la collection. La méthode se bloque pendant l'exécution des délégués.
type: docs
weight: 222
url: /fr/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/invoke/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::invoke(ArgumentTypes...) const méthode

Appelle tous les délégués actuellement présents dans la collection de délégués. Les délégués sont appelés dans le même ordre que celui dans lequel ils ont été ajoutés à la collection. La méthode se bloque pendant l'exécution des délégués.

```cpp
ReturnType System::MulticastDelegate<ReturnType(ArgumentTypes...)>::invoke(ArgumentTypes... args) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| args | ArgumentTypes... | Arguments à transmettre aux délégués à invoquer |

### Valeur de retour

Valeur renvoyée du dernier délégué invoqué

## Voir aussi

* Classe [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)
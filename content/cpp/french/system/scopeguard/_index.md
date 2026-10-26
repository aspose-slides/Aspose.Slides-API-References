---
title: ScopeGuard
second_title: Référence API Aspose.Slides pour C++
description: La classe de service qui fournit des services pour exécuter un objet fonction particulier lorsqu'une instance de la classe sort de la portée.
type: docs
weight: 1860
url: /fr/system/scopeguard/
---
## ScopeGuard struct

La classe de service qui fournit des services pour exécuter un objet fonction particulier lorsqu'une instance de la classe sort de la portée.

```cpp
template<typename F>class ScopeGuard
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| F | Le type de l'objet fonction invoqué par les instances de la classe ScopedGuard |
## Méthodes

| Méthode | Description |
| --- | --- |
| void [Disable](./disable/)() | Désactive l'invocation du garde. |
|  [ScopeGuard](./scopeguard/)(F) | Construit une instance qui est configurée pour invoquer l'objet fonction spécifié. |
|  [~ScopeGuard](./~scopeguard/)() | Invoque l'objet fonction passé au constructeur. |

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)
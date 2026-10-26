---
title: MakeScopeGuard()
second_title: Référence API Aspose.Slides pour C++
description: Une fonction usine qui crée des instances de la classe ScopedGuard.
type: docs
weight: 2770
url: /fr/system/makescopeguard/
---
## System::MakeScopeGuard(F) fonction

Une fonction usine qui crée des instances de la classe ScopedGuard.

```cpp
template<typename F> ScopeGuard<F> System::MakeScopeGuard(F f)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| The | type de l'objet fonction à invoquer par l'objet ScopedGuard construit |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| f | F | L'objet fonction à passer au constructeur de la classe ScopedGuard. |

### Valeur de retour

Une nouvelle instance de la classe ScopedGuard

## Voir aussi

* Structure [ScopeGuard](../scopeguard/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)
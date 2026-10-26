---
title: Trace
second_title: Référence de l'API Aspose.Slides pour C++
description: Fournit une interface pour accéder à la trace du débogueur (le cas échéant). Fonctionne uniquement en mode Debug. Il s'agit d'un type statique sans services d'instance. Vous ne devez jamais créer d'instances de celui-ci, quels que soient les moyens.
type: docs
weight: 131
url: /fr/system.diagnostics/trace/
---
## Structure Trace

Fournit une interface pour accéder à la trace du débogueur (le cas échéant). Fonctionne uniquement en mode [Debug](../debug/). Il s'agit d'un type statique sans services d'instance. Vous ne devez jamais créer d'instances de celui-ci, quels que soient les moyens.

```cpp
class Trace
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static void [Flush](./flush/)() | Vide le tampon de sortie et provoque l'écriture des données tamponnées aux écouteurs. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | Écrit une ligne dans la trace du débogueur. |
## Voir aussi

* Espace de noms [System::Diagnostics](../)
* Bibliothèque [Aspose.Slides](../../)
---
title: Parallel
second_title: Référence de l'API Aspose.Slides pour C++
description: Fournit une prise en charge des boucles et des régions parallèles.
type: docs
weight: 1
url: /fr/system.threading.tasks/parallel/
---
## Classe parallèle

Fournit une prise en charge des boucles et régions parallèles.

```cpp
class Parallel
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[ParallelOptions](../paralleloptions/)\>\&, const [Action](../../system/action/)\<TSource\>\&) | Exécute une opération foreach sur un IEnumerable dont les itérations peuvent s'exécuter en parallèle. |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [Action](../../system/action/)\<TSource\>\&) | Exécute une opération foreach sur un IEnumerable dont les itérations peuvent s'exécuter en parallèle. |
## Remarques

Cette classe fournit des méthodes pour l'exécution parallèle des boucles et des opérations. 
## Voir aussi

* Espace de noms [System::Threading::Tasks](../)
* Bibliothèque [Aspose.Slides](../../)
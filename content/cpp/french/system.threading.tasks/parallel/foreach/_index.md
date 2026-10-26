---
title: ForEach()
second_title: Référence de l'API Aspose.Slides pour C++
description: Exécute une opération foreach sur un IEnumerable dont les itérations peuvent s’exécuter en parallèle.
type: docs
weight: 1
url: /fr/system.threading.tasks/parallel/foreach/
---
## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const SharedPtr\<ParallelOptions\>\&, const Action\<TSource\>\&) méthode


Exécute une opération foreach sur un IEnumerable dont les itérations peuvent s'exécuter en parallèle.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const SharedPtr<ParallelOptions> &parallelOptions, const Action<TSource> &body)
```


### Paramètres de modèle

| Parameter | Description |
| --- | --- |
| TSource | Le type des données dans la source. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | Une source de données énumérable. |
| parallelOptions | const [SharedPtr](../../../system/sharedptr/)\<[ParallelOptions](../../paralleloptions/)\>\& | Un objet qui configure le comportement de cette opération. |
| body | const [Action](../../../system/action/)\<TSource\>\& | Le délégué qui est appelé une fois par itération. |

### Valeur de retour

Une structure [ParallelLoopResult](../../parallelloopresult/) qui contient des informations sur la partie de la boucle qui s’est terminée.
## Remarques



Cette méthode partitionne l’énumérable source et exécute le délégué body sur plusieurs threads simultanément. 
## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const Action\<TSource\>\&) méthode


Exécute une opération foreach sur un IEnumerable dont les itérations peuvent s'exécuter en parallèle.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const Action<TSource> &body)
```


### Paramètres de modèle

| Parameter | Description |
| --- | --- |
| TSource | Le type des données dans la source. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | Une source de données énumérable. |
| body | const [Action](../../../system/action/)\<TSource\>\& | Le délégué qui est appelé une fois par itération. |

### Valeur de retour

Une structure [ParallelLoopResult](../../parallelloopresult/) qui contient des informations sur la partie de la boucle qui s’est terminée.
## Remarques



Utilise le [ParallelOptions](../../paralleloptions/) par défaut avec un parallélisme illimité et aucune annulation. 
## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* Classe [ParallelLoopResult](../../parallelloopresult/)
* Classe [IEnumerable](../../../system.collections.generic/ienumerable/)
* Classe [ParallelOptions](../../paralleloptions/)
* Classe [Parallel](../)
* Espace de noms [System::Threading::Tasks](../../)
* Bibliothèque [Aspose.Slides](../../../)
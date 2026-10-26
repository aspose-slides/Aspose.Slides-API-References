---
title: ThreadPoolImpl
second_title: Référence de l'API Aspose.Slides pour C++
description: Données internes du pool de threads. Il s'agit d'un type singleton dont la gestion de la mémoire est effectuée par les fonction(s) d'accès. Vous ne devez jamais créer d'instances directement.
type: docs
weight: 235
url: /fr/system.threading/threadpoolimpl/
---
## ThreadPoolImpl classe


[Thread](../thread/) données internes du pool. Il s'agit d'un type singleton dont la gestion de la mémoire est assurée par les fonction(s) d'accès. Vous ne devez jamais créer d'instances directement.

```cpp
class ThreadPoolImpl
```

## Méthodes

| Méthode | Description |
| --- | --- |
| void [GetAvailableThreads](./getavailablethreads/)(int\&, int\&) | Obtient le nombre de threads disponibles. |
| static **bool**\& [GetInitialized](./getinitialized/)() | Obtient l'état d'initialisation du singleton. |
| void [GetMaxThreads](./getmaxthreads/)(int\&, int\&) | Obtient le nombre maximal de threads concurrents. |
| void [GetMinThreads](./getminthreads/)(int\&, int\&) | Obtient le nombre minimal de threads créés par le pool. |
| void [JoinAll](./joinall/)() | Joint tous les threads possédés. Attend indéfiniment. |
| **bool** [QueueUserWorkItem](./queueuserworkitem/)([WaitCallback](../waitcallback/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Ajoute un élément de travail à la file d'attente. |
| **bool** [SetMaxThreads](./setmaxthreads/)(int, int) | Définit le nombre de threads possédés par le pool. |
| **bool** [SetMinThreads](./setminthreads/)(int, int) | Définit le nombre minimal de threads possédés par le pool. |
|  [ThreadPoolImpl](./threadpoolimpl/)() | Constructeur. |
|  [~ThreadPoolImpl](./~threadpoolimpl/)() | Destructeur. Joint tous les threads s'ils n'ont pas encore été terminés. |
## Voir aussi

* Espace de noms [System::Threading](../)
* Bibliothèque [Aspose.Slides](../../)
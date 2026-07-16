---
title: "System::Threading::Tasks"
second_title: Référence de l'API Aspose.Slides pour C++
description: 
type: docs
weight: 1015
url: /fr/system.threading.tasks/
---
## Classes

| Class | Description |
| --- | --- |
| [Parallel](./parallel/) | Fournit la prise en charge des boucles parallèles et des régions. |
| [ParallelLoopResult](./parallelloopresult/) | Fournit le statut d'achèvement d'une boucle [Parallel](./parallel/). |
| [ParallelOptions](./paralleloptions/) | Stocke les options qui configurent le fonctionnement des méthodes sur la classe [Parallel](./parallel/). |
| [ResultTask](./resulttask/) | Une spécialisation [Task](./task/) qui renvoie une valeur de résultat à la fin. |
| [ResultValueTask](./resultvaluetask/) | Représente un type hybride de type tâche qui peut encapsuler soit une valeur de résultat directe, soit un ResultTask<T>. |
| [Task](./task/) | Représente une opération asynchrone qui peut être attendue et composée avec d'autres tâches. |
| [TaskScheduler](./taskscheduler/) | Représente un objet qui gère le travail de bas niveau consistant à mettre en file d'attente des tâches sur les threads. |
| [ValueTask](./valuetask/) | Fournit un résultat awaitable d'une opération asynchrone. |
## Functions

| Function | Description |
| --- | --- |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**) | Crée une tâche qui se termine après un délai. |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Crée une tâche qui se termine après un délai et qui peut être annulée. |
| [TaskPtr](../system/taskptr/) [FromCanceled](./fromcanceled/)(const [CancellationToken](../system.threading/cancellationtoken/)\&) | Crée une tâche qui s'est terminée en raison d'une annulation avec le jeton spécifié. |
| [TaskPtr](../system/taskptr/) [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | Crée une tâche qui s'est terminée avec une exception spécifiée. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | Crée une tâche qui s'est terminée avec une exception spécifiée et un type de résultat. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromResult](./fromresult/)(TResult) | Crée une tâche qui s'est terminée avec succès avec le résultat spécifié. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&) | Met en file d'attente le travail spécifié pour s'exécuter dans le pool de threads et renvoie un handle [Task](./task/) pour ce travail. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Met en file d'attente le travail spécifié pour s'exécuter dans le pool de threads et renvoie un handle [Task](./task/) pour ce travail. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Func](../system/func/)\<[TaskPtr](../system/taskptr/)\>\&) | Met en file d'attente le travail spécifié pour s'exécuter dans le pool de threads et renvoie un proxy pour le [Task](./task/) renvoyé par la fonction. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [Run](./run/)(const [Func](../system/func/)\<TResult\>\&) | Met en file d'attente le travail spécifié pour s'exécuter dans le pool de threads et renvoie un handle Task<TResult> pour ce travail. |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Attend que tous les objets [Task](./task/) fournis terminent leur exécution. |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Attend que tous les objets [Task](./task/) fournis terminent leur exécution. |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Attend que l'un des objets [Task](./task/) fournis termine son exécution. |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Attend que l'un des objets [Task](./task/) fournis termine son exécution. |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Crée une tâche qui se terminera lorsque toutes les tâches fournies seront terminées. |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | Crée une tâche qui se terminera lorsque toutes les tâches fournies seront terminées. |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | Crée une tâche qui se terminera lorsque toutes les tâches fournies seront terminées. |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | Crée une tâche qui se terminera lorsque toutes les tâches fournies seront terminées. |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | Crée une tâche qui se terminera dès que l'une des tâches fournies sera terminée. |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Crée une tâche qui se terminera dès que l'une des tâches fournies sera terminée. |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | Crée une tâche qui se terminera dès que l'une des tâches fournies sera terminée. |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | Crée une tâche qui se terminera dès que l'une des tâches fournies sera terminée. |
| [Runtime::CompilerServices::YieldAwaitable](../system.runtime.compilerservices/yieldawaitable/) [Yield](./yield/)() | Crée une tâche awaitable qui rend la main de manière asynchrone au contexte actuel lorsqu'elle est attendue. |
## Enums

| Enum | Description |
| --- | --- |
| [TaskStatus](./taskstatus/) |  |
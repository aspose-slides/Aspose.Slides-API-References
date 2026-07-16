---
title: Task()
second_title: Référence de l'API Aspose.Slides pour C++
description: Construit un Task avec une action à exécuter.
type: docs
weight: 1
url: /fr/system.threading.tasks/task/task/
---
## Task::Task(const Action<>\&) constructeur


Construit un [Task](../) avec une action à exécuter.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | L’action à exécuter de façon asynchrone |

## Task::Task(const Action<>\&, const CancellationToken\&) constructeur


Construit un [Task](../) avec une action et un jeton d’annulation.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action, const CancellationToken &cancellationToken)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | L’action à exécuter de façon asynchrone |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | Jeton pour surveiller les demandes d’annulation |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&) constructeur


Construit un [Task](../) avec une action avec état et un objet d’état.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | L’action à exécuter (accepte l’objet d’état) |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Objet d’état défini par l’utilisateur passé à l’action |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&, const CancellationToken\&) constructeur


Construit un [Task](../) avec une action avec état, un état et un jeton d’annulation.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state, const CancellationToken &cancellationToken)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | L’action à exécuter (accepte l’objet d’état) |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Objet d’état défini par l’utilisateur passé à l’action |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | Jeton pour surveiller les demandes d’annulation |

## Task::Task() constructeur


Constructeur interne pour créer des tâches non initialisées.

```cpp
System::Threading::Tasks::Task::Task()
```

## Voir aussi

* Typedef [Action](../../../system/action/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Task](../)
* Classe [CancellationToken](../../../system.threading/cancellationtoken/)
* Classe [Object](../../../system/object/)
* Espace de noms [System::Threading::Tasks](../../)
* Bibliothèque [Aspose.Slides](../../../)
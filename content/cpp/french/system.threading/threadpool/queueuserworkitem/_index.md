---
title: QueueUserWorkItem()
second_title: Référence de l'API Aspose.Slides pour C++
description: Place un élément de travail dans la file d’attente qui possède un rappel sans paramètre.
type: docs
weight: 14
url: /fr/system.threading/threadpool/queueuserworkitem/
---
## ThreadPool::QueueUserWorkItem(WaitCallback) méthode

Place un élément de travail dans la file d’attente qui possède un rappel sans paramètre.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Fonction de rappel à utiliser comme tâche. |

### Valeur de retour

Renvoie toujours true.

## ThreadPool::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) méthode

Place un élément de travail dans la file d’attente qui possède un rappel sans paramètre.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Fonction de rappel à utiliser comme tâche. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Paramètre de fonction de travail. |

### Valeur de retour

Renvoie toujours true.

## Voir aussi

* Typedef [WaitCallback](../../waitcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ThreadPool](../)
* Class [Object](../../../system/object/)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)
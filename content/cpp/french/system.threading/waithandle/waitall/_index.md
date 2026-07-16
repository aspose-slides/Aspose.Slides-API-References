---
title: WaitAll()
second_title: Référence de l'API Aspose.Slides pour C++
description: Attend que tous les handles se déclenchent.
type: docs
weight: 1
url: /fr/system.threading/waithandle/waitall/
---
## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) méthode


Attend que tous les handles se déclenchent.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handles à attendre. |
| millisecondsTimeout | int | [Timeout](../../timeout/) à attendre, en millisecondes ; -1 signifie attente infinie, 0 signifie vérification et retour, les valeurs positives sont des délais d’attente. |

### Valeur de retour

Vrai si tous les handles se sont déclenchés, faux si le délai d’attente est dépassé.

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) méthode


Attend que tous les handles se déclenchent.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handles à attendre. |
| timeout | [TimeSpan](../../../system/timespan/) | Un [System::TimeSpan](../../../system/timespan/) qui représente le nombre de millisecondes à attendre, ou un [System::TimeSpan](../../../system/timespan/) qui représente -1 millisecondes pour attendre indéfiniment. |

### Valeur de retour

Vrai si tous les handles se sont déclenchés, faux si le délai d’attente est dépassé.

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) méthode


Attend que tous les handles se déclenchent.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handles à attendre. |

### Valeur de retour

Vrai lorsque chaque élément de waitHandles a reçu un signal ; sinon la méthode ne retourne jamais.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [WaitHandle](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)
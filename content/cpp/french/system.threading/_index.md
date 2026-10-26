---
title: "System::Threading"
second_title: Référence de l'API Aspose.Slides pour C++
description: 
type: docs
weight: 1002
url: /fr/system.threading/
---
## Classes

| Classe | Description |
| --- | --- |
| [AutoResetEvent](./autoresetevent/) | Événement pour notifier le thread en attente qui se réinitialise automatiquement. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument. |
| [CancellationToken](./cancellationtoken/) | Propage une notification indiquant que les opérations doivent être annulées. Cette classe fournit un mécanisme d'annulation coopérative entre threads, permettant à un thread de notifier les autres qu'une opération doit être annulée. |
| [CancellationTokenRegistration](./cancellationtokenregistration/) | Représente un enregistrement pour un rappel de jeton d'annulation. |
| [CancellationTokenSource](./cancellationtokensource/) | Une source de jeton d'annulation qui peut être utilisée pour déclencher des notifications d'annulation. |
| [Details_SemaphoreFullException](./details_semaphorefullexception/) |  |
| [Details_SynchronizationLockException](./details_synchronizationlockexception/) |  |
| [Details_ThreadAbortException](./details_threadabortexception/) |  |
| [Details_ThreadInterruptedException](./details_threadinterruptedexception/) |  |
| [Details_ThreadStateException](./details_threadstateexception/) |  |
| [EventWaitHandle](./eventwaithandle/) | Événement pouvant être envoyé au thread en attente. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument. |
| [Interlocked](./interlocked/) | Fournit une API pour des opérations thread-safe. Il s'agit d'un type statique sans services d'instance. Vous ne devez jamais créer d'instances de ce type par aucun moyen. |
| [ManualResetEvent](./manualresetevent/) | Événement pour notifier le thread en attente qui ne se réinitialise pas automatiquement. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument. |
| [Monitor](./monitor/) | La classe [Monitor](./monitor/) fournit un mécanisme qui synchronise l'accès aux objets. |
| [Mutex](./mutex/) | [Mutex](./mutex/) implémentation. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument. |
| [Semaphore](./semaphore/) | [Semaphore](./semaphore/) implémentation. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument. |
| [SynchronizationContext](./synchronizationcontext/) | Fournit la fonctionnalité de base pour propager un contexte de synchronisation à travers diverses opérations de synchronisation. |
| [Thread](./thread/) | [Thread](./thread/) implémentation. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument. |
| [ThreadPool](./threadpool/) | [Thread](./thread/) API de pool permettant d'enfiler des travaux dans une file d'attente à lire par un pool de threads de travail. Il s'agit d'un type statique sans services d'instance. Vous ne devez jamais créer d'instances de ce type par aucun moyen. |
| [ThreadPoolImpl](./threadpoolimpl/) | [Thread](./thread/) données internes du pool. Il s'agit d'un type singleton dont la gestion de la mémoire est assurée par les fonctions d'accès. Vous ne devez jamais créer d'instances de ce type directement. |
| [Timer](./timer/) | [Timer](./timer/) classe qui exécute un élément de travail dans un thread séparé après un délai. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument. |
| [TimerQueue](./timerqueue/) | File d'attente qui gère les objets [Timer](./timer/). Il s'agit simplement d'une implémentation. Les objets [Timer](./timer/) s'y enregistrent eux-mêmes, vous n'avez pas besoin de le faire pour les utiliser – utilisez plutôt l'API de la classe [Timer](./timer/). Il s'agit d'un type singleton dont la gestion de la mémoire est assurée par les fonctions d'accès. Vous ne devez jamais créer d'instances de ce type directement. |
| [WaitHandle](./waithandle/) | Classe de base primitive d'attente. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument. |

## Structures

| Structure | Description |
| --- | --- |
| [Timeout](./timeout/) | [Threading](./) valeurs spéciales de délai d'attente. Il s'agit d'un type statique sans services d'instance. Vous ne devez jamais créer d'instances de ce type par aucun moyen. |

## Énumérations

| Énum | Description |
| --- | --- |
| [ApartmentState](./apartmentstate/) | Définit l'état d'appartement du thread. |
| [EventResetMode](./eventresetmode/) | Indique comment l'état de l'événement se réinitialise. |
| [ThreadState](./threadstate/) | État du thread. |

## Alias de type

| Alias | Description |
| --- | --- |
| [ThreadStateException](./threadstateexception/) |  |
| [SemaphoreFullException](./semaphorefullexception/) |  |
| [SynchronizationLockException](./synchronizationlockexception/) |  |
| [ThreadAbortException](./threadabortexception/) |  |
| [ThreadInterruptedException](./threadinterruptedexception/) |  |
| [SendOrPostCallback](./sendorpostcallback/) |  |
| [ParameterizedThreadStart](./parameterizedthreadstart/) | Fonction [Thread](./thread/) avec un seul paramètre. |
| [ThreadStart](./threadstart/) | Fonction [Thread](./thread/) sans paramètres. |
| [WaitCallback](./waitcallback/) | Élément de rappel à exécuter dès qu'un emplacement est disponible. |
| [TimerCallback](./timercallback/) | Fonction de rappel appelée par le minuteur. |
| [wait_handle_t](./wait_handle_t/) | Type de handle. |
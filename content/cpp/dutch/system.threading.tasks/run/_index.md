---
title: Run()
second_title: Aspose.Slides voor C++ API-referentie
description: Plaatst het opgegeven werk in de wachtrij om op de thread-pool uitgevoerd te worden en retourneert een Task-handle voor dat werk.
type: docs
weight: 157
url: /nl/system.threading.tasks/run/
---
## System::Threading::Tasks::Run(const Action<>\&) functie


Plaatst het opgegeven werk in de wachtrij om op de thread-pool uitgevoerd te worden en retourneert een [Task](../task/)-handle voor dat werk.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | Het werk dat asynchroon moet worden uitgevoerd. |

### Retourwaarde

Een [Task](../task/) die het in de wachtrij geplaatste werk vertegenwoordigt dat in de thread-pool wordt uitgevoerd.

## System::Threading::Tasks::Run(const Action<>\&, const CancellationToken\&) functie


Plaatst het opgegeven werk in de wachtrij om op de thread-pool uitgevoerd te worden en retourneert een [Task](../task/)-handle voor dat werk.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action, const CancellationToken &cancellationToken)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | Het werk dat asynchroon moet worden uitgevoerd. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Een annulerings-token dat kan worden gebruikt om het werk te annuleren als het nog niet is gestart. |

### Retourwaarde

Een [Task](../task/) die het in de wachtrij geplaatste werk vertegenwoordigt dat in de thread-pool wordt uitgevoerd.

## System::Threading::Tasks::Run(const Func\<TaskPtr\>\&) functie


Plaatst het opgegeven werk in de wachtrij om op de thread-pool uitgevoerd te worden en geeft een proxy terug voor de [Task](../task/) die door de functie wordt geretourneerd.

```cpp
TaskPtr System::Threading::Tasks::Run(const Func<TaskPtr> &function)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/)\>\& | Het werk dat asynchroon moet worden uitgevoerd en een [Task](../task/) retourneert. |

### Retourwaarde

Een [Task](../task/) die een proxy vertegenwoordigt voor de [Task](../task/) die door de functie wordt geretourneerd.

## System::Threading::Tasks::Run(const Func\<TResult\>\&) functie


Plaatst het opgegeven werk in de wachtrij om op de thread-pool uitgevoerd te worden en retourneert een Task<TResult>-handle voor dat werk.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Run(const Func<TResult> &function)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TResult | Het type van het resultaat dat door de taak wordt geretourneerd. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<TResult\>\& | Het werk dat asynchroon moet worden uitgevoerd. |

### Retourwaarde

Een Task<TResult> die het in de wachtrij geplaatste werk vertegenwoordigt dat in de thread-pool wordt uitgevoerd.

## Zie ook

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Action](../../system/action/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Class [Func](../../system/func/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)
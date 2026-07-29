---
title: Run()
second_title: Aspose.Slides för C++ API-referens
description: Köar det angivna arbetet att köras i trådpoolen och returnerar ett Task-handtag för det arbetet.
type: docs
weight: 157
url: /sv/system.threading.tasks/run/
---
## System::Threading::Tasks::Run(const Action<>\&) funktion


Köar det angivna arbetet att köras i trådpoolen och returnerar ett [Task](../task/)-handtag för det arbetet.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | Arbetet som ska köras asynkront. |

### Returvärde

Ett [Task](../task/) som representerar arbetet som köats för att köras i trådpoolen.

## System::Threading::Tasks::Run(const Action<>\&, const CancellationToken\&) funktion


Köar det angivna arbetet att köras i trådpoolen och returnerar ett [Task](../task/)-handtag för det arbetet.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action, const CancellationToken &cancellationToken)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | Arbetet som ska köras asynkront. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | En avboknings-token som kan användas för att avbryta arbetet om det ännu inte har startat. |

### Returvärde

Ett [Task](../task/) som representerar arbetet som köats för att köras i trådpoolen.

## System::Threading::Tasks::Run(const Func\<TaskPtr\>\&) funktion


Köar det angivna arbetet att köras i trådpoolen och returnerar en proxy för den [Task](../task/) som returneras av funktionen.

```cpp
TaskPtr System::Threading::Tasks::Run(const Func<TaskPtr> &function)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/)\>\& | Arbetet som ska köras asynkront, vilket returnerar ett [Task](../task/). |

### Returvärde

Ett [Task](../task/) som representerar en proxy för den [Task](../task/) som returneras av funktionen.

## System::Threading::Tasks::Run(const Func\<TResult\>\&) funktion


Köar det angivna arbetet att köras i trådpoolen och returnerar ett Task<TResult>-handtag för det arbetet.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Run(const Func<TResult> &function)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TResult | Typen av resultatet som returneras av uppgiften. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<TResult\>\& | Arbetet som ska köras asynkront. |

### Returvärde

Ett Task<TResult> som representerar arbetet som köats för att köras i trådpoolen.

## Se också

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Action](../../system/action/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Klass [CancellationToken](../../system.threading/cancellationtoken/)
* Klass [Func](../../system/func/)
* Namnrymd [System::Threading::Tasks](../)
* Bibliotek [Aspose.Slides](../../)
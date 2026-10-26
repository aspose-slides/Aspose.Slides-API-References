---
title: "System::Threading::Tasks"
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 1015
url: /sv/system.threading.tasks/
---
## Klasser

| Klass | Beskrivning |
| --- | --- |
| [Parallel](./parallel/) | Tillhandahåller stöd för parallella slingor och regioner. |
| [ParallelLoopResult](./parallelloopresult/) | Tillhandahåller slutförandestatus för en [Parallel](./parallel/) slinga. |
| [ParallelOptions](./paralleloptions/) | Lagrar alternativ som konfigurerar operationen av metoder på [Parallel](./parallel/) klass. |
| [ResultTask](./resulttask/) | En [Task](./task/)-specialisering som returnerar ett resultatvärde vid slutförande. |
| [ResultValueTask](./resultvaluetask/) | Representerar en hybrid uppgiftliknande typ som kan omsluta antingen ett direkt resultatvärde eller en ResultTask<T>. |
| [Task](./task/) | Representerar en asynkron operation som kan väntas på och kombineras med andra uppgifter. |
| [TaskScheduler](./taskscheduler/) | Representerar ett objekt som hanterar lågnivåarbetet med att köa uppgifter på trådar. |
| [ValueTask](./valuetask/) | Tillhandahåller ett väntbart resultat av en asynkron operation. |

## Funktioner

| Funktion | Beskrivning |
| --- | --- |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**) | Skapar en uppgift som slutförs efter en tidsfördröjning. |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Skapar en uppgift som slutförs efter en tidsfördröjning och kan avbrutas. |
| [TaskPtr](../system/taskptr/) [FromCanceled](./fromcanceled/)(const [CancellationToken](../system.threading/cancellationtoken/)\&) | Skapar en uppgift som har slutförts på grund av avbokning med den angivna token. |
| [TaskPtr](../system/taskptr/) [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | Skapar en uppgift som har slutförts med ett angivet undantag. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | Skapar en uppgift som har slutförts med ett angivet undantag och resultattyp. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromResult](./fromresult/)(TResult) | Skapar en uppgift som har slutförts framgångsrikt med det angivna resultatet. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&) | Köar det angivna arbetet för att köras i trådpoolen och returnerar ett [Task](./task/)-handtag för det arbetet. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Köar det angivna arbetet för att köras i trådpoolen och returnerar ett [Task](./task/)-handtag för det arbetet. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Func](../system/func/)\<[TaskPtr](../system/taskptr/)\>\&) | Köar det angivna arbetet för att köras i trådpoolen och returnerar en proxy för [Task](./task/) som returneras av funktionen. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [Run](./run/)(const [Func](../system/func/)\<TResult\>\&) | Köar det angivna arbetet för att köras i trådpoolen och returnerar ett Task<TResult>-handtag för det arbetet. |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Väntar på att alla de tillhandahållna [Task](./task/)-objekten ska slutföra exekveringen. |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Väntar på att alla de tillhandahållna [Task](./task/)-objekten ska slutföra exekveringen. |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Väntar på att någon av de tillhandahållna [Task](./task/)-objekten ska slutföra exekveringen. |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Väntar på att någon av de tillhandahållna [Task](./task/)-objekten ska slutföra exekveringen. |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Skapar en uppgift som kommer att slutföras när alla de levererade uppgifterna har slutförts. |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | Skapar en uppgift som kommer att slutföras när alla de levererade uppgifterna har slutförts. |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | Skapar en uppgift som kommer att slutföras när alla de levererade uppgifterna har slutförts. |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | Skapar en uppgift som kommer att slutföras när alla de levererade uppgifterna har slutförts. |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | Skapar en uppgift som kommer att slutföras när någon av de levererade uppgifterna har slutförts. |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Skapar en uppgift som kommer att slutföras när någon av de levererade uppgifterna har slutförts. |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | Skapar en uppgift som kommer att slutföras när någon av de levererade uppgifterna har slutförts. |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | Skapar en uppgift som kommer att slutföras när någon av de levererade uppgifterna har slutförts. |
| [Runtime::CompilerServices::YieldAwaitable](../system.runtime.compilerservices/yieldawaitable/) [Yield](./yield/)() | Skapar en väntbar uppgift som asynkront ger tillbaka till det aktuella sammanhanget när den väntas på. |

## Enums

| Enum | Beskrivning |
| --- | --- |
| [TaskStatus](./taskstatus/) |  |
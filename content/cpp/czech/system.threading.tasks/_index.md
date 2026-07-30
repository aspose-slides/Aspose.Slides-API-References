---
title: "System::Threading::Tasks"
second_title: Aspose.Slides pro C++ API Reference
description: 
type: docs
weight: 1015
url: /cs/system.threading.tasks/
---
## Třídy

| Třída | Popis |
| --- | --- |
| [Parallel](./parallel/) | Poskytuje podporu pro paralelní smyčky a oblasti. |
| [ParallelLoopResult](./parallelloopresult/) | Poskytuje stav dokončení smyčky [Parallel](./parallel/). |
| [ParallelOptions](./paralleloptions/) | Ukládá možnosti, které konfigurují provoz metod třídy [Parallel](./parallel/). |
| [ResultTask](./resulttask/) | Specializace [Task](./task/), která po dokončení vrací hodnotu výsledku. |
| [ResultValueTask](./resultvaluetask/) | Reprezentuje hybridní typ podobný úkolu, který může obalit buď přímou hodnotu výsledku, nebo ResultTask<T>. |
| [Task](./task/) | Reprezentuje asynchronní operaci, kterou lze čekat a skládati s ostatními úkoly. |
| [TaskScheduler](./taskscheduler/) | Reprezentuje objekt, který zpracovává nízkoúrovňovou práci s zařazováním úkolů na vlákna. |
| [ValueTask](./valuetask/) | Poskytuje výsledek, který lze čekat, asynchronní operace. |

## Funkce

| Funkce | Popis |
| --- | --- |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**) | Vytvoří úkol, který dokončí po časovém zpoždění. |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Vytvoří úkol, který dokončí po časovém zpoždění a může být zrušen. |
| [TaskPtr](../system/taskptr/) [FromCanceled](./fromcanceled/)(const [CancellationToken](../system.threading/cancellationtoken/)\&) | Vytvoří úkol, který byl dokončen z důvodu zrušení pomocí zadaného tokenu. |
| [TaskPtr](../system/taskptr/) [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | Vytvoří úkol, který byl dokončen s určenou výjimkou. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | Vytvoří úkol, který byl dokončen s určenou výjimkou a typem výsledku. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromResult](./fromresult/)(TResult) | Vytvoří úkol, který byl úspěšně dokončen s určeným výsledkem. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&) | Zařadí zadanou práci do vláknového fondu a vrátí [Task](./task/) handle pro tuto práci. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Zařadí zadanou práci do vláknového fondu a vrátí [Task](./task/) handle pro tuto práci. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Func](../system/func/)\<[TaskPtr](../system/taskptr/)\>\&) | Zařadí zadanou práci do vláknového fondu a vrátí proxy pro [Task](./task/) vrácený funkcí. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [Run](./run/)(const [Func](../system/func/)\<TResult\>\&) | Zařadí zadanou práci do vláknového fondu a vrátí Task<TResult> handle pro tuto práci. |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Čeká na dokončení provedení všech poskytnutých objektů [Task](./task/). |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Čeká na dokončení provedení všech poskytnutých objektů [Task](./task/). |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Čeká na dokončení provedení libovolného z poskytnutých objektů [Task](./task/). |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Čeká na dokončení provedení libovolného z poskytnutých objektů [Task](./task/). |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Vytvoří úkol, který bude dokončen, když budou dokončeny všechny dodané úkoly. |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | Vytvoří úkol, který bude dokončen, když budou dokončeny všechny dodané úkoly. |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | Vytvoří úkol, který bude dokončen, když budou dokončeny všechny dodané úkoly. |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | Vytvoří úkol, který bude dokončen, když budou dokončeny všechny dodané úkoly. |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | Vytvoří úkol, který bude dokončen, když bude dokončen libovolný z dodaných úkolů. |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Vytvoří úkol, který bude dokončen, když bude dokončen libovolný z dodaných úkolů. |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | Vytvoří úkol, který bude dokončen, když bude dokončen libovolný z dodaných úkolů. |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | Vytvoří úkol, který bude dokončen, když bude dokončen libovolný z dodaných úkolů. |
| [Runtime::CompilerServices::YieldAwaitable](../system.runtime.compilerservices/yieldawaitable/) [Yield](./yield/)() | Vytvoří úkol, který lze čekat a asynchronně vrací řízení zpět do aktuálního kontextu při čekání. |

## Výčty

| Výčet | Popis |
| --- | --- |
| [TaskStatus](./taskstatus/) |  |
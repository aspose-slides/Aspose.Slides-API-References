---
title: "System::Threading::Tasks"
second_title: Aspose.Slides voor C++ API-referentie
description: 
type: docs
weight: 1015
url: /nl/system.threading.tasks/
---
## Klassen

| Klasse | Beschrijving |
| --- | --- |
| [Parallel](./parallel/) | Biedt ondersteuning voor parallelle lussen en regio's. |
| [ParallelLoopResult](./parallelloopresult/) | Biedt de voltooiingsstatus van een [Parallel](./parallel/) loop. |
| [ParallelOptions](./paralleloptions/) | Slaat opties op die de werking van methoden op de [Parallel](./parallel/) klasse configureren. |
| [ResultTask](./resulttask/) | Een [Task](./task/)-specialisatie die een resultaatwaarde retourneert bij voltooiing. |
| [ResultValueTask](./resultvaluetask/) | Stelt een hybride taakachtig type voor dat ofwel een directe resultaatwaarde of een ResultTask<T> kan omsluiten. |
| [Task](./task/) | Stelt een asynchrone bewerking voor die kan worden afgewacht en gecombineerd met andere taken. |
| [TaskScheduler](./taskscheduler/) | Stelt een object voor dat het laag-niveau werk afhandelt van het in de wachtrij plaatsen van taken op threads. |
| [ValueTask](./valuetask/) | Biedt een afwachtbaar resultaat van een asynchrone bewerking. |

## Functies

| Functie | Beschrijving |
| --- | --- |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**) | Maakt een taak die voltooit na een tijdvertraging. |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Maakt een taak die voltooit na een tijdvertraging en kan worden geannuleerd. |
| [TaskPtr](../system/taskptr/) [FromCanceled](./fromcanceled/)(const [CancellationToken](../system.threading/cancellationtoken/)\&) | Maakt een taak die voltooid is vanwege annulering met het opgegeven token. |
| [TaskPtr](../system/taskptr/) [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | Maakt een taak die voltooid is met een opgegeven uitzondering. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | Maakt een taak die voltooid is met een opgegeven uitzondering en resultaattype. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromResult](./fromresult/)(TResult) | Maakt een taak die met succes voltooid is met het opgegeven resultaat. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&) | Plaatst het opgegeven werk in de wachtrij om uit te voeren op de thread-pool en retourneert een [Task](./task/)-handle voor dat werk. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Plaatst het opgegeven werk in de wachtrij om uit te voeren op de thread-pool en retourneert een [Task](./task/)-handle voor dat werk. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Func](../system/func/)\<[TaskPtr](../system/taskptr/)\>\&) | Plaatst het opgegeven werk in de wachtrij om uit te voeren op de thread-pool en retourneert een proxy voor de [Task](./task/) die door de functie wordt geretourneerd. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [Run](./run/)(const [Func](../system/func/)\<TResult\>\&) | Plaatst het opgegeven werk in de wachtrij om uit te voeren op de thread-pool en retourneert een Task<TResult>-handle voor dat werk. |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Wacht tot alle opgegeven [Task](./task/)-objecten de uitvoering hebben voltooid. |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Wacht tot alle opgegeven [Task](./task/)-objecten de uitvoering hebben voltooid. |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Wacht tot een van de opgegeven [Task](./task/)-objecten de uitvoering heeft voltooid. |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Wacht tot een van de opgegeven [Task](./task/)-objecten de uitvoering heeft voltooid. |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Maakt een taak die voltooit wanneer alle meegeleverde taken zijn voltooid. |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | Maakt een taak die voltooit wanneer alle meegeleverde taken zijn voltooid. |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | Maakt een taak die voltooit wanneer alle meegeleverde taken zijn voltooid. |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | Maakt een taak die voltooit wanneer alle meegeleverde taken zijn voltooid. |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | Maakt een taak die voltooit wanneer een van de meegeleverde taken is voltooid. |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Maakt een taak die voltooit wanneer een van de meegeleverde taken is voltooid. |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | Maakt een taak die voltooit wanneer een van de meegeleverde taken is voltooid. |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | Maakt een taak die voltooit wanneer een van de meegeleverde taken is voltooid. |
| [Runtime::CompilerServices::YieldAwaitable](../system.runtime.compilerservices/yieldawaitable/) [Yield](./yield/)() | Maakt een afwachtbare taak die asynchroon terugkeert naar de huidige context wanneer erop wordt gewacht. |

## Enumeraties

| Enum | Beschrijving |
| --- | --- |
| [TaskStatus](./taskstatus/) |  |
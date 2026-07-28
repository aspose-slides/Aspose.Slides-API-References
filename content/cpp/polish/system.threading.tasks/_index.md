---
title: "System::Threading::Tasks"
second_title: Aspose.Slides dla C++ API Referencja
description: 
type: docs
weight: 1015
url: /pl/system.threading.tasks/
---
## Klasy

| Klasa | Opis |
| --- | --- |
| [Parallel](./parallel/) | Zapewnia obsługę pętli równoległych i regionów. |
| [ParallelLoopResult](./parallelloopresult/) | Zapewnia status zakończenia pętli [Parallel](./parallel/). |
| [ParallelOptions](./paralleloptions/) | Przechowuje opcje konfiguracyjne operacji metod w klasie [Parallel](./parallel/). |
| [ResultTask](./resulttask/) | Specjalizacja [Task](./task/) zwracająca wartość wyniku po zakończeniu. |
| [ResultValueTask](./resultvaluetask/) | Reprezentuje hybrydowy typ podobny do zadania, który może opakowywać bezpośrednią wartość wyniku lub ResultTask<T>. |
| [Task](./task/) | Reprezentuje operację asynchroniczną, którą można oczekiwać i łączyć z innymi zadaniami. |
| [TaskScheduler](./taskscheduler/) | Reprezentuje obiekt, który obsługuje niskopoziomowe zadania kolejkowania zadań na wątkach. |
| [ValueTask](./valuetask/) | Zapewnia oczekiwalny wynik operacji asynchronicznej. |
## Funkcje

| Funkcja | Opis |
| --- | --- |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**) | Tworzy zadanie, które kończy się po opóźnieniu czasowym. |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Tworzy zadanie, które kończy się po opóźnieniu czasowym i może zostać anulowane. |
| [TaskPtr](../system/taskptr/) [FromCanceled](./fromcanceled/)(const [CancellationToken](../system.threading/cancellationtoken/)\&) | Tworzy zadanie, które zakończyło się z powodu anulowania przy użyciu określonego tokenu. |
| [TaskPtr](../system/taskptr/) [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | Tworzy zadanie, które zakończyło się z określonym wyjątkiem. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | Tworzy zadanie, które zakończyło się z określonym wyjątkiem i typem wyniku. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromResult](./fromresult/)(TResult) | Tworzy zadanie, które zakończyło się pomyślnie z określonym wynikiem. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&) | Umieszcza określone zadanie w kolejce w puli wątków i zwraca uchwyt [Task](./task/) do tego zadania. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Umieszcza określone zadanie w kolejce w puli wątków i zwraca uchwyt [Task](./task/) do tego zadania. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Func](../system/func/)\<[TaskPtr](../system/taskptr/)\>\&) | Umieszcza określone zadanie w kolejce w puli wątków i zwraca proxy dla [Task](./task/) zwróconego przez funkcję. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [Run](./run/)(const [Func](../system/func/)\<TResult\>\&) | Umieszcza określone zadanie w kolejce w puli wątków i zwraca uchwyt Task<TResult> do tego zadania. |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Czeka, aż wszystkie dostarczone obiekty [Task](./task/) zakończą wykonanie. |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Czeka, aż wszystkie dostarczone obiekty [Task](./task/) zakończą wykonanie. |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Czeka, aż dowolny z dostarczonych obiektów [Task](./task/) zakończy wykonanie. |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Czeka, aż dowolny z dostarczonych obiektów [Task](./task/) zakończy wykonanie. |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Tworzy zadanie, które zakończy się po zakończeniu wszystkich dostarczonych zadań. |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | Tworzy zadanie, które zakończy się po zakończeniu wszystkich dostarczonych zadań. |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | Tworzy zadanie, które zakończy się po zakończeniu wszystkich dostarczonych zadań. |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | Tworzy zadanie, które zakończy się po zakończeniu wszystkich dostarczonych zadań. |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | Tworzy zadanie, które zakończy się po zakończeniu dowolnego z dostarczonych zadań. |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Tworzy zadanie, które zakończy się po zakończeniu dowolnego z dostarczonych zadań. |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | Tworzy zadanie, które zakończy się po zakończeniu dowolnego z dostarczonych zadań. |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | Tworzy zadanie, które zakończy się po zakończeniu dowolnego z dostarczonych zadań. |
| [Runtime::CompilerServices::YieldAwaitable](../system.runtime.compilerservices/yieldawaitable/) [Yield](./yield/)() | Tworzy oczekiwalne zadanie, które asynchronicznie zwraca kontrolę do bieżącego kontekstu po oczekiwaniu. |
## Wyliczenia

| Wyliczenie | Opis |
| --- | --- |
| [TaskStatus](./taskstatus/) |  |
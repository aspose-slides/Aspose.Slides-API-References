---
title: "System::Threading::Tasks"
second_title: Aspose.Slides für C++ API-Referenz
description: 
type: docs
weight: 1015
url: /de/system.threading.tasks/
---
## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [Parallel](./parallel/) | Stellt Unterstützung für parallele Schleifen und Regionen bereit. |
| [ParallelLoopResult](./parallelloopresult/) | Stellt den Abschlussstatus einer [Parallel](./parallel/)-Schleife bereit. |
| [ParallelOptions](./paralleloptions/) | Speichert Optionen, die den Betrieb von Methoden der [Parallel](./parallel/)-Klasse konfigurieren. |
| [ResultTask](./resulttask/) | Eine [Task](./task/)-Spezialisierung, die bei Abschluss einen Ergebniswert zurückgibt. |
| [ResultValueTask](./resultvaluetask/) | Repräsentiert einen hybriden, task-ähnlichen Typ, der entweder einen direkten Ergebniswert oder ein ResultTask<T> einpacken kann. |
| [Task](./task/) | Repräsentiert eine asynchrone Operation, die abgewartet und mit anderen Tasks kombiniert werden kann. |
| [TaskScheduler](./taskscheduler/) | Repräsentiert ein Objekt, das die Low-Level-Arbeit des Einreihens von Tasks in Threads übernimmt. |
| [ValueTask](./valuetask/) | Stellt ein abwartbares Ergebnis einer asynchronen Operation bereit. |
## Funktionen

| Funktion | Beschreibung |
| --- | --- |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**) | Erstellt einen Task, der nach einer Zeitverzögerung abgeschlossen wird. |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Erstellt einen Task, der nach einer Zeitverzögerung abgeschlossen wird und abgebrochen werden kann. |
| [TaskPtr](../system/taskptr/) [FromCanceled](./fromcanceled/)(const [CancellationToken](../system.threading/cancellationtoken/)\&) | Erstellt einen Task, der wegen einer Abbruch mit dem angegebenen Token abgeschlossen ist. |
| [TaskPtr](../system/taskptr/) [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | Erstellt einen Task, der mit einer angegebenen Ausnahme abgeschlossen ist. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | Erstellt einen Task, der mit einer angegebenen Ausnahme und einem Ergebnistyp abgeschlossen ist. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromResult](./fromresult/)(TResult) | Erstellt einen Task, der erfolgreich mit dem angegebenen Ergebnis abgeschlossen wurde. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&) | Stellt die angegebene Arbeit zur Ausführung im Thread-Pool in die Warteschlange und gibt einen [Task](./task/)-Handle für diese Arbeit zurück. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Stellt die angegebene Arbeit zur Ausführung im Thread-Pool in die Warteschlange und gibt einen [Task](./task/)-Handle für diese Arbeit zurück. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Func](../system/func/)\<[TaskPtr](../system/taskptr/)\>\&) | Stellt die angegebene Arbeit zur Ausführung im Thread-Pool in die Warteschlange und gibt einen Proxy für das von der Funktion zurückgegebene [Task](./task/) zurück. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [Run](./run/)(const [Func](../system/func/)\<TResult\>\&) | Stellt die angegebene Arbeit zur Ausführung im Thread-Pool in die Warteschlange und gibt einen Task<TResult>-Handle für diese Arbeit zurück. |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Wartet, bis alle bereitgestellten [Task](./task/)-Objekte die Ausführung abgeschlossen haben. |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Wartet, bis alle bereitgestellten [Task](./task/)-Objekte die Ausführung abgeschlossen haben. |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Wartet, bis eines der bereitgestellten [Task](./task/)-Objekte die Ausführung abgeschlossen hat. |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Wartet, bis eines der bereitgestellten [Task](./task/)-Objekte die Ausführung abgeschlossen hat. |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Erstellt einen Task, der abgeschlossen wird, sobald alle bereitgestellten Tasks abgeschlossen sind. |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | Erstellt einen Task, der abgeschlossen wird, sobald alle bereitgestellten Tasks abgeschlossen sind. |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | Erstellt einen Task, der abgeschlossen wird, sobald alle bereitgestellten Tasks abgeschlossen sind. |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | Erstellt einen Task, der abgeschlossen wird, sobald alle bereitgestellten Tasks abgeschlossen sind. |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | Erstellt einen Task, der abgeschlossen wird, sobald einer der bereitgestellten Tasks abgeschlossen ist. |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Erstellt einen Task, der abgeschlossen wird, sobald einer der bereitgestellten Tasks abgeschlossen ist. |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | Erstellt einen Task, der abgeschlossen wird, sobald einer der bereitgestellten Tasks abgeschlossen ist. |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | Erstellt einen Task, der abgeschlossen wird, sobald einer der bereitgestellten Tasks abgeschlossen ist. |
| [Runtime::CompilerServices::YieldAwaitable](../system.runtime.compilerservices/yieldawaitable/) [Yield](./yield/)() | Erstellt einen abwartbaren Task, der beim Await asynchron zum aktuellen Kontext zurückkehrt. |
## Aufzählungen

| Aufzählung | Beschreibung |
| --- | --- |
| [TaskStatus](./taskstatus/) |  |
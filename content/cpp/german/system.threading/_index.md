---
title: "System::Threading"
second_title: Aspose.Slides für C++ API-Referenz
description: 
type: docs
weight: 1002
url: /de/system.threading/
---
## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [AutoResetEvent](./autoresetevent/) | Ereignis, das einen wartenden Thread benachrichtigt und automatisch zurücksetzt. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Umwickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Pointer und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [CancellationToken](./cancellationtoken/) | Überträgt die Benachrichtigung, dass Vorgänge abgebrochen werden sollen. Diese Klasse stellt einen Mechanismus für kooperative Abbrüche zwischen Threads bereit, der es einem Thread ermöglicht, andere darüber zu informieren, dass ein Vorgang abgebrochen werden soll. |
| [CancellationTokenRegistration](./cancellationtokenregistration/) | Stellt eine Registrierung für einen Abbruch-Token-Callback dar. |
| [CancellationTokenSource](./cancellationtokensource/) | Eine Abbruch-Token-Quelle, die verwendet werden kann, um Abbruchbenachrichtigungen auszulösen. |
| [Details_SemaphoreFullException](./details_semaphorefullexception/) |  |
| [Details_SynchronizationLockException](./details_synchronizationlockexception/) |  |
| [Details_ThreadAbortException](./details_threadabortexception/) |  |
| [Details_ThreadInterruptedException](./details_threadinterruptedexception/) |  |
| [Details_ThreadStateException](./details_threadstateexception/) |  |
| [EventWaitHandle](./eventwaithandle/) | Ereignis, das an einen wartenden Thread gesendet werden kann. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Umwickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Pointer und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [Interlocked](./interlocked/) | Stellt eine API für thread-sichere Operationen bereit. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals Instanzen davon auf irgendeine Weise erstellen. |
| [ManualResetEvent](./manualresetevent/) | Ereignis, das einen wartenden Thread benachrichtigt und nicht automatisch zurücksetzt. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Umwickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Pointer und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [Monitor](./monitor/) | Klasse [Monitor](./monitor/) stellt einen Mechanismus bereit, der den Zugriff auf Objekte synchronisiert. |
| [Mutex](./mutex/) | [Mutex](./mutex/)-Implementierung. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Umwickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Pointer und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [Semaphore](./semaphore/) | [Semaphore](./semaphore/)-Implementierung. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Umwickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Pointer und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [SynchronizationContext](./synchronizationcontext/) | Stellt die Grundfunktionalität zum Weitergeben eines Synchronisationskontexts über verschiedene Synchronisationsvorgänge bereit. |
| [Thread](./thread/) | [Thread](./thread/)-Implementierung. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Umwickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Pointer und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [ThreadPool](./threadpool/) | [Thread](./thread/)-Pool-API, die das Einreihen von Aufträgen in eine Warteschlange ermöglicht, die von einem Pool von Arbeitsthreads gelesen wird. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals Instanzen davon auf irgendeine Weise erstellen. |
| [ThreadPoolImpl](./threadpoolimpl/) | [Thread](./thread/)-Pool-Interndaten. Dies ist ein Singleton-Typ, dessen Speicherverwaltung über Zugriffs-Funktion(en) erfolgt. Sie sollten niemals Instanzen davon direkt erstellen. |
| [Timer](./timer/) | [Timer](./timer/)-Klasse, die ein Auftragselement nach einer Verzögerung in einem separaten Thread ausführt. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Umwickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Pointer und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [TimerQueue](./timerqueue/) | Warteschlange, die [Timer](./timer/)-Objekte verarbeitet. Dies ist lediglich eine Implementierung. [Timer](./timer/)-Objekte registrieren sich dort selbst, Sie müssen das nicht tun, um sie zu benutzen – verwenden Sie stattdessen die [Timer](./timer/)-Klassen-API. Dies ist ein Singleton-Typ, dessen Speicherverwaltung über Zugriffs-Funktion(en) erfolgt. Sie sollten niemals Instanzen davon direkt erstellen. |
| [WaitHandle](./waithandle/) | Warte-Primitive-Basisklasse. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Umwickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Pointer und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
## Strukturen

| Struktur | Beschreibung |
| --- | --- |
| [Timeout](./timeout/) | [Threading](./)-Timeout-Sonderwerte. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals Instanzen davon auf irgendeine Weise erstellen. |
## Aufzählungen

| Aufzählung | Beschreibung |
| --- | --- |
| [ApartmentState](./apartmentstate/) | Legt den Apartment-Zustand des Threads fest. |
| [EventResetMode](./eventresetmode/) | Gibt an, wie der Ereignis-Zustand zurückgesetzt wird. |
| [ThreadState](./threadstate/) | Zustand des Threads. |
## Typdefinitionen

| Typdefinition | Beschreibung |
| --- | --- |
| [ThreadStateException](./threadstateexception/) |  |
| [SemaphoreFullException](./semaphorefullexception/) |  |
| [SynchronizationLockException](./synchronizationlockexception/) |  |
| [ThreadAbortException](./threadabortexception/) |  |
| [ThreadInterruptedException](./threadinterruptedexception/) |  |
| [SendOrPostCallback](./sendorpostcallback/) |  |
| [ParameterizedThreadStart](./parameterizedthreadstart/) | [Thread](./thread/)-Funktion mit einem Parameter. |
| [ThreadStart](./threadstart/) | [Thread](./thread/)-Funktion ohne Parameter. |
| [WaitCallback](./waitcallback/) | Callback-Element, das ausgeführt wird, sobald ein Platz verfügbar ist. |
| [TimerCallback](./timercallback/) | Callback-Funktion, die vom Timer aufgerufen wird. |
| [wait_handle_t](./wait_handle_t/) | Handle-Typ. |
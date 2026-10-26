---
title: ThreadPoolImpl
second_title: Aspose.Slides für C++ API Referenz
description: Interne Daten des Thread-Pools. Dies ist ein Singleton-Typ mit Speicherverwaltung, die über Zugriffsfunktion(en) erfolgt. Sie sollten niemals Instanzen davon direkt erstellen.
type: docs
weight: 235
url: /de/system.threading/threadpoolimpl/
---
## ThreadPoolImpl Klasse

[Thread](../thread/) pool internal data. Dies ist ein Singleton-Typ mit Speicherverwaltung, die über Zugriffsfunktion(en) erfolgt. Sie sollten niemals Instanzen davon direkt erstellen.

```cpp
class ThreadPoolImpl
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| void [GetAvailableThreads](./getavailablethreads/)(int\&, int\&) | Ermittelt die Anzahl verfügbarer Threads. |
| static **bool**\& [GetInitialized](./getinitialized/)() | Ermittelt den Initialisierungszustand des Singletons. |
| void [GetMaxThreads](./getmaxthreads/)(int\&, int\&) | Ermittelt die maximale Anzahl gleichzeitiger Threads. |
| void [GetMinThreads](./getminthreads/)(int\&, int\&) | Ermittelt die minimale Anzahl von Threads, die vom Pool erstellt werden. |
| void [JoinAll](./joinall/)() | Führt Join für alle eigenen Threads durch. Wartet unendlich. |
| **bool** [QueueUserWorkItem](./queueuserworkitem/)([WaitCallback](../waitcallback/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Fügt ein Arbeitselement zur Warteschlange hinzu. |
| **bool** [SetMaxThreads](./setmaxthreads/)(int, int) | Legt die Anzahl von Threads fest, die dem Pool gehören. |
| **bool** [SetMinThreads](./setminthreads/)(int, int) | Legt die minimale Anzahl von Threads fest, die dem Pool gehören. |
|  [ThreadPoolImpl](./threadpoolimpl/)() | Konstruktor. |
|  [~ThreadPoolImpl](./~threadpoolimpl/)() | Destruktor. Führt Join für alle Threads aus, falls sie noch nicht beendet wurden. |

## Siehe auch

* Namensraum [System::Threading](../)
* Bibliothek [Aspose.Slides](../../)
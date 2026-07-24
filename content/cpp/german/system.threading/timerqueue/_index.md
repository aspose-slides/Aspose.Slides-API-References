---
title: TimerQueue
second_title: Aspose.Slides für C++ API-Referenz
description: Warteschlange, die Timer-Objekte verwaltet. Dies ist nur eine Implementierung. Timer-Objekte registrieren sich dort selbst, Sie müssen das nicht tun, um sie zu verwenden - verwenden Sie stattdessen die Timer class API. Es handelt sich um einen Singleton-Typ mit Speicherverwaltung, die über Zugriffs-Funktion(en) erfolgt. Sie sollten niemals direkt Instanzen davon erstellen.
type: docs
weight: 261
url: /de/system.threading/timerqueue/
---
## TimerQueue Klasse

Warteschlange, die [Timer](../timer/)-Objekte verwaltet. Dies ist nur eine Implementierung. [Timer](../timer/)-Objekte registrieren sich dort selbst, Sie müssen das nicht tun, um sie zu verwenden – verwenden Sie stattdessen die API der Klasse [Timer](../timer/). Es handelt sich um einen Singleton-Typ mit Speicherverwaltung, die über Zugriffs-Funktion(en) erfolgt. Sie sollten nie Instanzen davon direkt erstellen.

```cpp
class TimerQueue
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| **bool** [Add](./add/)([Timer](../timer/) *) | Registriert den Timer in der Warteschlange. |
| **bool** [Delete](./delete/)([Timer](../timer/) *) | Löscht den Timer aus der Warteschlange. |
| static [TimerQueue](./)\& [GetInstance](./getinstance/)() | Implementierungs-Singleton. |
| static void [JoinWorkerThread](./joinworkerthread/)() | Tritt dem Arbeitsthread bei. Wartet unendlich, falls erforderlich. |
| void [operator=](./operator_equal/)(const [TimerQueue](./)\&) | Keine Kopie. |
|  [TimerQueue](./timerqueue/)(const [TimerQueue](./)\&) | Keine Kopie. |

## Siehe auch

* Namensraum [System::Threading](../)
* Bibliothek [Aspose.Slides](../../)
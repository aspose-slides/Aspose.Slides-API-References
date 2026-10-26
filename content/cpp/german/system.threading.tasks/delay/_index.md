---
title: Delay()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt einen Task, der nach einer Zeitverzögerung abgeschlossen wird.
type: docs
weight: 105
url: /de/system.threading.tasks/delay/
---
## System::Threading::Tasks::Delay(int32_t) Funktion

Erstellt einen Task, der nach einer Zeitverzögerung abgeschlossen wird.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | Die Anzahl der Millisekunden, die gewartet werden soll, bevor der zurückgegebene Task abgeschlossen wird, oder -1, um unbegrenzt zu warten. |

### Rückgabewert

Ein Task, der die Zeitverzögerung darstellt.

## System::Threading::Tasks::Delay(int32_t, const CancellationToken\&) Funktion

Erstellt einen Task, der nach einer Zeitverzögerung abgeschlossen wird und abgebrochen werden kann.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay, const CancellationToken &cancellationToken)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | Die Anzahl der Millisekunden, die gewartet werden soll, bevor der zurückgegebene Task abgeschlossen wird, oder -1, um unbegrenzt zu warten. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Das Abbruch-Token, das zum Abbrechen der Verzögerung verwendet werden kann. |

### Rückgabewert

Ein Task, der die Zeitverzögerung darstellt.

## Siehe auch

* Typedef [TaskPtr](../../system/taskptr/)
* Klasse [CancellationToken](../../system.threading/cancellationtoken/)
* Namensraum [System::Threading::Tasks](../)
* Bibliothek [Aspose.Slides](../../)
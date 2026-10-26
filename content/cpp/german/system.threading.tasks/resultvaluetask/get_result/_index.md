---
title: get_Result()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt das Ergebnis der abgeschlossenen Aufgabe zurück.
type: docs
weight: 66
url: /de/system.threading.tasks/resultvaluetask/get_result/
---
## ResultValueTask::get_Result() Methode

Gibt das Ergebnis der abgeschlossenen Aufgabe zurück.

```cpp
T System::Threading::Tasks::ResultValueTask<T>::get_Result()
```

### Rückgabewert

T Der Ergebniswert.
## Hinweise



Wenn die Aufgabe von einem ResultTask<T> unterstützt wird, wartet diese Methode auf das Ergebnis und speichert es im Cache. Nachfolgende Aufrufe geben den zwischengespeicherten Wert zurück, ohne zu warten. 

## Siehe auch

* Klasse [ResultValueTask](../)
* Namensraum [System::Threading::Tasks](../../)
* Bibliothek [Aspose.Slides](../../../)
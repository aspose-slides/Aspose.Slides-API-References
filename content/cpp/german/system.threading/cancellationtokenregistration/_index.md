---
title: CancellationTokenRegistration
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt eine Registrierung für eine Abbruch-Token-Rückruffunktion dar.
type: docs
weight: 27
url: /de/system.threading/cancellationtokenregistration/
---
## CancellationTokenRegistration Klasse


Stellt eine Registrierung für eine Abbruch-Token-Rückruffunktion dar.

```cpp
class CancellationTokenRegistration
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| void [Dispose](./dispose/)() | Gibt die Registrierung frei und entfernt die Rückruffunktion aus dem zugehörigen [CancellationTokenSource](../cancellationtokensource/). Nach Aufruf dieser Methode wird die registrierte Rückruffunktion nicht mehr aufgerufen, wenn das zugehörige [CancellationTokenSource](../cancellationtokensource/) abgebrochen wird. |
## Bemerkungen


Diese Klasse ermöglicht die Abmeldung einer Rückruffunktion von einem Abbruch-Token. Beim Freigeben entfernt sie die Rückruffunktion aus dem zugehörigen [CancellationTokenSource](../cancellationtokensource/). 
Diese Klasse sollte nicht direkt erstellt werden – sie wird von den Registrierungs-Methoden von [CancellationToken](../cancellationtoken/) zurückgegeben. 

## Siehe auch

* Namensraum [System::Threading](../)
* Bibliothek [Aspose.Slides](../../)
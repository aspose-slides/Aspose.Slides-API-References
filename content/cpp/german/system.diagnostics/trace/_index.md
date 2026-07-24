---
title: Trace
second_title: Aspose.Slides für C++ API Referenz
description: Stellt eine Schnittstelle zum Zugriff auf die Debugger-Trace (falls vorhanden) bereit. Funktioniert nur im Debug-Modus. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten unter keinen Umständen Instanzen davon erzeugen.
type: docs
weight: 131
url: /de/system.diagnostics/trace/
---
## Trace-Struktur

Stellt eine Schnittstelle zum Zugriff auf die Debugger-Trace (falls vorhanden) bereit. Funktioniert nur im [Debug](../debug/) Modus. Dies ist ein static Typ ohne Instanzdienste. Sie sollten unter keinen Umständen Instanzen davon erzeugen.

```cpp
class Trace
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static void [Flush](./flush/)() | Leert den Ausgabepuffer und bewirkt, dass gepufferte Daten an die Listener geschrieben werden. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | Schreibt eine Zeile in die Debugger-Trace. |
## Siehe auch

* Namensraum [System::Diagnostics](../)
* Bibliothek [Aspose.Slides](../../)
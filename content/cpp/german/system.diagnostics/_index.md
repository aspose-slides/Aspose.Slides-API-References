---
title: "System::Diagnostics"
second_title: Aspose.Slides für C++ API-Referenz
description: 
type: docs
weight: 469
url: /de/system.diagnostics/
---
## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [FileVersionInfo](./fileversioninfo/) | Stellt Informationen zur Dateiversion bereit. Objekte dieser Klasse sollten nur mit der [System::MakeObject()](../system/makeobject/) Funktion zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Verpacken Sie diese Klasse stets in einen [System::SmartPtr](../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [PerformanceCounter](./performancecounter/) | Dummy-Klasse, damit mit PerformanceCounter-verwendeter übersetzter Code kompiliert werden kann. Objekte dieser Klasse sollten nur mit der [System::MakeObject()](../system/makeobject/) Funktion zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Verpacken Sie diese Klasse stets in einen [System::SmartPtr](../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [Process](./process/) | Kapselt Prozessinformationen und -manipulation. Objekte dieser Klasse sollten nur mit der [System::MakeObject()](../system/makeobject/) Funktion zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Verpacken Sie diese Klasse stets in einen [System::SmartPtr](../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [ProcessStartInfo](./processstartinfo/) | Beschreibt Prozessstartparameter. Objekte dieser Klasse sollten nur mit der [System::MakeObject()](../system/makeobject/) Funktion zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Verpacken Sie diese Klasse stets in einen [System::SmartPtr](../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [StackFrame](./stackframe/) | Erhält Informationen zu einem einzelnen Stack-Frame. Nur MSVS. Objekte dieser Klasse sollten nur mit der [System::MakeObject()](../system/makeobject/) Funktion zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Verpacken Sie diese Klasse stets in einen [System::SmartPtr](../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [StackTrace](./stacktrace/) | Sammlung von Stack-Frames. Objekte dieser Klasse sollten nur mit der [System::MakeObject()](../system/makeobject/) Funktion zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Verpacken Sie diese Klasse stets in einen [System::SmartPtr](../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [Stopwatch](./stopwatch/) | Ermöglicht Zeitmessung. Objekte dieser Klasse sollten nur mit der [System::MakeObject()](../system/makeobject/) Funktion zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Verpacken Sie diese Klasse stets in einen [System::SmartPtr](../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [TraceListener](./tracelistener/) | Schnittstelle, um auf Debug- und Trace-Informationen zu reagieren. Objekte dieser Klasse sollten nur mit der [System::MakeObject()](../system/makeobject/) Funktion zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Verpacken Sie diese Klasse stets in einen [System::SmartPtr](../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |

## Strukturen

| Struktur | Beschreibung |
| --- | --- |
| [Debug](./debug/) | Sammlung von Debug-Methoden, die das Senden von Debug-Informationen an registrierte Listener ermöglichen. Alle Ausgabefunktionen funktionieren nur in [Debug](./debug/). Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten unter keinen Umständen Instanzen davon erzeugen. |
| [Debugger](./debugger/) | [Debugger](./debugger/) Schnittstelle. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten unter keinen Umständen Instanzen davon erzeugen. |
| [Trace](./trace/) | Stellt eine Schnittstelle zum Zugriff auf den Debugger-Trace (falls vorhanden) bereit. Funktioniert nur im [Debug](./debug/) Modus. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten unter keinen Umständen Instanzen davon erzeugen. |

## Aufzählungen

| Aufzählung | Beschreibung |
| --- | --- |
| [ProcessWindowStyle](./processwindowstyle/) | Stil des Prozessfensters. |
| [TraceEventType](./traceeventtype/) | Identifiziert den Ereignistyp, der den Trace verursacht hat. |
| [TraceLevel](./tracelevel/) | Gibt an, welche Meldungen für die Klassen [System.Diagnostics.Debug](./debug/), [System.Diagnostics.Trace](./trace/) und System.Diagnostics.TraceSwitch ausgegeben werden sollen. |

## Typdefinitionen

| Typdefinition | Beschreibung |
| --- | --- |
| [StopwatchPtr](./stopwatchptr/) | Zeigertyp. |
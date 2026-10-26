---
title: Debug
second_title: Aspose.Slides für C++ API-Referenz
description: Sammlung von Debug-Methoden, die das Senden von Debug-Informationen an registrierte Listener ermöglichen. Alle Ausgabefunktionen funktionieren nur im Debug. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten unter keinen Umständen Instanzen davon erstellen.
type: docs
weight: 105
url: /de/system.diagnostics/debug/
---
## Debug-Struktur

Sammlung von Debug-Methoden, die das Senden von Debug-Informationen an registrierte Listener ermöglichen. Alle Ausgabefunktionen funktionieren nur in [Debug](./). Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten unter keinen Umständen Instanzen davon erstellen.

```cpp
class Debug
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static void [Assert](./assert/)(**bool**) | Prüft die Bedingung und sendet im Fehlerfall Informationen. |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&) | Prüft die Bedingung und sendet im Fehlerfall Informationen. |
| static void [Assert](./assert/)(**bool**, const char *) | Prüft die Bedingung und sendet im Fehlerfall Informationen. |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Prüft die Bedingung und sendet im Fehlerfall Informationen. |
| static void [Fail](./fail/)(const [String](../../system/string/)\&) | Sendet Fehlermeldung. |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<[TraceListener](../tracelistener/)\>\>\> [get_Listeners](./get_listeners/)() | Greift auf die statische Listener-Liste zu. |
| static void [Print](./print/)(const [String](../../system/string/)\&) | Gibt die Meldung an die Debug-Schnittstelle aus. |
| static void [Print](./print/)(const [String](../../system/string/)\&, const [System::ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>\&) | Gibt die Meldung an die Debug-Schnittstelle aus. |
| static void [Write](./write/)(const [String](../../system/string/)\&) | Schreibt die Zeichenkette an die Debug-Schnittstelle. |
| static void [Write](./write/)(const char_t *) | Schreibt die Zeichenkette an die Debug-Schnittstelle. |
| static void [WriteIf](./writeif/)(**bool**, const [System::String](../../system/string/)\&) | Schreibt die Zeichenkette an die Debug-Schnittstelle, wenn eine Bedingung wahr ist. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | Schreibt eine Zeile an die Debug-Schnittstelle. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Schreibt eine Zeile an die Debug-Schnittstelle. |
| static void [WriteLine](./writeline/)(const char_t *) | Schreibt eine Zeile an die Debug-Schnittstelle. |
| static void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Schreibt eine Zeile an die Debug-Schnittstelle. |
| static void [WriteLineIf](./writelineif/)(**bool**, const [System::String](../../system/string/)\&) | Schreibt eine Zeile an die Debug-Schnittstelle, wenn eine Bedingung wahr ist. |

## Siehe auch

* Namensraum [System::Diagnostics](../)
* Bibliothek [Aspose.Slides](../../)
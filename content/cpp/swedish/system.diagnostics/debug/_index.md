---
title: Debug
second_title: Aspose.Slides för C++ API-referens
description: Samling av felsökningsmetoder som möjliggör att skicka felsökningsinformation till registrerade lyssnare. Alla utskriftsfunktioner fungerar endast i Debug. Detta är en statisk typ utan instanstjänster. Du bör aldrig skapa instanser av den på något sätt.
type: docs
weight: 105
url: /sv/system.diagnostics/debug/
---
## Debugstruktur

Samling av felsökningsmetoder som möjliggör att skicka felsökningsinformation till registrerade lyssnare. Alla utskriftsfunktioner fungerar endast i [Debug](./). Detta är en statisk typ utan instanstjänster. Du bör aldrig skapa instanser av den på något sätt.

```cpp
class Debug
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static void [Assert](./assert/)(**bool**) | Kontrollera villkoret och skicka information vid fel. |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&) | Kontrollera villkoret och skicka information vid fel. |
| static void [Assert](./assert/)(**bool**, const char *) | Kontrollera villkoret och skicka information vid fel. |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Kontrollera villkoret och skicka information vid fel. |
| static void [Fail](./fail/)(const [String](../../system/string/)\&) | Skicka felmeddelande. |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<[TraceListener](../tracelistener/)\>\>\> [get_Listeners](./get_listeners/)() | Hämtar statisk lista över lyssnare. |
| static void [Print](./print/)(const [String](../../system/string/)\&) | Skriv ut meddelande till felsökningsgränssnittet. |
| static void [Print](./print/)(const [String](../../system/string/)\&, const [System::ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>\&) | Skriv ut meddelande till felsökningsgränssnittet. |
| static void [Write](./write/)(const [String](../../system/string/)\&) | Skriver sträng till felsökningsgränssnittet. |
| static void [Write](./write/)(const char_t *) | Skriver sträng till felsökningsgränssnittet. |
| static void [WriteIf](./writeif/)(**bool**, const [System::String](../../system/string/)\&) | Skriver sträng till felsökningsgränssnittet om ett villkor är sant. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | Skriver rad till felsökningsgränssnittet. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Skriver rad till felsökningsgränssnittet. |
| static void [WriteLine](./writeline/)(const char_t *) | Skriver rad till felsökningsgränssnittet. |
| static void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Skriver rad till felsökningsgränssnittet. |
| static void [WriteLineIf](./writelineif/)(**bool**, const [System::String](../../system/string/)\&) | Skriver rad till felsökningsgränssnittet om ett villkor är sant. |

## Se även

* Namnområde [System::Diagnostics](../)
* Bibliotek [Aspose.Slides](../../)
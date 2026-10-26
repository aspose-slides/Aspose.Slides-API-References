---
title: Debug
second_title: Aspose.Slides voor C++ API-referentie
description: Collectie van debugmethoden die het verzenden van debuginformatie naar geregistreerde luisteraars mogelijk maken. Alle uitvoerfuncties werken alleen in Debug. Dit is een statisch type zonder instantiediensten. Je moet nooit instanties ervan maken, op welke manier dan ook.
type: docs
weight: 105
url: /nl/system.diagnostics/debug/
---
## Debug struct

Collectie van debugmethoden die het mogelijk maken debug-informatie naar geregistreerde luisteraars te verzenden. Alle uitvoerfuncties werken alleen in [Debug](./). Dit is een statisch type zonder instantiediensten. Je moet nooit instanties ervan maken, op welke manier dan ook.

```cpp
class Debug
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static void [Assert](./assert/)(**bool**) | Controleer de voorwaarde en verzend informatie bij falen. |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&) | Controleer de voorwaarde en verzend informatie bij falen. |
| static void [Assert](./assert/)(**bool**, const char *) | Controleer de voorwaarde en verzend informatie bij falen. |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Controleer de voorwaarde en verzend informatie bij falen. |
| static void [Fail](./fail/)(const [String](../../system/string/)\&) | Verzend foutbericht. |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<[TraceListener](../tracelistener/)\>\>\> [get_Listeners](./get_listeners/)() | Benadert de statische lijst van luisteraars. |
| static void [Print](./print/)(const [String](../../system/string/)\&) | Print bericht naar debuginterface. |
| static void [Print](./print/)(const [String](../../system/string/)\&, const [System::ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>\&) | Print bericht naar debuginterface. |
| static void [Write](./write/)(const [String](../../system/string/)\&) | Schrijft string naar debuginterface. |
| static void [Write](./write/)(const char_t *) | Schrijft string naar debuginterface. |
| static void [WriteIf](./writeif/)(**bool**, const [System::String](../../system/string/)\&) | Schrijft string naar debuginterface als een voorwaarde waar is. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | Schrijft regel naar debuginterface. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Schrijft regel naar debuginterface. |
| static void [WriteLine](./writeline/)(const char_t *) | Schrijft regel naar debuginterface. |
| static void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Schrijft regel naar debuginterface. |
| static void [WriteLineIf](./writelineif/)(**bool**, const [System::String](../../system/string/)\&) | Schrijft regel naar debuginterface als een voorwaarde waar is. |

## Zie ook

* Namespace [System::Diagnostics](../)
* Library [Aspose.Slides](../../)
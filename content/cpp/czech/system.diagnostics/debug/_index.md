---
title: Debug
second_title: Aspose.Slides pro C++ referenční příručku
description: Sada ladicích metod umožňujících odesílání ladicích informací registrovaným posluchačům. Všechny výstupní funkce fungují pouze v Debug. Jedná se o statický typ bez instančních služeb. Neměli byste nikdy vytvářet jeho instance žádným způsobem.
type: docs
weight: 105
url: /cs/system.diagnostics/debug/
---
## Debug struktura


Sada ladicích metod umožňujících odesílání ladicích informací registrovaným posluchačům. Všechny výstupní funkce fungují pouze v [Debug](./). Jedná se o statický typ bez instančních služeb. Neměli byste nikdy vytvářet jeho instance žádným způsobem.

```cpp
class Debug
```

## Metody

| Metoda | Popis |
| --- | --- |
| static void [Assert](./assert/)(**bool**) | Ověří podmínku a po selhání odešle informace. |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&) | Ověří podmínku a po selhání odešle informace. |
| static void [Assert](./assert/)(**bool**, const char *) | Ověří podmínku a po selhání odešle informace. |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Ověří podmínku a po selhání odešle informace. |
| static void [Fail](./fail/)(const [String](../../system/string/)\&) | Odešle zprávu o selhání. |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<[TraceListener](../tracelistener/)\>\>\> [get_Listeners](./get_listeners/)() | Přistupuje ke statickému seznamu posluchačů. |
| static void [Print](./print/)(const [String](../../system/string/)\&) | Vytiskne zprávu do ladicího rozhraní. |
| static void [Print](./print/)(const [String](../../system/string/)\&, const [System::ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>\&) | Vytiskne zprávu do ladicího rozhraní. |
| static void [Write](./write/)(const [String](../../system/string/)\&) | Zapíše řetězec do ladicího rozhraní. |
| static void [Write](./write/)(const char_t *) | Zapíše řetězec do ladicího rozhraní. |
| static void [WriteIf](./writeif/)(**bool**, const [System::String](../../system/string/)\&) | Zapíše řetězec do ladicího rozhraní, pokud je podmínka pravdivá. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | Zapíše řádek do ladicího rozhraní. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Zapíše řádek do ladicího rozhraní. |
| static void [WriteLine](./writeline/)(const char_t *) | Zapíše řádek do ladicího rozhraní. |
| static void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Zapíše řádek do ladicího rozhraní. |
| static void [WriteLineIf](./writelineif/)(**bool**, const [System::String](../../system/string/)\&) | Zapíše řádek do ladicího rozhraní, pokud je podmínka pravdivá. |

## Viz také

* Jmenný prostor [System::Diagnostics](../)
* Knihovna [Aspose.Slides](../../)
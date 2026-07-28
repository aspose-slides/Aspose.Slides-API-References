---
title: Debug
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Zbiór metod debugowania umożliwiających wysyłanie informacji debugowych do zarejestrowanych słuchaczy. Wszystkie funkcje wyjściowe działają wyłącznie w trybie Debug. Jest to typ statyczny bez usług instancji. Nigdy nie należy tworzyć jego instancji w żaden sposób.
type: docs
weight: 105
url: /pl/system.diagnostics/debug/
---
## Struktura Debug

Zbiór metod debugowania umożliwiających wysyłanie informacji debugowych do zarejestrowanych słuchaczy. Wszystkie funkcje wyjściowe działają wyłącznie w [Debug](./). Jest to typ statyczny bez usług instancji. Nigdy nie należy tworzyć jego instancji w żaden sposób.

```cpp
class Debug
```

## Metody

| Metoda | Opis |
| --- | --- |
| static void [Assert](./assert/)(**bool**) | Sprawdź warunek i wyślij informacje w razie niepowodzenia. |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&) | Sprawdź warunek i wyślij informacje w razie niepowodzenia. |
| static void [Assert](./assert/)(**bool**, const char *) | Sprawdź warunek i wyślij informacje w razie niepowodzenia. |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Sprawdź warunek i wyślij informacje w razie niepowodzenia. |
| static void [Fail](./fail/)(const [String](../../system/string/)\&) | Wyślij komunikat o niepowodzeniu. |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<[TraceListener](../tracelistener/)\>\>\> [get_Listeners](./get_listeners/)() | Uzyskuje dostęp do statycznej listy słuchaczy. |
| static void [Print](./print/)(const [String](../../system/string/)\&) | Wypisz komunikat do interfejsu debugowania. |
| static void [Print](./print/)(const [String](../../system/string/)\&, const [System::ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>\&) | Wypisz komunikat do interfejsu debugowania. |
| static void [Write](./write/)(const [String](../../system/string/)\&) | Zapisuje ciąg znaków do interfejsu debugowania. |
| static void [Write](./write/)(const char_t *) | Zapisuje ciąg znaków do interfejsu debugowania. |
| static void [WriteIf](./writeif/)(**bool**, const [System::String](../../system/string/)\&) | Zapisuje ciąg znaków do interfejsu debugowania, jeśli warunek jest prawdziwy. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | Zapisuje linię do interfejsu debugowania. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Zapisuje linię do interfejsu debugowania. |
| static void [WriteLine](./writeline/)(const char_t *) | Zapisuje linię do interfejsu debugowania. |
| static void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Zapisuje linię do interfejsu debugowania. |
| static void [WriteLineIf](./writelineif/)(**bool**, const [System::String](../../system/string/)\&) | Zapisuje linię do interfejsu debugowania, jeśli warunek jest prawdziwy. |

## Zobacz także

* Przestrzeń nazw [System::Diagnostics](../)
* Biblioteka [Aspose.Slides](../../)
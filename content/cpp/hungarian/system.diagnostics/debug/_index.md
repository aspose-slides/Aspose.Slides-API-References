---
title: Debug
second_title: Aspose.Slides for C++ API-referencia
description: Debug-módszerek gyűjteménye, amely lehetővé teszi hibainformációk küldését a regisztrált hallgatóknak. Minden kimeneti függvény csak a Debug-ban működik. Ez egy statikus típus, amelynek nincs példányosítási szolgáltatása. Soha ne hozzon létre példányokat semmilyen módon.
type: docs
weight: 105
url: /hu/system.diagnostics/debug/
---
## Debug struktúra

A hibakeresési módszerek gyűjteménye, amely lehetővé teszi a hibainformációk küldését a regisztrált hallgatóknak. Minden kimeneti függvény csak a [Debug](./)-ban működik. Ez egy statikus típus, amelynek nincs példányosítási szolgáltatása. Soha ne hozzon létre példányokat semmilyen módon.

```cpp
class Debug
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| static void [Assert](./assert/)(**bool**) | Ellenőrzi a feltételt, és hiba esetén információt küld. |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&) | Ellenőrzi a feltételt, és hiba esetén információt küld. |
| static void [Assert](./assert/)(**bool**, const char *) | Ellenőrzi a feltételt, és hiba esetén információt küld. |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Ellenőrzi a feltételt, és hiba esetén információt küld. |
| static void [Fail](./fail/)(const [String](../../system/string/)\&) | Küld hibajelzést. |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<[TraceListener](../tracelistener/)\>\>\> [get_Listeners](./get_listeners/)() | Hozzáfér a statikus hallgatók listájához. |
| static void [Print](./print/)(const [String](../../system/string/)\&) | Kiírja az üzenetet a hibakeresési felületre. |
| static void [Print](./print/)(const [String](../../system/string/)\&, const [System::ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>\&) | Kiírja az üzenetet a hibakeresési felületre. |
| static void [Write](./write/)(const [String](../../system/string/)\&) | Szöveget ír a hibakeresési felületre. |
| static void [Write](./write/)(const char_t *) | Szöveget ír a hibakeresési felületre. |
| static void [WriteIf](./writeif/)(**bool**, const [System::String](../../system/string/)\&) | Szöveget ír a hibakeresési felületre, ha a feltétel igaz. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | Sorot ír a hibakeresési felületre. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Sorot ír a hibakeresési felületre. |
| static void [WriteLine](./writeline/)(const char_t *) | Sorot ír a hibakeresési felületre. |
| static void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Sorot ír a hibakeresési felületre. |
| static void [WriteLineIf](./writelineif/)(**bool**, const [System::String](../../system/string/)\&) | Sorot ír a hibakeresési felületre, ha a feltétel igaz. |

## Lásd még

* Névtér [System::Diagnostics](../)
* Könyvtár [Aspose.Slides](../../)
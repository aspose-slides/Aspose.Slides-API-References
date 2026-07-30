---
title: Debug
second_title: Riferimento API di Aspose.Slides per C++
description: Raccolta di metodi di debug che consentono l'invio di informazioni di debug a listener registrati. Tutte le funzioni di output funzionano solo in Debug. Si tratta di un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso in nessun modo.
type: docs
weight: 105
url: /it/system.diagnostics/debug/
---
## Struct di debug

Raccolta di metodi di debug che consentono l'invio di informazioni di debug a listener registrati. Tutte le funzioni di output funzionano solo in [Debug](./). Si tratta di un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso in nessun modo.

```cpp
class Debug
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| static void [Assert](./assert/)(**bool**) | Verifica la condizione e invia informazioni in caso di errore. |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&) | Verifica la condizione e invia informazioni in caso di errore. |
| static void [Assert](./assert/)(**bool**, const char *) | Verifica la condizione e invia informazioni in caso di errore. |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Verifica la condizione e invia informazioni in caso di errore. |
| static void [Fail](./fail/)(const [String](../../system/string/)\&) | Invia messaggio di errore. |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<[TraceListener](../tracelistener/)\>\>\> [get_Listeners](./get_listeners/)() | Accede all'elenco statico di listener. |
| static void [Print](./print/)(const [String](../../system/string/)\&) | Stampa messaggio sull'interfaccia di debug. |
| static void [Print](./print/)(const [String](../../system/string/)\&, const [System::ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>\&) | Stampa messaggio sull'interfaccia di debug. |
| static void [Write](./write/)(const [String](../../system/string/)\&) | Scrive stringa sull'interfaccia di debug. |
| static void [Write](./write/)(const char_t *) | Scrive stringa sull'interfaccia di debug. |
| static void [WriteIf](./writeif/)(**bool**, const [System::String](../../system/string/)\&) | Scrive stringa sull'interfaccia di debug se una condizione è vera. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | Scrive riga sull'interfaccia di debug. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Scrive riga sull'interfaccia di debug. |
| static void [WriteLine](./writeline/)(const char_t *) | Scrive riga sull'interfaccia di debug. |
| static void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Scrive riga sull'interfaccia di debug. |
| static void [WriteLineIf](./writelineif/)(**bool**, const [System::String](../../system/string/)\&) | Scrive riga sull'interfaccia di debug se una condizione è vera. |

## Vedi anche

* Spazio dei nomi [System::Diagnostics](../)
* Libreria [Aspose.Slides](../../)
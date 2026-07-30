---
title: Trace
second_title: Riferimento API di Aspose.Slides per C++
description: Fornisce un'interfaccia per accedere al trace del debugger (se presente). Funziona solo in modalità Debug. Questo è un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso in alcun modo.
type: docs
weight: 131
url: /it/system.diagnostics/trace/
---
## Struttura Trace

Fornisce un'interfaccia per accedere al trace del debugger (se presente). Funziona solo in modalità [Debug](../debug/). Questo è un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso in alcun modo.

```cpp
class Trace
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| static void [Flush](./flush/)() | Svuota il buffer di output e fa sì che i dati bufferizzati vengano scritti ai listener. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | Scrive una riga sul trace del debugger. |
## Vedi anche

* Namespace [System::Diagnostics](../)
* Libreria [Aspose.Slides](../../)
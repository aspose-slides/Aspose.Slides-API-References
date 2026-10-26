---
title: "System::Diagnostics"
second_title: Riferimento API Aspose.Slides per C++
description: 
type: docs
weight: 469
url: /it/system.diagnostics/
---
## Classi

| Classe | Descrizione |
| --- | --- |
| [FileVersionInfo](./fileversioninfo/) | Fornisce informazioni sulla versione del file. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò comporterà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento. |
| [PerformanceCounter](./performancecounter/) | Classe fittizia per consentire la compilazione del codice tradotto che utilizza PerformanceCounter. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò comporterà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento. |
| [Process](./process/) | Incapsula informazioni sul processo e la loro manipolazione. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò comporterà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento. |
| [ProcessStartInfo](./processstartinfo/) | Descrive i parametri di avvio del processo. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò comporterà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento. |
| [StackFrame](./stackframe/) | Ottiene informazioni su un singolo frame dello stack. Solo MSVS. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò comporterà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento. |
| [StackTrace](./stacktrace/) | Raccolta di frame dello stack. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò comporterà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento. |
| [Stopwatch](./stopwatch/) | Consente la misurazione del tempo. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò comporterà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento. |
| [TraceListener](./tracelistener/) | Interfaccia per reagire alle informazioni di debug e traccia. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò comporterà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento. |
## Strutture

| Struttura | Descrizione |
| --- | --- |
| [Debug](./debug/) | Raccolta di metodi di debug che consentono l'invio di informazioni di debug a listener registrati. Tutte le funzioni di output funzionano solo in [Debug](./debug/). Questo è un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso in alcun modo. |
| [Debugger](./debugger/) | Interfaccia [Debugger](./debugger/). Questo è un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso in alcun modo. |
| [Trace](./trace/) | Fornisce un'interfaccia per accedere alla traccia del debugger (se presente). Funziona solo in modalità [Debug](./debug/). Questo è un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso in alcun modo. |
## Enum

| Enum | Descrizione |
| --- | --- |
| [ProcessWindowStyle](./processwindowstyle/) | Stile della finestra del processo. |
| [TraceEventType](./traceeventtype/) | Identifica il tipo di evento che ha generato la traccia. |
| [TraceLevel](./tracelevel/) | Specifica quali messaggi emettere per le classi [System.Diagnostics.Debug](./debug/), [System.Diagnostics.Trace](./trace/) e System.Diagnostics.TraceSwitch. |
## Typedef

| Typedef | Descrizione |
| --- | --- |
| [StopwatchPtr](./stopwatchptr/) | Tipo puntatore. |
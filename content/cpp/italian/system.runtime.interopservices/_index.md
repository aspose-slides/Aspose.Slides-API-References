---
title: "System::Runtime::InteropServices"
second_title: Riferimento API di Aspose.Slides per C++
description: 
type: docs
weight: 781
url: /it/system.runtime.interopservices/
---
## Classi

| Classe | Descrizione |
| --- | --- |
| [Details_ExternalException](./details_externalexception/) | Il tipo di eccezione di base per tutte le eccezioni COM interop e le eccezioni di gestione delle eccezioni strutturate (SEH). Non creare mai istanze di questa classe manualmente. Utilizza invece la classe ExternalException. Non avvolgere mai le istanze della classe ExternalException in [System::SmartPtr](../system/smartptr/). |
| [Marshal](./marshal/) | Fornisce l'implementazione del marshalling. Solo per compatibilità con il codice tradotto, poiché nessun codice gestito è supportato sul lato C++. Questo è un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso con alcun mezzo. |
| [MemoryMarshal](./memorymarshal/) | Fornisce l'implementazione del marshalling della memoria. Solo per compatibilità con il codice tradotto, poiché nessun codice gestito è supportato sul lato C++. Questo è un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso con alcun mezzo. |
| [NativeLibrary](./nativelibrary/) |  |
| [OSPlatform](./osplatform/) |  |

## Strutture

| Struttura | Descrizione |
| --- | --- |
| [FILETIME](./filetime/) | Contiene i componenti di tempo del file. Questo tipo dovrebbe essere allocato sullo stack e passato alle funzioni per valore o per riferimento. Non usare mai la classe [System::SmartPtr](../system/smartptr/) per gestire oggetti di questo tipo. |
| [RuntimeInformation](./runtimeinformation/) |  |

## Enumerazioni

| Enumerazione | Descrizione |
| --- | --- |
| [GCHandleType](./gchandletype/) | Definisce come l'handle è gestito dal garbage collector. |
| [VarEnum](./varenum/) | Definisce come gli elementi dell'array devono essere marshalled. |

## Typedef

| Typedef | Descrizione |
| --- | --- |
| [ExternalException](./externalexception/) |  |
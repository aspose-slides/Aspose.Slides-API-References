---
title: BeginWrite()
second_title: Riferimento API Aspose.Slides per C++
description: Avvia un'operazione di scrittura asincrona.
type: docs
weight: 170
url: /it/system.io/stream/beginwrite/
---
## Stream::BeginWrite(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) metodo

Avvia un'operazione di scrittura asincrona.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Un buffer contenente i dati da scrivere |
| offset | int | Un offset basato su 0 in **buffer** che indica la posizione da cui iniziano i dati da scrivere |
| count | int | Il numero di byte da scrivere |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | Una callback da chiamare quando l'operazione è completata |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Dati forniti dall'utente usati per identificare univocamente ciascuna operazione di scrittura asincrona |

### Valore di ritorno

Un oggetto [IAsyncResult](../../../system/iasyncresult/) che rappresenta l'operazione di scrittura asincrona avviata

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Object](../../../system/object/)
* Classe [Stream](../)
* Spazio dei nomi [System::IO](../../)
* Libreria [Aspose.Slides](../../../)
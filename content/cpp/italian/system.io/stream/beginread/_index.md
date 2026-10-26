---
title: BeginRead()
second_title: Aspose.Slides per C++ Riferimento API
description: Avvia un'operazione di lettura asincrona.
type: docs
weight: 157
url: /it/system.io/stream/beginread/
---
## Stream::BeginRead(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) metodo


Avvia un'operazione di lettura asincrona.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginRead(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Un buffer su cui leggere |
| offset | int | Un offset base 0 in **buffer** che indica la posizione da cui iniziare a scrivere i dati letti |
| count | int | Il numero di byte da leggere |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | Un callback da chiamare quando l'operazione è completata |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Dati forniti dall'utente usati per identificare in modo univoco ogni operazione di lettura asincrona |

### Valore di ritorno

Un oggetto [IAsyncResult](../../../system/iasyncresult/) che rappresenta l'operazione di lettura asincrona avviata

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Object](../../../system/object/)
* Classe [Stream](../)
* Spazio dei nomi [System::IO](../../)
* Library [Aspose.Slides](../../../)
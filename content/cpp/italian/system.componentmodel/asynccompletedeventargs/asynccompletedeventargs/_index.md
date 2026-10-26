---
title: AsyncCompletedEventArgs()
second_title: Riferimento API di Aspose.Slides per C++
description: Costruttore.
type: docs
weight: 1
url: /it/system.componentmodel/asynccompletedeventargs/asynccompletedeventargs/
---
## AsyncCompletedEventArgs::AsyncCompletedEventArgs() costruttore

Costruttore.

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs()
```

## AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception\&, bool, const System::SharedPtr\<System::Object\>\&) costruttore

Inizializza una nuova istanza della classe [System.ComponentModel.AsyncCompletedEventArgs](../).

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception &error, bool canceled, const System::SharedPtr<System::Object> &userState)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| error | const [System::Exception](../../../system/exception/)\& | Qualsiasi errore verificatosi durante l'operazione asincrona. |
| canceled | **bool** | Un valore che indica se l'operazione asincrona è stata annullata. |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | L'oggetto di stato opzionale fornito dall'utente passato al metodo [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../backgroundworker/runworkerasync/)([System.Object](../../../system/object/)). |

## Vedi anche

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [AsyncCompletedEventArgs](../)
* Classe [Object](../../../system/object/)
* Spazio dei nomi [System::ComponentModel](../../)
* Libreria [Aspose.Slides](../../../)
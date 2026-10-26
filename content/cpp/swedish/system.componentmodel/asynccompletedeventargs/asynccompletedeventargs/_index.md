---
title: AsyncCompletedEventArgs()
second_title: Aspose.Slides för C++ API-referens
description: Konstruktör.
type: docs
weight: 1
url: /sv/system.componentmodel/asynccompletedeventargs/asynccompletedeventargs/
---
## AsyncCompletedEventArgs::AsyncCompletedEventArgs() konstruktör

Konstruktör.

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs()
```

## AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception\&, bool, const System::SharedPtr\<System::Object\>\&) konstruktör

Initierar en ny instans av klassen [System.ComponentModel.AsyncCompletedEventArgs](../).

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception &error, bool canceled, const System::SharedPtr<System::Object> &userState)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| error | const [System::Exception](../../../system/exception/)\& | Alla fel som uppstod under den asynkrona operationen. |
| canceled | **bool** | Ett värde som indikerar om den asynkrona operationen avbröts. |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Det valfria användarskickade tillståndsobjektet som skickas till metoden [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../backgroundworker/runworkerasync/)([System.Object](../../../system/object/)). |

## Se även

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [AsyncCompletedEventArgs](../)
* Klass [Object](../../../system/object/)
* Namnrymd [System::ComponentModel](../../)
* Bibliotek [Aspose.Slides](../../../)
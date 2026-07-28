---
title: AsyncCompletedEventArgs()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Konstruktor.
type: docs
weight: 1
url: /pl/system.componentmodel/asynccompletedeventargs/asynccompletedeventargs/
---
## AsyncCompletedEventArgs::AsyncCompletedEventArgs() konstruktor

Konstruktor.

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs()
```

## AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception\&, bool, const System::SharedPtr\<System::Object\>\&) konstruktor

Inicjalizuje nową instancję klasy [System.ComponentModel.AsyncCompletedEventArgs](../).

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception &error, bool canceled, const System::SharedPtr<System::Object> &userState)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| error | const [System::Exception](../../../system/exception/)\& | Jakikolwiek błąd, który wystąpił podczas operacji asynchronicznej. |
| canceled | **bool** | Wartość wskazująca, czy operacja asynchroniczna została anulowana. |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Opcjonalny obiekt stanu dostarczony przez użytkownika, przekazywany do metody [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../backgroundworker/runworkerasync/)([System.Object](../../../system/object/)). |

## Zobacz także

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [AsyncCompletedEventArgs](../)
* Klasa [Object](../../../system/object/)
* Przestrzeń nazw [System::ComponentModel](../../)
* Biblioteka [Aspose.Slides](../../../)
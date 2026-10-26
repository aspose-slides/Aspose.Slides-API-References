---
title: AsyncCompletedEventArgs()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Konstruktor.
type: docs
weight: 1
url: /cs/system.componentmodel/asynccompletedeventargs/asynccompletedeventargs/
---
## AsyncCompletedEventArgs::AsyncCompletedEventArgs() konstruktor


Konstruktor.

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs()
```

## AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception\&, bool, const System::SharedPtr\<System::Object\>\&) konstruktor


Inicializuje novou instanci třídy [System.ComponentModel.AsyncCompletedEventArgs](../).

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception &error, bool canceled, const System::SharedPtr<System::Object> &userState)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| error | const [System::Exception](../../../system/exception/)\& | Jakákoli chyba, která se vyskytla během asynchronní operace. |
| canceled | **bool** | Hodnota udávající, zda byla asynchronní operace zrušena. |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Volitelný objekt stavu dodaný uživatelem, předaný metodě [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../backgroundworker/runworkerasync/)([System.Object](../../../system/object/)). |

## Viz také

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [AsyncCompletedEventArgs](../)
* Třída [Object](../../../system/object/)
* Jmenný prostor [System::ComponentModel](../../)
* Knihovna [Aspose.Slides](../../../)
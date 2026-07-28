---
title: AsyncCompletedEventArgs()
second_title: Aspose.Slides C++ API referenciája
description: Konstruktor.
type: docs
weight: 1
url: /hu/system.componentmodel/asynccompletedeventargs/asynccompletedeventargs/
---
## AsyncCompletedEventArgs::AsyncCompletedEventArgs() konstruktor


Konstruktor.

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs()
```

## AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception\&, bool, const System::SharedPtr\<System::Object\>\&) konstruktor


Új példányt inicializál a [System.ComponentModel.AsyncCompletedEventArgs](../) osztályból.

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception &error, bool canceled, const System::SharedPtr<System::Object> &userState)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| error | const [System::Exception](../../../system/exception/)\& | Bármilyen hiba, amely az aszinkron művelet során történt. |
| canceled | **bool** | Érték, amely jelzi, hogy az aszinkron művelet le lett-e állítva. |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Az opcionálisan felhasználó által megadott állapotobjektum, amelyet a [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../backgroundworker/runworkerasync/)([System.Object](../../../system/object/)) metódusba adtak át. |

## Lásd még

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [AsyncCompletedEventArgs](../)
* Class [Object](../../../system/object/)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)
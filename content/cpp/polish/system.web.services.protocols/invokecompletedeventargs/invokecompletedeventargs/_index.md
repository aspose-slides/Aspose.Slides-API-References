---
title: InvokeCompletedEventArgs()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Tworzy nową instancję.
type: docs
weight: 14
url: /pl/system.web.services.protocols/invokecompletedeventargs/invokecompletedeventargs/
---
## InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception, bool, System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<Object\>\>) konstruktor


Tworzy nową instancję.

```cpp
System::Web::Services::Protocols::InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception error, bool cancelled, System::SharedPtr<Object> userState, System::ArrayPtr<System::SharedPtr<Object>> results)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| error | [Exception](../../../system/exception/) | Dowolny błąd, który wystąpił podczas operacji asynchronicznej. |
| cancelled | **bool** | Wartość wskazująca, czy operacja asynchroniczna została anulowana. |
| userState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Opcjonalny obiekt stanu dostarczony przez użytkownika, przekazywany do metody [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../../system.componentmodel/backgroundworker/runworkerasync/)([System.Object](../../../system/object/)). |
| results | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | Zbiór wyników operacji asynchronicznej. |

## Zobacz także

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [Object](../../../system/object/)
* Klasa [InvokeCompletedEventArgs](../)
* Przestrzeń nazw [System::Web::Services::Protocols](../../)
* Biblioteka [Aspose.Slides](../../../)
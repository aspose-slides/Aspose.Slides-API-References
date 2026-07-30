---
title: InvokeCompletedEventArgs()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Vytvoří novou instanci.
type: docs
weight: 14
url: /cs/system.web.services.protocols/invokecompletedeventargs/invokecompletedeventargs/
---
## InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception, bool, System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<Object\>\>) constructor


Vytvoří novou instanci.

```cpp
System::Web::Services::Protocols::InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception error, bool cancelled, System::SharedPtr<Object> userState, System::ArrayPtr<System::SharedPtr<Object>> results)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| error | [Exception](../../../system/exception/) | Jakákoliv chyba, ke které došlo během asynchronní operace. |
| cancelled | **bool** | Hodnota, která označuje, zda je asynchronní operace zrušena. |
| userState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Volitelný stavový objekt poskytnutý uživatelem, který je předán metodě [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../../system.componentmodel/backgroundworker/runworkerasync/)([System.Object](../../../system/object/)). |
| results | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | Kolekce výsledků asynchronní operace. |

## Viz také

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Object](../../../system/object/)
* Class [InvokeCompletedEventArgs](../)
* Namespace [System::Web::Services::Protocols](../../)
* Library [Aspose.Slides](../../../)
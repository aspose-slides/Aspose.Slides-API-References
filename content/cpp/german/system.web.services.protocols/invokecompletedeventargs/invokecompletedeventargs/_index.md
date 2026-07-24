---
title: InvokeCompletedEventArgs()
second_title: Aspose.Slides für C++ API-Referenz
description: Konstruiert eine neue Instanz.
type: docs
weight: 14
url: /de/system.web.services.protocols/invokecompletedeventargs/invokecompletedeventargs/
---
## InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception, bool, System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<Object\>\>) constructor

Konstruiert eine neue Instanz.

```cpp
System::Web::Services::Protocols::InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception error, bool cancelled, System::SharedPtr<Object> userState, System::ArrayPtr<System::SharedPtr<Object>> results)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| error | [Exception](../../../system/exception/) | Ein beliebiger Fehler, der während einer asynchronen Operation aufgetreten ist. |
| cancelled | **bool** | Ein Wert, der angibt, ob eine asynchrone Operation abgebrochen wurde. |
| userState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Das optionale vom Benutzer bereitgestellte Zustandsobjekt, das an die [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../../system.componentmodel/backgroundworker/runworkerasync/)([System.Object](../../../system/object/)) Methode übergeben wird. |
| results | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | Eine Sammlung von Ergebnissen asynchroner Operationen. |

## Siehe auch

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Object](../../../system/object/)
* Klasse [InvokeCompletedEventArgs](../)
* Namensraum [System::Web::Services::Protocols](../../)
* Bibliothek [Aspose.Slides](../../../)
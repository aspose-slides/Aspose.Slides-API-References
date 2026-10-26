---
title: InvokeCompletedEventArgs()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny instans.
type: docs
weight: 14
url: /sv/system.web.services.protocols/invokecompletedeventargs/invokecompletedeventargs/
---
## InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception, bool, System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<Object\>\>) konstruktor


Skapar en ny instans.

```cpp
System::Web::Services::Protocols::InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception error, bool cancelled, System::SharedPtr<Object> userState, System::ArrayPtr<System::SharedPtr<Object>> results)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| error | [Exception](../../../system/exception/) | Eventuellt fel som inträffade under en asynkron operation. |
| cancelled | **bool** | Ett värde som indikerar om en asynkron operation har avbrutits. |
| userState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Det valfria av användaren tillhandahållna tillståndsobjektet som skickas till metoden [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../../system.componentmodel/backgroundworker/runworkerasync/)([System.Object](../../../system/object/)). |
| results | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | En samling av resultat från asynkrona operationer. |

## Se också

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [Object](../../../system/object/)
* Klass [InvokeCompletedEventArgs](../)
* Namnrymd [System::Web::Services::Protocols](../../)
* Bibliotek [Aspose.Slides](../../../)
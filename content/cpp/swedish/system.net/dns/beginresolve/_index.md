---
title: BeginResolve()
second_title: Aspose.Slides för C++ API-referens
description: Initierar en asynkron operation för att skapa en ny IPHostEntry-klassinstans med det angivna värdnamnet.
type: docs
weight: 157
url: /sv/system.net/dns/beginresolve/
---
## Dns::BeginResolve(String, AsyncCallback, System::SharedPtr\<Object\>) metod


Initierar en asynkron operation för att skapa en ny IPHostEntry-klassinstans med det angivna värdnamnet.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginResolve(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | Ett värdnamn som används för att skapa en ny instans av klassen [IPHostEntry](../../iphostentry/). |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | En återuppringning som ska anropas när operationen är klar. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Användarlevererad data som används för att unikt identifiera varje asynkron operation. |

### Returvärde

Ett [IAsyncResult](../../../system/iasyncresult/)-objekt som representerar den initierade asynkrona operationen.

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klass [IAsyncResult](../../../system/iasyncresult/)
* Klass [String](../../../system/string/)
* Klass [Object](../../../system/object/)
* Klass [Dns](../)
* Namnrymd [System::Net](../../)
* Bibliotek [Aspose.Slides](../../../)
---
title: BeginGetHostAddresses()
second_title: Aspose.Slides för C++ API-referens
description: Initierar en asynkron operation för att skapa en ny IPHostEntry-class instans med den angivna strängen som innehåller ett värdnamn eller en IP-adress.
type: docs
weight: 131
url: /sv/system.net/dns/begingethostaddresses/
---
## Dns::BeginGetHostAddresses(String, AsyncCallback, System::SharedPtr\<Object\>) metod


Initierar en asynkron operation för att skapa en ny IPHostEntry-class instans med den angivna strängen som innehåller ett värdnamn eller en IP-adress.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostAddresses(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | En sträng som innehåller ett värdnamn eller en IP-adress. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Ett återanrop som ska anropas när operationen är klar. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Användarlevererade data som används för att unikt identifiera varje asynkron operation. |

### Returvärde

Ett [IAsyncResult](../../../system/iasyncresult/) objekt som representerar den initierade asynkrona operationen.

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klass [IAsyncResult](../../../system/iasyncresult/)
* Klass [String](../../../system/string/)
* Klass [Object](../../../system/object/)
* Klass [Dns](../)
* Namnrymd [System::Net](../../)
* Bibliotek [Aspose.Slides](../../../)
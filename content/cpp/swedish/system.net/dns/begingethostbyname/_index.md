---
title: BeginGetHostByName()
second_title: Aspose.Slides för C++ API-referens
description: Initierar en asynkron operation för att skapa en ny IPHostEntry-klassinstans med det angivna värdnamnet.
type: docs
weight: 53
url: /sv/system.net/dns/begingethostbyname/
---
## Dns::BeginGetHostByName(String, AsyncCallback, System::SharedPtr\<Object\>) metod

Initierar en asynkron operation för att skapa en ny IPHostEntry-klassinstans med det angivna värdnamnet.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostByName(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | Ett värdnamn. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Ett återanrop som ska anropas när operationen slutförs. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Användarlevererade data som används för att entydigt identifiera varje asynkron operation. |

### Returvärde

Ett [IAsyncResult](../../../system/iasyncresult/)-objekt som representerar den initierade asynkrona operationen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klass [IAsyncResult](../../../system/iasyncresult/)
* Klass [String](../../../system/string/)
* Klass [Object](../../../system/object/)
* Klass [Dns](../)
* Namnrymd [System::Net](../../)
* Library [Aspose.Slides](../../../)
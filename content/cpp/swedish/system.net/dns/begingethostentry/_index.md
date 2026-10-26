---
title: BeginGetHostEntry()
second_title: Aspose.Slides för C++ API-referens
description: Initierar en asynkron operation för att skapa en ny IPHostEntry-klassinstans med den angivna strängen som innehåller ett värdnamn eller en IP-adress.
type: docs
weight: 105
url: /sv/system.net/dns/begingethostentry/
---
## Dns::BeginGetHostEntry(String, AsyncCallback, System::SharedPtr\<Object\>) metod

Initierar en asynkron operation för att skapa en ny IPHostEntry-klassinstans med den angivna strängen som innehåller ett värdnamn eller en IP-adress.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | Strängen som innehåller ett värdnamn eller en IP-adress. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | En återuppringning som ska anropas när operationen slutförs. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Användarlevererad data som används för att unikt identifiera varje asynkron operation. |

### Returvärde

Ett [IAsyncResult](../../../system/iasyncresult/)-objekt som representerar den initierade asynkrona operationen.

## Dns::BeginGetHostEntry(System::SharedPtr\<IPAddress\>, AsyncCallback, System::SharedPtr\<Object\>) metod

Initierar en asynkron operation för att skapa en ny IPHostEntry-klassinstans med den angivna IP-adressen.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(System::SharedPtr<IPAddress> address, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | IP-adressen. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | En återuppringning som ska anropas när operationen slutförs. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Användarlevererad data som används för att unikt identifiera varje asynkron operation. |

### Returvärde

Ett [IAsyncResult](../../../system/iasyncresult/)-objekt som representerar den initierade asynkrona operationen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klass [IAsyncResult](../../../system/iasyncresult/)
* Klass [String](../../../system/string/)
* Klass [Object](../../../system/object/)
* Klass [Dns](../)
* Klass [IPAddress](../../ipaddress/)
* Namnrymd [System::Net](../../)
* Bibliotek [Aspose.Slides](../../../)
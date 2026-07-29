---
title: BeginGetRequestStream()
second_title: Aspose.Slides för C++ API-referens
description: Initierar en asynkron operation för att hämta en ström för att skriva data till resursen.
type: docs
weight: 469
url: /sv/system.net/httpwebrequest/begingetrequeststream/
---
## HttpWebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) metod

Initierar en asynkron operation för att hämta en ström för att skriva data till resursen.

```cpp
System::SharedPtr<IAsyncResult> System::Net::HttpWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | En återuppringning som ska anropas när operationen är klar. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Användardefinierade data som används för att unikt identifiera varje asynkron operation. |

### Returvärde

Ett [IAsyncResult](../../../system/iasyncresult/)-objekt som representerar den initierade asynkrona operationen.

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klass [IAsyncResult](../../../system/iasyncresult/)
* Klass [Object](../../../system/object/)
* Klass [HttpWebRequest](../)
* Namnrymd [System::Net](../../)
* Bibliotek [Aspose.Slides](../../../)
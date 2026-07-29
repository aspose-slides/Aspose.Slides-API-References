---
title: BeginGetResponse()
second_title: Aspose.Slides för C++ API-referens
description: Initierar en asynkron begäran av resursen.
type: docs
weight: 495
url: /sv/system.net/httpwebrequest/begingetresponse/
---
## HttpWebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) metod

Initierar en asynkron begäran av resursen.

```cpp
System::SharedPtr<IAsyncResult> System::Net::HttpWebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | En återuppringning som ska anropas när operationen slutförs. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Data som tillhandahålls av användaren och används för att unikt identifiera varje asynkron operation. |

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
---
title: BeginGetResponse()
second_title: Aspose.Slides för C++ API-referens
description: Initierar en asynkron begäran om resursen.
type: docs
weight: 170
url: /sv/system.net/filewebrequest/begingetresponse/
---
## FileWebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) metod


Initierar en asynkron begäran om resursen.

```cpp
System::SharedPtr<IAsyncResult> System::Net::FileWebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | En återuppringning som ska anropas när operationen är slutförd. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Användargenererade data som används för att unikt identifiera varje asynkron operation. |

### Returvärde

Ett [IAsyncResult](../../../system/iasyncresult/)-objekt som representerar den initierade asynkrona operationen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klass [IAsyncResult](../../../system/iasyncresult/)
* Klass [Object](../../../system/object/)
* Klass [FileWebRequest](../)
* Namnrymd [System::Net](../../)
* Bibliotek [Aspose.Slides](../../../)
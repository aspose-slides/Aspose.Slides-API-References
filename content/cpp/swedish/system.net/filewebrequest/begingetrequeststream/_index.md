---
title: BeginGetRequestStream()
second_title: Aspose.Slides för C++ API-referens
description: Initierar en asynkron operation för att få en ström för att skriva data till resursen.
type: docs
weight: 144
url: /sv/system.net/filewebrequest/begingetrequeststream/
---
## FileWebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) metod

Initierar en asynkron operation för att få en ström för att skriva data till resursen.

```cpp
System::SharedPtr<IAsyncResult> System::Net::FileWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | En återuppringning som ska anropas när operationen är klar. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Användarlevererade data som används för att unikt identifiera varje asynkron operation. |

### Returvärde

Ett [IAsyncResult](../../../system/iasyncresult/)-objekt som representerar den initierade asynkrona operationen.

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Typdefinition [AsyncCallback](../../../system/asynccallback/)
* Klass [IAsyncResult](../../../system/iasyncresult/)
* Klass [Object](../../../system/object/)
* Klass [FileWebRequest](../)
* Namnrymd [System::Net](../../)
* Bibliotek [Aspose.Slides](../../../)
---
title: BeginGetResponse()
second_title: Aspose.Slides C++ API referenciája
description: Aszinkron kérést indít az erőforrásra.
type: docs
weight: 170
url: /hu/system.net/filewebrequest/begingetresponse/
---
## FileWebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) metódus


Aszinkron kérést indít az erőforrásra.

```cpp
System::SharedPtr<IAsyncResult> System::Net::FileWebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | A visszahívás, amelyet akkor hívnak meg, amikor a művelet befejeződik. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Felhasználó által megadott adat, amely egyedileg azonosítja az egyes aszinkron műveleteket. |

### Visszatérési érték

Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely az indított aszinkron műveletet képviseli.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Típusdefiníció [AsyncCallback](../../../system/asynccallback/)
* Osztály [IAsyncResult](../../../system/iasyncresult/)
* Osztály [Object](../../../system/object/)
* Osztály [FileWebRequest](../)
* Névtér [System::Net](../../)
* Könyvtár [Aspose.Slides](../../../)
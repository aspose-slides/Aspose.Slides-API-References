---
title: BeginGetResponse()
second_title: Aspose.Slides C++ API referencia
description: Elindít egy aszinkron kérést az erőforrásra.
type: docs
weight: 274
url: /hu/system.net/webrequest/begingetresponse/
---
## WebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) módszer

Elindít egy aszinkron kérést az erőforrásra.

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | A visszahívás, amely a művelet befejeződésekor hívódik meg. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | A felhasználó által biztosított adat, amelyet az egyes aszinkron műveletek egyedi azonosítására használnak. |

### Visszatérési érték

Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely a kezdeményezett aszinkron műveletet képviseli.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Típusdefiníció [AsyncCallback](../../../system/asynccallback/)
* Osztály [IAsyncResult](../../../system/iasyncresult/)
* Osztály [Object](../../../system/object/)
* Osztály [WebRequest](../)
* Névterület [System::Net](../../)
* Könyvtár [Aspose.Slides](../../../)
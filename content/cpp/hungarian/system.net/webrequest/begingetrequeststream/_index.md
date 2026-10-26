---
title: BeginGetRequestStream()
second_title: Aspose.Slides C++ API referencia
description: Elindít egy aszinkron műveletet, amelynek célja egy adatfolyam megszerzése az erőforrásba íráshoz.
type: docs
weight: 300
url: /hu/system.net/webrequest/begingetrequeststream/
---
## WebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) method

Elindít egy aszinkron műveletet, amelynek célja egy adatfolyam megszerzése az erőforrásba íráshoz.

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Egy visszahívás, amelyet a művelet befejeződésekor hívnak meg. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | A felhasználó által biztosított adat, amely egyedileg azonosítja az egyes aszinkron műveleteket. |

### Visszatérési érték

Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely a kezdeményezett aszinkron műveletet képviseli.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Osztály [IAsyncResult](../../../system/iasyncresult/)
* Osztály [Object](../../../system/object/)
* Osztály [WebRequest](../)
* Névtér [System::Net](../../)
* Könyvtár [Aspose.Slides](../../../)
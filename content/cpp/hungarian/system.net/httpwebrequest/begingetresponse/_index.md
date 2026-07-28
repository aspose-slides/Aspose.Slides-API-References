---
title: BeginGetResponse()
second_title: Aspose.Slides for C++ API Referencia
description: Elindít egy aszinkron kérést az erőforrásra.
type: docs
weight: 495
url: /hu/system.net/httpwebrequest/begingetresponse/
---
## HttpWebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) metódus

Elindít egy aszinkron kérést az erőforrásra.

```cpp
System::SharedPtr<IAsyncResult> System::Net::HttpWebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Egy visszahívás, amely a művelet befejezésekor hívódik meg. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Felhasználó által biztosított adat, amely minden aszinkron művelet egyedi azonosítására szolgál. |

### Visszatérési érték

Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely az elindított aszinkron műveletet képviseli.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Osztály [IAsyncResult](../../../system/iasyncresult/)
* Osztály [Object](../../../system/object/)
* Osztály [HttpWebRequest](../)
* Névtér [System::Net](../../)
* Könyvtár [Aspose.Slides](../../../)
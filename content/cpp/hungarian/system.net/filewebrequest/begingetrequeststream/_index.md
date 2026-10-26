---
title: BeginGetRequestStream()
second_title: Aspose.Slides for C++ API referenciája
description: Elindít egy aszinkron műveletet, amely adatfolyamot biztosít az erőforrásba írandó adatokhoz.
type: docs
weight: 144
url: /hu/system.net/filewebrequest/begingetrequeststream/
---
## FileWebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) metódus

Elindít egy aszinkron műveletet, amely adatfolyamot biztosít az erőforrásba írandó adatokhoz.

```cpp
System::SharedPtr<IAsyncResult> System::Net::FileWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Egy visszahívás, amely a művelet befejezésekor hívódik meg. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Felhasználó által megadott adatok, amelyek egyedileg azonosítják az egyes aszinkron műveleteket. |

### Visszatérési érték

Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely az elindított aszinkron műveletet képviseli.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Típusdefiníció [AsyncCallback](../../../system/asynccallback/)
* Osztály [IAsyncResult](../../../system/iasyncresult/)
* Osztály [Object](../../../system/object/)
* Osztály [FileWebRequest](../)
* Névtér [System::Net](../../)
* Könyvtár [Aspose.Slides](../../../)
---
title: BeginGetResponse()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Spouští asynchronní požadavek na zdroj.
type: docs
weight: 495
url: /cs/system.net/httpwebrequest/begingetresponse/
---
## HttpWebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) metoda

Spouští asynchronní požadavek na zdroj.

```cpp
System::SharedPtr<IAsyncResult> System::Net::HttpWebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Callback, který bude zavolán po dokončení operace. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Uživatelem poskytnutá data používaná k jednoznačné identifikaci každé asynchronní operace. |

### Návratová hodnota

Objekt [IAsyncResult](../../../system/iasyncresult/) představující zahájenou asynchronní operaci.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Třída [IAsyncResult](../../../system/iasyncresult/)
* Třída [Object](../../../system/object/)
* Třída [HttpWebRequest](../)
* Jmenný prostor [System::Net](../../)
* Knihovna [Aspose.Slides](../../../)
---
title: BeginGetResponse()
second_title: Referenční příručka API Aspose.Slides pro C++
description: Zahajuje asynchronní požadavek na zdroj.
type: docs
weight: 170
url: /cs/system.net/filewebrequest/begingetresponse/
---
## FileWebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) metoda

Zahajuje asynchronní požadavek na zdroj.

```cpp
System::SharedPtr<IAsyncResult> System::Net::FileWebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | callback, který bude vyvolán po dokončení operace. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Uživatelem poskytnutá data používaná k jedinečné identifikaci každé asynchronní operace. |

### Návratová hodnota

Objekt [IAsyncResult](../../../system/iasyncresult/) představující zahájenou asynchronní operaci.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Třída [IAsyncResult](../../../system/iasyncresult/)
* Třída [Object](../../../system/object/)
* Třída [FileWebRequest](../)
* Jmenný prostor [System::Net](../../)
* Knihovna [Aspose.Slides](../../../)
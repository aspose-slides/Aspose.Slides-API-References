---
title: BeginGetResponse()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Inicializuje asynchronní požadavek na zdroj.
type: docs
weight: 274
url: /cs/system.net/webrequest/begingetresponse/
---
## WebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) metoda

Inicializuje asynchronní požadavek na zdroj.

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Zpětné volání, které bude vyvoláno po dokončení operace. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Uživatelem poskytnutá data používaná k jedinečnému identifikování každé asynchronní operace. |

### Návratová hodnota

Objekt [IAsyncResult](../../../system/iasyncresult/) představující zahájenou asynchronní operaci.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Object](../../../system/object/)
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)
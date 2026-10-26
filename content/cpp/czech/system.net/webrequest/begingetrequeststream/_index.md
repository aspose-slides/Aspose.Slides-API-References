---
title: BeginGetRequestStream()
second_title: Aspose.Slides pro C++ – reference API
description: Inicializuje asynchronní operaci pro získání streamu pro zápis dat do prostředku.
type: docs
weight: 300
url: /cs/system.net/webrequest/begingetrequeststream/
---
## WebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) metoda

Inicializuje asynchronní operaci pro získání streamu pro zápis dat do prostředku.

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Callback, který se má zavolat po dokončení operace. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Data poskytnutá uživatelem používaná k jednoznačné identifikaci každé asynchronní operace. |

### Návratová hodnota

Objekt [IAsyncResult](../../../system/iasyncresult/) představující zahájenou asynchronní operaci.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Třída [IAsyncResult](../../../system/iasyncresult/)
* Třída [Object](../../../system/object/)
* Třída [WebRequest](../)
* Jmenný prostor [System::Net](../../)
* Library [Aspose.Slides](../../../)
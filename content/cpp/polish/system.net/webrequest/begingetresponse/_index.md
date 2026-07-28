---
title: BeginGetResponse()
second_title: Aspose.Slides for C++ Referencja API
description: Inicjuje asynchroniczne żądanie zasobu.
type: docs
weight: 274
url: /pl/system.net/webrequest/begingetresponse/
---
## WebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) metoda

Inicjuje asynchroniczne żądanie zasobu.

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Wywołanie zwrotne, które zostanie wywołane po zakończeniu operacji. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dane dostarczone przez użytkownika, używane do jednoznacznego identyfikowania każdej asynchronicznej operacji. |

### Wartość zwracana

Obiekt [IAsyncResult](../../../system/iasyncresult/) reprezentujący zainicjowaną asynchroniczną operację.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klasa [IAsyncResult](../../../system/iasyncresult/)
* Klasa [Object](../../../system/object/)
* Klasa [WebRequest](../)
* Przestrzeń nazw [System::Net](../../)
* Biblioteka [Aspose.Slides](../../../)
---
title: BeginGetRequestStream()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Inicjuje asynchroniczną operację w celu uzyskania strumienia do zapisywania danych w zasobie.
type: docs
weight: 300
url: /pl/system.net/webrequest/begingetrequeststream/
---
## WebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) metoda

Inicjuje asynchroniczną operację w celu uzyskania strumienia do zapisywania danych w zasobie.

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Wywołanie zwrotne, które zostanie wywołane po zakończeniu operacji. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dane dostarczone przez użytkownika używane do jednoznacznej identyfikacji każdej asynchronicznej operacji. |

### Wartość zwracana

[IAsyncResult](../../../system/iasyncresult/) obiekt reprezentujący zainicjowaną asynchroniczną operację.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klasa [IAsyncResult](../../../system/iasyncresult/)
* Klasa [Object](../../../system/object/)
* Klasa [WebRequest](../)
* Przestrzeń nazw [System::Net](../../)
* Biblioteka [Aspose.Slides](../../../)
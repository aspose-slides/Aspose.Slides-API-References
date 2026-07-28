---
title: BeginGetRequestStream()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Inicjuje asynchroniczną operację uzyskania strumienia do zapisywania danych w zasobie.
type: docs
weight: 469
url: /pl/system.net/httpwebrequest/begingetrequeststream/
---
## HttpWebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) metoda

Inicjuje asynchroniczną operację uzyskania strumienia do zapisywania danych w zasobie.

```cpp
System::SharedPtr<IAsyncResult> System::Net::HttpWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Wywołanie zwrotne, które zostanie wywołane po zakończeniu operacji. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dane dostarczone przez użytkownika używane do jednoznacznej identyfikacji każdej asynchronicznej operacji. |

### Wartość zwracana

Obiekt [IAsyncResult](../../../system/iasyncresult/) reprezentujący zainicjowaną asynchroniczną operację.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klasa [IAsyncResult](../../../system/iasyncresult/)
* Klasa [Object](../../../system/object/)
* Klasa [HttpWebRequest](../)
* Przestrzeń nazw [System::Net](../../)
* Library [Aspose.Slides](../../../)
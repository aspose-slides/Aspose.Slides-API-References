---
title: EndGetRequestStream()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Czeka, aż określona asynchroniczna operacja uzyskania strumienia zostanie zakończona.
type: docs
weight: 313
url: /pl/system.net/webrequest/endgetrequeststream/
---
## WebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) metoda

Czeka, aż określona asynchroniczna operacja uzyskania strumienia zostanie zakończona.

```cpp
virtual System::SharedPtr<IO::Stream> System::Net::WebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Obiekt [IAsyncResult](../../../system/iasyncresult/) reprezentujący asynchroniczną operację uzyskania strumienia. |

### Wartość zwracana

Strumień do zapisywania danych w zasobie.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Stream](../../../system.io/stream/)
* Klasa [IAsyncResult](../../../system/iasyncresult/)
* Klasa [WebRequest](../)
* Przestrzeń nazw [System::Net](../../)
* Biblioteka [Aspose.Slides](../../../)
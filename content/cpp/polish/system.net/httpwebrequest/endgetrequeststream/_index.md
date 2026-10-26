---
title: EndGetRequestStream()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Czeka, aż określona asynchroniczna operacja pobierania strumienia zostanie zakończona.
type: docs
weight: 482
url: /pl/system.net/httpwebrequest/endgetrequeststream/
---
## HttpWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) metoda

Czeka, aż określona asynchroniczna operacja pobierania strumienia zostanie zakończona.

```cpp
System::SharedPtr<IO::Stream> System::Net::HttpWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Obiekt [IAsyncResult](../../../system/iasyncresult/) reprezentujący asynchroniczną operację pobierania strumienia. |

### Wartość zwracana

Strumień służący do zapisywania danych w zasobie.

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [Stream](../../../system.io/stream/)
* Klasa [IAsyncResult](../../../system/iasyncresult/)
* Klasa [HttpWebRequest](../)
* Przestrzeń nazw [System::Net](../../)
* Biblioteka [Aspose.Slides](../../../)
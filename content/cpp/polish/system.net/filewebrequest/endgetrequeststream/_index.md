---
title: EndGetRequestStream()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Czeka, aż określona asynchroniczna operacja pobrania strumienia zostanie zakończona.
type: docs
weight: 157
url: /pl/system.net/filewebrequest/endgetrequeststream/
---
## FileWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) metoda

Czeka, aż określona asynchroniczna operacja pobrania strumienia zakończy się.

```cpp
System::SharedPtr<IO::Stream> System::Net::FileWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Obiekt [IAsyncResult](../../../system/iasyncresult/) reprezentujący asynchroniczną operację pobrania strumienia. |

### Wartość zwracana

Strumień służący do zapisywania danych w zasobie.

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [Stream](../../../system.io/stream/)
* Klasa [IAsyncResult](../../../system/iasyncresult/)
* Klasa [FileWebRequest](../)
* Przestrzeń nazw [System::Net](../../)
* Biblioteka [Aspose.Slides](../../../)
---
title: EndRead()
second_title: Referencja API Aspose.Slides dla C++
description: Czeka, aż określona asynchroniczna operacja odczytu zostanie zakończona.
type: docs
weight: 183
url: /pl/system.io/stream/endread/
---
## Stream::EndRead(System::SharedPtr\<System::IAsyncResult\>) metoda

Czeka, aż określona asynchroniczna operacja odczytu zostanie zakończona.

```cpp
virtual int System::IO::Stream::EndRead(System::SharedPtr<System::IAsyncResult> asyncResult)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[System::IAsyncResult](../../../system/iasyncresult/)\> | Obiekt [IAsyncResult](../../../system/iasyncresult/) reprezentujący asynchroniczną operację odczytu |

### Wartość zwracana

Liczba bajtów odczytanych podczas operacji odczytu reprezentowanej przez **asyncResult**

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IAsyncResult](../../../system/iasyncresult/)
* Klasa [Stream](../)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)
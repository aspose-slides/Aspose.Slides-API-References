---
title: EndRead()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Czeka, aż określona asynchroniczna operacja odczytu zostanie zakończona.
type: docs
weight: 430
url: /pl/system.net.security/sslstream/endread/
---
## SslStream::EndRead(System::SharedPtr\<IAsyncResult\>) metoda

Czeka, aż określona asynchroniczna operacja odczytu zostanie zakończona.

```cpp
int32_t System::Net::Security::SslStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Obiekt [IAsyncResult](../../../system/iasyncresult/) reprezentujący asynchroniczną operację odczytu |

### Wartość zwracana

Liczba bajtów odczytanych podczas operacji odczytu reprezentowanej przez **asyncResult**

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IAsyncResult](../../../system/iasyncresult/)
* Klasa [SslStream](../)
* Przestrzeń nazw [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)
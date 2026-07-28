---
title: EndRead()
second_title: Aspose.Slides – referencja API dla C++
description: Czeka, aż określona asynchroniczna operacja odczytu zakończy się.
type: docs
weight: 261
url: /pl/system.net.sockets/networkstream/endread/
---
## NetworkStream::EndRead(System::SharedPtr\<IAsyncResult\>) metoda

Czeka, aż określona asynchroniczna operacja odczytu zakończy się.

```cpp
int32_t System::Net::Sockets::NetworkStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Obiekt [IAsyncResult](../../../system/iasyncresult/), który reprezentuje asynchroniczną operację odczytu |

### Wartość zwracana

Liczba bajtów odczytanych podczas operacji odczytu reprezentowanej przez **asyncResult**

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IAsyncResult](../../../system/iasyncresult/)
* Klasa [NetworkStream](../)
* Przestrzeń nazw [System::Net::Sockets](../../)
* Biblioteka [Aspose.Slides](../../../)
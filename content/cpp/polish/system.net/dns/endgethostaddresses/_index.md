---
title: EndGetHostAddresses()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Czeka, aż określona asynchroniczna operacja tworzenia nowej instancji klasy IPHostEntry-class zakończy się.
type: docs
weight: 144
url: /pl/system.net/dns/endgethostaddresses/
---
## Dns::EndGetHostAddresses(System::SharedPtr\<IAsyncResult\>) metoda

Czeka, aż określona asynchroniczna operacja tworzenia nowej instancji klasy IPHostEntry-class zakończy się.

```cpp
static System::ArrayPtr<System::SharedPtr<IPAddress>> System::Net::Dns::EndGetHostAddresses(System::SharedPtr<IAsyncResult> asyncResult)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Obiekt [IAsyncResult](../../../system/iasyncresult/) reprezentujący asynchroniczną operację. |

### Wartość zwracana

Nowo utworzona instancja klasy IPHostEntry-class.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IPAddress](../../ipaddress/)
* Klasa [IAsyncResult](../../../system/iasyncresult/)
* Klasa [Dns](../)
* Przestrzeń nazw [System::Net](../../)
* Biblioteka [Aspose.Slides](../../../)
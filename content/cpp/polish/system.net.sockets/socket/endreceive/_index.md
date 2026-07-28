---
title: EndReceive()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Czeka, aż określona asynchroniczna operacja odbioru zostanie zakończona.
type: docs
weight: 534
url: /pl/system.net.sockets/socket/endreceive/
---
## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>) metoda

Czeka, aż określona asynchroniczna operacja odbioru zostanie zakończona.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Obiekt [IAsyncResult](../../../system/iasyncresult/) reprezentujący asynchroniczną operację odbioru. |

### Wartość zwracana

Liczba bajtów, które zostały odebrane.

## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>, SocketError\&) metoda

Czeka, aż określona asynchroniczna operacja odbioru zostanie zakończona.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Obiekt [IAsyncResult](../../../system/iasyncresult/) reprezentujący asynchroniczną operację odbioru. |
| errorCode | [SocketError](../../socketerror/)\& | Parametr wyjściowy, w którym zostanie przypisany kod błędu, gdy operacja odbioru się nie powiedzie. |

### Wartość zwracana

Liczba odebranych bajtów.

## Zobacz również

* Enum [SocketError](../../socketerror/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IAsyncResult](../../../system/iasyncresult/)
* Klasa [Socket](../)
* Przestrzeń nazw [System::Net::Sockets](../../)
* Biblioteka [Aspose.Slides](../../../)
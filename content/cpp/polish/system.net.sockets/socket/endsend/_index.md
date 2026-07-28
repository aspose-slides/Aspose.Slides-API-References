---
title: EndSend()
second_title: Aspose.Slides dla C++ – referencja API
description: Czeka, aż określona asynchroniczna operacja wysyłania zostanie zakończona.
type: docs
weight: 508
url: /pl/system.net.sockets/socket/endsend/
---
## Socket::EndSend(System::SharedPtr\<IAsyncResult\>) metoda

Czeka, aż określona asynchroniczna operacja wysyłania zostanie zakończona.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Obiekt [IAsyncResult](../../../system/iasyncresult/) reprezentujący asynchroniczną operację wysyłania. |

### Wartość zwracana

Liczba wysłanych bajtów.

## Socket::EndSend(System::SharedPtr\<IAsyncResult\>, SocketError\&) metoda

Czeka, aż określona asynchroniczna operacja wysyłania zostanie zakończona.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Obiekt [IAsyncResult](../../../system/iasyncresult/) reprezentujący asynchroniczną operację wysyłania. |
| errorCode | [SocketError](../../socketerror/)\& | Parametr wyjściowy, w którym zostanie przypisany kod błędu, gdy operacja wysyłania się nie powiedzie. |

### Wartość zwracana

Liczba wysłanych bajtów.

## Zobacz także

* Wyliczenie [SocketError](../../socketerror/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IAsyncResult](../../../system/iasyncresult/)
* Klasa [Socket](../)
* Przestrzeń nazw [System::Net::Sockets](../../)
* Biblioteka [Aspose.Slides](../../../)
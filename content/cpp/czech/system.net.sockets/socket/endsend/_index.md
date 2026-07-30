---
title: EndSend()
second_title: Aspose.Slides pro C++ referenci API
description: Čeká, dokud není dokončena zadaná asynchronní operace odesílání.
type: docs
weight: 508
url: /cs/system.net.sockets/socket/endsend/
---
## Socket::EndSend(System::SharedPtr\<IAsyncResult\>) metoda

Čeká, dokud není dokončena zadaná asynchronní operace odesílání.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Objekt [IAsyncResult](../../../system/iasyncresult/), který představuje asynchronní operaci odesílání. |

### Návratová hodnota

Počet odeslaných bajtů.

## Socket::EndSend(System::SharedPtr\<IAsyncResult\>, SocketError\&) metoda

Čeká, dokud není dokončena zadaná asynchronní operace odesílání.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Objekt [IAsyncResult](../../../system/iasyncresult/), který představuje asynchronní operaci odesílání. |
| errorCode | [SocketError](../../socketerror/)\& | Výstupní parametr, do kterého bude při selhání operace odesílání přiřazen kód chyby. |

### Návratová hodnota

Počet odeslaných bajtů.

## Viz také

* Výčet [SocketError](../../socketerror/)
* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [IAsyncResult](../../../system/iasyncresult/)
* Třída [Socket](../)
* Jmenný prostor [System::Net::Sockets](../../)
* Knihovna [Aspose.Slides](../../../)
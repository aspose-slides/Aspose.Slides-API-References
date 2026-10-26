---
title: EndReceive()
second_title: Aspose.Slides pro C++ referenční dokumentace API
description: Čeká, dokud nedokončí zadanou asynchronní operaci příjmu.
type: docs
weight: 534
url: /cs/system.net.sockets/socket/endreceive/
---
## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>) metoda

Čeká, dokud nedokončí zadanou asynchronní operaci příjmu.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Objekt [IAsyncResult](../../../system/iasyncresult/), který představuje asynchronní operaci příjmu. |

### Návratová hodnota

Počet bajtů, které jsou přijaty.

## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>, SocketError\&) metoda

Čeká, dokud nedokončí zadanou asynchronní operaci příjmu.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Objekt [IAsyncResult](../../../system/iasyncresult/), který představuje asynchronní operaci příjmu. |
| errorCode | [SocketError](../../socketerror/)\& | Výstupní parametr, do kterého bude při selhání operace příjmu přiřazen chybový kód. |

### Návratová hodnota

Počet přijatých bajtů.

## Viz také

* Výčet [SocketError](../../socketerror/)
* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [IAsyncResult](../../../system/iasyncresult/)
* Třída [Socket](../)
* Jmenný prostor [System::Net::Sockets](../../)
* Knihovna [Aspose.Slides](../../../)
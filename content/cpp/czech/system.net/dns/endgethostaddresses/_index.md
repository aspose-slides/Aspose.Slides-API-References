---
title: EndGetHostAddresses()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Čeká, dokud nedojde k dokončení zadané asynchronní operace, která vytvoří novou instanci třídy IPHostEntry.
type: docs
weight: 144
url: /cs/system.net/dns/endgethostaddresses/
---
## Dns::EndGetHostAddresses(System::SharedPtr\<IAsyncResult\>) metoda


Čeká, dokud nedojde k dokončení zadané asynchronní operace, která vytvoří novou instanci třídy IPHostEntry.

```cpp
static System::ArrayPtr<System::SharedPtr<IPAddress>> System::Net::Dns::EndGetHostAddresses(System::SharedPtr<IAsyncResult> asyncResult)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Objekt [IAsyncResult](../../../system/iasyncresult/), který představuje asynchronní operaci. |

### Návratová hodnota

Nově vytvořená instance třídy IPHostEntry.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IPAddress](../../ipaddress/)
* Třída [IAsyncResult](../../../system/iasyncresult/)
* Třída [Dns](../)
* Jmenný prostor [System::Net](../../)
* Knihovna [Aspose.Slides](../../../)
---
title: GetHostByAddress()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří novou instanci třídy IPHostEntry-class pomocí zadané řetězcové reprezentace IP adresy.
type: docs
weight: 14
url: /cs/system.net/dns/gethostbyaddress/
---
## Dns::GetHostByAddress(String) method

Vytvoří novou instanci třídy IPHostEntry-class pomocí zadané řetězcové reprezentace IP adresy.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(String address)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| address | [String](../../../system/string/) | Řetězcová reprezentace IP adresy. |

### Návratová hodnota

Nově vytvořená instance třídy IPHostEntry-class.

## Dns::GetHostByAddress(System::SharedPtr\<IPAddress\>) method

Vytvoří novou instanci třídy IPHostEntry-class pomocí zadané IP adresy.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(System::SharedPtr<IPAddress> address)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | IP adresa. |

### Návratová hodnota

Nově vytvořená instance třídy IPHostEntry-class.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPHostEntry](../../iphostentry/)
* Class [String](../../../system/string/)
* Class [Dns](../)
* Class [IPAddress](../../ipaddress/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)
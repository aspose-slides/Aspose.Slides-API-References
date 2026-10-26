---
title: GetHostEntry()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw IPHostEntry-klasse instantie met de opgegeven string die een hostnaam of IP-adres bevat.
type: docs
weight: 79
url: /nl/system.net/dns/gethostentry/
---
## Dns::GetHostEntry(String) methode


Maakt een nieuw IPHostEntry-klasse instantie met de opgegeven string die een hostnaam of IP-adres bevat.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(String hostNameOrAddress)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | Een string die een hostnaam of IP-adres bevat. |

### Retourwaarde

Een nieuw aangemaakte IPHostEntry-klasse instantie.

## Dns::GetHostEntry(System::SharedPtr\<IPAddress\>) methode


Maakt een nieuw IPHostEntry-klasse instantie met het opgegeven IP-adres.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(System::SharedPtr<IPAddress> address)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | Het IP-adres. |

### Retourwaarde

Een nieuw aangemaakte IPHostEntry-klasse instantie.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPHostEntry](../../iphostentry/)
* Class [String](../../../system/string/)
* Class [Dns](../)
* Class [IPAddress](../../ipaddress/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)
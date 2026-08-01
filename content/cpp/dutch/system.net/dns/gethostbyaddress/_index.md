---
title: GetHostByAddress()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw IPHostEntry-class exemplaar aan met behulp van de opgegeven tekenreeksrepresentatie van een IP-adres.
type: docs
weight: 14
url: /nl/system.net/dns/gethostbyaddress/
---
## Dns::GetHostByAddress(String) method


Maakt een nieuw IPHostEntry-class exemplaar aan met behulp van de opgegeven tekenreeksrepresentatie van een IP-adres.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(String address)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| address | [String](../../../system/string/) | De tekenreeksrepresentatie van een IP-adres. |

### Retourwaarde

Een nieuw aangemaakt IPHostEntry-class exemplaar.

## Dns::GetHostByAddress(System::SharedPtr\<IPAddress\>) method


Maakt een nieuw IPHostEntry-class exemplaar aan met behulp van het opgegeven IP-adres.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(System::SharedPtr<IPAddress> address)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | Het IP-adres. |

### Retourwaarde

Een nieuw aangemaakt IPHostEntry-class exemplaar.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPHostEntry](../../iphostentry/)
* Klasse [String](../../../system/string/)
* Klasse [Dns](../)
* Klasse [IPAddress](../../ipaddress/)
* Namespace [System::Net](../../)
* Bibliotheek [Aspose.Slides](../../../)
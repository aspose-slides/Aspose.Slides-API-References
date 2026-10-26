---
title: GetHostByAddress()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine neue Instanz der IPHostEntry-class anhand der angegebenen Zeichenkettenrepräsentation einer IP-Adresse.
type: docs
weight: 14
url: /de/system.net/dns/gethostbyaddress/
---
## Dns::GetHostByAddress(String) Methode

Erstellt eine neue Instanz der IPHostEntry-Klasse anhand der angegebenen Zeichenkettenrepräsentation einer IP-Adresse.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(String address)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| address | [String](../../../system/string/) | Die Zeichenkettenrepräsentation einer IP-Adresse. |

### Rückgabewert

Eine neu erstellte Instanz der IPHostEntry-Klasse.

## Dns::GetHostByAddress(System::SharedPtr\<IPAddress\>) Methode

Erstellt eine neue Instanz der IPHostEntry-Klasse anhand der angegebenen IP-Adresse.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(System::SharedPtr<IPAddress> address)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | Die IP-Adresse. |

### Rückgabewert

Eine neu erstellte Instanz der IPHostEntry-Klasse.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPHostEntry](../../iphostentry/)
* Klasse [String](../../../system/string/)
* Klasse [Dns](../)
* Klasse [IPAddress](../../ipaddress/)
* Namensraum [System::Net](../../)
* Bibliothek [Aspose.Slides](../../../)
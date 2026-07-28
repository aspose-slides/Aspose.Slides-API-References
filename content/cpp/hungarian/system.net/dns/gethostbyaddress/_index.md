---
title: GetHostByAddress()
second_title: Aspose.Slides C++ API-referencia
description: Új IPHostEntry-osztálypéldányt hoz létre a megadott IP-cím karakterlánc ábrázolásával.
type: docs
weight: 14
url: /hu/system.net/dns/gethostbyaddress/
---
## Dns::GetHostByAddress(String) metódus

Új IPHostEntry-osztálypéldányt hoz létre a megadott IP-cím karakterlánc ábrázolásával.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(String address)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| address | [String](../../../system/string/) | Az IP-cím karakterlánc ábrázolása. |

### Visszatérési érték

Egy újonnan létrehozott IPHostEntry-osztálypéldány.

## Dns::GetHostByAddress(System::SharedPtr\<IPAddress\>) metódus

Új IPHostEntry-osztálypéldányt hoz létre a megadott IP-címmel.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(System::SharedPtr<IPAddress> address)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | Az IP-cím. |

### Visszatérési érték

Egy újonnan létrehozott IPHostEntry-osztálypéldány.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IPHostEntry](../../iphostentry/)
* Osztály [String](../../../system/string/)
* Osztály [Dns](../)
* Osztály [IPAddress](../../ipaddress/)
* Névterület [System::Net](../../)
* Könyvtár [Aspose.Slides](../../../)
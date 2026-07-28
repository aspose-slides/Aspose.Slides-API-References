---
title: GetHostEntry()
second_title: Aspose.Slides C++ API referencia
description: Új IPHostEntry-class példányt hoz létre a megadott karakterlánc használatával, amely gépnevet vagy IP-címet tartalmaz.
type: docs
weight: 79
url: /hu/system.net/dns/gethostentry/
---
## Dns::GetHostEntry(String) metódus


Új IPHostEntry-class példányt hoz létre a megadott karakterlánc használatával, amely gépnevet vagy IP-címet tartalmaz.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(String hostNameOrAddress)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | Egy karakterlánc, amely gépnevet vagy IP-címet tartalmaz. |

### Visszatérési érték

Újonnan létrehozott IPHostEntry-class példány.

## Dns::GetHostEntry(System::SharedPtr\<IPAddress\>) metódus


Új IPHostEntry-class példányt hoz létre a megadott IP-cím használatával.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(System::SharedPtr<IPAddress> address)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | Az IP-cím. |

### Visszatérési érték

Újonnan létrehozott IPHostEntry-class példány.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IPHostEntry](../../iphostentry/)
* Osztály [String](../../../system/string/)
* Osztály [Dns](../)
* Osztály [IPAddress](../../ipaddress/)
* Névterület [System::Net](../../)
* Könyvtár [Aspose.Slides](../../../)
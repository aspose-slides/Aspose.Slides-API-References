---
title: GetHostEntry()
second_title: Aspose.Slides pro API referenci C++
description: Vytvoří novou instanci IPHostEntry-class pomocí zadaného řetězce, který obsahuje název hostitele nebo IP adresu.
type: docs
weight: 79
url: /cs/system.net/dns/gethostentry/
---
## Dns::GetHostEntry(String) metoda

Vytvoří novou instanci IPHostEntry-class pomocí zadaného řetězce, který obsahuje název hostitele nebo IP adresu.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(String hostNameOrAddress)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | Řetězec, který obsahuje název hostitele nebo IP adresu. |

### Návratová hodnota

Nově vytvořená IPHostEntry-class instance.

## Dns::GetHostEntry(System::SharedPtr\<IPAddress\>) metoda

Vytvoří novou instanci IPHostEntry-class pomocí zadané IP adresy.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(System::SharedPtr<IPAddress> address)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | IP adresa. |

### Návratová hodnota

Nově vytvořená IPHostEntry-class instance.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IPHostEntry](../../iphostentry/)
* Třída [String](../../../system/string/)
* Třída [Dns](../)
* Třída [IPAddress](../../ipaddress/)
* Jmenný prostor [System::Net](../../)
* Knihovna [Aspose.Slides](../../../)
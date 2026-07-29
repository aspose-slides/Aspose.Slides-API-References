---
title: GetHostEntry()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny IPHostEntry-klassinstans med den angivna strängen som innehåller ett värdnamn eller en IP-adress.
type: docs
weight: 79
url: /sv/system.net/dns/gethostentry/
---
## Dns::GetHostEntry(String) metod

Skapar en ny IPHostEntry-klass instans med den angivna strängen som innehåller ett värdnamn eller en IP-adress.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(String hostNameOrAddress)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | En sträng som innehåller ett värdnamn eller en IP-adress. |

### Returvärde

En ny IPHostEntry-klass instans.

## Dns::GetHostEntry(System::SharedPtr\<IPAddress\>) metod

Skapar en ny IPHostEntry-klass instans med den angivna IP-adressen.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(System::SharedPtr<IPAddress> address)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | IP-adressen. |

### Returvärde

En ny IPHostEntry-klass instans.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IPHostEntry](../../iphostentry/)
* Klass [String](../../../system/string/)
* Klass [Dns](../)
* Klass [IPAddress](../../ipaddress/)
* Namnrymd [System::Net](../../)
* Bibliotek [Aspose.Slides](../../../)
---
title: GetHostByAddress()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny IPHostEntry-class-instans med den angivna strängrepresentationen av en IP-adress.
type: docs
weight: 14
url: /sv/system.net/dns/gethostbyaddress/
---
## Dns::GetHostByAddress(String) metod

Skapar en ny IPHostEntry-class-instans med den angivna strängrepresentationen av en IP-adress.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(String address)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| address | [String](../../../system/string/) | Strängrepresentationen av en IP-adress. |

### Returvärde

En ny skapad IPHostEntry-class-instans.

## Dns::GetHostByAddress(System::SharedPtr\<IPAddress\>) metod

Skapar en ny IPHostEntry-class-instans med den angivna IP-adressen.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(System::SharedPtr<IPAddress> address)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | IP-adressen. |

### Returvärde

En ny skapad IPHostEntry-class-instans.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPHostEntry](../../iphostentry/)
* Class [String](../../../system/string/)
* Class [Dns](../)
* Class [IPAddress](../../ipaddress/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)
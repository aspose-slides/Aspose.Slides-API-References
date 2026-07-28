---
title: GetHostEntry()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Tworzy nową instancję klasy IPHostEntry-class przy użyciu określonego ciągu zawierającego nazwę hosta lub adres IP.
type: docs
weight: 79
url: /pl/system.net/dns/gethostentry/
---
## Dns::GetHostEntry(String) metoda

Tworzy nową instancję klasy IPHostEntry-class przy użyciu określonego ciągu zawierającego nazwę hosta lub adres IP.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(String hostNameOrAddress)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | Ciąg zawierający nazwę hosta lub adres IP. |

### Wartość zwracana

Nowo utworzona instancja klasy IPHostEntry-class.

## Dns::GetHostEntry(System::SharedPtr\<IPAddress\>) metoda

Tworzy nową instancję klasy IPHostEntry-class przy użyciu określonego adresu IP.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(System::SharedPtr<IPAddress> address)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | Adres IP. |

### Wartość zwracana

Nowo utworzona instancja klasy IPHostEntry-class.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPHostEntry](../../iphostentry/)
* Class [String](../../../system/string/)
* Class [Dns](../)
* Class [IPAddress](../../ipaddress/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)
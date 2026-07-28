---
title: GetHostByAddress()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Tworzy nową instancję klasy IPHostEntry przy użyciu podanej reprezentacji tekstowej adresu IP.
type: docs
weight: 14
url: /pl/system.net/dns/gethostbyaddress/
---
## Dns::GetHostByAddress(String) metoda

Tworzy nową instancję klasy IPHostEntry przy użyciu podanej tekstowej reprezentacji adresu IP.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(String address)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| address | [String](../../../system/string/) | Reprezentacja tekstowa adresu IP. |

### Wartość zwracana

Nowo utworzona instancja klasy IPHostEntry.

## Dns::GetHostByAddress(System::SharedPtr\<IPAddress\>) metoda

Tworzy nową instancję klasy IPHostEntry przy użyciu podanego adresu IP.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(System::SharedPtr<IPAddress> address)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | Adres IP. |

### Wartość zwracana

Nowo utworzona instancja klasy IPHostEntry.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IPHostEntry](../../iphostentry/)
* Klasa [String](../../../system/string/)
* Klasa [Dns](../)
* Klasa [IPAddress](../../ipaddress/)
* Przestrzeń nazw [System::Net](../../)
* Biblioteka [Aspose.Slides](../../../)
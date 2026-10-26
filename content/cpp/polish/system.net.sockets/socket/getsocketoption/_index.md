---
title: GetSocketOption()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Zwraca wartość odpowiadającą określonej nazwie opcji.
type: docs
weight: 729
url: /pl/system.net.sockets/socket/getsocketoption/
---
## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName) metoda

Zwraca wartość, która odpowiada określonej nazwie opcji.

```cpp
System::SharedPtr<Object> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | Poziom opcji gniazda. |
| optionName | [SocketOptionName](../../socketoptionname/) | Nazwa opcji. |

### Wartość zwracana

Wartość, która odpowiada określonej nazwie opcji.

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) metoda

Pobiera wartość, która odpowiada określonej nazwie opcji.

```cpp
void System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::ArrayPtr<uint8_t> optionValue)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | Poziom opcji gniazda. |
| optionName | [SocketOptionName](../../socketoptionname/) | Nazwa opcji. |
| optionValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Parametr wyjściowy, w którym zostanie przypisana odpowiednia wartość. |

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, int32_t) metoda

Zwraca wartość, która odpowiada określonej nazwie opcji.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, int32_t optionLength)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | Poziom opcji gniazda. |
| optionName | [SocketOptionName](../../socketoptionname/) | Nazwa opcji. |
| optionLength | **int32_t** | Długość opcji. |

### Wartość zwracana

Wartość, która odpowiada określonej nazwie opcji.

## Zobacz także

* Enum [SocketOptionLevel](../../socketoptionlevel/)
* Enum [SocketOptionName](../../socketoptionname/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Object](../../../system/object/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
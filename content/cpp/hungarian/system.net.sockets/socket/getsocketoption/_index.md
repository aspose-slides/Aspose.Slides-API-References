---
title: GetSocketOption()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja a megadott opció nevének megfelelő értéket.
type: docs
weight: 729
url: /hu/system.net.sockets/socket/getsocketoption/
---
## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName) metódus

Visszaadja az adott opciónevhöz tartozó értéket.

```cpp
System::SharedPtr<Object> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | A socket opció szintje. |
| optionName | [SocketOptionName](../../socketoptionname/) | Az opció neve. |

### Visszatérési érték

Az adott opciónevhöz tartozó érték.

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) metódus

Lekéri az adott opciónevhöz tartozó értéket.

```cpp
void System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::ArrayPtr<uint8_t> optionValue)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | A socket opció szintje. |
| optionName | [SocketOptionName](../../socketoptionname/) | Az opció neve. |
| optionValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A kimeneti paraméter, amelybe a megfelelő érték kerül hozzárendelésre. |

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, int32_t) metódus

Visszaadja az adott opciónevhöz tartozó értéket.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, int32_t optionLength)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | A socket opció szintje. |
| optionName | [SocketOptionName](../../socketoptionname/) | Az opció neve. |
| optionLength | **int32_t** | Az opció hossza. |

### Visszatérési érték

Az adott opciónevhöz tartozó érték.

## Lásd még

* Enum [SocketOptionLevel](../../socketoptionlevel/)
* Enum [SocketOptionName](../../socketoptionname/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Object](../../../system/object/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
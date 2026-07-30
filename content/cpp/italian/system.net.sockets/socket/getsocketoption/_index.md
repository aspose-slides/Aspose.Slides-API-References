---
title: GetSocketOption()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce il valore che corrisponde al nome dell'opzione specificata.
type: docs
weight: 729
url: /it/system.net.sockets/socket/getsocketoption/
---
## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName) metodo


Restituisce il valore che corrisponde al nome dell'opzione specificata.

```cpp
System::SharedPtr<Object> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | Il livello dell'opzione socket. |
| optionName | [SocketOptionName](../../socketoptionname/) | Il nome dell'opzione. |

### Valore restituito

Il valore che corrisponde al nome dell'opzione specificata.

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) metodo


Ottiene il valore che corrisponde al nome dell'opzione specificata.

```cpp
void System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::ArrayPtr<uint8_t> optionValue)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | Il livello dell'opzione socket. |
| optionName | [SocketOptionName](../../socketoptionname/) | Il nome dell'opzione. |
| optionValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Il parametro di output dove verrà assegnato il valore corrispondente. |

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, int32_t) metodo


Restituisce il valore che corrisponde al nome dell'opzione specificata.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, int32_t optionLength)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | Il livello dell'opzione socket. |
| optionName | [SocketOptionName](../../socketoptionname/) | Il nome dell'opzione. |
| optionLength | **int32_t** | La lunghezza dell'opzione. |

### Valore restituito

Il valore che corrisponde al nome dell'opzione specificata.

## Vedi anche

* Enum [SocketOptionLevel](../../socketoptionlevel/)
* Enum [SocketOptionName](../../socketoptionname/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Object](../../../system/object/)
* Classe [Socket](../)
* Spazio dei nomi [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
---
title: GetSocketOption()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve el valor que corresponde al nombre de opción especificado.
type: docs
weight: 729
url: /es/system.net.sockets/socket/getsocketoption/
---
## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName) método

Devuelve el valor que corresponde al nombre de opción especificado.

```cpp
System::SharedPtr<Object> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | El nivel de opción del socket. |
| optionName | [SocketOptionName](../../socketoptionname/) | El nombre de la opción. |

### Valor de retorno

El valor que corresponde al nombre de opción especificado.

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) método

Obtiene el valor que corresponde al nombre de opción especificado.

```cpp
void System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::ArrayPtr<uint8_t> optionValue)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | El nivel de opción del socket. |
| optionName | [SocketOptionName](../../socketoptionname/) | El nombre de la opción. |
| optionValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | El parámetro de salida donde se asignará el valor correspondiente. |

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, int32_t) método

Devuelve el valor que corresponde al nombre de opción especificado.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, int32_t optionLength)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | El nivel de opción del socket. |
| optionName | [SocketOptionName](../../socketoptionname/) | El nombre de la opción. |
| optionLength | **int32_t** | La longitud de la opción. |

### Valor de retorno

El valor que corresponde al nombre de opción especificado.

## Ver también

* Enum [SocketOptionLevel](../../socketoptionlevel/)
* Enum [SocketOptionName](../../socketoptionname/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [Object](../../../system/object/)
* Clase [Socket](../)
* espacio de nombres [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
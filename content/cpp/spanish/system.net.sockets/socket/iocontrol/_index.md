---
title: IOControl()
second_title: Referencia de API de Aspose.Slides para C++
description: Establece modos de operación de bajo nivel para el socket.
type: docs
weight: 703
url: /es/system.net.sockets/socket/iocontrol/
---
## Socket::IOControl(int32_t, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) método


Establece modos de operación de bajo nivel para el socket.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(int32_t ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ioControlCode | **int32_t** | El código de control de la operación a realizar. |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | La matriz de bytes que contiene los datos de entrada. |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | La matriz de bytes que contiene los datos de salida. |

### Valor devuelto

El número de bytes en el parámetro **optionOutValue**.

## Socket::IOControl(IOControlCode, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) método


Establece modos de operación de bajo nivel para el socket.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(IOControlCode ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ioControlCode | [IOControlCode](../../iocontrolcode/) | El código de control de la operación a realizar. |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | La matriz de bytes que contiene los datos de entrada. |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | La matriz de bytes que contiene los datos de salida. |

### Valor devuelto

El número de bytes en el parámetro **optionOutValue**.

## Ver también

* Enumeración [IOControlCode](../../iocontrolcode/)
* Definición de tipo [ArrayPtr](../../../system/arrayptr/)
* Clase [Socket](../)
* Espacio de nombres [System::Net::Sockets](../../)
* Biblioteca [Aspose.Slides](../../../)
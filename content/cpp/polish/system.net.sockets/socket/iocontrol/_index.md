---
title: IOControl()
second_title: Aspose.Slides dla referencji API C++
description: Ustawia tryby operacyjne niskiego poziomu dla gniazda.
type: docs
weight: 703
url: /pl/system.net.sockets/socket/iocontrol/
---
## Socket::IOControl(int32_t, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metoda


Ustawia tryby operacyjne niskiego poziomu dla gniazda.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(int32_t ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| ioControlCode | **int32_t** | The control code of the operation to perform. |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | The byte array that contains the input data. |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | The byte array that contains the output data. |

### Wartość zwracana

Liczba bajtów w parametrze **optionOutValue**.

## Socket::IOControl(IOControlCode, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metoda


Ustawia tryby operacyjne niskiego poziomu dla gniazda.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(IOControlCode ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| ioControlCode | [IOControlCode](../../iocontrolcode/) | The control code of the operation to perform. |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | The byte array that contains the input data. |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | The byte array that contains the output data. |

### Wartość zwracana

Liczba bajtów w parametrze **optionOutValue**.

## Zobacz także

* Enum [IOControlCode](../../iocontrolcode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
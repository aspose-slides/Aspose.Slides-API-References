---
title: IOControl()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in lågnivådriftslägen för socketen.
type: docs
weight: 703
url: /sv/system.net.sockets/socket/iocontrol/
---
## Socket::IOControl(int32_t, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metod


Ställer in lågnivådriftslägen för socketen.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(int32_t ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ioControlCode | **int32_t** | Kontrollkoden för den operation som ska utföras. |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytearrayen som innehåller indata. |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytearrayen som innehåller utdata. |

### Returvärde

Antalet byte i parametern **optionOutValue**.

## Socket::IOControl(IOControlCode, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metod


Ställer in lågnivådriftslägen för socketen.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(IOControlCode ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ioControlCode | [IOControlCode](../../iocontrolcode/) | Kontrollkoden för den operation som ska utföras. |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytearrayen som innehåller indata. |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytearrayen som innehåller utdata. |

### Returvärde

Antalet byte i parametern **optionOutValue**.

## Se även

* Enum [IOControlCode](../../iocontrolcode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
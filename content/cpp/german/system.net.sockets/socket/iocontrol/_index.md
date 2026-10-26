---
title: IOControl()
second_title: Aspose.Slides für C++ API-Referenz
description: Setzt Low-Level-Betriebsmodi für den Socket.
type: docs
weight: 703
url: /de/system.net.sockets/socket/iocontrol/
---
## Socket::IOControl(int32_t, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) Methode

Setzt Low-Level-Betriebsmodi für den Socket.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(int32_t ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ioControlCode | **int32_t** | Der Steuercode der auszuführenden Operation. |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Das Byte-Array, das die Eingabedaten enthält. |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Das Byte-Array, das die Ausgabedaten enthält. |

### Rückgabewert

Die Anzahl der Bytes im **optionOutValue** Parameter.

## Socket::IOControl(IOControlCode, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) Methode

Setzt Low-Level-Betriebsmodi für den Socket.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(IOControlCode ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ioControlCode | [IOControlCode](../../iocontrolcode/) | Der Steuercode der auszuführenden Operation. |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Das Byte-Array, das die Eingabedaten enthält. |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Das Byte-Array, das die Ausgabedaten enthält. |

### Rückgabewert

Die Anzahl der Bytes im **optionOutValue** Parameter.

## Siehe auch

* Enum [IOControlCode](../../iocontrolcode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
---
title: IOControl()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt low-level operationele modi in voor de socket.
type: docs
weight: 703
url: /nl/system.net.sockets/socket/iocontrol/
---
## Socket::IOControl(int32_t, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) methode

Stelt low-level operationele modi in voor de socket.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(int32_t ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```

### Argumenten

| Parameter | Type | Omschrijving |
| --- | --- | --- |
| ioControlCode | **int32_t** | De besturingscode van de uit te voeren bewerking. |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | De byte-array die de invoergegevens bevat. |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | De byte-array die de uitvoergegevens bevat. |

### Retourwaarde

Het aantal bytes in de **optionOutValue** parameter.

## Socket::IOControl(IOControlCode, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) methode

Stelt low-level operationele modi in voor de socket.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(IOControlCode ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```

### Argumenten

| Parameter | Type | Omschrijving |
| --- | --- | --- |
| ioControlCode | [IOControlCode](../../iocontrolcode/) | De besturingscode van de uit te voeren bewerking. |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | De byte-array die de invoergegevens bevat. |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | De byte-array die de uitvoergegevens bevat. |

### Retourwaarde

Het aantal bytes in de **optionOutValue** parameter.

## Zie ook

* Enum [IOControlCode](../../iocontrolcode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Socket](../)
* Naamruimte [System::Net::Sockets](../../)
* Bibliotheek [Aspose.Slides](../../../)
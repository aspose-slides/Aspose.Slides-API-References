---
title: IOControl()
second_title: Aspose.Slides C++ API referenciája
description: A socket alacsony szintű működési módjait állítja be.
type: docs
weight: 703
url: /hu/system.net.sockets/socket/iocontrol/
---
## Socket::IOControl(int32_t, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metódus


Az alacsony szintű működési módokat állítja be a socket számára.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(int32_t ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| ioControlCode | **int32_t** | A végrehajtandó művelet vezérlőkódja. |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A bemeneti adatokat tartalmazó bájt tömb. |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A kimeneti adatokat tartalmazó bájt tömb. |


### Visszatérési érték

A **optionOutValue** paraméterben lévő bájtok száma.

## Socket::IOControl(IOControlCode, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metódus


Az alacsony szintű működési módokat állítja be a socket számára.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(IOControlCode ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| ioControlCode | [IOControlCode](../../iocontrolcode/) | A végrehajtandó művelet vezérlőkódja. |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A bemeneti adatokat tartalmazó bájt tömb. |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A kimeneti adatokat tartalmazó bájt tömb. |


### Visszatérési érték

A **optionOutValue** paraméterben lévő bájtok száma.

## Lásd még

* Enum [IOControlCode](../../iocontrolcode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [Socket](../)
* Névtér [System::Net::Sockets](../../)
* Könyvtár [Aspose.Slides](../../../)
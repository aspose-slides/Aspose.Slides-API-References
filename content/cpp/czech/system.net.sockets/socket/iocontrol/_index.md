---
title: IOControl()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Nastavuje nízkoúrovňové provozní režimy pro socket.
type: docs
weight: 703
url: /cs/system.net.sockets/socket/iocontrol/
---
## Socket::IOControl(int32_t, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metoda

Nastavuje nízkoúrovňové provozní režimy pro socket.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(int32_t ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| ioControlCode | **int32_t** | Ovládací kód operace, která se má provést. |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Pole bajtů obsahující vstupní data. |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Pole bajtů obsahující výstupní data. |

### Návratová hodnota

Počet bajtů v parametru **optionOutValue**.

## Socket::IOControl(IOControlCode, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metoda

Nastavuje nízkoúrovňové provozní režimy pro socket.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(IOControlCode ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| ioControlCode | [IOControlCode](../../iocontrolcode/) | Ovládací kód operace, která se má provést. |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Pole bajtů obsahující vstupní data. |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Pole bajtů obsahující výstupní data. |

### Návratová hodnota

Počet bajtů v parametru **optionOutValue**.

## Viz také

* Výčet [IOControlCode](../../iocontrolcode/)
* Definice typu [ArrayPtr](../../../system/arrayptr/)
* Třída [Socket](../)
* Jmenný prostor [System::Net::Sockets](../../)
* Knihovna [Aspose.Slides](../../../)
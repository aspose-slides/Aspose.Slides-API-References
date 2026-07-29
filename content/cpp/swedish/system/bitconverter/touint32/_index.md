---
title: ToUInt32()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar fyra byte från den angivna arrayen med start vid det angivna indexet till ett osignerat 32-bit heltalsvärde.
type: docs
weight: 105
url: /sv/system/bitconverter/touint32/
---
## BitConverter::ToUInt32(const System::ArrayPtr\<uint8_t\>\&, int) metod

Konverterar fyra byte från den angivna arrayen med start vid det angivna indexet till ett osignerat 32-bit heltalsvärde.

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) som innehåller byte att konvertera |
| startIndex | int | [Index](../../index/) i arrayen där man börjar ta byte för konvertering |

### Returvärde

Osignerat 32-bit heltalsvärde som erhålls från konverteringen

## BitConverter::ToUInt32(const System::Details::ArrayView\<uint8_t\>\&, int) metod

Konverterar fyra byte från den angivna arrayen med start vid det angivna indexet till ett osignerat 32-bit heltalsvärde.

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView som innehåller byte att konvertera |
| startIndex | int | [Index](../../index/) i arrayen där man börjar ta byte för konvertering |

### Returvärde

Osignerat 32-bit heltalsvärde som erhålls från konverteringen

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Klass [BitConverter](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)
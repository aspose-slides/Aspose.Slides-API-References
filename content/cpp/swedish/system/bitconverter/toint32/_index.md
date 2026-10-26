---
title: ToInt32()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar fyra byte från den angivna arrayen med start vid det angivna indexet till ett 32-bit heltalsvärde.
type: docs
weight: 66
url: /sv/system/bitconverter/toint32/
---
## BitConverter::ToInt32(const System::ArrayPtr\<uint8_t\>\&, int) metod

Konverterar fyra byte från den angivna arrayen med start vid det angivna indexet till ett 32-bit heltalsvärde.

```cpp
static int System::BitConverter::ToInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) som innehåller byte att konvertera |
| startIndex | int | [Index](../../index/) i arrayen där man börjar ta byte för konvertering |

### Returvärde

32-bit heltalsvärde som resultat av konverteringen

## BitConverter::ToInt32(const System::Details::ArrayView\<uint8_t\>\&, int) metod

Konverterar fyra byte från den angivna arrayen med start vid det angivna indexet till ett 32-bit heltalsvärde.

```cpp
static int System::BitConverter::ToInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView som innehåller byte att konvertera |
| startIndex | int | [Index](../../index/) i arrayen där man börjar ta byte för konvertering |

### Returvärde

32-bit heltalsvärde som resultat av konverteringen

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Klass [BitConverter](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)
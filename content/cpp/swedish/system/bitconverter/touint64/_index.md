---
title: ToUInt64()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar åtta byte från den angivna arrayen med start vid det angivna indexet till ett osignerat 64-bit heltalvärde.
type: docs
weight: 118
url: /sv/system/bitconverter/touint64/
---
## BitConverter::ToUInt64(const System::ArrayPtr\<uint8_t\>\&, int) metod


Konverterar åtta byte från den angivna arrayen med start vid det angivna indexet till ett osignerat 64-bits heltalvärde.

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) som innehåller byte att konvertera |
| startIndex | int | [Index](../../index/) i arrayen där man ska börja ta byte för konvertering |

### Returvärde

Osignerat 64-bits heltalvärde som resultat av konverteringen

## BitConverter::ToUInt64(const System::Details::ArrayView\<uint8_t\>\&, int) metod


Konverterar åtta byte från den angivna arrayen med start vid det angivna indexet till ett osignerat 64-bits heltalvärde.

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView som innehåller byte att konvertera |
| startIndex | int | [Index](../../index/) i arrayen där man ska börja ta byte för konvertering |

### Returvärde

Osignerat 64-bits heltalvärde som resultat av konverteringen

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Klass [BitConverter](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)
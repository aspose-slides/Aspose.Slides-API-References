---
title: ToInt64()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar åtta byte från den angivna arrayen med start vid det angivna indexet till ett 64-bits heltal.
type: docs
weight: 79
url: /sv/system/bitconverter/toint64/
---
## BitConverter::ToInt64(const System::ArrayPtr\<uint8_t\>\&, int) metod


Konverterar åtta byte från den angivna arrayen med start vid det angivna indexet till ett 64-bits heltal.

```cpp
static int64_t System::BitConverter::ToInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) som innehåller byte att konvertera |
| startIndex | int | [Index](../../index/) i arrayen där man ska börja ta byte för konvertering |

### Returvärde

64-bits heltal som resultat av konverteringen

## BitConverter::ToInt64(const System::Details::ArrayView\<uint8_t\>\&, int) metod


Konverterar åtta byte från den angivna arrayen med start vid det angivna indexet till ett 64-bits heltal.

```cpp
static int64_t System::BitConverter::ToInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView som innehåller byte att konvertera |
| startIndex | int | [Index](../../index/) i arrayen där man ska börja ta byte för konvertering |

### Returvärde

64-bits heltal som resultat av konverteringen

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Klass [BitConverter](../)
* Namnrymd [System](../../)
* Library [Aspose.Slides](../../../)
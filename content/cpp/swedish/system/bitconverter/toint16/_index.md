---
title: ToInt16()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar två byte från den angivna arrayen med start på det angivna indexet till ett 16-bitars heltalsvärde.
type: docs
weight: 53
url: /sv/system/bitconverter/toint16/
---
## BitConverter::ToInt16(const System::ArrayPtr\<uint8_t\>\&, int) method


Konverterar två byte från den angivna arrayen med start på det angivna indexet till ett 16-bitars heltalsvärde.

```cpp
static int16_t System::BitConverter::ToInt16(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) som innehåller byte att konvertera |
| startIndex | int | [Index](../../index/) i arrayen där byte för konvertering ska tas från |

### Returvärde

16-bitars heltalsvärde som resultat av konverteringen

## BitConverter::ToInt16(const System::Details::ArrayView\<uint8_t\>\&, int) method


Konverterar två byte från den angivna arrayen med start på det angivna indexet till ett 16-bitars heltalsvärde.

```cpp
static int16_t System::BitConverter::ToInt16(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView som innehåller byte att konvertera |
| startIndex | int | [Index](../../index/) i arrayen där byte för konvertering ska tas från |

### Returvärde

16-bitars heltalsvärde som resultat av konverteringen

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Klass [BitConverter](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)
---
title: ToUInt16()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar två byte från den angivna arrayen med start på det angivna indexet till ett osignerat 16-bitars heltalsvärde.
type: docs
weight: 92
url: /sv/system/bitconverter/touint16/
---
## BitConverter::ToUInt16(const System::ArrayPtr\<uint8_t\>\&, int) metod

Konverterar två byte från den angivna arrayen med start på det angivna indexet till ett osignerat 16-bitars heltalsvärde.

```cpp
static uint16_t System::BitConverter::ToUInt16(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) som innehåller byte som ska konverteras |
| startIndex | int | [Index](../../index/) i arrayen där man ska börja ta byte för konvertering |

### Returvärde

Osignerat 16-bitars heltalsvärde som resultat av konverteringen

## BitConverter::ToUInt16(const System::Details::ArrayView\<uint8_t\>\&, int) metod

Konverterar två byte från den angivna arrayen med start på det angivna indexet till ett osignerat 16-bitars heltalsvärde.

```cpp
static uint16_t System::BitConverter::ToUInt16(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView som innehåller byte som ska konverteras |
| startIndex | int | [Index](../../index/) i arrayen där man ska börja ta byte för konvertering |

### Returvärde

Osignerat 16-bitars heltalsvärde som resultat av konverteringen

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Klass [BitConverter](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)
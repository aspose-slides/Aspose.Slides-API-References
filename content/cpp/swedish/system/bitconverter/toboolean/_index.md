---
title: ToBoolean()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar en byte från den angivna arrayen med start vid det angivna indexet till ett booleskt värde.
type: docs
weight: 27
url: /sv/system/bitconverter/toboolean/
---
## BitConverter::ToBoolean(const System::ArrayPtr\<uint8_t\>\&, int) metod

Konverterar en byte från den angivna arrayen med start vid det angivna indexet till ett booleskt värde.

```cpp
static bool System::BitConverter::ToBoolean(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) som innehåller byte att konvertera |
| startIndex | int | [Index](../../index/) i arrayen där man ska börja ta byte för konvertering |

### Returvärde

[Boolean](../../boolean/) värde som resultat av konverteringen

## BitConverter::ToBoolean(const System::Details::ArrayView\<uint8_t\>\&, int) metod

Konverterar en byte från den angivna arrayen med start vid det angivna indexet till ett booleskt värde.

```cpp
static bool System::BitConverter::ToBoolean(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView som innehåller byte att konvertera |
| startIndex | int | [Index](../../index/) i arrayen där man ska börja ta byte för konvertering |

### Returvärde

[Boolean](../../boolean/) värde som resultat av konverteringen

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Klass [BitConverter](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)
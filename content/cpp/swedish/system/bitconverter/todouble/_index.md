---
title: ToDouble()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar åtta byte från den angivna arrayen med start vid det angivna indexet till ett dubbelprecisionsflyttal.
type: docs
weight: 144
url: /sv/system/bitconverter/todouble/
---
## BitConverter::ToDouble(const System::ArrayPtr\<uint8_t\>\&, int) metod

Konverterar åtta byte från den angivna arrayen med start från det angivna indexet till ett dubbelprecisionsflyttal.

```cpp
static double System::BitConverter::ToDouble(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) som innehåller byte att konvertera |
| startIndex | int | [Index](../../index/) i arrayen där man börjar ta byte för konvertering |

### Returvärde

Dubbelprecisionsflyttal som resultat av konverteringen

## BitConverter::ToDouble(const System::Details::ArrayView\<uint8_t\>\&, int) metod

Konverterar åtta byte från den angivna arrayen med start från det angivna indexet till ett dubbelprecisionsflyttal.

```cpp
static double System::BitConverter::ToDouble(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView som innehåller byte att konvertera |
| startIndex | int | [Index](../../index/) i arrayen där man börjar ta byte för konvertering |

### Returvärde

Dubbelprecisionsflyttal som resultat av konverteringen

## Se även

* Typdefinition [ArrayPtr](../../arrayptr/)
* Klass [BitConverter](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)
---
title: ToSingle()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar fyra byte från den specificerade arrayen med start vid det angivna indexet till ett flyttal med enkel precision.
type: docs
weight: 131
url: /sv/system/bitconverter/tosingle/
---
## BitConverter::ToSingle(const System::ArrayPtr\<uint8_t\>\&, int) metod


Konverterar fyra byte från den specificerade arrayen med start vid det angivna indexet till ett flyttal med enkel precision.

```cpp
static float System::BitConverter::ToSingle(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) som innehåller byte att konvertera |
| startIndex | int | [Index](../../index/) i arrayen där man börjar ta byte för konvertering |

### Returvärde

Flyttal med enkel precision som resultat av konverteringen

## BitConverter::ToSingle(const System::Details::ArrayView\<uint8_t\>\&, int) metod


Konverterar fyra byte från den specificerade arrayen med start vid det angivna indexet till ett flyttal med enkel precision.

```cpp
static float System::BitConverter::ToSingle(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView som innehåller byte att konvertera |
| startIndex | int | [Index](../../index/) i arrayen där man börjar ta byte för konvertering |

### Returvärde

Flyttal med enkel precision som resultat av konverteringen

## Se även

* Typdefinition [ArrayPtr](../../arrayptr/)
* Klass [BitConverter](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)
---
title: ToDouble()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert acht Bytes aus dem angegebenen Array, beginnend beim angegebenen Index, in einen double-Genauigkeits-Fließkommawert.
type: docs
weight: 144
url: /de/system/bitconverter/todouble/
---
## BitConverter::ToDouble(const System::ArrayPtr\<uint8_t\>\&, int) method


Konvertiert acht Bytes aus dem angegebenen Array, beginnend beim angegebenen Index, in einen double-Genauigkeits-Fließkommawert.

```cpp
static double System::BitConverter::ToDouble(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) die Bytes zum Konvertieren enthält |
| startIndex | int | [Index](../../index/) im Array, bei dem das Entnehmen von Bytes für die Konvertierung beginnen soll |

### Rückgabewert

Double-Genauigkeits-Fließkommawert, der aus der Konvertierung resultiert

## BitConverter::ToDouble(const System::Details::ArrayView\<uint8_t\>\&, int) method


Konvertiert acht Bytes aus dem angegebenen Array, beginnend beim angegebenen Index, in einen double-Genauigkeits-Fließkommawert.

```cpp
static double System::BitConverter::ToDouble(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView, die Bytes zum Konvertieren enthält |
| startIndex | int | [Index](../../index/) im Array, bei dem das Entnehmen von Bytes für die Konvertierung beginnen soll |

### Rückgabewert

Double-Genauigkeits-Fließkommawert, der aus der Konvertierung resultiert

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [BitConverter](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)
---
title: ToInt64()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert acht Bytes aus dem angegebenen Array, beginnend am angegebenen Index, in einen 64-bit-Ganzzahlwert.
type: docs
weight: 79
url: /de/system/bitconverter/toint64/
---
## BitConverter::ToInt64(const System::ArrayPtr\<uint8_t\>\&, int) method


Konvertiert acht Bytes aus dem angegebenen Array, beginnend am angegebenen Index, in einen 64-Bit-Ganzzahlwert.

```cpp
static int64_t System::BitConverter::ToInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) die Bytes zum Konvertieren enthält |
| startIndex | int | [Index](../../index/) im Array, an dem die Bytes für die Konvertierung entnommen werden |

### Rückgabewert

64-Bit-Ganzzahlwert, der aus der Konvertierung resultiert

## BitConverter::ToInt64(const System::Details::ArrayView\<uint8_t\>\&, int) method


Konvertiert acht Bytes aus dem angegebenen Array, beginnend am angegebenen Index, in einen 64-Bit-Ganzzahlwert.

```cpp
static int64_t System::BitConverter::ToInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView die Bytes zum Konvertieren enthält |
| startIndex | int | [Index](../../index/) im Array, an dem die Bytes für die Konvertierung entnommen werden |

### Rückgabewert

64-Bit-Ganzzahlwert, der aus der Konvertierung resultiert

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
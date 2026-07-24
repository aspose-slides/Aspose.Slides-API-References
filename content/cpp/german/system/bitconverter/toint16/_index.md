---
title: ToInt16()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert zwei Bytes aus dem angegebenen Array, beginnend am angegebenen Index, in einen 16-Bit-Ganzzahlwert.
type: docs
weight: 53
url: /de/system/bitconverter/toint16/
---
## BitConverter::ToInt16(const System::ArrayPtr\<uint8_t\>\&, int) Methode


Konvertiert zwei Bytes aus dem angegebenen Array, beginnend am angegebenen Index, in einen 16-Bit-Ganzzahlwert.

```cpp
static int16_t System::BitConverter::ToInt16(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) die Bytes enthält, die konvertiert werden sollen |
| startIndex | int | [Index](../../index/) im Array, ab dem Bytes für die Konvertierung entnommen werden sollen |

### Rückgabewert

16-Bit-Ganzzahlwert, der aus der Konvertierung resultiert

## BitConverter::ToInt16(const System::Details::ArrayView\<uint8_t\>\&, int) Methode


Konvertiert zwei Bytes aus dem angegebenen Array, beginnend am angegebenen Index, in einen 16-Bit-Ganzzahlwert.

```cpp
static int16_t System::BitConverter::ToInt16(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView die Bytes enthält, die konvertiert werden sollen |
| startIndex | int | [Index](../../index/) im Array, ab dem Bytes für die Konvertierung entnommen werden sollen |

### Rückgabewert

16-Bit-Ganzzahlwert, der aus der Konvertierung resultiert

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
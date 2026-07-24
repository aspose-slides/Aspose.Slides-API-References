---
title: ToUInt32()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert vier Bytes aus dem angegebenen Array, beginnend am angegebenen Index, in einen vorzeichenlosen 32-bit-Ganzzahlwert.
type: docs
weight: 105
url: /de/system/bitconverter/touint32/
---
## BitConverter::ToUInt32(const System::ArrayPtr\<uint8_t\>\&, int) Methode

Konvertiert vier Bytes aus dem angegebenen Array beginnend am angegebenen Index in einen vorzeichenlosen 32-bit-Ganzzahlwert.

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) die Bytes enthält, die konvertiert werden sollen |
| startIndex | int | [Index](../../index/) im Array, bei dem die Bytes für die Konvertierung entnommen werden |

### Rückgabewert

Vorzeichenloser 32-bit-Ganzzahlwert, der aus der Konvertierung resultiert

## BitConverter::ToUInt32(const System::Details::ArrayView\<uint8_t\>\&, int) Methode

Konvertiert vier Bytes aus dem angegebenen Array beginnend am angegebenen Index in einen vorzeichenlosen 32-bit-Ganzzahlwert.

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView, das Bytes enthält, die konvertiert werden sollen |
| startIndex | int | [Index](../../index/) im Array, bei dem die Bytes für die Konvertierung entnommen werden |

### Rückgabewert

Vorzeichenloser 32-bit-Ganzzahlwert, der aus der Konvertierung resultiert

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [BitConverter](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)
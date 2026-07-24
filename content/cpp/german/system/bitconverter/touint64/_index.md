---
title: ToUInt64()
second_title: Aspose.Slides für C++ API Referenz
description: Konvertiert acht Bytes aus dem angegebenen Array, beginnend am angegebenen Index, in einen vorzeichenlosen 64-bit Ganzzahlwert.
type: docs
weight: 118
url: /de/system/bitconverter/touint64/
---
## BitConverter::ToUInt64(const System::ArrayPtr\<uint8_t\>\&, int) Methode

Konvertiert acht Bytes aus dem angegebenen Array, beginnend am angegebenen Index, in einen vorzeichenlosen 64-bit Ganzzahlwert.

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) das die Bytes zum Konvertieren enthält |
| startIndex | int | [Index](../../index/) im Array, an dem das Entnehmen von Bytes für die Konvertierung beginnen soll |

### Rückgabewert

Vorzeichenloser 64-bit Ganzzahlwert, der durch die Konvertierung entsteht

## BitConverter::ToUInt64(const System::Details::ArrayView\<uint8_t\>\&, int) Methode

Konvertiert acht Bytes aus dem angegebenen Array, beginnend am angegebenen Index, in einen vorzeichenlosen 64-bit Ganzzahlwert.

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView, das die zu konvertierenden Bytes enthält |
| startIndex | int | [Index](../../index/) im Array, an dem das Entnehmen von Bytes für die Konvertierung beginnen soll |

### Rückgabewert

Vorzeichenloser 64-bit Ganzzahlwert, der durch die Konvertierung entsteht

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [BitConverter](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)
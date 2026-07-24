---
title: ToInt32()
second_title: Aspose.Slides für C++ API Referenz
description: Konvertiert vier Bytes aus dem angegebenen Array, beginnend beim angegebenen Index, in einen 32-bit Ganzzahlwert.
type: docs
weight: 66
url: /de/system/bitconverter/toint32/
---
## BitConverter::ToInt32(const System::ArrayPtr\<uint8_t\>\&, int) Methode

Konvertiert vier Bytes aus dem angegebenen Array, beginnend beim angegebenen Index, in einen 32-Bit-Ganzzahlwert.

```cpp
static int System::BitConverter::ToInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) das die zu konvertierenden Bytes enthält |
| startIndex | int | [Index](../../index/) im Array, an dem das Entnehmen von Bytes für die Konvertierung beginnen soll |

### Rückgabewert

32-Bit-Ganzzahlwert, der aus der Konvertierung resultiert

## BitConverter::ToInt32(const System::Details::ArrayView\<uint8_t\>\&, int) Methode

Konvertiert vier Bytes aus dem angegebenen Array, beginnend beim angegebenen Index, in einen 32-Bit-Ganzzahlwert.

```cpp
static int System::BitConverter::ToInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView das die zu konvertierenden Bytes enthält |
| startIndex | int | [Index](../../index/) im Array, an dem das Entnehmen von Bytes für die Konvertierung beginnen soll |

### Rückgabewert

32-Bit-Ganzzahlwert, der aus der Konvertierung resultiert

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [BitConverter](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)
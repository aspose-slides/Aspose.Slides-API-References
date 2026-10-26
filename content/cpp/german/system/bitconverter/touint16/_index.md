---
title: ToUInt16()
second_title: Aspose.Slides für C++ API Referenz
description: Konvertiert zwei Bytes aus dem angegebenen Array, beginnend am angegebenen Index, in einen vorzeichenlosen 16-Bit-Ganzzahlwert.
type: docs
weight: 92
url: /de/system/bitconverter/touint16/
---
## BitConverter::ToUInt16(const System::ArrayPtr\<uint8_t\>\&, int) Methode


Konvertiert zwei Bytes aus dem angegebenen Array, beginnend am angegebenen Index, in einen vorzeichenlosen 16-Bit-Ganzzahlwert.

```cpp
static uint16_t System::BitConverter::ToUInt16(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) die Bytes zum Konvertieren enthält |
| startIndex | int | [Index](../../index/) im Array, ab dem Bytes für die Konvertierung genommen werden |

### Rückgabewert

Vorzeichenloser 16-Bit-Ganzzahlwert, der aus der Konvertierung resultiert

## BitConverter::ToUInt16(const System::Details::ArrayView\<uint8_t\>\&, int) Methode


Konvertiert zwei Bytes aus dem angegebenen Array, beginnend am angegebenen Index, in einen vorzeichenlosen 16-Bit-Ganzzahlwert.

```cpp
static uint16_t System::BitConverter::ToUInt16(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView die Bytes zum Konvertieren enthält |
| startIndex | int | [Index](../../index/) im Array, ab dem Bytes für die Konvertierung genommen werden |

### Rückgabewert

Vorzeichenloser 16-Bit-Ganzzahlwert, der aus der Konvertierung resultiert

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [BitConverter](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)
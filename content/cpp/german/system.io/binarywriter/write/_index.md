---
title: Write()
second_title: Aspose.Slides für C++ API-Referenz
description: Schreibt den angegebenen vorzeichenlosen 8-bit-Ganzzahlwert in den Ausgabestream.
type: docs
weight: 92
url: /de/system.io/binarywriter/write/
---
## BinaryWriter::Write(uint8_t) Methode

Schreibt den angegebenen vorzeichenlosen 8-bit Ganzzahlwert in den Ausgabestream.

```cpp
virtual void System::IO::BinaryWriter::Write(uint8_t value)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | **uint8_t** | Der zu schreibende Wert |

## BinaryWriter::Write(const ArrayPtr\<uint8_t\>\&, int, int) Methode

Schreibt den angegebenen Teilbereich von Bytes aus dem angegebenen Byte-Array in den Ausgabestream.

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<uint8_t> &buffer, int index=0, int count=-1)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Das Array, das die zu schreibenden Bytes enthält |
| index | int | Ein bei 0 beginnender Index des Elements in **buffer**, an dem der zu schreibende Teilbereich beginnt |
| count | int | Die Anzahl der Elemente im zu schreibenden Teilbereich; -1 gibt an, dass der Teilbereich dort endet, wo das **buffer**-Array endet |

## BinaryWriter::Write(const ArrayPtr\<char_t\>\&, int, int) Methode

Schreibt den angegebenen Teilbereich von UTF-16-Zeichen aus dem angegebenen Zeichenarray in den Ausgabestream.

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<char_t> &buffer, int index=0, int count=-1)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Das Array, das die zu schreibenden Zeichen enthält |
| index | int | Ein bei 0 beginnender Index des Elements in **buffer**, an dem der zu schreibende Teilbereich beginnt |
| count | int | Die Anzahl der Zeichen im zu schreibenden Teilbereich; -1 gibt an, dass der Teilbereich dort endet, wo das **buffer**-Array endet |

## BinaryWriter::Write(bool) Methode

Schreibt ein einzelnes Byte mit dem Wert 0, wenn **value** 'true' ist, und 1, wenn **value** 'false' ist, in den Ausgabestream.

```cpp
virtual void System::IO::BinaryWriter::Write(bool value)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | **bool** | Der boolesche Wert, der den zu schreibenden Byte-Wert im Ausgabestream bestimmt |

## BinaryWriter::Write(char16_t) Methode

Schreibt den angegebenen 16-bit Breitenzeichenwert in den Ausgabestream.

```cpp
virtual void System::IO::BinaryWriter::Write(char16_t value)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | char16_t | Der zu schreibende Wert |

## BinaryWriter::Write(int16_t) Methode

Schreibt den angegebenen 16-bit Ganzzahlwert in den Ausgabestream.

```cpp
virtual void System::IO::BinaryWriter::Write(int16_t value)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | **int16_t** | Der zu schreibende Wert |

## BinaryWriter::Write(int) Methode

Schreibt den angegebenen 32-bit Ganzzahlwert in den Ausgabestream.

```cpp
virtual void System::IO::BinaryWriter::Write(int value)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int | Der zu schreibende Wert |

## BinaryWriter::Write(int64_t) Methode

Schreibt den angegebenen 64-bit Ganzzahlwert in den Ausgabestream.

```cpp
virtual void System::IO::BinaryWriter::Write(int64_t value)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | **int64_t** | Der zu schreibende Wert |

## BinaryWriter::Write(uint16_t) Methode

Schreibt den angegebenen vorzeichenlosen 16-bit Ganzzahlwert in den Ausgabestream.

```cpp
virtual void System::IO::BinaryWriter::Write(uint16_t value)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | **uint16_t** | Der zu schreibende Wert |

## BinaryWriter::Write(uint32_t) Methode

Schreibt den angegebenen vorzeichenlosen 32-bit Ganzzahlwert in den Ausgabestream.

```cpp
virtual void System::IO::BinaryWriter::Write(uint32_t value)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | **uint32_t** | Der zu schreibende Wert |

## BinaryWriter::Write(uint64_t) Methode

Schreibt den angegebenen vorzeichenlosen 64-bit Ganzzahlwert in den Ausgabestream.

```cpp
virtual void System::IO::BinaryWriter::Write(uint64_t value)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | **uint64_t** | Der zu schreibende Wert |

## BinaryWriter::Write(float) Methode

Schreibt den angegebenen Gleitkommawert einfacher Genauigkeit in den Ausgabestream.

```cpp
virtual void System::IO::BinaryWriter::Write(float value)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | **float** | Der zu schreibende Wert |

## BinaryWriter::Write(double) Methode

Schreibt den angegebenen Gleitkommawert doppelter Genauigkeit in den Ausgabestream.

```cpp
virtual void System::IO::BinaryWriter::Write(double value)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | **double** | Der zu schreibende Wert |

## BinaryWriter::Write(const Decimal\&) Methode

Schreibt die Byte-Darstellung des angegebenen [Decimal](../../../system/decimal/)-Werts in den Ausgabestream.

```cpp
virtual void System::IO::BinaryWriter::Write(const Decimal &value)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [Decimal](../../../system/decimal/)\& | Der zu schreibende Wert |

## BinaryWriter::Write(const String\&) Methode

Schreibt einen Längen-vorgelagerten String in der aktuellen Kodierung in den Ausgabestream.

```cpp
virtual void System::IO::BinaryWriter::Write(const String &value)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Der zu schreibende String |

## BinaryWriter::Write(const char_t *) Methode

Schreibt einen Längen-vorgelagerten String in der aktuellen Kodierung in den Ausgabestream.

```cpp
virtual void System::IO::BinaryWriter::Write(const char_t *value)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const char_t * | Der zu schreibende C-String |

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [BinaryWriter](../)
* Klasse [Decimal](../../../system/decimal/)
* Klasse [String](../../../system/string/)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)
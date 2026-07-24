---
title: Read()
second_title: Aspose.Slides für C++ API-Referenz
description: Liest ein einzelnes Zeichen aus dem Eingabestream.
type: docs
weight: 66
url: /de/system.io/binaryreader/read/
---
## BinaryReader::Read() Methode

Liest ein einzelnes Zeichen aus dem Eingabestream.

```cpp
virtual int System::IO::BinaryReader::Read()
```

### Rückgabewert

Gelesenes Zeichen, kodiert mit UTF-16; falls das gelesene Zeichen durch zwei Codepunkte in UTF-16 dargestellt wird, wird nur das High Surrogate zurückgegeben.

## BinaryReader::Read(ArrayPtr\<uint8_t\>, int, int) Methode

Liest die angegebene Anzahl von Bytes aus dem Eingabestream und schreibt sie in das angegebene Byte-Array.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<uint8_t> buffer, int index, int count)
```

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Das Byte-Array, in das die gelesenen Bytes geschrieben werden |
| index | int | Eine 0-basierte Position in **buffer**, an der das Schreiben beginnt |
| count | int | Die Anzahl der zu lesenden Bytes |

### Rückgabewert

Die Anzahl der gelesenen Bytes

## BinaryReader::Read(ArrayPtr\<char_t\>, int, int) Methode

Liest die angegebene Anzahl von Zeichen aus dem Eingabestream, konvertiert sie in UTF-16 und schreibt die resultierenden UTF-16-Zeichen in das angegebene Zeichen-Array, beginnend an der angegebenen Position.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Das UTF-16-Zeichen-Array, in das die aus dem Eingabestream gelesenen Zeichen geschrieben werden |
| index | int | Ein 0-basierter Index in **buffer**, an dem das Schreiben beginnt |
| count | int | Die Anzahl der aus dem Stream zu lesenden Zeichen |

### Rückgabewert

Die Anzahl der aus dem Eingabestream gelesenen Zeichen

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [BinaryReader](../)
* Namensraum [System::IO](../../)
* Library [Aspose.Slides](../../../)
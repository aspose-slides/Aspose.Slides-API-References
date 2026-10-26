---
title: Write()
second_title: Aspose.Slides für C++ API-Referenz
description: Schreibt den angegebenen Teilbereich von Bytes aus dem angegebenen Byte-Array in den Stream.
type: docs
weight: 248
url: /de/system.io/filestream/write/
---
## FileStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) Methode

Schreibt den angegebenen Teilbereich von Bytes aus dem angegebenen Byte-Array in den Stream.

```cpp
void System::IO::FileStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Das Array, das die zu schreibenden Bytes enthält. |
| offset | **int32_t** | Ein nullbasierter Index des Elements in **buffer**, an dem der zu schreibende Teilbereich beginnt. |
| count | **int32_t** | Die Anzahl der Elemente im zu schreibenden Teilbereich. |

## FileStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) Methode

Schreibt den angegebenen Teilbereich von Bytes aus dem angegebenen Byte-Array in den Stream.

```cpp
void System::IO::FileStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Die Array-Ansicht, die die zu schreibenden Bytes enthält. |
| offset | **int32_t** | Ein nullbasierter Index des Elements in **buffer**, an dem der zu schreibende Teilbereich beginnt. |
| count | **int32_t** | Die Anzahl der Elemente im zu schreibenden Teilbereich. |

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [FileStream](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)
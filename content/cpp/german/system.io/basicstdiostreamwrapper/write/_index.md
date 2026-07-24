---
title: Write()
second_title: Aspose.Slides für C++ API-Referenz
description: Wenn der Wrapmodus binär ist, schreibt er den angegebenen Teilbereich von Bytes aus dem angegebenen Byte-Array in den Stream, andernfalls konvertiert er den angegebenen Teilbereich von Bytes aus dem angegebenen Byte-Array in den Typ char_type und schreibt das Ergebnis dann in den Stream.
type: docs
weight: 79
url: /de/system.io/basicstdiostreamwrapper/write/
---
## BasicSTDIOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) Methode

Wenn der Umwrapmodus binär ist, schreibt er den angegebenen Teilbereich von Bytes aus dem angegebenen Byte-Array in den Stream, andernfalls konvertiert er den angegebenen Teilbereich von Bytes aus dem angegebenen Byte-Array in den Typ char_type und schreibt das Ergebnis dann in den Stream.

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Das Array, das die zu schreibenden Bytes enthält |
| offset | **int32_t** | Ein nullbasierter Index des Elements in **buffer**, an dem der zu schreibende Teilbereich beginnt |
| count | **int32_t** | Die Anzahl der Elemente im zu schreibenden Teilbereich |

## BasicSTDIOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) Methode

Schreibt den angegebenen Teilbereich von Bytes aus dem angegebenen Byte-Array in den Stream.

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Das Array-View, das die zu schreibenden Bytes enthält |
| offset | **int32_t** | Ein nullbasierter Index des Elements in **buffer**, an dem der zu schreibende Teilbereich beginnt |
| count | **int32_t** | Die Anzahl der Elemente im zu schreibenden Teilbereich |

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [BasicSTDIOStreamWrapper](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)
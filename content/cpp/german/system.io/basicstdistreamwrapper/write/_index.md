---
title: Write()
second_title: Aspose.Slides für C++ API Referenz
description: Wenn der Umwicklungsmodus binär ist, schreibt es den angegebenen Teilbereich von Bytes aus dem angegebenen Byte-Array in den Stream, andernfalls wird der angegebene Teilbereich von Bytes aus dem angegebenen Byte-Array in den Typ char_type konvertiert und das Ergebnis in den Stream geschrieben. Nicht unterstützt!
type: docs
weight: 79
url: /de/system.io/basicstdistreamwrapper/write/
---
## BasicSTDIStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) Methode

If wrapping mode is binary, writes to the stream the specified subrange of bytes from the specified byte array, otherwise convert the specified subrange of bytes from the specified byte array to char_type type ant then writes result to the stream. Not supported!

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Das Array, das die zu schreibenden Bytes enthält. |
| offset | **int32_t** | Ein nullbasierter Index des Elements in **buffer**, an dem der zu schreibende Teilbereich beginnt. |
| count | **int32_t** | Die Anzahl der Elemente im zu schreibenden Teilbereich. |

## BasicSTDIStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) Methode

Writes the specified subrange of bytes from the specified byte array to the stream.

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Das Array-View, das die zu schreibenden Bytes enthält |
| offset | **int32_t** | Ein nullbasierter Index des Elements in **buffer**, an dem der zu schreibende Teilbereich beginnt |
| count | **int32_t** | Die Anzahl der Elemente im zu schreibenden Teilbereich |

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [BasicSTDIStreamWrapper](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)
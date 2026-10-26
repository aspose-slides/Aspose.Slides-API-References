---
title: Write()
second_title: Aspose.Slides für C++ API-Referenz
description: Schreibt den angegebenen Teilbereich von Bytes aus dem angegebenen Byte-Array in den Stream.
type: docs
weight: 53
url: /de/system.io/stream/write/
---
## Stream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) Methode

Schreibt den angegebenen Teilbereich von Bytes aus dem angegebenen Byte-Array in den Stream.

```cpp
virtual void System::IO::Stream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```

### Argumente

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Das Array, das die zu schreibenden Bytes enthält |
| offset | **int32_t** | Ein nullbasierter Index des Elements in **buffer**, an dem der zu schreibende Teilbereich beginnt |
| count | **int32_t** | Die Anzahl der Elemente im zu schreibenden Teilbereich |

## Stream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) Methode

Schreibt den angegebenen Teilbereich von Bytes aus dem angegebenen Byte-Array in den Stream.

```cpp
virtual void System::IO::Stream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```

### Argumente

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Die Array-Ansicht, die die zu schreibenden Bytes enthält |
| offset | **int32_t** | Ein nullbasierter Index des Elements in **buffer**, an dem der zu schreibende Teilbereich beginnt |
| count | **int32_t** | Die Anzahl der Elemente im zu schreibenden Teilbereich |

## Stream::Write(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) Methode

Schreibt den angegebenen Teilbereich von Bytes aus dem angegebenen Byte-Array in den Stream.

```cpp
template<std::size_t> void System::IO::Stream::Write(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| N | Die Größe des Stack-Arrays |

### Argumente

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | Das Stack-Array, das die zu schreibenden Bytes enthält |
| offset | **int32_t** | Ein nullbasierter Index des Elements in **buffer**, an dem der zu schreibende Teilbereich beginnt |
| count | **int32_t** | Die Anzahl der Elemente im zu schreibenden Teilbereich |

## Stream::Write(const System::ReadOnlySpan\<uint8_t\>\&) Methode

Schreibt den angegebenen Teilbereich von Bytes aus dem angegebenen Byte-Span in den Stream.

```cpp
virtual void System::IO::Stream::Write(const System::ReadOnlySpan<uint8_t> &buffer)
```

### Argumente

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| buffer | const [System::ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | Der Byte-Span, aus dem die zu schreibenden Bytes gelesen werden |

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Stream](../)
* Klasse [ReadOnlySpan](../../../system/readonlyspan/)
* Namensraum [System::IO](../../)
* Library [Aspose.Slides](../../../)
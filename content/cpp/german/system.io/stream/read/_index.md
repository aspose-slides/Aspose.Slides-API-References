---
title: Read()
second_title: Aspose.Slides für C++ API-Referenz
description: Liest die angegebene Anzahl von Bytes aus dem Stream und schreibt sie in das angegebene Byte-Array.
type: docs
weight: 27
url: /de/system.io/stream/read/
---
## Stream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) Methode

Liest die angegebene Anzahl von Bytes aus dem Stream und schreibt sie in das angegebene Byte-Array.

```cpp
virtual int32_t System::IO::Stream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Das Byte-Array, in das die gelesenen Bytes geschrieben werden |
| offset | **int32_t** | Eine nullbasierte Position in **buffer**, an der das Schreiben beginnt |
| count | **int32_t** | Die Anzahl der zu lesenden Bytes |

### Rückgabewert

Die Anzahl der gelesenen Bytes

## Stream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) Methode

Liest die angegebene Anzahl von Bytes aus dem Stream und schreibt sie in das angegebene Byte-Array.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Die Byte-Array-Ansicht, in die die gelesenen Bytes geschrieben werden |
| offset | **int32_t** | Eine nullbasierte Position in **buffer**, an der das Schreiben beginnt |
| count | **int32_t** | Die Anzahl der zu lesenden Bytes |

### Rückgabewert

Die Anzahl der gelesenen Bytes

## Stream::Read(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) Methode

Liest die angegebene Anzahl von Bytes aus dem Stream und schreibt sie in das angegebene Byte-Array.

```cpp
template<std::size_t> int32_t System::IO::Stream::Read(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| N | Die Größe des Stapel-Arrays |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | Das Byte-Stapel-Array, in das die gelesenen Bytes geschrieben werden |
| offset | **int32_t** | Eine nullbasierte Position in **buffer**, an der das Schreiben beginnt |
| count | **int32_t** | Die Anzahl der zu lesenden Bytes |

### Rückgabewert

Die Anzahl der gelesenen Bytes

## Stream::Read(const System::Span\<uint8_t\>\&) Methode

Liest die angegebene Anzahl von Bytes aus dem Stream und schreibt sie in das angegebene Byte-Span.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Span<uint8_t> &buffer)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const [System::Span](../../../system/span/)\<**uint8_t**\>\& | Das Byte-Span, in das die gelesenen Bytes geschrieben werden |

### Rückgabewert

Die Anzahl der gelesenen Bytes

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Stream](../)
* Klasse [Span](../../../system/span/)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)
---
title: Read()
second_title: Aspose.Slides für C++ API-Referenz
description: Liest die angegebene Anzahl von Bytes aus dem Stream und schreibt sie in das angegebene Byte-Array.
type: docs
weight: 144
url: /de/system.io/unmanagedmemorystream/read/
---
## UnmanagedMemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) Methode


Liest die angegebene Anzahl von Bytes aus dem Stream und schreibt sie in das angegebene Byte-Array.

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Das Byte-Array, in das die gelesenen Bytes geschrieben werden |
| offset | **int32_t** | Eine 0-basierte Position in **buffer**, an der das Schreiben beginnt |
| count | **int32_t** | Die Anzahl der zu lesenden Bytes |

### Rückgabewert

Die Anzahl der gelesenen Bytes

## UnmanagedMemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) Methode


Liest die angegebene Anzahl von Bytes aus dem Stream und schreibt sie in das angegebene Byte-Array.

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Das Byte-Array-View, in das die gelesenen Bytes geschrieben werden |
| offset | **int32_t** | Eine 0-basierte Position in **buffer**, an der das Schreiben beginnt |
| count | **int32_t** | Die Anzahl der zu lesenden Bytes |

### Rückgabewert

Die Anzahl der gelesenen Bytes

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [UnmanagedMemoryStream](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)
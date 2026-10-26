---
title: Read()
second_title: Aspose.Slides für C++ API-Referenz
description: Liest die angegebene Anzahl von Bytes aus dem Stream und schreibt sie in das angegebene Byte-Array.
type: docs
weight: 79
url: /de/system.io/memorystream/read/
---
## MemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Liest die angegebene Anzahl von Bytes aus dem Stream und schreibt sie in das angegebene Byte-Array.

```cpp
int32_t System::IO::MemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Parameter

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Das Byte-Array, in das die gelesenen Bytes geschrieben werden |
| offset | **int32_t** | Eine bei 0 beginnende Position in **buffer**, an der das Schreiben startet |
| count | **int32_t** | Die Anzahl der zu lesenden Bytes |

### Rückgabewert

Die Anzahl der gelesenen Bytes

## MemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Liest die angegebene Anzahl von Bytes aus dem Stream und schreibt sie in das angegebene Byte-Array.

```cpp
int32_t System::IO::MemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Parameter

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Das Byte-Array-View, in das die gelesenen Bytes geschrieben werden |
| offset | **int32_t** | Eine bei 0 beginnende Position in **buffer**, an der das Schreiben startet |
| count | **int32_t** | Die Anzahl der zu lesenden Bytes |

### Rückgabewert

Die Anzahl der gelesenen Bytes

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [MemoryStream](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)
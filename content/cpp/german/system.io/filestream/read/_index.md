---
title: Read()
second_title: Aspose.Slides für C++ API-Referenz
description: Liest die angegebene Anzahl von Bytes aus dem Stream und schreibt sie in das angegebene Byte-Array.
type: docs
weight: 183
url: /de/system.io/filestream/read/
---
## FileStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) Methode


Liest die angegebene Anzahl von Bytes aus dem Stream und schreibt sie in das angegebene Byte-Array.

```cpp
int32_t System::IO::FileStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Das Byte-Array, in das die gelesenen Bytes geschrieben werden. |
| offset | **int32_t** | Eine 0-basierte Position in **buffer**, an der das Schreiben beginnt. |
| count | **int32_t** | Die Anzahl der zu lesenden Bytes. |

### Rückgabewert

Die Anzahl der gelesenen Bytes.

## FileStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) Methode


Liest die angegebene Anzahl von Bytes aus dem Stream und schreibt sie in die angegebene Byte-Array-Ansicht.

```cpp
int32_t System::IO::FileStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Die Byte-Array-Ansicht, in die die gelesenen Bytes geschrieben werden. |
| offset | **int32_t** | Eine 0-basierte Position in **buffer**, an der das Schreiben beginnt. |
| count | **int32_t** | Die Anzahl der zu lesenden Bytes. |

### Rückgabewert

Die Anzahl der gelesenen Bytes.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [FileStream](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)
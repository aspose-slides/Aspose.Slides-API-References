---
title: Read()
second_title: Aspose.Slides für C++ API-Referenz
description: Liest die angegebene Anzahl von Bytes aus dem zugrunde liegenden Stream und schreibt sie in das angegebene Byte-Array.
type: docs
weight: 53
url: /de/system.io/bufferedstream/read/
---
## BufferedStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) Methode

Liest die angegebene Anzahl von Bytes aus dem zugrunde liegenden Stream und schreibt sie in das angegebene Byte-Array.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Das Byte-Array, in das die gelesenen Bytes geschrieben werden |
| offset | **int32_t** | Eine nullbasierte Position in **buffer**, an der das Schreiben beginnt |
| count | **int32_t** | Die Anzahl der zu lesenden Bytes |

### Rückgabewert

Die Anzahl der gelesenen Bytes

## BufferedStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) Methode

Liest die angegebene Anzahl von Bytes aus dem zugrunde liegenden Stream und schreibt sie in das angegebene Byte-Array.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Das Byte-Array, in das die gelesenen Bytes geschrieben werden |
| offset | **int32_t** | Eine nullbasierte Position in **buffer**, an der das Schreiben beginnt |
| count | **int32_t** | Die Anzahl der zu lesenden Bytes |

### Rückgabewert

Die Anzahl der gelesenen Bytes

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [BufferedStream](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)
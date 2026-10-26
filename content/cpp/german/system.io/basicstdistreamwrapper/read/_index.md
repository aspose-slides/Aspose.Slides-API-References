---
title: Read()
second_title: Aspose.Slides für C++ API Referenz
description: Wenn der Wrap-Modus binär ist, liest er die angegebene Anzahl von Bytes aus dem Stream, andernfalls liest er die angegebene Anzahl von Zeichen und konvertiert sie in den Typ uint8_t. Das Ergebnis des Lesens wird in das angegebene Byte-Array geschrieben.
type: docs
weight: 66
url: /de/system.io/basicstdistreamwrapper/read/
---
## BasicSTDIStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) Methode


Wenn der Wrap-Modus binär ist, liest er die angegebene Anzahl von Bytes aus dem Stream, andernfalls liest er die angegebene Anzahl von Zeichen und konvertiert sie in den Typ **uint8_t**. Das Ergebnis des Lesens wird in das angegebene Byte-Array geschrieben.

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Das Byte-Array, in das die gelesenen Bytes geschrieben werden |
| offset | **int32_t** | Eine nullbasierte Position in **buffer**, an der das Schreiben beginnt |
| count | **int32_t** | Anzahl der zu lesenden Bytes |

### Rückgabewert

Anzahl der gelesenen Bytes oder Zeichen

## BasicSTDIStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) Methode


Liest die angegebene Anzahl von Bytes aus dem Stream und schreibt sie in das angegebene Byte-Array.

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Das Byte-Array-View, in das die gelesenen Bytes geschrieben werden |
| offset | **int32_t** | Eine nullbasierte Position in **buffer**, an der das Schreiben beginnt |
| count | **int32_t** | Anzahl der zu lesenden Bytes |

### Rückgabewert

Anzahl der gelesenen Bytes

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [BasicSTDIStreamWrapper](../)
* Namensraum [System::IO](../../)
* Library [Aspose.Slides](../../../)
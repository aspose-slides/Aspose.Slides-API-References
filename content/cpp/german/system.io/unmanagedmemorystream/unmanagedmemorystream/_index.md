---
title: UnmanagedMemoryStream()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine neue Instanz von UnmanagedMemoryStream.
type: docs
weight: 118
url: /de/system.io/unmanagedmemorystream/unmanagedmemorystream/
---
## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t) Konstruktor


Erstellt eine neue Instanz von [UnmanagedMemoryStream](../).

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pointer | **uint8_t** * | Ein Zeiger auf einen nicht verwalteten Puffer |
| length | **int64_t** | Die Größe des nicht verwalteten Puffers in Byte |

## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t, int64_t, FileAccess) Konstruktor


Erstellt eine neue Instanz von [UnmanagedMemoryStream](../).

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length, int64_t capacity, FileAccess access)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pointer | **uint8_t** * | Ein Zeiger auf einen nicht verwalteten Puffer |
| length | **int64_t** | Die Größe des nicht verwalteten Puffers in Byte |
| capacity | **int64_t** | Die gesamte dem Stream zugewiesene Speichermenge |
| access | [FileAccess](../../fileaccess/) | Gibt an, ob der Stream nur lesend, nur schreibend oder beides sein soll |

## Siehe auch

* Aufzählung [FileAccess](../../fileaccess/)
* Klasse [UnmanagedMemoryStream](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)
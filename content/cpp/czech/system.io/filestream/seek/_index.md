---
title: Seek()
second_title: Aspose.Slides pro C++ - reference API
description: Nastaví pozici proudu reprezentovaného aktuálním objektem.
type: docs
weight: 209
url: /cs/system.io/filestream/seek/
---
## FileStream::Seek(int64_t, SeekOrigin) metoda

Nastaví pozici proudu reprezentovaného aktuálním objektem.

```cpp
int64_t System::IO::FileStream::Seek(int64_t offset, SeekOrigin origin) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| offset | **int64_t** | Posun bajtů vzhledem k pozici určené **origin**. |
| origin | [SeekOrigin](../../seekorigin/) | Určuje pozici, ze které a směr, kam je offset vypočítán. |

### Vrácená hodnota

Nová pozice proudu.

## Viz také

* Enum [SeekOrigin](../../seekorigin/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
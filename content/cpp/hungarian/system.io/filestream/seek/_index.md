---
title: Seek()
second_title: Aspose.Slides for C++ API Referencia
description: Beállítja a jelenlegi objektum által képviselt adatfolyam pozícióját.
type: docs
weight: 209
url: /hu/system.io/filestream/seek/
---
## FileStream::Seek(int64_t, SeekOrigin) metódus

A jelenlegi objektum által képviselt adatfolyam pozícióját állítja be.

```cpp
int64_t System::IO::FileStream::Seek(int64_t offset, SeekOrigin origin) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| offset | **int64_t** | A **origin** által meghatározott pozícióhoz viszonyított bájt eltolás. |
| origin | [SeekOrigin](../../seekorigin/) | Megadja azt a pozíciót, ahonnan, és az irányt, amely felé az eltolás számítva van. |

### Visszatérési érték

Az adatfolyam új pozíciója.

## Lásd még

* Enum [SeekOrigin](../../seekorigin/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
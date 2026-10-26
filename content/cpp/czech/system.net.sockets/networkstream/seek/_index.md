---
title: Seek()
second_title: Aspose.Slides pro C++ API Reference
description: Nastavuje pozici proudu reprezentovaného aktuálním objektem.
type: docs
weight: 183
url: /cs/system.net.sockets/networkstream/seek/
---
## NetworkStream::Seek(int64_t, IO::SeekOrigin) metoda

Sets the position of the stream represented by the current object.

```cpp
int64_t System::Net::Sockets::NetworkStream::Seek(int64_t offset, IO::SeekOrigin origin) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| offset | **int64_t** | Posun v bajtech relativně k pozici určené pomocí **origin** |
| origin | [IO::SeekOrigin](../../../system.io/seekorigin/) | Určuje pozici, od níž a směr, ve kterém je vypočítán offset |

### Návratová hodnota

Nová pozice proudu

## Viz také

* Výčet [SeekOrigin](../../../system.io/seekorigin/)
* Třída [NetworkStream](../)
* Prostor názvů [System::Net::Sockets](../../)
* Knihovna [Aspose.Slides](../../../)
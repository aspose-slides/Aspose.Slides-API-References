---
title: TryGetBuffer()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací pole bajtů bez znaménka, ze kterého byl tento proud vytvořen.
type: docs
weight: 170
url: /cs/system.io/memorystream/trygetbuffer/
---
## MemoryStream::TryGetBuffer(ArraySegment\<uint8_t\>\&) metoda

Vrací pole bajtů bez znaménka, ze kterého byl tento proud vytvořen.

```cpp
bool System::IO::MemoryStream::TryGetBuffer(ArraySegment<uint8_t> &buffer)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\& | pole byte – výstupní parametr. Když tato metoda vrátí true, segment pole byte, ze kterého byl tento proud vytvořen; kdy tato metoda vrátí false, je tento parametr nastaven na výchozí hodnotu. |

### Návratová hodnota

True pokud konverze byla úspěšná.

## Viz také

* Třída [ArraySegment](../../../system/arraysegment/)
* Třída [MemoryStream](../)
* Jmenný prostor [System::IO](../../)
* Library [Aspose.Slides](../../../)
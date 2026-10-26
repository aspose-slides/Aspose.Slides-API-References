---
title: DtdProcessing
second_title: Aspose.Slides C++ API-referencia
description: Meghatározza a DTD-k feldolgozásának lehetőségeit. A DtdProcessing felsorolást a XmlReaderSettings osztály használja.
type: docs
weight: 638
url: /hu/system.xml/dtdprocessing/
---
## DtdProcessing enum

Meghatározza a DTD-k feldolgozásának lehetőségeit. A DtdProcessing felsorolás a [XmlReaderSettings](../xmlreadersettings/) osztály által használatos.

```cpp
enum class DtdProcessing
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| Prohibit | 0 | Megadja, hogy amikor DTD található, egy XmlException kerül kivételként dobásra egy olyan üzenettel, amely azt jelzi, hogy a DTD-k tiltottak. Ez az alapértelmezett viselkedés. |
| Ignore | 1 | Az DOCTYPE elemet figyelmen kívül hagyja. Nem történik DTD-feldolgozás, és a DTD/DOCTYPE elveszik a kimeneten. |
| Parse | 2 | A DTD-k elemzéséhez használható. |

## Lásd még

* Névtere [System::Xml](../)
* Könyvtár [Aspose.Slides](../../)
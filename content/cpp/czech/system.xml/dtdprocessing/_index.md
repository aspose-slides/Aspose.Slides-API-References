---
title: DtdProcessing
second_title: Aspose.Slides pro C++ referenci API
description: Určuje možnosti zpracování DTD. Výčet DtdProcessing používá třída XmlReaderSettings.
type: docs
weight: 638
url: /cs/system.xml/dtdprocessing/
---
## DtdProcessing výčet

Určuje možnosti zpracování DTD. Výčet DtdProcessing používá třída [XmlReaderSettings](../xmlreadersettings/).

```cpp
enum class DtdProcessing
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| Prohibit | 0 | Určuje, že když je nalezeno DTD, je vyhozena výjimka XmlException se zprávou, která uvádí, že DTD jsou zakázány. Toto je výchozí chování. |
| Ignore | 1 | Způsobí, že prvek DOCTYPE bude ignorován. Nedojde k žádnému zpracování DTD a DTD/DOCTYPE bude při výstupu ztraceno. |
| Parse | 2 | Používá se pro parsování DTD. |

## Viz také

* Jmenný prostor [System::Xml](../)
* Knihovna [Aspose.Slides](../../)
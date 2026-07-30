---
title: NewLineHandling
second_title: Aspose.Slides pro C++ API Reference
description: Určuje, jak zacházet s konci řádků.
type: docs
weight: 690
url: /cs/system.xml/newlinehandling/
---
## NewLineHandling enum

Určuje, jak zacházet s konci řádků.

```cpp
enum class NewLineHandling
```

### Values

| Název | Hodnota | Popis |
| --- | --- | --- |
| Replace | 0 | Znaky nového řádku jsou nahrazeny tak, aby odpovídaly znaku určenému v hodnotě [XmlWriterSettings::set_NewLineChars](../xmlwritersettings/set_newlinechars/). |
| Entitize | 1 | Znaky nového řádku jsou převáděny na entity. Toto nastavení zachovává všechny znaky, když výstup čte normalizující [XmlReader](../xmlreader/). |
| None | 2 | Znaky nového řádku zůstávají nezměněny. Výstup je stejný jako vstup. |

## Viz také

* Jmenný prostor [System::Xml](../)
* Knihovna [Aspose.Slides](../../)
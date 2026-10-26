---
title: XmlSchemaContentProcessing
second_title: Aspose.Slides pro C++ API Reference
description: Poskytuje informace o režimu validace náhrad elementů any a anyAttribute.
type: docs
weight: 976
url: /cs/system.xml.schema/xmlschemacontentprocessing/
---
## XmlSchemaContentProcessing enum

Poskytuje informace o režimu validace náhrad elementů **any** a **anyAttribute**.

```cpp
enum class XmlSchemaContentProcessing
```

### Values

| Název | Hodnota | Popis |
| --- | --- | --- |
| None | 0 | Položky dokumentu nejsou validovány. |
| Skip | 1 | Položky dokumentu musí být dobře formovaný XML a nejsou validovány schématem. |
| Lax | 2 | Pokud je nalezeno související schéma, položky dokumentu budou validovány. V opačném případě nebudou vyvolány žádné chyby. |
| Strict | 3 | Procesor schématu musí najít schéma související s uvedeným jmenným prostorem, aby validoval položky dokumentu. |

## Viz také

* Jmenný prostor [System::Xml::Schema](../)
* Knihovna [Aspose.Slides](../../)
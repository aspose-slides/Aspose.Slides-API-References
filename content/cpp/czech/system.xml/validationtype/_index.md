---
title: ValidationType
second_title: Aspose.Slides pro C++ API Reference
description: Určuje typ validace, která se má provést.
type: docs
weight: 729
url: /cs/system.xml/validationtype/
---
## ValidationType enum

Specifies the type of validation to perform.

```cpp
enum class ValidationType
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| None | 0 | Žádná validace se neprovádí a nejsou vyvolány žádné chyby validace. Toto nastavení vytvoří parser nevalidující, který je v souladu s XML 1.0. |
| Auto | 1 | Validuje, pokud jsou nalezeny informace DTD nebo schématu. |
| DTD | 2 | Validuje podle DTD. |
| XDR | 3 | Validuje podle schémat XML-Data Reduced (XDR), včetně vložených XDR schémat. XDR schémata jsou rozpoznávána pomocí předpony jmenného prostoru **x-schema** nebo hodnoty [XmlValidatingReader::get_Schemas](../xmlvalidatingreader/get_schemas/). |
| Schema | 4 | Validuje podle definovacího jazyka XML [Schema](../../system.xml.schema/) (XSD) schémat, včetně vložených XML schémat. XML schémata jsou přiřazena k URI jmenných prostorů buď pomocí atributu **schemaLocation**, nebo pomocí poskytnutých **Schemas**. |

## Viz také

* Jmenný prostor [System::Xml](../)
* Knihovna [Aspose.Slides](../../)
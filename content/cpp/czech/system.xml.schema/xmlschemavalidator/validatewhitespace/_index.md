---
title: ValidateWhitespace()
second_title: Aspose.Slides pro C++ API Reference
description: Ověřuje, zda je bílý znak v zadaném řetězci povolen v aktuálním kontextu elementu, a shromažďuje bílý znak pro validaci, pokud má aktuální element jednoduchý obsah.
type: docs
weight: 196
url: /cs/system.xml.schema/xmlschemavalidator/validatewhitespace/
---
## XmlSchemaValidator::ValidateWhitespace(const String\&) metoda

Ověřuje, zda je bílý znak v zadaném **string** povolen v aktuálním kontextu elementu, a shromažďuje bílý znak pro validaci, pokud má aktuální element jednoduchý obsah.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace(const String &elementValue)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | Bílý znak **string** k ověření v aktuálním kontextu elementu. |

## XmlSchemaValidator::ValidateWhitespace(XmlValueGetter) metoda

Ověřuje, zda je bílý znak vrácený zadaným objektem XmlValueGetter povolen v aktuálním kontextu elementu, a shromažďuje bílý znak pro validaci, pokud má aktuální element jednoduchý obsah.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace(XmlValueGetter elementValue)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | Callback XmlValueGetter používaný k předání hodnoty bílého znaku jako typu kompatibilního s XML [Schema](../../) Definition Language (XSD) typem atributu. |

## Viz také

* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Třída [String](../../../system/string/)
* Třída [XmlSchemaValidator](../)
* Jmenný prostor [System::Xml::Schema](../../)
* Knihovna [Aspose.Slides](../../../)